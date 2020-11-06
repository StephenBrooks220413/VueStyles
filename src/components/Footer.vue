<template>
    <div class="container footer">
            <hr />
            <div class="row text-center">
                <div class="col-md-4">
                    <h1>Locate</h1>
                    <address>
                        1141 Main St - Some City, State
                    </address>
                </div>
                <div class="col-md-4">
                    <h1>About</h1>
                    Tincidunt integer eu augue augue nunc elit dolor
                    luctus placerat scelerisque euismod, iaculis eu.
                </div>
                <div class="col-md-4">
                    <h1>Developer</h1>
                    Email / Call
                </div>
            </div>
    </div>
</template>

<script>
    export default {
        name: 'Footer',
        props: {
            msg: String
        }
    };
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
</style>
