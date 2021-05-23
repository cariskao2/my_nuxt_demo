<template>
  <div id="wrapper">
    <Header></Header>
    <Menu></Menu>

    <!-- Main -->
    <div id="main">
      <div class="inner">
        <header>
          <h1>
            This is Phantom, a free, fully responsive site<br />
            template designed by <a href="http://html5up.net">HTML5 UP</a>.
          </h1>
          <p>
            Etiam quis viverra lorem, in semper lorem. Sed nisl arcu euismod sit
            amet nisi euismod sed cursus arcu elementum ipsum arcu vivamus quis
            venenatis orci lorem ipsum et magna feugiat veroeros aliquam. Lorem
            ipsum dolor sit amet nullam dolore.
          </p>
        </header>
        <section class="tiles">
          <article class="style1">
            <span class="image">
              <img src="~/assets/images/pic01.jpg" alt="" />
            </span>
            <a href="generic.html">
              <h2>Magna</h2>
              <div class="content">
                <p>
                  Sed nisl arcu euismod sit amet nisi lorem etiam dolor veroeros
                  et feugiat.
                </p>
              </div>
            </a>
          </article>
        </section>
      </div>
    </div>
    <Footer></Footer>
  </div>
</template>

<script>
  import Header from '~/components/Header.vue'
  import Menu from '~/components/Menu.vue'
  import Footer from '~/components/Footer.vue'

  export default { components: { Header, Menu, Footer } }
</script>

<style>
  .container {
    margin: 0 auto;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
  }

  .title {
    font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
      'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
    display: block;
    font-weight: 300;
    font-size: 100px;
    color: #35495e;
    letter-spacing: 1px;
  }

  .subtitle {
    font-weight: 300;
    font-size: 42px;
    color: #526488;
    word-spacing: 5px;
    padding-bottom: 15px;
  }

  .links {
    padding-top: 15px;
  }
</style>
