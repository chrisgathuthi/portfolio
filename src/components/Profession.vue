<script setup>
import Articles from './Articles.vue';
import Bio from './Bio.vue';
import Projects from './Projects.vue';
import TechStack from './TechStack.vue';

</script>
<template>
    <section>
        <Bio />
    </section>
    <section>
        <TechStack />
    </section>
    <v-divider></v-divider>
    <section>
        <Projects />
    </section>
    <v-divider></v-divider>
    <section>
        <Articles />
    </section>
</template>