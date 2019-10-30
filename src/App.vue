<template>
    <div class="container">
        <div class="row">
            <div class="col-xs-12 col-sm-8 col-sm-offset-2 col-md-6 col-md-offset-3">
                <h1>Built-in Directives</h1>
                    <p v-text="' v text directivesome text'"></p>
                    <p v-html=" 'html directive' "></p>
            </div>
        </div>


        <div class="row">
            <div class="col-xs-12 col-sm-8 col-sm-offset-2 col-md-6 col-md-offset-3">
                <h1>Built-in Directives</h1>
                    <h1>custom directive</h1>
                   <p v-highlight="'red'">color directive</p> 
            </div>
        </div>
    </div>
</template>

<script>
    export default {
    }
</script>

<style>

</style>
