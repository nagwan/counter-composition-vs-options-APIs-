<script setup>
import { ref } from "vue";

const count = ref(0);

function increment() {
    ++count.value;
}

function decrement() {
    --count.value;
}
</script>
<template>
    <div>
        <button @click="decrement">-</button>
        Count is {{ count }}
        <button @click="increment">+</button>
    </div>
</template>
<style scoped lang='sass'></style>
