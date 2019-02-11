<template>
<div class="top-content">
        <div class="container">

            <div class="row">
                <div class="col-sm-10 col-sm-offset-1 col-md-8 col-md-offset-2 col-lg-6 col-lg-offset-3 form-box">
                    <form role="form" action="" method="post" class="f1">
                        <div class="f1-steps">
                            <div class="f1-progress">
                            </div>

                            <div class="f1-step active">
                                <div class="f1-step-icon">
                                    <i class="fa fa-check"></i>
                                </div>
                            </div>

                            <div class="f1-step active">
                                <div class="f1-step-icon">
                                    <i class="fa fa-check"></i>
                                </div>
                            </div>

                            <div class="f1-step active">
                                <div class="f1-step-icon">
                                    <i class="fa fa-check"></i>
                                </div>
                            </div>

                            <div class="f1-step active">
                                <div class="f1-step-icon">
                                    <i class="fa fa-user"></i>
                                </div>
                            </div>

                            <div class="f1-step">
                                <div class="f1-step-icon"></div>
                            </div>

                            <div class="form-elements">

                                <a style="float:left;">Upload Profile Picture</a><br><br><br><br>
                                <div class="f1-pic-icon">
                                    <i class="fa fa-user" style="color: rgb(0,143,237);font-size:40px;padding:20px;"></i>
                                    <br><br>
                                </div>
                                <center>
                                    <button type="submit" class="btn btn-upload">Upload</button>
                                </center>
                            </div>
                           
                           
                            <div class="pull-right">
                                <nuxt-link to="/complete"><button type="submit" class="btn btn-next">Next</button></nuxt-link>
                            </div>

                            <div class="pull-left">
                                <nuxt-link to="/address"><button type="submit" class="btn btn-previous">Back</button></nuxt-link>
                            </div>
                        </div>
                    </form>
                </div>
            </div> 
        </div>
    </div>
</template>