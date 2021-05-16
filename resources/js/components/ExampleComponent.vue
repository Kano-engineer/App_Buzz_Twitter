<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">Example Component</div>

                    <div class="card-body">
                        {{ message }}
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

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
