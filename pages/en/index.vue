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
        'I have been working in frontend development since 2019. For two years, I worked as a freelancer, participated in the development of large projects, as well as the enhancement and refactoring of existing solutions for clients. In my free time, I enjoy sports and reading.',
      ogDescription:
        'I have been working in frontend development since 2019. For two years, I worked as a freelancer, participated in the development of large projects, as well as the enhancement and refactoring of existing solutions for clients. In my free time, I enjoy sports and reading.',
      ogImage: '/ogImageEn.png',
      twitterCard: 'summary_large_image',
    });
  },
};
</script>
