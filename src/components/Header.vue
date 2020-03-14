<template>
    <div class="header">
        <button @click="userClick" type="button">受け取る</button>
        <p>{{show}}</p>
    </div>
</template>

<script>
export default {
    data() {
        return {
            show: ''
        }
    },
    props: ["parentText"],
    methods: {
        userClick() {
                this.show = this.parentText
        }
    }
}
</script>

