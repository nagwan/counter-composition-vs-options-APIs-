<script>
export default {
    components: {},
    props: {},
    data() {
        return {
            count: 0,
        };
    },
    computed: {},
    methods: {
        increment() {
            this.count++;
        },

        decrement() {
            this.count--;
        },
    },
};
</script>
<template>
    <div>
        <button @click="decrement">-</button>
        Count is {{ count }}
        <button @click="increment">+</button>
    </div>
</template>
<style scoped lang='sass'></style>
