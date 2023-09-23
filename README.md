<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Bootstrap Navbar with Logo Image</title>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"></script>

<style>

body{
	position: relative; /* required */
}
  
/* Custom style to stick list group on top */
.list-group{
    position: sticky;
    top: 15px;
}

#myImg {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}


#myImg:hover {opacity: 0.7;}

/* The Modal (background) */
.modal {
  display: none; /* Hidden by default */
  position: fixed; /* Stay in place */
  z-index: 1; /* Sit on top */
  padding-top: 100px; /* Location of the box */
  left: 0;
  top: 0;
  width: 100%; /* Full width */
  height: 100%; /* Full height */
  overflow: auto; /* Enable scroll if needed */
  background-color: rgb(0,0,0); /* Fallback color */
  background-color: rgba(0,0,0,0.9); /* Black w/ opacity */
}

#myImg1 {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}


#myImg1:hover {opacity: 0.7;}



#myImg2 {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}


#myImg2:hover {opacity: 0.7;}


#myImg3 {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}


#myImg3:hover {opacity: 0.7;}


#myImg4 {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}


#myImg4:hover {opacity: 0.7;}



#myImg5 {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}


#myImg5:hover {opacity: 0.7;}


#myImg6 {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}


#myImg6:hover {opacity: 0.7;}


#myImg7 {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}


#myImg7:hover {opacity: 0.7;}


#myImg8 {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}


#myImg8:hover {opacity: 0.7;}


#myImg9 {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}


#myImg9:hover {opacity: 0.7;}


#myImg10 {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}


#myImg10:hover {opacity: 0.7;}


#myImg11 {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}


#myImg11:hover {opacity: 0.7;}


#myImg12 {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}


#myImg12:hover {opacity: 0.7;}


#myImg13 {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}


#myImg13:hover {opacity: 0.7;}


#myImg14 {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}


#myImg14:hover {opacity: 0.7;}


#myImg15 {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}


#myImg15:hover {opacity: 0.7;}


#myImg16 {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}


#myImg16:hover {opacity: 0.7;}


#myImg17 {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}


#myImg17:hover {opacity: 0.7;}


#myImg18 {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}


#myImg18:hover {opacity: 0.7;}


#myImg19 {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}


#myImg19:hover {opacity: 0.7;}

/* The Modal (background) */
.modal {
  display: none; /* Hidden by default */
  position: fixed; /* Stay in place */
  z-index: 1; /* Sit on top */
  padding-top: 100px; /* Location of the box */
  left: 0;
  top: 0;
  width: 100%; /* Full width */
  height: 100%; /* Full height */
  overflow: auto; /* Enable scroll if needed */
  background-color: rgb(0,0,0); /* Fallback color */
  background-color: rgba(0,0,0,0.9); /* Black w/ opacity */
}
/* Modal Content (image) */
.modal-content {
  margin: auto;
  display: block;
  width: 80%;
  max-width: 700px;
}

/* Caption of Modal Image */
#caption {
  margin: auto;
  display: block;
  width: 80%;
  max-width: 700px;
  text-align: center;
  color: #ccc;
  padding: 10px 0;
  height: 150px;
}

/* Add Animation */
.modal-content, #caption {  
  animation-name: zoom;
  animation-duration: 0.6s;
}

@keyframes zoom {
  from {transform: scale(0.1)} 
  to {transform: scale(1)}
}

/* The Close Button */
.close {
  position: absolute;
  top: 15px;
  right: 35px;
  color: #f1f1f1;
  font-size: 40px;
  font-weight: bold;
  transition: 0.3s;
}

.close:hover,
.close:focus {
  color: #bbb;
  text-decoration: none;
  cursor: pointer;
}

/* 100% Image Width on Smaller Screens */
@media only screen and (max-width: 700px){
  .modal-content {
    width: 100%;
  }
}


</style>

</head>
<body style="background-color:rgb(219, 158, 150);">
    
