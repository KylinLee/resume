<main>
  <section class="forword">
    我是李麒麟，一个文艺的理工男，喜欢动手制作，热爱生活。
    <p>一行</p>
    <p>一行</p>
    <p>又一行</p>
  </section>
  <p>大家好</p>
  <p>Hello World</p>
</main>

<style>
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
    left: 0;
  }

  .forword::after {
    content: "”";
    right: 0;
  }
</style>
