week2 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstap 4 Jumbotron Web Page</title>
   <!-- <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css">
    <script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" ></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"></script>-->
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <script src="js/bootstrap.min.js"></script>
    <script src="js/jquery.js"></script>
<style>
    form{
        position:absolute;
        right: 0px;
        background-color:blanchedalmond;
    }
    body{
        background-color:blanchedalmond;
    }
</style>
</head>
<body>
    <nav class="navbar nav navbar-expand-lg blanchedalmond">
        <a class="navbar-brand" href="#"><img src="./Logo.jpg" height="10%" width="10%">CMRIT Hyderabad </a>
        <!--<a class="navbar-brand" href="#"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR-3wgJUtABCq7yKLnJKJLYP2-eYdFY3WhDSQ&s" height="10%" width="10%">CMRIT Hyderabad</a>-->
        <div class="collapse navbar-collapse ">
            <ul class="nav nav-pills">
                  <li class="nav-item">
                     <a class="nav-link active" href="#">Home </a></li>
                  <li class="nav-item">
                     <a class="nav-link" href="#">About Us</a>
                  </li>  
                  
                  <li class="nav-item dropdown text-center">
                     <a class="nav-link dropdown-toggle" href="#" data-toggle="dropdown" aria-expanded="false">Departments</a>
                        <div class="dropdown-menu">
                           <a class="dropdown-item" href="#">CSE</a>
                           <a class="dropdown-item" href="#">CSD</a>
                           <a class="dropdown-item" href="#">AIML</a>
                       </div>
                 </li>
                 <li class="nav-item">
                    <a class="nav-link disabled" >Admissions</a>
                 </li>
            </ul>
            <form class="form-inline">
              <input class="form-control" type="text" placeholder="Search" aria-label="Search">
              <button class="btn btn-success" type="submit">Search</button>
            </form>
          </div>
    </nav>

    <div class="jumbotron" style="background-color:blanchedalmond">
         <div class="container"> 
            <h1>Hello, CMRIT Students!</h1>
            <p>CMR Institute of Technology is one of the best engineering Colleges for aspiring engineering students. It is one of the three colleges established by MGR Educational Society. CMR Institute of Technology was established in 2005</p>
            <p><a class="btn btn-primary btn-lg" href="#" role="button">Learn more &raquo;</a></p>
         </div>
    </div>
      <div class="container">
        <div class="row">
            <div class="col-md-4">
              <h2><center>CSE</center></h2><br>
              <p style="text-align:justify;"> Dr. KUMBALA PRADEEP REDDY, is a Technocrat with exposure to academics and Research. He has obtained PhD in Computer Science and Engineering form JNTU Hyderabad in the area of Machine learning and Image processing.</p>
              <p style="text-align:right;"><a class="btn btn-warning" href="#" role="button">Read More &raquo;</a></p>
            </div>
            <div class="col-md-4">
              <h2><center>CSD</center></h2><br>
              <p style="text-align:justify;">Dr. A Nirmal Kumar is a model for academic excellence and research in the field of computer science and engineering that prepares competent professionals with innovative skills, moral values and societal concern.!</p>
              <p style="text-align:right;"><a class="btn btn-info" href="#" role="button">Read More &raquo;</a></p>
            </div>
            <div class="col-md-4">
              <h2><center>AIML</center></h2><br>
              <p style="text-align:justify;">Dr. L. Arokia Jesu Prabhu is a Technophile with exposure to Academics and Research. He has obtained PhD in Computer Science and Engineering from Anna University, Chennai in the area of Machine learning and Image processing!</p>
              <p style="text-align:right;"><a class="btn btn-danger" href="#" role="button">Read More &raquo;</a></p>
            </div>
          </div>
      </div>
      <footer class="container text-center">
        <p>&copy; Institute Established in 2005</p>
      </footer>
</body>
</html>
