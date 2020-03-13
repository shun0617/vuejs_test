<template>
    <div class="home">
        <input v-model="sendText" type="text">
        <Header :parentText="sendText"></Header>
        <p>ここは、Home.vueのページです。</p>
    </div>
</template>

<script>
    import Header from '../components/Header.vue'
    export default {
        data() {
            return {
                sendText: "テスト完了！"
            }
        },
        components: {
            Header
        }
    } 
</script>