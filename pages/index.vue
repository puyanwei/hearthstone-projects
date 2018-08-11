<template>
    <div class="container">
        <h1>Layout Training</h1>
       <p>{{ introduction }}</p>
    </div>
</template>

<script>
export default {
    data() {
        return {
            introduction:
                "This is my layout training website that I'm going to use to practice copying webpages. I will be trying to use CSS grid most of the time, using the minimal amount of code possible to achieve the correct responsive designs."
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
    font-family: "Quicksand", "Source Sans Pro", -apple-system,
        BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial,
        sans-serif;
    h1 {
        text-align: center;
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
