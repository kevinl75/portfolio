<script>
import IconItem from './IconItem.vue'
export default {
    data() {
        return {
            icons: [
                {
                    id: 1,
                    src: "src/assets/icons8-programming-24.png",
                    text: "My GitHub account",
                    url: "https://github.com/kevinl75",
                },
                {
                    id: 2,
                    src: "src/assets/icons8-twitter-24.png",
                    text: "My Twitter account",
                    url: "https://twitter.com/kevinLtp59",
                },
                {
                    id: 3,
                    src: "src/assets/icons8-linkedin-24.png",
                    text: "My Linkedin account",
                    url: "http://linkedin.com/in/kletupe60/",
                }
            ]
        };
    },
    components: { IconItem }
}
</script>


<template>
    <div class="flex justify-around mt-8">
        <IconItem
            v-for="icon in icons"
            v-bind:key="icon.id"
            v-bind:input="icon"
        />
    </div>
</template>


<style>


</style>