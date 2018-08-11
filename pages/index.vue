<template>
    <div class="container">
        <h1>Hearthstone</h1>
       <p>{{ introduction }}</p>
    </div>
</template>

<script>
export default {
    data() {
        return {
            introduction: "Lets enjoy Hearthstone!"
        };
    }
};
</script>

<style lang="scss">
.container {
    min-height: 50vh;
    display: grid;
    grid-template-columns: 1fr;
    align-items: center;
    text-align: center;
    font-family: "Quicksand", "Source Sans Pro", -apple-system,
        BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial,
        sans-serif;
    h1 {
        font-weight: 300;
        font-size: 100px;
        color: #35495e;
        letter-spacing: 1px;
    }
    p {
        margin: 0 8rem;
    }
}
</style>
