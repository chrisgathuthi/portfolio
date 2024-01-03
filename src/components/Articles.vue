<script setup>
const data = [
    {
        "title": "Asynchronous form field validation with HTMX and Django.",
        "image": "https://miro.medium.com/v2/resize:fit:720/format:webp/1*q2nn5LnlI6Er5UAzP_WjzQ.png",
        "link": "https://medium.com/@soverignchriss/asynchronous-form-field-validation-with-htmx-and-django-eb721165b5e8"
    },
    {
        "title": "Chat Application with Django-channels & Htmx.",
        "image": "https://miro.medium.com/v2/resize:fit:720/format:webp/1*ruxX_5TyIWPDN0mx8VbfUg.png",
        "link": "https://medium.com/@soverignchriss/chat-application-with-django-channels-htmx-dd8174f59a03"

    },
    {
        "title": "Understanding select_related and prefetch_related Methods in Django ORM.",
        "image": "https://miro.medium.com/v2/resize:fit:720/format:webp/1*VjVO6-6TYcJuFzLNW2alhg.png",
        "link": "https://medium.com/@soverignchriss/understanding-select-related-and-prefetch-related-methods-in-django-orm-db36003d5fbf"

    },
    {
        "title": "Querying Related Objects in Django Web Framework",
        "image": "https://miro.medium.com/v2/resize:fit:720/format:webp/1*VjVO6-6TYcJuFzLNW2alhg.png",
        "link": "https://medium.com/@soverignchriss/querying-related-objects-in-django-web-framework-3aece5bd927d"
    }
]
</script>
<template>
    <v-row justify="center" align="center">
        <v-col cols="auto" class="text-h4">
            Articles
        </v-col>
    </v-row>
        <v-row justify="center" align="center" class="px-3">
            <v-col cols="auto" v-for="(item, index) in data" :key="index">
                <v-card class="mx-auto my-8" max-width="380" min-height="300">
                    <v-img :src="item.image" height="200px" cover></v-img>

                    <v-card-text class="text-subtitle-1">
                        {{ item.title }}
                    </v-card-text>
                    <v-card-subtitle>
                        <a :href="item.link" target="_blank" class="block">
                            Read more
                        </a>
                    </v-card-subtitle>
                </v-card>

            </v-col>
        </v-row>

</template>