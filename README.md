<!DOCTYPE html>
<html><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

<title>Module 2 solution</title>
<style>

/*Base styles*/
html 
{
  box-sizing: inherit;
}
	
h1 
{
  font-size: 175%;
  margin: 40px;
  text-align: center;
}
	
body 
{
  font-family: Cambria, "Hoefler Text", "Liberation Serif", Times, "Times New Roman", "serif"
  font-size: 20px;
}
*, *:before, *:after 
{
  box-sizing: border box;
}

.text 
{
  color: #2c3e58;
  background-color: #ccffff;
  border: 1px solid black;
  padding: 0px 10px 10px 10px;
  margin: 10px;
 
}

.text h2 
{
  color: #ffff;
  font-size: 125%;
  padding: 2px 35px;
  border-bottom: 1px solid black;
  border-left: 1px solid black;
  float: right;
  margin: 0 -10px 10px 0;
}

.text p 
{
  clear: right;
}

#chicken h2 {
  background-color: #fed455;
}

#beef h2 {
  background-color: #fdfd3e;
}

#sushi h2 {
  background-color: #3efe4c;
}



	
/* Large devices*/
@media (min-width: 992px) 
{
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 
	{
    float: left;
  }

  .col-lg-1 
	{
    width: 8.33%;
  }

  .col-lg-2 
	{
    width: 16.66%;
  }

  .col-lg-3 
	{
    width: 25%;
  }

  .col-lg-4 
	{
    width: 33%;
  }

  .col-lg-5 
	{
    width: 41.66%;
  }

  .col-lg-6 
	{
    width: 50%;
  }

  .col-lg-7 
	{
    width: 58.33%;
  }

  .col-lg-8 
	{
    width: 66.66%;
  }

  .col-lg-9 
	{
    width: 74.99%;
  }

  .col-lg-10 
	{
    width: 83.33%;
  }

  .col-lg-11 {
    width: 91.66%;
  }

  .col-lg-12 
	{
    width: 100%;
  }
}

/*Medium devices*/
@media (min-width: 768px) and (max-width: 991px) 
{
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 
	{
    float: left;
  }

  .col-md-1 
	{
    width: 8.33%;
  }

  .col-md-2 
	{
    width: 16.66%;
  }

  .col-md-3 
	{
    width: 25%;
  }

  .col-md-4 {
    width: 33%;
  }

  .col-md-5 
	{
    width: 41.66%;
  }

  .col-md-6 
	{
    width: 50%;
  }

  .col-md-7 
	{
    width: 58.33%;
  }

  .col-md-8 
	{
    width: 66.66%;
  }

  .col-md-9 
	{
    width: 74.99%;
  }

  .col-md-10 {
    width: 83.33%;
  }

  .col-md-11 
	{
    width: 91.66%;
  }

  .col-md-12 
	{
    width: 99%;
  }
}

	/*Small devices*/
@media (max-width: 767px) 
{
  .col-sd-1, .col-sd-2, .col-sd-3, .col-sd-4, .col-sd-5, .col-sd-6, .col-sd-7, .col-sd-8, .col-sd-9, .col-sd-10, .col-sd-11, .col-sd-12 
	{
    float: left;
  }

  .col-sd-1 
	{
      width: 8.33%;
  }

  .col-sd-2 
	{
     width: 16.66%;
  }

  .col-sd-3 
	{
    width: 25%;
  }

  .col-sd-4 
	{
    width: 33%;
  }

  .col-sd-5 
	{
    width: 41.66%;
  }

  .col-sd-6 
	{
    width: 50%;
  }

  .col-sd-7 
	{
    width: 58.33%;
  }

  .col-sd-8 
	{
    width: 66.66%;
  }

  .col-sd-9 
	{
    width: 74.99%;
  }

  .col-sm-10 
	{
    width: 83.33%;
  }

  .col-sd-11 
	{
    width: 91.66%;
  }

  .col-sd-12 
	{
    width: 100%;
  }
}


.clear 
	{
  clear: both;
}
* {
  box-sizing: border-box;
}
  }
  
}
</style>
</head>
<body>  <h1>Our Menu</h1>
<div class="row">

  <div class="col col-lg-4 col-md-6 col-sm-12">
    <div id="chicken" class="text">
      <h2>Chicken</h2>
      <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    </div>
  </div>
  <div class="col col-lg-4 col-md-6 col-sm-12">
    <div id="beef" class="text">
      <h2>Beef</h2>
      <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    </div>
  </div>
  <div class="col col-lg-4 col-md-12 col-sm-12">
    <div id="sushi" class="text">
      <h2>Sushi</h2>
      <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    </div>
  </div>
</body>
</html>
