<template>
  <footer class="footer">
    <div class="content has-text-centered">
      <p>
        <strong>qrcode2stl</strong> by <a href="https://flxn.de">Felix Stein</a>. The source code is licensed
        <a href="http://opensource.org/licenses/mit-license.php">MIT</a>. The website content
        is licensed <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY NC SA 4.0</a>.
      </p>
      <p>
        If you like my stuff you can follow me on
        <a href="https://twitter.com/flxnde" target="_blank"><i class="fab fa-twitter"></i> Twitter</a>
        or on
        <a href="https://github.com/flxn" target="_blank"><i class="fab fa-github"></i> Github</a>
        or if you really like it you can even
        <a href="https://ko-fi.com/flxn256" target="_blank">
          💵☕️ buy me a coffee... or a tea, or a Club Mate (I actually don't like coffee)
        </a>
      </p>
      <p>
        If you need help or have some great idea, you can write me a mail:
        <a href="mailto:mail@flxn.de"><i class="fa fa-envelope"></i> mail@flxn.de</a>
      </p>
      <ShareButtons />
    </div>
  </footer>
</template>

<script>
import ShareButtons from './ShareButtons.vue';

export default {
  name: 'Footer',
  components: {
    ShareButtons,
  },
};
</script>

<style>

</style>
