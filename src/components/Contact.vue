<template>
    <div class="container">
        <form action="/" method="POST">
            <div class="form-group">
                <label for="email">Email address</label>
                <input type="email" name="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
            </div>
            <div class="form-group">
                <label for="name">Name</label>
                <input type="text" name="name" class="form-control" id="exampleInputPassword1">
            </div>
            <div class="form-group">
                <label for="exampleFormControlTextarea1">Message</label>
                <textarea name="message" class="form-control" id="exampleFormControlTextarea1" rows="5"></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Submit</button>
        </form>
    </div>
</template>

<script>
    export default {
        name: 'Contact',
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
