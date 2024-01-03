<script setup>
import { ref } from 'vue'

const show = ref(false)

const getImageUrl = (path) => {
    return new URL(`./images/${path}`, import.meta.url).href;
};
const data = [
    {
        "title": "Rystoport",
        "link": "https://rystoport.com/",
        "image": "https://rystoport.com/static/img/android-chrome-192x192.png",
        "summary":"lorem"
    },
    {
        "title": "Fastech",
        "link": "https://fastechinternet.co.ke/",
        "image": "https://fastechinternet.co.ke/assets/logo-730f1e60.png",
        "summary":"lorem"
    }
]
</script>
<template>
    <v-row justify="center" class="pt-8 my-8">
        <v-col cols="auto" class="text-h4">
            Projects
        </v-col>
    </v-row>
    <v-container>
        <v-row>
            <v-col cols="auto" v-for="(item, index) in data" :key="index">
                <v-card class="mx-auto my-8" width="344" >
                    <v-img :src="item.image" height="200px" contain></v-img>

                    <v-card-title>
                        {{ item.title }}
                    </v-card-title>


                    <v-card-actions>
                        <v-btn  color="orange-lighten-2" variant="text" :icon="show ? 'mdi-chevron-up' : 'mdi-chevron-down'"
                            @click="show = !show" class="ml-6 d-none">
                            Summary
                        </v-btn>
                        <v-divider vertical class="ml-6 mr-2" inset></v-divider>
                        <a :href="item.link" target="_blank" rel="noopener noreferrer">View</a>

                    </v-card-actions>

                    <v-expand-transition>
                        <div v-show="show">
                            <v-divider></v-divider>

                            <v-card-text>
                                I'm a thing. But, like most politicians, he promised more than he could deliver. You won't
                                have
                                time for
                                sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data
                                file! Hey,
                                you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to
                                find
                                a way
                                to escape.
                            </v-card-text>
                        </div>
                    </v-expand-transition>
                </v-card>

            </v-col>
        </v-row>

    </v-container>
</template>
