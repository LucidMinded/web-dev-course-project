<template>
    <div>
        <Post v-for="post in posts" :post="post" :users="users" :key="post.id"/>
    </div>
</template>

<script>
import Post from "@/components/page/Post.vue";

export default {
    name: "Posts",
    components: {Post},
    props: ["posts", "users"],
}
</script>

<style scoped>

</style>
