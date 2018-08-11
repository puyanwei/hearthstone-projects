<template>
    <div class="container">
        <h1>{{ testText }}</h1>
    </div>
</template>

<script>
export default {
    data() {
        return {
            testText: "This is a test"
        };
    }
};
</script>

<style lang="scss">
.container {
    margin: 1rem;
}
</style>
