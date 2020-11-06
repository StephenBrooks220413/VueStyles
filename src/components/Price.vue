<template>
    <div>
        <div class="card-group">
            <div class="card">
                <div class="card-body">
                    <h1 class="card-title">VueBarber</h1>
                    <img src="https://images.unsplash.com/photo-1521490214993-bfb6f7dc096d?ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80" width="90%" alt="kid hair" />
                    <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
                    <center>
                        <h4 class="card-text">Kid's Cuts</h4>
                        <h2>$16</h2>

                        <button class="btn btn-primary">MAKE APPOINTMENT</button>
                    </center>
                </div>
            </div>
            <div class="card">
                <div class="card-body">
                    <h1 class="card-title">VueBarber</h1>
                    <img src="https://images.unsplash.com/photo-1565766046621-5548ffdf30af?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1052&q=80" width="90%" alt="men hair" />
                    <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
                    <center>
                        <h4 class="card-text">Men's Cuts</h4>
                        <h2>$16</h2>

                        <button class="btn btn-primary">MAKE APPOINTMENT</button>
                    </center>
                </div>
            </div>
            <div class="card">
                <div class="card-body">
                    <h1 class="card-title">VueBarber</h1>
                    <img src="https://images.unsplash.com/photo-1557254328-d5eb837709b4?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80" width="90%" alt="men hair" />
                    <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
                    <center>
                        <h4 class="card-text">Women's Cuts</h4>
                        <h2>$16</h2>

                        <button class="btn btn-primary">MAKE APPOINTMENT</button>
                    </center>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Price',
        props: {
            msg: String
        }
    };
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
    #schedule {
        margin-top: 90px;
        margin-bottom: 90px;
        border: 1px solid grey;
        border-radius:4px;
        width: 350px;
        height: auto;
        padding-top:20px;
        padding-bottom:30px;
    }
</style>
