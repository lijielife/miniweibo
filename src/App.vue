<script>
export default {
  created() {
    console.log('app created');
  },
};
</script>

<style>
.container {
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
  padding: 200rpx 0;
  box-sizing: border-box;
}
/* this rule will be remove */
* {
  transition: width 2s;
  -moz-transition: width 2s;
  -webkit-transition: width 2s;
  -o-transition: width 2s;
}

@font-face {
    font-family: 'iconfont';
    src: url(data:application/font-woff2;charset=utf-8;base64,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) format('woff2'),
        url(data:application/font-woff;charset=utf-8;base64,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) format('woff');
    font-weight: normal;
    font-style: normal;
}

.iconfont {
  font-family:"iconfont" !important;
  font-size:16px;
  font-style:normal;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.icon-guanyuwomen:before { content: "\e601"; }

.icon-hezuofang:before { content: "\e602"; }

.icon-mulu:before { content: "\e603"; }

.icon-pinglun:before { content: "\e604"; }

.icon-sousuo:before { content: "\e605"; }

.icon-shuqian:before { content: "\e606"; }

.icon-zuijinyuedu:before { content: "\e607"; }

.icon-xihuan:before { content: "\e608"; }

.icon-dianzan:before { content: "\e610"; }
</style>
