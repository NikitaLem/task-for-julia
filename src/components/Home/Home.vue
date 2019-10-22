<template>
  <div class="container">
    <blog-header></blog-header>
    <section class="section">
      <blog-body></blog-body>
    </section>
    <blog-footer></blog-footer>
  </div>
</template>

<script>
import Header from './Header/Header';
import Body from './Body/Body';
import Footer from './Footer/Footer';

export default {
  name: 'Home',
  components: {
    'blog-header': Header,
    'blog-body': Body,
    'blog-footer': Footer,
  },
};
</script>