<div class="m-4">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
            <a href="#" class="navbar-brand">
                <img src="cpelogo.png" height="28" alt="CoolBrand">
            </a>
            <button type="button" class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#navbarCollapse">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarCollapse">
                <div class="navbar-nav">
                    <a href="#myCarousel" class="nav-item nav-link active">Home</a>
                    <a href="#myAbout us" class="nav-item nav-link">About CpE</a>
                    <a href="#card-group" class="nav-item nav-link">Specialization</a>
                    <a href="#outcomes" class="nav-item nav-link">Program Outcomes</a>
                    <a href="#org" class="nav-item nav-link">Student Organization</a>
                    <a href="#studentwork" class="nav-item nav-link">Student Work</a>
                
                </div>
                
              
            </div>
        </div>
    </nav>

    <div id="myCarousel" class="carousel slide" data-bs-ride="carousel">
        <!-- Carousel indicators -->
        <ol class="carousel-indicators">
            <li data-bs-target="#myCarousel" data-bs-slide-to="0" class="active"></li>
            <li data-bs-target="#myCarousel" data-bs-slide-to="1"></li>
            <li data-bs-target="#myCarousel" data-bs-slide-to="2"></li>
        </ol>
        
        <!-- Wrapper for carousel items -->
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="cpe.jpg" class="d-block w-100" alt="Slide 1" style="height: 400px;">
                <div class="carousel-caption d-none d-md-block">
                
                </div>
            </div>
            <div class="carousel-item">
                <img src="cpe1.jpg" class="d-block w-100" alt="Slide 2" style="height: 400px;">
                <div class="carousel-caption d-none d-md-block">
                
                </div>
            </div>
            <div class="carousel-item">
                <img src="cp3.jpg" class="d-block w-100" alt="Slide 3" style="height: 400px;">
                <div class="carousel-caption d-none d-md-block">
                  
                </div>
            </div>
        </div>
    
        <!-- Carousel controls -->
        <a class="carousel-control-prev" href="#myCarousel" data-bs-slide="prev">
            <span class="carousel-control-prev-icon"></span>
        </a>
        <a class="carousel-control-next" href="#myCarousel" data-bs-slide="next">
            <span class="carousel-control-next-icon"></span>
        </a>
    </div>
</div>
<hr>

<div class="container" id="myAbout us" >
    
    
    <div class="p-5 my-4 bg-light rounded-3">
        
        <h4>Bachelor of Science in</h4>
        <h2>Computer Engineering</h2>

        <br>
        <hr>
        
        <div class="row">
            <div class="col-md-4">
                <h6>The BS Computer Engineering is a four-year degree program that merges electrical engineering and computer science, focusing on computer hardware and software systems, and offering specializations in software development, embedded systems, artificial intelligence, 
                    machine learning, and network administration, preparing graduates for the dynamic technology industry.</h6>
                    <br>
            <div>
                <div class="d-flex">

                    <img src="contact.png" style="height: 20px; width: 20px;">
                
                 <div class="flex-grow-1 ms-3">
                    <p>0926 301 3900</p>
                </div>
                </div>
            </div>

            <div>
                <div class="d-flex">

                    <img src="email.png" style="height: 25px; width: 23px;">
                
                 <div class="flex-grow-1 ms-3">
                    <p>scpesofficial@gmail.com</p>
                </div>
                </div>
            </div>
            <div>
                <div class="d-flex">

                    <img src="direction.png" style="height: 25px; width: 23px;">
                
                 <div class="flex-grow-1 ms-3">
                    <p>2219 CM Recto Ave. Manila, Philippines 1008, Manila, Philippines, Manila, Philippines</p>
                 </div>
                
                </div>
          
            </div>
                
                
                
            </div>
            <div class="col-md-4">

            </div>

            <div class="col-md-4" style="width: 350px;">
                <h4>Career Opportunities</h4>
                <li>Project Engineer/Manager</li>
                <li>Network System Administrator/Manager</li>
                <li>Data Communications Engineer</li>
                <li>Systems Engineer/Developer/Manager</li>
                <li>Systems Analyst/Designer</li>
                <li>Technical Support Engineer/Manager</li>
                <li>Test Engineer</li>
                <li>Technopreneur</li>
                <li>Software Engineer</li>
                <li>Quality Assurance Engineer</li>
                <li>Educator and Researcher</li>

                </div>

        </div>
                <hr>
        
         
           
        <div class="m-4">
            
            <div class="d-flex">
                <div class="flex-shrink-0">
                    <img src="uelogo.jpg" width="70" height="70" alt="Sample Image">
                </div>
                <br>
                <div class="flex-grow-1 ms-3">
                    <h3>University of the East </h3>
                    <h6>College of Engineering</h6>
                </div>
                <div class="flex-shrink-0">
                    <a href="https://www.facebook.com/UniversityoftheEastUE">
                   <img src="fblogo.png" width="30" height="30" alt="Sample Image">
                   </a>
                   <a href="https://www.ue.edu.ph/mla/">
                    <img src="weblogo.png" width="30" height="30" alt="Sample Image">
                    </a>
                </div>
                
            </div>
        </div>
        
     </div>
    
    


</div>

<hr>
<div id="card-group" class="m-4" style="margin-left: 50px; margin-right: 50px;">
    <div class="card-group">
        <div class="card">
            <img src="cpe14.jpg" class="card-img-top" alt="..." style="height: 226px;">
            <div class="card-body">
                <h5 class="card-title">Network and System Administration</h5>
                <p class="card-text">Network and computer systems administrators install, configure, and maintain organizations' 
                    local area networks (LANs), wide area networks (WANs), data communication networks, operating systems, and servers.</p>
            </div>
        </div>
        <div class="card">
            <img src="cpe123.jpg" class="card-img-top" alt="..." >
            <div class="card-body">
                <h5 class="card-title">Embedded Systems</h5>
                <p class="card-text">Embedded Software Engineering is the process of controlling various devices and machines 
                    that are different from traditional computers, using software engineering.</p>
            </div>
        </div>
        <div class="card">
            <img src="cpe112.jpg" class="card-img-top" alt="..." style="height: 226px;">
            <div class="card-body">
                <h5 class="card-title">Software Development</h5>
                <p class="card-text"> is the set of instructions or programs that tell a computer what to do. 
                    It is independent of hardware and makes computers programmable.</p>
            </div>
        </div>
    </div>
