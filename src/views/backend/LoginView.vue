<script setup>
</script>

<template>
    <div class="login-container">
        <div class="panel-head">
            <h1 class="heading-upper">Login</h1>
            <div class="heading-desc">Welcome to login page</div>
        </div>
        <div class="panel-body">
            <div class="form-row">
                <div class="label">
                    User name
                </div>
                <input 
                    type="text"
                    name="email"
                    value=""
                    class="input-text"
                    autocomplete="off"
                >
            </div>

            <div class="form-row">
                <div class="label">
                    <div class="uk-flex uk-flex-between">
                        <span>Password</span>
                        <a href="" title="" class="forgot">Forgot password?</a>
                    </div>
                </div>
                <input 
                    type="password"
                    name="password"
                    value=""
                    class="input-text"
                    autocomplete="off"
                >
            </div>

            <div class="form-row">
                <div class="label">
                    <div class="uk-flex uk-flex-middle">
                        <input 
                            type="checkbox"
                            name="remember"
                            class="input-checkbox"
                            id="remeber-checkbox"
                        >
                        <label for="remeber-checkbox">Remember me!</label>
                    </div>
                </div>
            </div>

            <div class="form-row">
                <button class="uk-button btn-login">Login</button>
            </div>
        </div>

        <div class="panel-footer">
            <span>Coppyright vantuong197@gmail.com</span>
        </div>
    </div>
</template>
<style scoped>
    .login-container{
        max-height: 450px;
        max-width: 450px;
        flex: 1;
        margin: auto auto;
        background-color: white;
        /* text-align: center; */
        padding:50px;
        border-radius: 5px;
    }
    .panel-head{
        text-align: center;
    }
    .panel-head .heading-upper{
        font-weight: 700;
        text-transform: uppercase;
        font-size: 24px;
    }

    .panel-head .heading-desc{
        font-weight: 500;
        font-size: 16px;
    }

    .btn-login{
        background: rgb(132,90,223);
        width: 100%;
        border-radius: 5px;
        height: 40px;
        color: white;
    }

    .login-container .panel-footer{
        text-align: center;
    }

    .form-row .label span,
    .form-row .label{
        font-weight: 500;
        color: black;
    }

    .forgot{
        text-decoration: none;
    }

    .form-row .label .input-checkbox{
        margin-right: 5px;
    }
</style>
