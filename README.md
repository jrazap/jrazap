

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css"/>
    <title>Cool profile Card</title>
      <style>
        * {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
body {
  font-family: "poppins", sans-serif;
}
.main-container {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.container {
  position: relative;
  width: 280px;
  height: 380px;
  background: #040404;
  box-shadow: 0 15px 18px rgba(179, 179, 179, 0.6);
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-evenly;
  overflow: hidden;
  z-index: 1;
  font-size: 0.9rem;
}
.profile-pic {
  width: 100px;
  height: 100px;
  background: url(../img/01.png);
  border: 3px solid #fff;
  border-radius: 50%;
}
.layer {
  position: absolute;
  top: 21%;
  width: 100%;
  height: 3px;
  background: #fff;
  transition: 0.4s ease;
  z-index: -1;
  overflow: hidden;
}
.detailes {
  color: #fff;
}
.skills {
  font-size: 1.5rem;
}
.skills i {
  margin: 0 0.3rem;
  opacity: 0;
  transition: 0.4s ease;
}
.fa-html5 {
  color: #e34c26;
}
.fa-css3-alt {
  color: #0098ff;
}
.fa-js {
  color: #f0db4f;
}
.fa-react {
  color: #61dafb;
}
.fa-angular {
  color: #dd1b16;
}
.btn a {
  display: block;
  text-decoration: none;
  width: 200px;
  height: 50px;
  border: 1px solid #fff;
  border-radius: 35px;
  text-align: center;
  line-height: 50px;
  color: #fff;
  letter-spacing: 2px;
  transition: 0.4s ease;
}
.container:hover .layer {
  height: 100%;
}
.container:hover .detailes {
  color: #040404;
}
.container:hover .btn a {
  border-color: #040404;
  color: #040404;
}
.container:hover .btn:hover a {
  background-color: #040404;
  color: #fff;
}
.container:hover .skills i {
  opacity: 1;
}
    </style>
</head>
<body>
    <div class="main-container">
        <div class="container">
            <div class="profile-pic"></div>
            <div class="layer"></div>
            <div class="detailes">
                <p>Mohamed Elazap</p>
                <p>Front End Developer</p>
            </div>
            <div class="skills">
                <i class="fab fa-html5"></i>
                <i class="fab fa-css3-alt"></i>
                <i class="fab fa-js"></i>
                <i class="fab fa-react"></i>
                <i class="fab fa-angular"></i>
                
            </div>
            <div class="btn">
                <a href="#">Hire me</a>
            </div>
        </div>
    </div>
</body>