</div>
<hr>
    <div class="container-fluid" id="outcomes" style="margin: 5%; width: 900px; margin-top: 2%;">
        <h2><ins>Bachelor of Science in Computer Engineering (BSCpE).</ins></h2>
        <p>Computer engineering deals with the application of engineering principles and methodologies in the analysis, 
            design, implementation and management of hardware and software, and the integration of both..</p>

        <p> The Computer Engineering (CpE) Program educates students to understand both sides of the hardware-software interface, 
            from designing circuits to creating operating systems. Multidisciplinary in scope, the CpE curriculum integrates the 
            fields of electrical engineering and computer science. This program will uniquely prepare CpE graduates to design and 
            develop embedded digital and computer systems. Graduates with a degree in CpE will be highly skilled and ideally suited 
            for 21st-century industries, 
            including the games industry.</p>
        <p>UE CpE concentrates on the practical application of theoretical learning through a variety of semestral and year long 
            projects. Students will have 
            increasing levels of creative control in their projects and receive feedback from expert instructors. </p>
            
        <hr>
        <p><strong>Program Educational Objectives</strong></p>
        <p> Three to five years after graduation, the Computer Engineering alumni shall:</p>
        <p> 1. have pursued advancement towards becoming globally competitive leaders in their chosen
            field of practice.</p>
        <p> 2. be contributors to the development of a progressive society, guided by the UE core values of
            Excellence, Integrity, Professionalism, Teamwork, Commitment, Transparency, Accountability
            and Social Responsibility.</p>
        <hr>
        <p><strong>Student Outcomes</strong></p>
        <p> 1. Ability to apply knowledge of mathematics and science to solve engineering problems.</p>
        <p> 2. Ability to design and conduct experiments, as well as to analyze and interpret data.</p>
        <p> 3. Ability to design a system, component or process to meet desired needs within realistic 
            constraints such as economic, environmental, social, political, ethical, health and safety,
             manufacturability, and sustainability, in accordance with standards.</p>
        <p> 4. Ability to function in multidisciplinary teams.</p>
        <p> 5. Ability to identify, formulate and solve engineering problems.</p>
        <p> 6. Understanding of professional and ethical responsibilities.</p>
        <p> 7. Ability to communicate effectively.</p>
        <p> 8. Broad education necessary to understand the impact of engineering solutions in global, 
            economic, environmental and societal contexts.</p>
        <p> 9. Recognition of the need for and an ability to engage in lifelong learning.</p>
        <p> 10. Knowledge of contemporary issues.</p>
        <p> 11. Ability to use techniques, skills and modern engineering tools necessary for engineering practice.</p>
        <p> 12. Knowledge and understanding of engineering and management principles as a member and leader in a team, to 
            manage projects in multidisciplinary environments.</p>
        
        <hr>

        <p><strong>Program Outcomes</strong></p>
        <p><em>By the time of graduation, the students of the program shall have the ability to:</em></p>
        <li> Ability to apply knowledge of mathematics and sciences to solve complex engineering
            problems;</li>
        <li> Ability to design and conduct experiments, as well as to analyze and interpret data;</li>
        <li> Ability to design a system, component, or process to meet desired needs within
             realistic constraints such as economic, environmental, social, political, ethical, health
             and safety, manufacturability, and sustainability, in accordance with standards;</li>
        <li> Ability to function in multi-disciplinary teams;</li>
        <li> Ability to identify, formulate and solve complex problems in computer engineering problems;</li>
        <li> Understanding of professional and ethical responsibility;</li>
        <li> Ability to communicate effectively;</li>
        <li> Broad education necessary to understand the impact of engineering solutions in
             global, economic, environmental, and societal context;</li>
        <li> Recognition of the need for, and an ability to engage in life-long learning;</li>
        <li> Knowledge contemporary issues;</li>
        <li> Ability to use techniques, skills and modern engineering tools necessary for computer
             engineering practice; </li>
        <li> Knowledge and understand engineering and management principles as a member and
             leader in a team, and to manage projects and in a multidisciplinary environment.</li>
        
        <hr>
        <p><strong>Faculties:</strong></p>
        <div class="m-4">
            <div class="row row-cols-1 row-cols-md-2 g-4">
                <div class="col">
                    <div class="card">
                        <img src="sirerrol.jpg" class="card-img-top" alt="..." style="height: 357px;">
                        <div class="card-body">
                            <center>
                            <h5 class="card-title">Errol John M. Antonio</h5>
                            </center>
                            <p class="card-text">BSCpE, UE (2012); MEng-CpE, PLM (2018); DIT, UE</p>
                        </div>
        
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="sircorpuz.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <center>
                            <h5 class="card-title">Onofre F. Corpuz</h5>
                            </center>
                            <p class="card-text">BSECE, FEATI (1993); MES, UE (2017)</p>
                            
                            
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="maamlim.jpg" class="card-img-top" alt="..." style="height: 357px;">
                        <div class="card-body">
                            <center>
                            <h5 class="card-title">Mary Ann L. Limkian </h5>
                            </center>
                            <p class="card-text"> BSCpE, UE (2000); MEng-CpE, PLM (2006); DBA, UE (units earned); DIT, UE</p>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="maamcasuat.PNG" class="card-img-top" alt="..." style="height: 357px;">
                        <div class="card-body">
                            <center>
                            <h5 class="card-title">Cherry Casuat</h5>
                            </center>
                            <p class="card-text">BSCpE, TIP Manila (2006); MEng-CpE, Adamson University (2010); Deng – CpE, TIP QC (2021)</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
