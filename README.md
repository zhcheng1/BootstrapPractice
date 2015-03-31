# BootstrapPractice
BootstrapPractice


<!DOCTYPE html>
<html>
<head lang="en">
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>JM Ocean Avenue</title>

    <!-- Bootstrap -->
    <link href="css/bootstrap.min.css" rel="stylesheet">
    <link href="css/CustomStyle.css" rel="stylesheet">

    <!-- HTML5 Shim and Respond.js IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
    <script src="https://oss.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script>
    <script src="https://oss.maxcdn.com/libs/respond.js/1.4.2/respond.min.js"></script>
    <![endif]-->
</head>
<body>
    <div class="container">
        <nav class="navbar navbar-default">
            <div class="navbar-brand">
                <a href="#">
                    <img class="logo-size" src="images/OA_logo.png">
                </a>
            </div>
            <div class="navbar-header">
                <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#navbarMenu">
                    <span class="sr-only">Toggle navigation</span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
            </div>
            <div class="navbar-collapse collapse" id="navbarMenu">
                <ul class="nav navbar-nav">
                    <li class="active"><a href="#">Home</a></li>
                    <li class="dropdown">
                        <a href="#" class="dropdown-toggle" data-toggle="dropdown">
                            Company <span class="caret"></span>
                        </a>
                        <ul class="dropdown-menu" role="menu">
                            <li ><a href="#">Company Profile</a></li>
                            <li ><a href="#">Culture</a></li>
                            <li ><a href="#">Executive Team</a></li>
                            <li ><a href="#">Policies & Procedures</a></li>
                        </ul>
                    </li>
                    <li class="dropdown">
                        <a href="#" class="dropdown-toggle" data-toggle="dropdown">
                            Products <span class="caret"></span>
                        </a>
                        <ul class="dropdown-menu" role="menu">
                            <li ><a href="#">Living</a></li>
                            <li ><a href="#">Nutrition</a></li>
                            <li ><a href="#">Care</a></li>
                        </ul>
                    </li>
                    <li class="dropdown">
                        <a href="#" class="dropdown-toggle" data-toggle="dropdown">
                            Opportunity <span class="caret"></span>
                        </a>
                        <ul class="dropdown-menu" role="menu">
                            <li ><a href="#">Opportunity</a></li>
                            <li ><a href="#">Recognition</a></li>
                            <li ><a href="#">Marketing Plan</a></li>
                        </ul>
                    </li>
                    <li><a href="#">News</a></li>
                    <li class="dropdown">
                        <a href="#" class="dropdown-toggle" data-toggle="dropdown">
                            Select Country <span class="caret"></span>
                        </a>
                        <ul class="dropdown-menu" role="menu">
                            <li class="dropdown-header">North America</li>
                            <li ><a href="#">United States</a></li>
                            <li ><a href="#">Canada</a></li>
                            <li class="divider"></li>
                            <li class="dropdown-header">Latin America</li>
                            <li><a href="#">Peru</a></li>
                            <li class="divider"></li>
                            <li class="dropdown-header">East China</li>
                            <li><a href="#">Hongkong</a></li>
                        </ul>
                    </li>
                </ul>
            </div>
        </nav>
    </div>

    <section>
        <div class="container">
            <div class="jumbotron text-center">
                <h1>JM Ocean Avenue</h1>
                <h3>-- Our mission is to help families create amazing life experiences with the people they love and care about the most.</h3>
            </div>
        </div>
    </section>

    <div class="container">
    <div class="jumbotron image-section">
        <div class="row">
            <div class="col-xs-12 col-md-4">
                <a href="#" class="thumbnail">
                <img class="frontpage-photo" src="images/skinproduct.jpg">
                </a>
                <a href="#"><h3 class="text-center">Care Products</h3></a>

            </div>

            <div class="col-xs-12 col-md-4">
                <a href="#" class="thumbnail">
                <img class="frontpage-photo" src="images/life.jpg">
                </a>
                <a href="#"><h3 class="text-center">Life</h3></a>

            </div>
            <div class="col-xs-12 col-md-4">
                <a href="#" class="thumbnail">
                <img src="images/nutrition.jpg">
                </a>
                <a href="#"><h3 class="text-center">Nutrition</h3></a>

            </div>
        </div>
    </div>
    </div>

    <div class="container">
        <div class="row">
            <div class="col-sm=12 col-md-6">
                <div class="jumbotron contact">

                    <h3 class="text-center">Contact Us</h3>
                    <form class="form-horizontal" role="form">
                        <div class="form-group">
                            <label for="contact-name" class="col-sm-2 control-label">Name</label>
                            <div class="col-xs-12 col-md-10">
                                <input type="text" class="form-control" id="contact-name" placeholder="Your Name">
                            </div>
                        </div>
                        <div class="form-group">
                            <label for="contact-email" class="col-sm-2 control-label">Email</label>
                            <div class="col-xs-12 col-md-10">
                                <input type="email" class="form-control" id="contact-email" placeholder="example@domain.com">
                            </div>
                        </div>
                        <div class="form-group">
                            <label class="col-sm-2 control-label">Message</label>
                            <div class="col-xs-12 col-md-10">
                                <textarea class="form-control" rows="4"></textarea>
                            </div>
                        </div>
                        <div class="col-sm-3 col-md-3 col-md-push-4">
                            <button class="btn btn-primary text-center" type="submit">Submit</button>
                        </div>
                    </form>
                </div>
            </div>
            <div class="col-sm=12 col-md-6">
                <div class="jumbotron">
                    <h3>Culture and Corporate Values</h3>
                    <p class="text-muted">JM Ocean Avenue is more than just a company, it’s a lifestyle! Our Founders, Distributors and Employees are dedicated to our mission—to empower people and strengthen families through living a healthy active lifestyle.
                        <br>
                        <br>
                    </p>
                </div>
            <div>
        </div>
    </div>

    <!-- Fixed footer -->
    <div class="navbar navbar-inverse navbar-fixed-bottom" role="navigation">
        <div class="container">
            <div class="navbar-text pull-left">
                <p>Copyright</p>
            </div>
        </div>
    </div>

    <!-- Bootstrap core JavaScript
    ================================================== -->
    <!-- Placed at the end of the document so the pages load faster -->
    <div class="model fade" id="skinproduct-modal" role="dialog" aria-labelledby="myModalLabel">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header" >
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
                    <h4 class="modal-title" id="myModalLabel">Care Products</h4>
                </div>
                <div class="modal-body">
                    <p>The products you use to care for your body are as important as the food you eat. Unfortunately, too many people are comfortable using mediocre and unreliable products. Some of these products may even contain low doses of harsh ingredients that could cause harm over time. At JM Ocean Avenue, we understand the need for products that are simple, natural, and effective.

                        2 Minute Miracle: Your skin is much more than a barrier – it is an organ. As with other organs, your skin’s health and ability to function are affected by your lifestyle, diet, and environment. Over time, low doses of harsh soaps, chemicals, pollution, and sunlight can lead to premature aging and self-image dissatisfaction. The 2 Minute Miracle is made of natural ingredients that feed the skin daily vitamins and minerals to enhance its ability to regenerate while providing resistance to adverse conditions in our environment. It reduces the signs of ageing by improving the health of your skin. Compared to other complex skin care systems, the 2 Minute Miracle is simple and offers results in just two minutes!

                        Angels Secret: A woman’s period is a time when the body can be less resistant to disease. It can also be a time of great discomfort and sometimes embarrassment. Angels Secret provides protection that is both reliable and comfortable. With calculated design and natural materials, Angels Secret will free your mind and leave you feeling fresh and confident.</p>
                </div>
            </div>
        </div>
    </div>

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
</body>


</html>


.logo-size{
    padding-top:0;
    height: 35px;
}

.frontpage-photo{
    width: 290px;
    height: 150px;
}
@media(min-width: 769px){{}
.thumbnail{
    width: 290px;
    height: 180px;
    overflow: hidden;
}}
@media(min-width: 769px){
.thumbnail img{
    width: 280px;
    height: 150px;
    transition: all 0.3s ease 0s;
}}

.thumbnail img:hover{
    transform: scale(1.1);
}

@media(min-width: 769px){
.contact{
    background-color: #b9def0;
    height: 375px;
}}

.image-section{
    background-color: #f2dede;

}

body{
    background-color: #fffacd;
}
