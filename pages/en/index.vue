<template>
  <div class="container">
    <TheMain />
    <TheExperience />
    <TheContacts />
  </div>
</template>

<script>
export default {
  mounted() {
    this.$i18n.locale = 'en';
  },
  setup() {
    useSeoMeta({
      title: 'Fedyanov Stepan – Frontend Developer | CV',
      ogTitle: 'Fedyanov Stepan – Frontend Developer | CV',
      description:
        'Frontend developer at VueJS. I am currently an intern at the Art. Lebedev Studio. I have been working as a freelancer for two years, participating in the development of large projects, as well as updating and refactoring existing solutions for clients. In my free time, I enjoy sports and reading.',
      ogDescription:
        'Frontend developer at VueJS. I am currently an intern at the Art. Lebedev Studio. I have been working as a freelancer for two years, participating in the development of large projects, as well as updating and refactoring existing solutions for clients. In my free time, I enjoy sports and reading.',
      ogImage: '/ogImageEn.png',
      twitterCard: 'summary_large_image',
    });
  },
};
</script>