</div>
<hr>
<body data-bs-spy="scroll" data-bs-offset="15" data-bs-target="#myScrollspy">
    <div class="container-lg my-2" id="org">
        <h1>UE Manila - Society of Computer Engineering Students</h1>
        <p class="lead"><i>Student Organization Activities</i></p>
        <div class="row">
            <div class="col-sm-3" id="myScrollspy">
                <div class="list-group">
                    <a class="list-group-item list-group-item-action active" href="#section1">Section One</a>
                    <a class="list-group-item list-group-item-action" href="#section2">Section Two</a>
                    <a class="list-group-item list-group-item-action" href="#section3">Section Three</a>
                    <a class="list-group-item list-group-item-action" href="#section4">Section Four</a>
                    <a class="list-group-item list-group-item-action" href="#section5">Section Five</a>
                </div>
            </div>
            <div class="col-sm-9">
                <div id="section1">
                    <h3>Mini-Hackathon and Techno Imperium (2022-2023)</h3>
                    <div>
                        <div class="d-flex">
        
                            <img src="ht1.jpg" style="height: 450px; width: 450px;" id="myImg" alt="Mini-Hackathon and Techno Imperium (2022-2023)">

<!-- The Modal -->
<div id="myModal" class="modal">
  <span class="close">&times;</span>
  <img class="modal-content" id="img01">
  <div id="caption"></div>
</div>

<script>
// Get the modal
var modal = document.getElementById('myModal');

// Get the image and insert it inside the modal - use its "alt" text as a caption
var img = document.getElementById('myImg');
var modalImg = document.getElementById("img01");
var captionText = document.getElementById("caption");
img.onclick = function(){
  modal.style.display = "block";
  modalImg.src = this.src;
  captionText.innerHTML = this.alt;
}

</script>
                        
                         <div class="flex-grow-1 ms-3">
                            <img src="ht2.jpg" style="height: 450px; width: 450px;" id="myImg1" alt="Mini-Hackathon and Techno Imperium (2022-2023)">

                            <!-- The Modal -->
<div id="myModal" class="modal">
    <span class="close">&times;</span>
    <img class="modal-content" id="img02">
    <div id="caption"></div>
  </div>
  
  <script>
  // Get the modal
  var modal = document.getElementById('myModal');
  
  // Get the image and insert it inside the modal - use its "alt" text as a caption
  var img = document.getElementById('myImg1');
  var modalImg = document.getElementById("img02");
  var captionText = document.getElementById("caption");
  img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
  }
  </script>
                           
                         </div>

                        </div>
                    </div>
                    <br>

                    <div>
                        <div class="d-flex">
        
                            <img src="ht3.jpg" style="height: 450px; width: 450px;" id="myImg2" alt="Mini-Hackathon and Techno Imperium (2022-2023)">
                            <!-- The Modal -->
<div id="myModal" class="modal">
    <span class="close">&times;</span>
    <img class="modal-content" id="img03">
    <div id="caption"></div>
  </div>
  
  <script>
  // Get the modal
  var modal = document.getElementById('myModal');
  
  // Get the image and insert it inside the modal - use its "alt" text as a caption
  var img = document.getElementById('myImg2');
  var modalImg = document.getElementById("img03");
  var captionText = document.getElementById("caption");
  img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
  }
  
 
  </script>
                        
                         <div class="flex-grow-1 ms-3">
                            <img src="ht4.jpg" style="height: 450px; width: 450px;" id="myImg3" alt="Mini-Hackathon and Techno Imperium (2022-2023)">
                            <!-- The Modal -->
