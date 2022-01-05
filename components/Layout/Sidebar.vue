<template>
    <div
    id="navBar"
    class="
        absolute left-0 top-0 w-full mt-8 ml-16 sidebar transition-all duration-300
        flex space-x-14
      "
    >
      <div id="site-icon" class="site-icon transition-opacity">
        <img src="~assets/icon/ffwpu.png" width="88" alt="" srcset="">
      </div>
      <nav id="nav" class="mt-12 flex self-start relative space-x-20">
        <div
          id="nav-item-group"
          class="
            nav-item-group space-x-14 flex-grow relative
            top-0 transition-all duration-300 delay-300
            flex
          "
        >
          <transition name="transition">
            <div v-if="$route.name !== 'index'">
              <NuxtLink class="text-hot-pink cursor-pointer" data-text="Home" to="/">Home</NuxtLink>
            </div>
          </transition>
          <transition name="transition">
            <div v-if="$route.name !== 'holysongs'">
              <NuxtLink class="text-mint cursor-pointer" data-text="聖歌本" to="/holysongs">聖歌本</NuxtLink>
            </div>
          </transition>
          <transition name="transition">
            <div v-if="$route.name !== 'songs'">
              <NuxtLink class="text-yellow cursor-pointer" data-text="歌詞本" to="/songs">歌詞本</NuxtLink>
            </div>
          </transition>
          <transition name="transition">
            <div v-if="$route.name !== 'search'">
              <NuxtLink class="text-tiffany-blue cursor-pointer" data-text="搜尋" to="/search">搜尋</NuxtLink>
            </div>
          </transition>
        </div>
        <!-- <div
          id="arrow"
          class="
            material-icons select-none cursor-pointer arrow self-center
            relative top-0 transition-all duration-300 delay-300
          "
          @click="toggleSidebar"
        >
          keyboard_arrow_down
        </div> -->
      </nav>
    </div>
</template>

<script>
export default {
  data () {
    return {
      openSideBar: true,
      showSiteIcon: true
    }
  },
  created () {
    console.log(this.$route)
  },
  methods: {
    toggleSidebar (navbarStatus) {
      this.openSideBar = !this.openSideBar
      this.showSiteIcon = !this.showSiteIcon
      const hidePX = '-100px'
      const arrowHidePX = '-50px'
      if (!this.showSiteIcon) {
        const arrow = document.getElementById('arrow')
        document.getElementById('site-icon').style.opacity = 0
        document.getElementById('nav-item-group').style.top = hidePX
        arrow.style.top = arrowHidePX
        setTimeout(() => {
          arrow.style.cssText = `
            top: ${arrowHidePX};
            transform: rotate(-180deg);
          `
        }, 300)
      } else {
        const arrow = document.getElementById('arrow')
        arrow.style.transform = 'rotate(0deg)'
        setTimeout(() => {
          document.getElementById('site-icon').style.opacity = 1
          document.getElementById('nav-item-group').style.top = '0%'
          arrow.style.cssText = `
            top: 0%;
            transform: rotate(0deg);
          `
        }, 300)
      }
      // const navbar = document.getElementById('navBar')
      // if (this.openSideBar) {
      //   navbar.style.opacity = 1
      //   navbar.style.left = '0'
      // } else {
      //   navbar.style.opacity = 0
      //   navbar.style.left = '-100%'
      // }
    }
  }
}
</script>

<style lang="scss">
@mixin text-base($color) {
  position: relative;
  top: 2px;
  left: 20px;
  color: transparent;
  background: linear-gradient($color 0 10%) left / 0% no-repeat;
  background-clip: text;
  -webkit-background-clip: text;
  transition: background-size 0.2s 0.04s;
  font-size: 18px;
  &::before {
    position: absolute;
    content: '';
    width: 8px;
    height: 100%;
    background-color: $color;
    transition: 0.6s;
    left: -20px;
  }
  &::after {
    position: absolute;
    content: attr(data-text);
    z-index: -1;
    color: $sidebar-text-color;
    top: -2px;
    left: 0;
    font-size: 18px;
  }
  &:hover {
    &::before {
      left: calc(100% + 1.5rem);
    }
    background-size: 100%;
    // @each $name, $color in $color-box {
    //     background-size: 100%;
    // }
  }
}

.nav-item-group {
  .text {
    @include text-base($sky-blue);
  }
  @each $name, $color in $color-box {
    .text-#{""+$name} {
      @include text-base($color);
    }
  }
}

#arrow {
  color: $sidebar-arrow-color
}

</style>
