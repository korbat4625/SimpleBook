<template>
  <svg width="100%" class="page-title select-none">
    <defs>
      <pattern
        id="polka-dots"
        x="0"
        y="0"
        width="100"
        height="100"
        patternUnits="userSpaceOnUse"
      >
        <circle fill="#be9ddf" cx="25" cy="25" r="3"></circle>
      </pattern>
    </defs>
    <!-- <rect
      x="0"
      y="0"
      width="100%"
      height="100%"
      fill="url(#polka-dots)"
    ></rect> -->
    <text :style="`font-size: ${fontSize}px;`" x="45%" y="65%">{{ title }}</text>
  </svg>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      default: ''
    },
    fontSize: {
      type: Number,
      default: 100
    }
  }
}
</script>

<style>
svg {
  height: 50px;
  overflow: visible;
}
svg text {
  letter-spacing: 10px;
  stroke: #ffa5d8;
  font-weight: 700;
  stroke-width: 1;
  animation: textAnimate 5s infinite alternate;
}
@keyframes textAnimate {
  0% {
    stroke-dasharray: 0 50%;
    stroke-dashoffset:  20%;
    fill:hsl(189, 68%, 75%)

  }
  100% {
    stroke-dasharray: 50% 0;
    stroke-dashoffstet: -20%;
    fill: hsla(189, 68%, 75%,0%)
  }
}
</style>