<div id="myModal" class="modal">
    <span class="close">&times;</span>
    <img class="modal-content" id="img04">
    <div id="caption"></div>
  </div>
  
  <script>
  // Get the modal
  var modal = document.getElementById('myModal');
  
  // Get the image and insert it inside the modal - use its "alt" text as a caption
  var img = document.getElementById('myImg3');
  var modalImg = document.getElementById("img04");
  var captionText = document.getElementById("caption");
  img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
  }

  </script>
                         </div>

                        </div>
                    </div>
                
                </div>
                <hr>
                <div id="section2">
                    <h3>Tech Crush: Discovering the Future of Computer Engineering</h3>
                    <p class="lead"><i>A SHS STEM & ICT Work Immersion Program (S.Y. 2022-2023)</i></p>
                    <div id="section1">
                        <div>
                            <div class="d-flex">
            
                                <img src="a1.jpg" style="height: 450px; width: 450px;" id="myImg4" alt="Tech Crush: Discovering the Future of Computer Engineering">
                                <!-- The Modal -->
<div id="myModal" class="modal">
    <span class="close">&times;</span>
    <img class="modal-content" id="img05">
    <div id="caption"></div>
  </div>
  
  <script>
  // Get the modal
  var modal = document.getElementById('myModal');
  
  // Get the image and insert it inside the modal - use its "alt" text as a caption
  var img = document.getElementById('myImg4');
  var modalImg = document.getElementById("img05");
  var captionText = document.getElementById("caption");
  img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
  }
  </script>
                            
                             <div class="flex-grow-1 ms-3">
                                <img src="a2.jpg" style="height: 450px; width: 450px;" id="myImg5" alt="Tech Crush: Discovering the Future of Computer Engineering">

                                <!-- The Modal -->
<div id="myModal" class="modal">
    <span class="close">&times;</span>
    <img class="modal-content" id="img06">
    <div id="caption"></div>
  </div>
  
  <script>
  // Get the modal
  var modal = document.getElementById('myModal');
  
  // Get the image and insert it inside the modal - use its "alt" text as a caption
  var img = document.getElementById('myImg5');
  var modalImg = document.getElementById("img06");
  var captionText = document.getElementById("caption");
  img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
  }
  </script>
                             </div>
    
                            </div>
                        </div>
                        <br>
    
                        <div>
                            <div class="d-flex">
            
                                <img src="a3.jpg" style="height: 450px; width: 450px;" id="myImg6" alt="Tech Crush: Discovering the Future of Computer Engineering">

                                <!-- The Modal -->
<div id="myModal" class="modal">
    <span class="close">&times;</span>
    <img class="modal-content" id="img07">
    <div id="caption"></div>
  </div>
  
  <script>
  // Get the modal
  var modal = document.getElementById('myModal');
  
  // Get the image and insert it inside the modal - use its "alt" text as a caption
  var img = document.getElementById('myImg6');
  var modalImg = document.getElementById("img07");
  var captionText = document.getElementById("caption");
  img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
  }
  </script>
                            
                             <div class="flex-grow-1 ms-3">
                                <img src="a4.jpg" style="height: 450px; width: 450px;" id="myImg7" alt="Tech Crush: Discovering the Future of Computer Engineering">
                                 <!-- The Modal -->
<div id="myModal" class="modal">
    <span class="close">&times;</span>
    <img class="modal-content" id="img08">
    <div id="caption"></div>
  </div>
  
  <script>
  // Get the modal
  var modal = document.getElementById('myModal');
  
  // Get the image and insert it inside the modal - use its "alt" text as a caption
  var img = document.getElementById('myImg7');
  var modalImg = document.getElementById("img08");
  var captionText = document.getElementById("caption");
  img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
  }
  </script>
                             </div>
    
                            </div>
                        </div>

                        
                    
                    </div>
                </div>
                <hr>
                <div id="section3">
                    <h3>UE Manila SHS ICT Arduino Workshop 2022-2023</h3>
                    <div>
                        <div class="d-flex">
        
                            <img src="s1.jpg" style="height: 450px; width: 450px;" id="myImg8" alt="UE Manila SHS ICT Arduino Workshop 2022-2023">
                            <!-- The Modal -->
<div id="myModal" class="modal">
    <span class="close">&times;</span>
    <img class="modal-content" id="img09">
    <div id="caption"></div>
  </div>
  
  <script>
  // Get the modal
  var modal = document.getElementById('myModal');
  
  // Get the image and insert it inside the modal - use its "alt" text as a caption
  var img = document.getElementById('myImg8');
  var modalImg = document.getElementById("img09");
  var captionText = document.getElementById("caption");
  img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
  }
  </script>
                        
                         <div class="flex-grow-1 ms-3">
                            <img src="s2.jpg" style="height: 450px; width: 450px;" id="myImg9" alt="UE Manila SHS ICT Arduino Workshop 2022-2023">
                             <!-- The Modal -->
