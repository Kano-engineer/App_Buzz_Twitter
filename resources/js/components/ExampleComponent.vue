<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">Example Component</div>

                    <div id="app">
                    {{ message }}
                    </div>

                </div>
            </div>
        </div>
    </div>
</template>

<style>
#app {
    font-size: 3rem;
    font-weight: bold;
    text-align: center;
    margin: 30% auto;
    color: #41BA83;
}
</style>

<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }

    const vm = new Vue({
    el: "#app",
    data: {
      message: "Hello Vue.js!!",
    },
    });

</script>
