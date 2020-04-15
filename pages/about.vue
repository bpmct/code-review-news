<template>
  <div id="about-page" class="page-wrapper about-page content-page">
    <site-hero
      title="About Us"
      subtitle=""
      image="/uploads/coding.jpg"
    ></site-hero>
    <main-section theme="sidebar-right">
      <template v-slot:default>
        <div class="tile is-ancestor">
          <div class="tile is-parent">
            <article class="tile is-child box">
              <figure class="image is-1by1 ">
                <opti-image
                  :src="require('~/assets/uploads/ben.jpg').src"
                  :srcset="require('~/assets/uploads/ben.jpg').srcSet"
                />
              </figure>
              <br />
              <div class="content">
                <p>
                  Have a question? Want to be featured? Send me an email:
                  <a
                    href="
                mailto:me@bpmct.net
              "
                  >
                    me@bpmct.net
                  </a>
                </p>
              </div>
            </article>
          </div>
          <div class="tile is-parent is-8">
            <article class="tile is-child box">
              <p class="title">
                Hey 👋
              </p>
              <p>
                <a href="https://codereviewnews.com">Code Review News</a> is a
                simple blog highlighting the latest news and updates on code
                review tools and practices. Currently being ran by Ben Potter.
              </p>
              <br />
              <p>
                Huge shoutout to <a href="https://netlify.com">Netlify</a>,
                <a href="https://nuxtjs.org/">Nuxt.js</a>, and the
                <a href="https://github.com/danielkellyio/awake-template">
                  awake template
                </a>
                by danielkellyio for making this site so fast! 😁
              </p>
              <hr />
              <p>
                ⚠ Disclaimer: I do contract social media work for
                <a href="https://codestream.com/use-cases/code-reviews">
                  CodeStream
                </a>
                , which currently offers an in-IDE code review tool.
              </p>
            </article>
          </div>
        </div>
      </template>
      <template v-slot:sidebar>
        <h3 class="subtitle is-4">
          Latest Posts
        </h3>
        <!-- Latest Posts -->
        <posts-grid :per-row="1" :number="2" />
      </template>
    </main-section>
  </div>
</template>
<script>
export default {
  head() {
    return {
      title: `About | ${this.$siteConfig.siteName}`
    }
  }
}
</script>