<div id="myModal" class="modal">
    <span class="close">&times;</span>
    <img class="modal-content" id="img10">
    <div id="caption"></div>
  </div>
  
  <script>
  // Get the modal
  var modal = document.getElementById('myModal');
  
  // Get the image and insert it inside the modal - use its "alt" text as a caption
  var img = document.getElementById('myImg9');
  var modalImg = document.getElementById("img10");
  var captionText = document.getElementById("caption");
  img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
  }
  </script>
                            
                         </div>

                        </div>
                    </div>
                    <br>

                    <div>
                        <div class="d-flex">
        
                            <img src="s3.jpg" style="height: 450px; width: 450px;" id="myImg10" alt="UE Manila SHS ICT Arduino Workshop 2022-2023">
                            <!-- The Modal -->
<div id="myModal" class="modal">
    <span class="close">&times;</span>
    <img class="modal-content" id="img11">
    <div id="caption"></div>
  </div>
  
  <script>
  // Get the modal
  var modal = document.getElementById('myModal');
  
  // Get the image and insert it inside the modal - use its "alt" text as a caption
  var img = document.getElementById('myImg10');
  var modalImg = document.getElementById("img11");
  var captionText = document.getElementById("caption");
  img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
  }
  </script>
                        
                         <div class="flex-grow-1 ms-3">
                            <img src="s4.jpg" style="height: 450px; width: 450px;" id="myImg11" alt="UE Manila SHS ICT Arduino Workshop 2022-2023">
                            <!-- The Modal -->
<div id="myModal" class="modal">
    <span class="close">&times;</span>
    <img class="modal-content" id="img12">
    <div id="caption"></div>
  </div>
  
  <script>
  // Get the modal
  var modal = document.getElementById('myModal');
  
  // Get the image and insert it inside the modal - use its "alt" text as a caption
  var img = document.getElementById('myImg11');
  var modalImg = document.getElementById("img12");
  var captionText = document.getElementById("caption");
  img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
  }
  </script>
                         </div>

                        </div>
                    </div>
                </div>
                <hr>
                <div id="section4">
                    <h3>CpE Team Building v8.0</h3>
                    <div>
                        <div class="d-flex">
        
                            <img src="d4.jpg" style="height: 450px; width: 450px;" id="myImg12" alt="CpE Team Building v8.0">
                             <!-- The Modal -->
<div id="myModal" class="modal">
    <span class="close">&times;</span>
    <img class="modal-content" id="img13">
    <div id="caption"></div>
  </div>
  
  <script>
  // Get the modal
  var modal = document.getElementById('myModal');
  
  // Get the image and insert it inside the modal - use its "alt" text as a caption
  var img = document.getElementById('myImg12');
  var modalImg = document.getElementById("img13");
  var captionText = document.getElementById("caption");
  img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
  }
  </script>
                        
                         <div class="flex-grow-1 ms-3">
                            <img src="d2.jpg" style="height: 450px; width: 450px;" id="myImg13" alt="CpE Team Building v8.0">
                             <!-- The Modal -->
<div id="myModal" class="modal">
    <span class="close">&times;</span>
    <img class="modal-content" id="img14">
    <div id="caption"></div>
  </div>
  
  <script>
  // Get the modal
  var modal = document.getElementById('myModal');
  
  // Get the image and insert it inside the modal - use its "alt" text as a caption
  var img = document.getElementById('myImg13');
  var modalImg = document.getElementById("img14");
  var captionText = document.getElementById("caption");
  img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
  }
  </script>
                         </div>

                        </div>
                    </div>
                    <br>

                    <div>
                        <div class="d-flex">
        
                            <img src="d3.jpg" style="height: 450px; width: 450px;" id="myImg14" alt="CpE Team Building v8.0">
                             <!-- The Modal -->
<div id="myModal" class="modal">
    <span class="close">&times;</span>
    <img class="modal-content" id="img15">
    <div id="caption"></div>
  </div>
  
  <script>
  // Get the modal
  var modal = document.getElementById('myModal');
  
  // Get the image and insert it inside the modal - use its "alt" text as a caption
  var img = document.getElementById('myImg14');
  var modalImg = document.getElementById("img15");
  var captionText = document.getElementById("caption");
  img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
  }
  </script>
                        
                         <div class="flex-grow-1 ms-3">
                            <img src="d1.jpg" style="height: 450px; width: 450px;" id="myImg15" alt="CpE Team Building v8.0">
                            <!-- The Modal -->
