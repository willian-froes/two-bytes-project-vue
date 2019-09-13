<template>
  <div>
    <header>
        <div class="container">
            <nav class="navbar navbar-expand-lg pt-4">
                <a class="navbar-brand" href="index.html">
                    <img src="src/img/logo.png" alt="header-logo">
                </a>

                <button class="fa fa-bars fa-2x navbar-toggler menu-access" data-toggle="collapse"
                    data-target="#header-menu" aria-controls="header-menu" aria-expanded="false"></button>

                <div class="collapse navbar-collapse" id="header-menu">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
                        <li class="nav-item"><a class="nav-link" href="#">About us</a></li>
                        <li class="nav-item"><a class="nav-link" href="#">Jobs</a></li>
                        <li class="nav-item"><a class="nav-link" href="#">Clients</a></li>
                        <li class="nav-item"><a class="nav-link" href="#">Employers</a></li>
                        <li class="nav-item"><a class="nav-link" href="#">Contact us</a></li>
                    </ul>
                </div>
            </nav>

            <div class="header-banner">
                <h1 class="main-title font-italic">I'm looking for...</h1>

                <form>
                    <div class="row">

                        <div class="col-12 col-sm-12 col-md-8 col-lg-10 pr-lg-5">
                            <div class="form-group">
                                <input class="form-control form-control-lg" type="text" name="job-description"
                                    id="job-description" placeholder="Enter a Job Description">
                            </div>

                            <div class="row">
                                <div class="form-group col-12 col-sm-8 col-md-6">
                                    <div class="row">
                                        <div class="col-md-12 col-lg-4">
                                            <div class="custom-control custom-checkbox mr-sm-2">
                                                <input class="custom-control-input" type="checkbox" id="job-time-full"
                                                    value="full time">
                                                <label class="custom-control-label checkbox-content font-italic"
                                                    for="job-time-full">Full
                                                    Time</label>
                                            </div>
                                        </div>

                                        <div class="col-md-12 col-lg-8">
                                            <div class="custom-control custom-checkbox mr-sm-2">
                                                <input class="custom-control-input" type="checkbox" id="job-time-all"
                                                    value="part casual free">
                                                <label class="custom-control-label checkbox-content font-italic"
                                                    for="job-time-all">Part Time /
                                                    Casual /
                                                    Freelance</label>
                                            </div>
                                        </div>
                                    </div>
                                </div>

                                <div class="col-12 col-sm-12 col-md-6">
                                    <select class="form-group form-control font-italic" name="job-location" id="job-location">
                                        <option class="default-value" value="default" selected disabled>Select your
                                            location
                                        </option>
                                        <option value="Brasil">Brasil</option>
                                        <option value="Estados Unidos">Estados Unidos</option>
                                        <option value="Japao">Japão</option>
                                    </select>
                                </div>
                            </div>
                        </div>

                        <div class="col-12 col-sm-12 col-md-4 col-lg-2">
                            <button
                                class="btn btn-default btn-lg float-right d-flex justify-content-center align-items-center search-button font-italic">
                                <span class="fa fa-search fa-xs mr-2"></span>
                                <text class="search-btn-icon">Search</text>
                            </button>
                        </div>
                    </div>

                </form>
            </div>
        </div>
    </header>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style lang="scss">
    @import '../../../assets/sass/styles.scss';
</style>
