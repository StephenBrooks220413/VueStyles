<template>
    <div>
        <div class="card-group">
            <div class="card">
                <div class="card-body">
                    <h1 class="card-title">VueBarber</h1>
                    <img src="https://images.unsplash.com/photo-1521490214993-bfb6f7dc096d?ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80" width="90%" alt="kid hair" />
                    <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
                    <center>
                        <p class="card-text"><h4>Kid's Cuts</h4></p>
                        <h2>$16</h2>

                        <button class="btn btn-primary">Kids' Gallery</button>
                    </center>
                </div>
            </div>
            <div class="card">
                <div class="card-body">
                    <h1 class="card-title">VueBarber</h1>
                    <img src="https://images.unsplash.com/photo-1565766046621-5548ffdf30af?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1052&q=80" width="90%" alt="men hair" />
                    <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
                    <center>
                        <p class="card-text"><h4>Men's Cuts</h4></p>
                        <h2>$16</h2>

                        <button class="btn btn-primary">Men's Gallery</button>
                    </center>
                </div>
            </div>
            <div class="card">
                <div class="card-body">
                    <h1 class="card-title">VueBarber</h1>
                    <img src="https://images.unsplash.com/photo-1557254328-d5eb837709b4?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80" width="90%" alt="men hair" />
                    <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
                    <center>
                        <p class="card-text"><h4>Women's Cuts</h4></p>
                        <h2>$16</h2>

                        <button class="btn btn-primary">Women's Gallery</button>
                    </center>
                </div>
            </div>
        </div>
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
    .card-body h1 {
        color: orangered;
    }
    .card-group {
        margin-bottom: 130px;
    }
    .footer {
        margin-top:70px;
        padding-top: 60px;
        padding-bottom: 60px;
    }
</style>