<div id="myModal" class="modal">
    <span class="close">&times;</span>
    <img class="modal-content" id="img16">
    <div id="caption"></div>
  </div>
  
  <script>
  // Get the modal
  var modal = document.getElementById('myModal');
  
  // Get the image and insert it inside the modal - use its "alt" text as a caption
  var img = document.getElementById('myImg15');
  var modalImg = document.getElementById("img16");
  var captionText = document.getElementById("caption");
  img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
  }
  </script>
                         </div>

                        </div>
                    </div>
                </div>
                <hr>
                <div id="section5">
                    <h3>CpE Exhibit</h3>
                    <div>
                        <div class="d-flex">
        
                            <img src="e1.jpg" style="height: 450px; width: 450px;" id="myImg16" alt="CpE Exhibit">
                             <!-- The Modal -->
<div id="myModal" class="modal">
    <span class="close">&times;</span>
    <img class="modal-content" id="img17">
    <div id="caption"></div>
  </div>
  
  <script>
  // Get the modal
  var modal = document.getElementById('myModal');
  
  // Get the image and insert it inside the modal - use its "alt" text as a caption
  var img = document.getElementById('myImg16');
  var modalImg = document.getElementById("img17");
  var captionText = document.getElementById("caption");
  img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
  }
  </script>
                        
                         <div class="flex-grow-1 ms-3">
                            <img src="e2.jpg" style="height: 450px; width: 450px;" id="myImg17" alt="CpE Exhibit">
                            <!-- The Modal -->
<div id="myModal" class="modal">
    <span class="close">&times;</span>
    <img class="modal-content" id="img18">
    <div id="caption"></div>
  </div>
  
  <script>
  // Get the modal
  var modal = document.getElementById('myModal');
  
  // Get the image and insert it inside the modal - use its "alt" text as a caption
  var img = document.getElementById('myImg17');
  var modalImg = document.getElementById("img18");
  var captionText = document.getElementById("caption");
  img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
  }
  </script>
                         </div>

                        </div>
                    </div>
                    <br>

                    <div>
                        <div class="d-flex">
        
                            <img src="e3.jpg" style="height: 450px; width: 450px;" id="myImg18" alt="CpE Exhibit">
                            <!-- The Modal -->
<div id="myModal" class="modal">
    <span class="close">&times;</span>
    <img class="modal-content" id="img19">
    <div id="caption"></div>
  </div>
  
  <script>
  // Get the modal
  var modal = document.getElementById('myModal');
  
  // Get the image and insert it inside the modal - use its "alt" text as a caption
  var img = document.getElementById('myImg18');
  var modalImg = document.getElementById("img19");
  var captionText = document.getElementById("caption");
  img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
  }
  </script>
                        
                         <div class="flex-grow-1 ms-3">
                            <img src="e4.jpg" style="height: 450px; width: 450px;" id="myImg19" alt="CpE Exhibit">
                             <!-- The Modal -->
<div id="myModal" class="modal">
    <span class="close">&times;</span>
    <img class="modal-content" id="img20">
    <div id="caption"></div>
  </div>
  
  <script>
  // Get the modal
  var modal = document.getElementById('myModal');
  
  // Get the image and insert it inside the modal - use its "alt" text as a caption
  var img = document.getElementById('myImg19');
  var modalImg = document.getElementById("img20");
  var captionText = document.getElementById("caption");
  img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
  }
  </script>
                         </div>

                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
                           
 
