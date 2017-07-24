<template>
    <div class="c2f">
        <h2>C2F</h2>
        <h2>華氏溫度：{{ cel * 9/5 + 32 }}</h2>
        <h2>華氏溫度：{{ fa }}</h2>
        攝氏：
        <input type="number" v-model="cel" /> °C
    </div>
</template>

<script>
export default {
    name: 'c2f',
    data() {
        return {
            cel: 0
        }
    },
    computed: {
        fa() {
            return this.cel * 9 / 5 + 32;
        }
    },
    methods: {
        temConvert(val) {
    
        }
    }
} 
</script>