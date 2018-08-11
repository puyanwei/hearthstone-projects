<template>
    <div class="container">
        <h1>{{ text }}</h1>
    </div>
</template>

<script>
export default {
    data() {
        return {
            text: "We're gonna open some packs!"
        };
    }
};
</script>

<style lang="scss">
.container {
    margin: 1rem;
}
</style>
