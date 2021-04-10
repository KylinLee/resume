<main>
  <section class="forword">
    欢迎来到这里，我叫李麒麟，一个热爱生活的普通人，现就读本科三年级。
    关于生活，我希望每一天过起来是不一样的额色彩。写代码时是编辑器的<span
      class="dark">深色</span
    >，喜欢旅游亲近大自然，在相机镜头中是<span class="blue">蓝色</span>和<span
      class="green">绿色</span
    >的，当然我也是一个传统文化的爱好者，诸子百家的著作对我的影响很大。
    我一直深信，兴趣是学习的最大动力，作为一个非科班的Coder，支持我持续学习的就是热爱吧。
    当然我本身的专业也让我了解了很多，数字图像处理是我比较喜欢的课程，遥感课程也让我对机器学习产生了一些兴趣。
    最开始我是一个前端开发者，一些偶然的机会，我对推荐系统产生了极大的兴趣，现在在阅读一些机器学习的书籍。
  </section>
</main>

<style>
  :root {
    font-size: 10px;
  }
  main {
    padding: 1em;
    width: 90%;
    max-width: 21cm;
    margin: 0 auto;
  }

  .forword {
    display: block;
    position: relative;
    padding: 2rem 4rem;
    border-radius: 6px;
    line-height: 1.5;
    text-indent: 2em;
    font-size: 2rem;
    letter-spacing: 0.2rem;
    color: #131124;
  }

  .forword::before,
  .forword::after {
    display: inline-block;
    position: absolute;
    line-height: 4rem;
    font-size: 4rem;
    color: rgb(209 209 209);
  }

  .forword::before {
    content: "“";
    top: 0;
    left: -2rem;
  }

  .forword::after {
    content: "”";
    right: 0;
    bottom: -2rem;
  }

  .dark,
  .blue,
  .green {
    color: #f1f1f1;
    padding: 0.5rem 0.2rem;
  }

  .dark {
    background-color: #393733;
  }

  .blue {
    color: #f1f1f1;
    background-color: #5698c3;
  }

  .green {
    color: #393733;
    background-color: #8cc269;
  }
</style>
