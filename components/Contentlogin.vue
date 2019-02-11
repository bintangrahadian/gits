<template>
 <div class="top-content">
        <div class="container">

            <div class="row">
                <div class="col-sm-10 col-sm-offset-1 col-md-8 col-md-offset-2 col-lg-6 col-lg-offset-3 form-box">
                	<form role="form" action="" method="post" class="f1">
                        <div class="f1-steps" style="padding:70px;">
                            <div class="form-group">
                                <div class="input-group">
                                    <span class="input-group-addon-login">
                                        <i class="fa fa-user"></i>
                                    </span>
                                    <input type="text" class="form-control" name="username" placeholder="Username" style="border-bottom:1px solid #ccc;border-left:none;border-bottom:1px solid #ccc;border-top:none;border-right:none;">
                                </div>
                            </div>
                            <div class="form-group">
                                <div class="input-group">
                                    <span class="input-group-addon-login">
                                        <i class="fa fa-lock"></i>
                                    </span>
                                    <input type="text" class="form-control" name="password" placeholder="Password" style="border-bottom:1px solid #ccc;border-left:none;border-bottom:1px solid #ccc;border-top:none;border-right:none;">
                                </div>
                                <div class="form-group" style="display: inline;">
                                <a style="float: left;color:#000;padding:5px;font-size: 14px;"><input type="checkbox">Remember Me</a>
                                    <a style="float:right;color:#000;padding:5px;font-size: 14px;">Forgot Password</a>
                                </div>
                            </div>
                            <div class="form-group" style="padding-top:50px;">
                                <nuxt-link to="/province"><button type="submit" class="button-sign">Sign In</button></nuxt-link>
                                <p class="text-hint" style="font-size: 14px;">
                                    Don't have account? <b>Register</b>
                                </p>
                            </div>
                            
                        </div>
                	</form>
                </div>
            </div> 
        </div>
    </div>
</template>