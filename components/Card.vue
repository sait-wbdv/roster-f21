<template>
  <article>
    <nuxt-img :src="person.image" />
    <div>
      <h3>{{ person.name }}</h3>
      <p>{{ person.tagline }}</p>
      <ul>
        <li v-for="social in person.socials" :key="social.id">
          <a :href="social.link" v-html="social.label"></a>
        </li>
      </ul>
    </div>
  </article>
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