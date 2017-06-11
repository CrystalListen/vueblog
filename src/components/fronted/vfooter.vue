<template lang="html">
  <footer>
     <div class="footavatar">
     <img src="../../assets/img/photo.jpg" class="footphoto">
     <ul class="footinfo">
       <p class="fname"><a href="../zipline-build-a-personal-portfolio-webpage/index.html" alt="点击查看简历">轻舞飞扬</a>  </p>
       <p class="finfo">性别：女 年龄：25</p>
       <p>现居：广东深圳</p></ul>
       </div>
       <div class="Copyright">
    <p>Copyrights © 2017 轻舞飞扬. All Rights Reserved.</p>
    </div>
  </footer>
  
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>
 footer { border-top: .3em solid #f16e50; background: #242221; width: 100%; }
.footavatar { width: 700px; margin: auto; position: relative; color: #666; }
.footavatar img{ height:110px}
.footphoto { position: absolute; top: -3.5em; left: 2em; display: block; border: #F16E50 0.3em solid; }
.footinfo { display: block; padding: 0 0 0 160px }
.fname { color: #f16e50; margin-top: 16px; font-size: 18px; line-height: 1.5em; }
.fname a { color: #f16e50; }
.finfo { line-height: 1.6em; }
.Copyright { text-align: center; color: #959595; margin: 40px 0 0 }
@media screen and (max-width:768px){
    footer{
      height: 6rem;
    }
  }
</style>
