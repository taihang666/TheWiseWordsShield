<script>
  import uniIdPageInit from '@/uni_modules/uni-id-pages/init.js';
  export default {
    onLaunch: async function() {
      console.log('App Launch')
      await uniIdPageInit()
    },
    onShow: function() {
      console.log('App Show')
    },
    onHide: function() {
      console.log('App Hide')
    }
  }
</script>
<style>
  /************************************************************
  ** 请将全局样式拷贝到项目的全局 CSS 文件或者当前页面的顶部 **
  ** 否则页面将无法正常显示                                  **
  ************************************************************/

  html {
    font-size: 16px;
  }

  body {
    margin: 0;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Oxygen', 'Ubuntu', 'Cantarell', 'Fira Sans',
      'Droid Sans', 'Helvetica Neue', 'Microsoft Yahei', sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }

  view,
  image,
  text {
    box-sizing: border-box;
    flex-shrink: 0;
  }

  #app {
    width: 100vw;
    height: 100vh;
  }

  .flex-row {
    display: flex;
    flex-direction: row;
  }

  .flex-col {
    display: flex;
    flex-direction: column;
  }

  .justify-start {
    justify-content: flex-start;
  }

  .justify-end {
    justify-content: flex-end;
  }

  .justify-center {
    justify-content: center;
  }

  .justify-between {
    justify-content: space-between;
  }

  .justify-around {
    justify-content: space-around;
  }

  .justify-evenly {
    justify-content: space-evenly;
  }

  .items-start {
    align-items: flex-start;
  }

  .items-end {
    align-items: flex-end;
  }

  .items-center {
    align-items: center;
  }

  .items-baseline {
    align-items: baseline;
  }

  .items-stretch {
    align-items: stretch;
  }

  .self-start {
    align-self: flex-start;
  }

  .self-end {
    align-self: flex-end;
  }

  .self-center {
    align-self: center;
  }

  .self-baseline {
    align-self: baseline;
  }

  .self-stretch {
    align-self: stretch;
  }

  .flex-1 {
    flex: 1 1 0%;
  }

  .flex-auto {
    flex: 1 1 auto;
  }

  .grow {
    flex-grow: 1;
  }

  .grow-0 {
    flex-grow: 0;
  }

  .shrink {
    flex-shrink: 1;
  }

  .shrink-0 {
    flex-shrink: 0;
  }

  .relative {
    position: relative;
  }

  .ml-2 {
    margin-left: 4.17rpx;
  }

  .mt-2 {
    margin-top: 4.17rpx;
  }

  .ml-4 {
    margin-left: 8.33rpx;
  }

  .mt-4 {
    margin-top: 8.33rpx;
  }

  .ml-6 {
    margin-left: 12.5rpx;
  }

  .mt-6 {
    margin-top: 12.5rpx;
  }

  .ml-8 {
    margin-left: 16.67rpx;
  }

  .mt-8 {
    margin-top: 16.67rpx;
  }

  .ml-10 {
    margin-left: 20.83rpx;
  }

  .mt-10 {
    margin-top: 20.83rpx;
  }

  .ml-12 {
    margin-left: 25rpx;
  }

  .mt-12 {
    margin-top: 25rpx;
  }

  .ml-14 {
    margin-left: 29.17rpx;
  }

  .mt-14 {
    margin-top: 29.17rpx;
  }

  .ml-16 {
    margin-left: 33.33rpx;
  }

  .mt-16 {
    margin-top: 33.33rpx;
  }

  .ml-18 {
    margin-left: 37.5rpx;
  }

  .mt-18 {
    margin-top: 37.5rpx;
  }

  .ml-20 {
    margin-left: 41.67rpx;
  }

  .mt-20 {
    margin-top: 41.67rpx;
  }

  .ml-22 {
    margin-left: 45.83rpx;
  }

  .mt-22 {
    margin-top: 45.83rpx;
  }

  .ml-24 {
    margin-left: 50rpx;
  }

  .mt-24 {
    margin-top: 50rpx;
  }

  .ml-26 {
    margin-left: 54.17rpx;
  }

  .mt-26 {
    margin-top: 54.17rpx;
  }

  .ml-28 {
    margin-left: 58.33rpx;
  }

  .mt-28 {
    margin-top: 58.33rpx;
  }

  .ml-30 {
    margin-left: 62.5rpx;
  }

  .mt-30 {
    margin-top: 62.5rpx;
  }

  .ml-32 {
    margin-left: 66.67rpx;
  }

  .mt-32 {
    margin-top: 66.67rpx;
  }

  .ml-34 {
    margin-left: 70.83rpx;
  }

  .mt-34 {
    margin-top: 70.83rpx;
  }

  .ml-36 {
    margin-left: 75rpx;
  }

  .mt-36 {
    margin-top: 75rpx;
  }

  .ml-38 {
    margin-left: 79.17rpx;
  }

  .mt-38 {
    margin-top: 79.17rpx;
  }

  .ml-40 {
    margin-left: 83.33rpx;
  }

  .mt-40 {
    margin-top: 83.33rpx;
  }

  .ml-42 {
    margin-left: 87.5rpx;
  }

  .mt-42 {
    margin-top: 87.5rpx;
  }

  .ml-44 {
    margin-left: 91.67rpx;
  }

  .mt-44 {
    margin-top: 91.67rpx;
  }

  .ml-46 {
    margin-left: 95.83rpx;
  }

  .mt-46 {
    margin-top: 95.83rpx;
  }

  .ml-48 {
    margin-left: 100rpx;
  }

  .mt-48 {
    margin-top: 100rpx;
  }

  .ml-50 {
    margin-left: 104.17rpx;
  }

  .mt-50 {
    margin-top: 104.17rpx;
  }

  .ml-52 {
    margin-left: 108.33rpx;
  }

  .mt-52 {
    margin-top: 108.33rpx;
  }

  .ml-54 {
    margin-left: 112.5rpx;
  }

  .mt-54 {
    margin-top: 112.5rpx;
  }

  .ml-56 {
    margin-left: 116.67rpx;
  }

  .mt-56 {
    margin-top: 116.67rpx;
  }

  .ml-58 {
    margin-left: 120.83rpx;
  }

  .mt-58 {
    margin-top: 120.83rpx;
  }

  .ml-60 {
    margin-left: 125rpx;
  }

  .mt-60 {
    margin-top: 125rpx;
  }

  .ml-62 {
    margin-left: 129.17rpx;
  }

  .mt-62 {
    margin-top: 129.17rpx;
  }

  .ml-64 {
    margin-left: 133.33rpx;
  }

  .mt-64 {
    margin-top: 133.33rpx;
  }

  .ml-66 {
    margin-left: 137.5rpx;
  }

  .mt-66 {
    margin-top: 137.5rpx;
  }

  .ml-68 {
    margin-left: 141.67rpx;
  }

  .mt-68 {
    margin-top: 141.67rpx;
  }

  .ml-70 {
    margin-left: 145.83rpx;
  }

  .mt-70 {
    margin-top: 145.83rpx;
  }

  .ml-72 {
    margin-left: 150rpx;
  }

  .mt-72 {
    margin-top: 150rpx;
  }

  .ml-74 {
    margin-left: 154.17rpx;
  }

  .mt-74 {
    margin-top: 154.17rpx;
  }

  .ml-76 {
    margin-left: 158.33rpx;
  }

  .mt-76 {
    margin-top: 158.33rpx;
  }

  .ml-78 {
    margin-left: 162.5rpx;
  }

  .mt-78 {
    margin-top: 162.5rpx;
  }

  .ml-80 {
    margin-left: 166.67rpx;
  }

  .mt-80 {
    margin-top: 166.67rpx;
  }

  .ml-82 {
    margin-left: 170.83rpx;
  }

  .mt-82 {
    margin-top: 170.83rpx;
  }

  .ml-84 {
    margin-left: 175rpx;
  }

  .mt-84 {
    margin-top: 175rpx;
  }

  .ml-86 {
    margin-left: 179.17rpx;
  }

  .mt-86 {
    margin-top: 179.17rpx;
  }

  .ml-88 {
    margin-left: 183.33rpx;
  }

  .mt-88 {
    margin-top: 183.33rpx;
  }

  .ml-90 {
    margin-left: 187.5rpx;
  }

  .mt-90 {
    margin-top: 187.5rpx;
  }

  .ml-92 {
    margin-left: 191.67rpx;
  }

  .mt-92 {
    margin-top: 191.67rpx;
  }

  .ml-94 {
    margin-left: 195.83rpx;
  }

  .mt-94 {
    margin-top: 195.83rpx;
  }

  .ml-96 {
    margin-left: 200rpx;
  }

  .mt-96 {
    margin-top: 200rpx;
  }

  .ml-98 {
    margin-left: 204.17rpx;
  }

  .mt-98 {
    margin-top: 204.17rpx;
  }

  .ml-100 {
    margin-left: 208.33rpx;
  }

  .mt-100 {
    margin-top: 208.33rpx;
  }
</style>