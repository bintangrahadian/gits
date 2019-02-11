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
                                    <i class="fa fa-map-marker"></i>
                                </div>
                            </div>

                            <div class="f1-step">
                                <div class="f1-step-icon">
                                   
                                </div>
                            </div>

                            <div class="f1-step">
                                <div class="f1-step-icon">
                                </div>
                            </div>

                            <div class="f1-step">
                                <div class="f1-step-icon"></div>
                            </div>

                            <div class="form-elements" style="padding:15px;">
                            <a style="float:left;">Province</a><br><br><br><br>
                                <div class="row">
                                <div class="col-sm-4">
                                <button class="btnProv activeProv">Aceh</button>
                                <button class="btnProv activeProv">Jawa Barat</button>
                                <button class="btnProv activeProv">Bali</button>
                                </div>

                                <div class="col-sm-4">
                                <button class="btnProv activeProv">Riau</button>
                                <button class="btnProv activeProv">Jawa Tengah</button>
                                <button class="btnProv activeProv">Jambi</button>
                                </div>

                                <div class="col-sm-4">
                                <button class="btnProv activeProv">DKI Jakarta</button>
                                <button class="btnProv activeProv">Jawa Timur</button>
                                <button class="btnProv activeProv">Banten</button></div>
                                </div> 
                            </div>
                           
                           
                            <div class="pull-right">
                                <nuxt-link to="/address"><button type="submit" class="btn btn-next">Next</button></nuxt-link>
                            </div>

                            <div class="pull-left">
                                <nuxt-link to="/"><button type="submit" class="btn btn-previous">Back</button></nuxt-link>
                            </div>
                        </div>
                    </form>
                </div>
            </div> 
        </div>
    </div>
</template>

<style>
.btnProv {
  border: none;
  color: white;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 5px;
  -webkit-transition-duration: 0.4s; /* Safari */
  transition-duration: 0.4s;
  cursor: pointer;
  width:130px;
  height:30px;
}

.activeProv {
  background-color: white; 
  color: black; 
  border: 1px solid rgb(0,143,237);
  border-radius:10px;
}

.activeProv:hover {
 background: rgb(0,143,237);
    background: linear-gradient(90deg, rgba(0,143,237,1) 21%, rgba(0,143,237,1) 21%, rgba(0,143,237,1) 28%, rgba(0,143,237,1) 32%, rgba(103,190,247,1) 67%);  

}


</style>