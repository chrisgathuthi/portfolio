<script setup>
const getImageUrl = (path) => {
    return new URL(`./images/${path}`, import.meta.url).href;
};
const data = [
    {
        "icon": "python.png",
        "language": "Python"
    },
    {
        "icon": "javaScript.png",
        "language": "javascript"
    },
    {
        "icon": "go.png",
        "language": "Go"
    },
    {
        "icon": "django.png",
        "language": "Django"
    },
    {
        "icon": "vue.png",
        "language": "Vue"
    },
    {
        "icon": "git.png",
        "language": "Git"
    },
    {

        "icon": "linux.png",
        "language": "Bash"
    }
]
</script>
<template>
    <v-row justify="center" align="center">
        <v-col cols="auto" class="text-h4">
            Tech Stack
        </v-col>
    </v-row>
    <v-row justify="center" align="center" id="tech">
        <v-col cols="auto" v-for="(item, index) in data" :key="index">

            <v-card class="rounded" width="100" height="150">
                <v-card-text class=" h-100">
                    <v-img :src="getImageUrl(item.icon)" :alt="item.language" class="h-75" ></v-img>
                    
                    <span>{{ item.language }}</span>
                </v-card-text>
            </v-card>
        </v-col>
    </v-row>
</template>
<style scoped>
#tech {
    min-height: 50vh;
}
</style>