</body>
<hr>
  <div class="container" id="studentwork">    
    <div class="jumbotron">
        <h3 style="margin-left: 10px;">Student Work</h3>
        <div class="accordion" id="myAccordion" style="margin-left: 10px; margin-right: 10px;">
          <div class="accordion-item">
              <h2 class="accordion-header" id="headingOne">
                  <button type="button" class="accordion-button collapsed" data-bs-toggle="collapse" data-bs-target="#collapseOne">1. Student work of Computer Engineering Course.</button>									
              </h2>
              <div id="collapseOne" class="accordion-collapse collapse">
                  <div class="card-body">
                      <p><h5>Homework Assignments:</h5> These are typically problem-solving exercises or theoretical questions that students complete outside of class to reinforce their understanding of the course material.</p>
                      <p><h5>Labs:</h5> In computer engineering courses, students often participate in laboratory sessions where they get hands-on experience with hardware and software components. Lab work can include designing, building, and testing electronic circuits or writing and debugging software programs.</p>
                      <p><h5>Projects:</h5> Larger-scale assignments or group projects that require students to apply their knowledge to solve real-world engineering problems. This might involve building a digital system, developing software applications, or designing a computer hardware component.</p>
                      <p><h5>Quizzes and Exams: </h5>These are assessments that test students' understanding of the course content. Quizzes are often shorter and more frequent, while exams are comprehensive and typically occur at the end of a course or semester.</p>
                      <p><h5>Research Papers: </h5> In more advanced courses, students might be required to conduct research on a specific topic within computer engineering and write research papers or reports to communicate their findings.</p>
                      <p><h5>Presentations:</h5>Students may be asked to give presentations on a particular topic related to computer engineering. This helps develop their communication skills and the ability to convey complex technical information to an audience.</p>
                      <p><h5>Coding Assignments:</h5>For courses related to programming or software development, students may have coding assignments where they need to write, debug, and optimize computer programs.</p>
                      <p><h5>Hardware Design:</h5>In courses focusing on hardware design and digital systems, students may be tasked with designing and building digital circuits or components using tools like VHDL or Verilog.</p>
                      <p><h5>Team Projects:</h5>Collaborative projects where students work in teams to design and implement complex systems. This simulates the teamwork often required in the field of computer engineering.</p>
                      <p><h5>Final Projects:</h5>In some courses, students may have a culminating final project where they can showcase their skills and knowledge by designing and building a significant computer engineering project from start to finish.</p>
                      <p>The specific nature of student work can vary depending on the level of the course (introductory, intermediate, advanced), the institution's curriculum, and the instructor's teaching approach. However, these types of assignments and activities are commonly found in computer engineering courses to provide a well-rounded education in the field.</p>
                  </div>
              </div>
          </div>
          <div class="accordion-item">
              <h2 class="accordion-header" id="headingTwo">
                  <button type="button" class="accordion-button collapsed" data-bs-toggle="collapse" data-bs-target="#collapseTwo">2. The Computer Engineering Curriculum</button>
              </h2>
              <div id="collapseTwo" class="accordion-collapse collapse">
                  <div class="card-body">
                      <p>The CpE curriculum and student projects will focus on embedded systems, a term that refers to
                        any device that uses a microprocessor or microcontroller for a specific purpose. Embedded systems
                        appear in a wide array of household and industrial systems, and including portable and console game
                        systems, robots, game peripherals, electronic toys, digital cameras, audio/video component systems,
                        and even aircraft flight systems.</p>
                  </div>
              </div>
          </div>
          <div class="accordion-item">
              <h2 class="accordion-header" id="headingThree">
                  <button type="button" class="accordion-button collapsed" data-bs-toggle="collapse" data-bs-target="#collapseThree">3. The UE CPE Design And Laboratory Experience</button>                     
              </h2>
              <div id="collapseThree" class="accordion-collapse collapse">
                  <div class="card-body">
                      <p>The computer engineering program at UE is a balance of engineering science and design. The freshman and sophomore year courses are structured to lay a solid foundation for the junior and senior level design courses by the introduction of courses in hardware, software and the engineering sciences (math, physics, and chemistry).</p>
                      <p>Design methodology and analysis techniques are stressed throughout the curriculum in the majority of the core courses required for graduation. The lecture classes are typically complemented by laboratory experiments that the student has designed, simulated and analyzed before commencing with the actual hands-on construction and testing. Students are well prepared in the software/hardware design procedure when they reach the final classes of Microprocessor System Design and the Senior Project Classes.</p>
                      <p>Skills in both software and hardware are employed in the design of a microcomputer system that require the student to write his own operating system in a high-level language ( e.g. C or C++) with embedded assembly language. The hardware support requirement is the design and implementation of a direct memory access (DMA) controller using a PLD or FPGA and a peripheral interface controller that supports a printer and an external bus. Students have several pattern electives to choose from in advanced software and hardware design classes. Such classes include topics in networks, embedded systems, VHDL, digital signal processing, state machine design, VLSI, control systems, communications and artificial intelligence.</p>
                      <p>The senior project class brings together, in a balance of solid software and hardware skills acquired throughout the required and elective curriculum, a culminating experience which involves teamwork, design, report writing and oral presentation. These experiences prepare our graduates to be successful engineers with an awareness of the many challenges involved in the workplace.</p>
                  </div>
              </div>
          </div>
      </div>
      <br>
         <p><a href="https://www.ue.edu.ph/onlineadmission/main.html" target="_blank" class="btn btn-primary btn-lg">Enroll Now!</a></p>
    </div>

</div>

<hr>
                        <!-- The Modal -->
<div id="myModal" class="modal">
    <span class="close">&times;</span>
    <img class="modal-content" id="img01">
    <div id="caption"></div>
</div>


  <script>
      // Get the modal
      var modal = document.getElementById('myModal');
      
      // Get the image and insert it inside the modal - use its "alt" text as a caption
      var img = document.getElementById('myImg');
      var modalImg = document.getElementById("img01");
      var captionText = document.getElementById("caption");
      img.onclick = function(){
        modal.style.display = "block";
        modalImg.src = this.src;
        captionText.innerHTML = this.alt;
      }
      
      // Get the <span> element that closes the modal
      var span = document.getElementsByClassName("close")[0];
      
      // When the user clicks on <span> (x), close the modal
      span.onclick = function() { 
        modal.style.display = "none";
      }
      </script>
      

<div class="wrapper" style="margin-left: 2%;">
  <h6> Copyright © 2023 Computer Engineering Department, All Rights Reserved.</h6>
  </div>
</div>
<br>

      



</body>
</html>
