
<template>
    <div class="header">
        <input @click="userClick" type="submit" placeholder="受け取る">
        <p>{{text}}</p>
    </div>
</template>

<script>
export default {
    props: ["parentText"],

    methods: {
        userClick() {
                this.text = this.parentText
        }
    }
}
</script>

<style scoped>

</style>