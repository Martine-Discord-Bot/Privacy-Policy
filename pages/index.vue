<template>
  <div id="_saber" data-server-rendered="true">
    <div>
      <header class="site-header">
        <div class="wrapper">
          <a
            href="/"
            aria-current="page"
            rel="author"
            class="site-title router-link-exact-active router-link-active"
          >Martine - Privacy Policy</a>
          <nav class="site-nav">
            <input type="checkbox" id="nav-trigger" class="nav-trigger" />
            <label for="nav-trigger">
              <span class="menu-icon">
                <svg viewBox="0 0 18 15" width="18px" height="15px">
                  <path
                    d="M18,1.484c0,0.82-0.665,1.484-1.484,1.484H1.484C0.665,2.969,0,2.304,0,1.484l0,0C0,0.665,0.665,0,1.484,0 h15.032C17.335,0,18,0.665,18,1.484L18,1.484z M18,7.516C18,8.335,17.335,9,16.516,9H1.484C0.665,9,0,8.335,0,7.516l0,0 c0-0.82,0.665-1.484,1.484-1.484h15.032C17.335,6.031,18,6.696,18,7.516L18,7.516z M18,13.516C18,14.335,17.335,15,16.516,15H1.484 C0.665,15,0,14.335,0,13.516l0,0c0-0.82,0.665-1.483,1.484-1.483h15.032C17.335,12.031,18,12.695,18,13.516L18,13.516z"
                  />
                </svg>
              </span>
            </label>
            <div class="trigger">
              <a
                href="/"
                aria-current="page"
                class="page-link router-link-exact-active router-link-active"
              >Home</a>
            </div>
          </nav>
        </div>
      </header>
      <main aria-label="Content" class="page-content">
        <div class="wrapper">
          <article class="post">
            <header class="post-header">
              <h1 class="post-title"></h1>
            </header>
            <div class="post-content">
              <h1 id="contents">Contents</h1>
              <ol>
                <li>
                  <a
                    href="/#what-data-do-Martine-collects-about-you"
                  >What data do Martine collects about you</a>
                </li>
                <li>
                  <a href="/#how-do-we-use-your-data">How do we use your data</a>
                </li>
                <li>
                  <a href="/#how-to-request-your-data-removal">How to request your data removal</a>
                </li>
              </ol>
              <h2 id="what-data-do-martine-collects-about-you">
                <a
                  href="/#what-data-do-Martine-collects-about-you"
                >What data do Martine collects about you</a>
              </h2>
              <p>Martine collect some amount of data about users for the bot's normal operations. Which is in particular the ID your user is assigned by Discord. Linked to a handful of things depending on what you interact with in the bot.</p>
              <h2 id="how-do-we-use-your-data">
                <a href="/#how-do-we-use-your-data">How do we use your data</a>
              </h2>
              <p>
                It is used so the bot can take the appropriate actions and respect settings that has been set.
                Such as: any user or server setting that you configure through the bot, moderation actions against your Discord account if enabled in a server where the bot is in, any interaction with the bot that requires to store your Discord user ID.
              </p>
              <p>See Discord Privacy Policy for more information about your Discord data.</p>
              <h2 id="how-to-request-your-data-removal">
                <a href="/#how-to-request-your-data-removal">How to request your data removal</a>
              </h2>
              <p>
                The command
                <code>,mydata forgetme</code> provides a way to remove large portions of your own data from the bot. This command will not remove operational data, such as a record that your Discord account was the target of a moderation action.
              </p>
            </div>
          </article>
        </div>
      </main>
      <footer class="site-footer h-card">
        <div class="wrapper">
          <div class="footer-col-wrapper">
            <div class="footer-col one-half">
              <h2 class="footer-heading">Martine - Privacy Policy</h2>
              <ul class="contact-list">
                <li class="p-name">Predä - 11/08/2020</li>
              </ul>
            </div>
          </div>
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
export default {
  layout: 'page',
  head: {
    meta: [
      {
        name: "description",
        content: "Martine Privacy Policy",
      },
    ],
  },
};
</script>