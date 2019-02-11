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

                            <div class="f1-step">
                                <div class="f1-step-icon">
                                </div>
                            </div>

                            <div class="f1-step">
                                <div class="f1-step-icon"></div>
                            </div>

                            <div class="form-elements">

                                <a style="float:left;">Address</a><br><br><br><br>
                                 <div class="form-group">
                                    <label style="float:left;"><b>City</b></label><br><br>
                                    <select class="form-control" style="width:35%;">
                                      <option></option>
                                     
                                    </select>
                                  </div>
                                  <div class="form-group">
                                    <label style="float:left;"><b>Zip Code</b></label><br><br>
                                    <input type="text" class="form-control" style="width:30%;">
                                  </div>
                                  <div class="form-group">
                                    <label style="float:left;"><b>Complete Address</b></label><br><br>
                                    <textarea class="form-control" style="resize:none;"></textarea>
                                  </div>
                                
                            </div>
                           
                           
                            <div class="pull-right">
                                <nuxt-link to="/upload"><button type="submit" class="btn btn-next">Next</button></nuxt-link>
                            </div>

                            <div class="pull-left">
                                <nuxt-link to="/province"><button type="submit" class="btn btn-previous">Back</button></nuxt-link>
                            </div>
                        </div>
                    </form>
                </div>
            </div> 
        </div>
    </div>
</template>