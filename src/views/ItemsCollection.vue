<template>
  <main id="main">
    <Sidebar path="items" title="Список снаряжения"/>
    <section class="content">
      <router-view/>
    </section>
  </main>
</template>


<script>
import Sidebar from '@/components/Sidebar';

export default {
  components: {
    Sidebar,
  },
};
</script>
