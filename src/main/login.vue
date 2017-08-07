<template>
  <div class="login-body">
    <div class="container">

      <form class="form-signin" action="index.html">
        <h2 class="form-signin-heading">登陆</h2>
        <div class="login-wrap">
          <div class="user-login-info">
            <input type="text" class="form-control" placeholder="登陆名" autofocus>
            <input type="password" class="form-control" placeholder="密码">
          </div>
          <label class="checkbox">
            <input type="checkbox" value="remember-me"> 记住我
            <span class="pull-right">
                    <a data-toggle="modal" href="#myModal"> 忘记密码?</a>
                </span>
          </label>
          <button class="btn btn-lg btn-login btn-block" type="submit">登 陆</button>
        </div>

      </form>

    </div>
  </div>

</template>

<script>

</script>
<style>
  .login-body {
    background:url("../assets/img/login.jpg");
    background-size:cover;
    background-position: center;
    position: fixed;
    width:100%;
    height:100%;
    overflow: auto;
  }
  .form-signin {
    max-width:330px;
    margin:100px auto;
    /*background:#fff;*/
    border-radius:5px;
    -webkit-border-radius:5px;
  }
  .form-signin h2.form-signin-heading {
    margin:0;
    padding:35px 15px;
    text-align:center;
    background-color: rgba(41, 127, 199, 0.4);
    border-radius:5px 5px 5px 5px;
    -webkit-border-radius:5px 5px 0 0;
    color:#fff;
    font-size:18px;
    text-transform:uppercase;
    font-weight:300;
    font-family:'Open Sans',sans-serif;
  }
  .form-signin .checkbox {
    margin-bottom:14px;
  }
  .form-signin .checkbox {
    font-weight:normal;
    color:#b6b6b6;
    font-weight:300;
    font-family:'Open Sans',sans-serif;
  }
  .form-signin .form-control {
    position:relative;
    font-size:16px;
    height:auto;
    padding:10px;
    -webkit-box-sizing:border-box;
    -moz-box-sizing:border-box;
    box-sizing:border-box;
  }
  .form-signin .form-control:focus {
    z-index:2;
  }
  .form-signin input[type="text"],.form-signin input[type="password"] {
    margin-bottom:15px;
    border-radius:5px;
    -webkit-border-radius:5px;
    border:1px solid #eaeaea;
    box-shadow:none;
    font-size:12px;
  }
  .form-signin .btn-login {
    background:rgba(31,171,182,0.6);
    color: #66dadd;
    font-weight:300;
    font-family:'Open Sans',sans-serif;
    margin:20px 0 5px;
  }
  .form-signin p {
    text-align:left;
    color:#b6b6b6;
    font-size:16px;
    font-weight:300;
  }
  .form-signin .btn-login:hover{
    background-color: #1fb5ac;
    color: #ffffff;
  }
  .form-signin a,.form-signin a:hover {
    color:#1fb5ac;
  }
  .form-signin a:hover {
    text-decoration:underline;
  }
  .login-wrap {
    padding:20px;
    position:relative;
  }
  .user-login-info {
    /*background:#eaeaec;*/
    margin:-20px -20px 20px -20px;
    padding:20px;
  }
  .user-login-info .form-control:last-child {
    margin-bottom:0 !important;
  }
  .registration {
    position:absolute;
    right:0;
    bottom:-35px;
    color: #b8bab9;
  }
</style>
