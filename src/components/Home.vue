<template>
    <div>
        <div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="https://images.unsplash.com/photo-1503951914875-452162b0f3f1?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80" class="d-block w-100" alt="barber">
                    <div class="carousel-text d-sm-block">
                        <h1>About Beard Trimming</h1>
                        <h4>Nulla vitae elit libero, a pharetra augue mollis interdum.</h4>
                        <button class="btn btn-danger">More Info</button>
                    </div>
                </div>
            </div>
        </div>

        <div class="jumbotron features text-center">
            <hr />
            <h1>Special Features</h1>
            <hr />
        </div>
        
        <div class="container spacer">
            <div class="row text-center">
                <div class="col-md-4">
                    <img src="https://images.unsplash.com/photo-1598887142487-3c854d51eabb?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80" width="90%" alt="beards" />
                    Tincidunt integer eu augue augue nunc elit dolor, luctus placerat
                </div>
                <div class="col-md-4">
                    <img src="https://images.unsplash.com/photo-1493256338651-d82f7acb2b38?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80" width="90%" alt="hair" />
                    scelerisque euismod, iaculis eu lacus nunc mi elit, vehicula ut

                </div>
                <div class="col-md-4">
                    <img src="https://images.unsplash.com/photo-1524230616393-d6229fcd2eff?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80" width="90%" alt="barber tools" />
                    laoreet ac, aliquam sit amet justo nunc tempor, metus vel.
                </div>
            </div>
        </div>
        <br><br>
        <div class="container articleBg text-center" style="width:70%">
            <h1 class="display-4">Article Title</h1>
            <p>
                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Corrupti laborum, 
            pariatur quos molestiae sit similique necessitatibus optio reiciendis suscipit, asperiores 
            beatae expedita accusantium! Eveniet, repellendus nisi molestias magnam ab quibusdam? Lorem 
            ipsum dolor sit amet consectetur, adipisicing elit. Voluptate illo molestiae sunt eaque 
            aspernatur modi at rerum, consequuntur laboriosam quam soluta dolorum dolore dolorem, adipisci 
            libero. Quae aliquid adipisci architecto!
            </p>
        </div>
        <br><br><br><br><br><br>
        <div class="container">
            <div class="row">
                <div class="col-md-6 text-center">
                    <img src="https://momunicipallaw.files.wordpress.com/2017/02/cell-phone1.png" width="240px" height="290px" alt="phone">
                </div>
                <div class="col-md-6">
                    <h1>Flexibility</h1>
                    <p>
                        Built mobile first and remains flexible for any viewing device,
                        using Vue.js and Bootstrap.
                    </p>
                    <br><br>
                    <h1>Reliability</h1>
                    <p>
                        Light for bandwidth and fast on web pages, no need to worry about 
                        acquiring more servers.
                    </p>
                </div>
            </div>
        </div>
        <br><br><br><br><br><br>
    </div>
</template>

<script>
    export default {
        name: 'Home',
        props: {
            msg: String
        }
    };
    // Initialize and add the map
    
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
    .carousel-text {
        color: red;
        position: absolute;
        top: 35%;
        left: 20%;
    }
    .carousel-text h1 {
        color: red;
    }
        .carousel-text h4 {
            color: red;
        }
    .spacer {
        margin-top: 80px;
        margin-bottom: 80px;
    }

    .features {
        margin-top: 130px;
        background-color:white;
    }
    .features hr {
        width: 60%;
    }
    .articleBg{
        background: url(https://i.stack.imgur.com/M2A8V.png) no-repeat center center; 
        -webkit-background-size: cover;
        -moz-background-size: cover;
        -o-background-size: cover;
        background-size: cover;
    }
    .articleBg p {
        font-weight: 600!important;
    }
</style>

