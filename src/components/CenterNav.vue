<template>
  <div class="center-div">
    <div class="so-box row">
        <ul class="type_li" >
          <li class="col-lg-1" style="margin-left: 200px"><a href="#">商品分类</a></li>
          <li class="col-lg-1"><a href="#">首页</a></li>
          <li class="col-lg-1"><a href="download/index.html">orsp下载</a></li>
          <li class="col-lg-1"><a href="#">精品推荐</a></li>
          <li class="col-lg-1"><a href="download/upload.html">上传物品</a></li>
          <li class="col-lg-1"><a href="search.html">交换物品</a></li>
          <li class="col-lg-1"><a href="#">超值购</a></li>
        </ul>

    </div>
  </div>
</template>

<script>
export default {
  name: 'CenterNav',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  methods:{

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

  *{margin: 0;padding: 0;list-style: none;}
  body, h1, h2, h3, h4, h5, h6, hr, p, blockquote, /* structural elements 结构元素 */
  dl, dt, dd, ul, ol, li, /* list elements 列表元素 */
  pre, /* text formatting elements 文本格式元素 */
  form, fieldset, legend, button, input, textarea, /* form elements 表单元素 */
  th, td /* table elements 表格元素 */ {
    margin: 0;
    padding: 0;
  }
  input{
    background:none;
    outline:none;
    border:0px;
  }
  ul, ol { list-style: none; }

  /** 重置文本格式元素 **/
  a { text-decoration: none;}
  .so-box {
    width: 100%;
    height: 30px;
    line-height: 30px;
    background-color: rgba(255, 144, 0, 0.53);
    /*position: fixed;*/
    /*top: 0px;*/
    z-index: 10;
  }

  .so-box-content {
    width: 850px;
    height: 30px;
    margin-left: 146px;

  }
  .type_li a:hover{
    color: red;
  }
</style>
