<template>
  <div class="w-full">
    <BigText title="聖歌本" class="mt-80" />
    <ul class="holy-song-list list-none text-4xl">
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/天一國國歌'">天一國國歌</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/孝情之光'">孝情之光</NuxtLink>
      </li>
    </ul>
    這邊做一個翻頁，把上下變左右
    <ul class="holy-song-list list-none text-4xl">
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/勝利者新歌'">勝利者新歌</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/聖美的新歌'">聖美的新歌</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/榮耀的恩賜'">榮耀的恩賜</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/黑暗裡的勢力'">黑暗裡的勢力</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/復歸的樂園'">復歸的樂園</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/勝苑的恩賜'">勝苑的恩賜</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/樂園之歌'">樂園之歌</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/青年之歌'">青年之歌</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/朝陽之歌'">朝陽之歌</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/我要勇往'">我要勇往</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/苦難與新生命'">苦難與新生命</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/我是供物'">我是供物</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/誓約'">誓約</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/成和勇士之歌'">成和勇士之歌</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/吹走嘆息吧'">吹走嘆息吧</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/光輝的祖國'">光輝的祖國</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/復歸的心情'">復歸的心情</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/來成就神的偉業'">來成就神的偉業</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/天的勇士'">天的勇士</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/找到的榮光'">找到的榮光</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/歸我背負的十字架'">歸我背負的十字架</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/光是從東方來'">光是從東方來</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/獻上一切往前進'">獻上一切往前進</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/苦難的耶穌'">苦難的耶穌</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/聚集成一體'">聚集成一體</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/統一勇士之歌'">統一勇士之歌</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/新伊甸園之歌'">新伊甸園之歌</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/被召命的我'">被召命的我</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/我的小羊'">我的小羊</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/成和青年進行曲'">成和青年進行曲</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/榮耀之日'">榮耀之日</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/願祢回應'">願祢回應</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/寂寞的山谷'">寂寞的山谷</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/主臨到'">主臨到</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/主啊！願祢來'">主啊<div>！</div>願祢來</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/農園之歌'">農園之歌</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/找到的羊群'">找到的羊群</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/夢般的旅途'">夢般的旅途</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/主是我的一切'">主是我的一切</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/我的朋友耶穌'">我的朋友耶穌</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/飲喝生命水'">飲喝生命水</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/我想到主面前'">我想到主面前</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/吾心所願'">吾心所願</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/天的盛宴'">天的盛宴</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/生活在活泉邊'">生活在活泉邊</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/樂園春天之歌'">樂園春天之歌</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/主日學兒童之歌'">主日學兒童之歌</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/趕快回來吧！'">趕快回來吧<div>！</div></NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/主是我們的牧者'">主是我們的牧者</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/蒙召的青年們'">蒙召的青年們</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/丹心歌'">丹心歌</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/出埃及'">出埃及</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/再相會'">再相會</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/勝利之歌'">勝利之歌</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/榮耀的主'">榮耀的主</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/確信的人'">確信的人</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/主常在我身邊'">主常在我身邊</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/蒙召前進'">蒙召前進</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/我的故鄉'">我的故鄉</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/危險的試煉中'">危險的試煉中</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/珍貴的寶物'">珍貴的寶物</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/向迦南前進'">向迦南前進</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/黑暗的路途上'">黑暗的路途上</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/我主的家庭'">我主的家庭</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/所盼望的那一日'">所盼望的那一日</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/傳揚吧'">傳揚吧</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/早晨的小鳥'">早晨的小鳥</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/恩惠與奇蹟'">恩惠與奇蹟</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/十字架上的呼求'">十字架上的呼求</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/大自然的禮讚'">大自然的禮讚</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/早晨的讚美'">早晨的讚美</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/與主同生'">與主同生</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/向著十字架'">向著十字架</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/儆醒禱告'">儆醒禱告</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/以色列啊歸來吧！'">以色列啊歸來吧<div>！</div></NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/善的征戰已成就了'">善的征戰已成就了</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/青年之樹'">青年之樹</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/光照亮大地'">光照亮大地</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/愛鄉歌'">愛鄉歌</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/愛的統一'">愛的統一</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/空中的飛鳥'">空中的飛鳥</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/由我心而出'">由我心而出</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/幸福是什麼'">幸福是什麼</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/光榮的聖戰'">光榮的聖戰</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/追求美的心'">追求美的心</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/春之旅'">春之旅</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/小小的生命'">小小的生命</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/生命之樹'">生命之樹</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/星光'">星光</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/總有一天會明瞭'">總有一天會明瞭</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/TheLordisOne'">The Lord is One</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/I\'llNeverleaveyou'">I'll Never leave you</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/讓我們手拉手'">讓我們手拉手</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/奉獻歌'">奉獻歌</NuxtLink>
      </li>
      <li class="holy-song">
        <NuxtLink :to="$route.path + '/統一歌'">統一歌</NuxtLink>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  transition: {
    name: 'transition',
    mode: 'out-in'
  },
  data () {
    return {
      showList: false
    }
  },
  mounted () {
    this.showList = true
  }
}
</script>

<style lang="scss">
/* List */
ul.holy-song-list {
  display: flex;
  flex-wrap: wrap;
  counter-reset: index;
  padding: 0;
  /* List element */
  max-width: 850px;
  margin: 50px auto;
  li {
    counter-increment: index;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 12px 12px 12px 0;
    box-sizing: border-box;
    color: $main-text-color;
    max-width: 80px;
    a {
      width: 12px;
    }
  }
  /* Element counter */
  li::before {
    content: counters(index, ".", decimal-leading-zero);
    font-size: 1.5rem;
    text-align: right;
    font-weight: bold;
    min-width: 50px;
    padding-right: 12px;
    font-variant-numeric: tabular-nums;
    align-self: flex-start;
    background-image: linear-gradient(to bottom, aquamarine, orangered);
    background-attachment: fixed;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }
  /* Element separation */
  li {
    border-top: 1px solid rgba(255, 255, 255, 0.2);
  }
}
</style>
