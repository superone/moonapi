<template>
    <div class="code-edit code-right">
        <div class="cont">

        </div>
    </div>
</template>

<script>
    export default Vue.extend({
        data () {
            return {
                msg: 'Hello World!'
            }
        },
        methods : {
            message( e ){
                console.log(e);
            }
        }
    })
</script>

<style>
</style>