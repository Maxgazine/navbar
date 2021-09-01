# navbar
<head>
  <style>
  .nav{
  background: linear-gradient(45deg, #00a79d, #1c4696);
  width: 100%;
  height: 8%;
  display: flex;
  justify-content: flex-end;
  position: fixed;
  top: 0;
  left: 0;
  box-shadow: 0 1px 0.4em ;
  z-index: 10;
}
.nav-list{
  display: flex;
  padding: 2px;
  margin: 0;
}
.ul-non-style{list-style: none;}
@media (max-width: 1980px){
.nav-link{
  height: 50%;
  display: block;
  font-size: 130%;
  color: white;
  padding: 2vh;
}
}
.nav-link:hover{
  background-color: darkgray;
  cursor: pointer;
}
  </style>
</head>
<body>
<nav id="navbar" class="nav">
    <ul class="nav-list ul-non-style">
      <li><a href="#welcome-section" class="nav-link">Home</a></li>
      <li><a href="#Introduction-section" class="nav-link">Introduction</a></li>
      <li><a href="#work-section" class="nav-link">Work</a></li>
      <li><a href="#contact-section" class="nav-link">Contact</a></li>
    </ul>
  </nav>
</body>  
