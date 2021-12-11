<template>
  <div>
    <main>
      <header>
        <h1>Roster</h1>
      </header>
      <div v-for="student in students" :key="student.id">
        <Card :person="student" />
      </div>
    </main>
  </div>
</template>

<script>
export default {
  async asyncData({ $content, params }) {
    const students = await $content("roster").fetch();

    return {
      students,
    };
  },
};
</script>
