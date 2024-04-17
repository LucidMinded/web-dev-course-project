<template>
    <div>
        <Posts :posts="posts" :users="users"/>
    </div>
</template>

<script>
import Posts from "@/components/page/Posts.vue";

export default {
    name: "Index",
    components: {Posts},
    props: ["posts", "users"]
}
</script>

<style scoped>

</style>
