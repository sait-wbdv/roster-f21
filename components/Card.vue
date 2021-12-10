<template>
  <figure>
    <nuxt-img :src="person.image" />
    <figcaption>
      <h3>{{ person.name }}</h3>
      <p>{{ person.tagline }}</p>
      <ul>
        <li v-for="social in person.socials" :key="social.id">
          <a :href="social.link" v-html="social.label"></a>
        </li>
      </ul>
    </figcaption>
  </figure>
</template>
<script>
export default {
  props: {
    person: {
      type: Object,
    },
  },
};
</script>
<style scoped>

</style>