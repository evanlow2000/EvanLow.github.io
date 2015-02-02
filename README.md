<!DOCTYPE html>
<html lang = "en-US">
<head>
<title> Made by Evan Low </title>
<style>
  table, th, td {  
  border: 1px solid black; 
  border-collapse: collapse; 
  padding: 3px 
  }
  table {
   border-spacing: 5px 
   }
  table#t1 {
     width: 50%}
  table#t1 th { 
	 background-color: black;
	 color: white}	
  body { background-color:azure }
  #nav {
    line-height:30px;
    background-color:black;
	color: white;
    height:20px;
    width:150px;
    float:top;
    padding:5px; 
}
  footer {
   background-color: black;
   color: white;
   cleaR: both;
   text-align: center;
   padding: 5px
   }
</style>
</head>
<body>
<h1 style="text-align:center"> HTML PRACTICE PAGE </h1>
<hr>
<div id="nav">  
Schools							 Teams 									Family
</div>
<section>
<p style="font-family:courier">
<b> Welcome to my website! </b> <br>
I am currently a <del> novice </del> in using <small> HTML. </small> 
<br> If you are in the mood for music, here is a direct link to listen to "Let it Go" from <i> Frozen: </i> <a href="https://www.youtube.com/watch?v=L0MK7qz13bU" target= "_blank"> Click here</a>
</p>
</section>
<hr>
<article>
<h2 style="text-align:center"> About Me </h2>
<p style="color:grey">
<i> Hello. My name is Evan Low. </i>
<strong> I am a ninth grader studying </strong> <em> at Stuyvesant High School. </em>
<br> I enjoy playing games such as pokemon and osu!.   
<br> <pre> <img src="http://i.imgur.com/ET8tgug.jpg" alt="html5.gif" width="300" height="200">             <img src= "http://i1-games.softpedia-static.com/screenshots/OSU_1.jpg" alt="html5.gif" width="300" height="200">  </pre> 
<!--Any other information are to be censored and will not be shown :p-->
<br>
<table id="t1">
  <caption> <strong> SCHEDULE FOR THE SPRING TERM </strong> </caption>
    <tr>
      <th>  Period </th>
	  <th colspan = "2">  Class </th>
    </tr>
    <tr> 
      <td> 1 </td>
	  <td> Geometry Avigdor </td>
    </tr>  
    <tr>
       <td> 2 </td>
	   <td> Topics in Biology Horenstein </td>
    </tr>
	<tr> 
	   <td> 3 </td>
	   <td> Topics in Biology Horenstein </td>
	</tr>
	<tr>
	   <td> 3 </td>
	   <td> Phys ed Rosenthal </td>
	</tr>
	<tr> 
	    <td> 4 </td>
		<td> Art App Cappel </td>
    </tr>
    <tr>
        <td> 5 </td>
        <td> Global Valentin </td>
    </tr>
    <tr> 
        <td> 6 </td>
        <td> Freshman Comp Pohan </td>
    </tr>
    <tr>
        <td> 7 </td>
        <td> Lunch </td>
    </tr>
    <tr> 
        <td> 8 </td>
        <td> Band Winkel </td>
    </tr>
    <tr> 
        <td> 9 </td>
        <td> Spanish Carpenter </td>	
</table>		
<h3> To Do List </h3>
<ul style="list-style-type:disc"> 
  <li> Master HTML </li>
  <li> Master Java </li> 
  <li> Learn C for Robotics </li>
</ul>	
<h4> Morning Routines </h4> 
<ol type="1"> 
  <li> Wake up promptly at 5:30 am.</li>
  <li> Brush my teeth </li> 
  <li> Prepare and eat breakfast </li>
  <li> Get dressed and ready for school </li>
  <li> Leave approximatley around 6:10 am. </li> 
<h5> Detailed Descriptions of My Classes </h5>
<dl> 
  <dt> Freshman Composition </dt> 
  <dd>- writing class </dd>
  <dt> Geometry </dt>
  <dd>- math class involving shapes and objects </dd> 
  <dt> Biology </dt>
  <dd>- study of life </dd>
  <dt>- Global History </dt>
  <dd>- study of history of the world </dd>
  <dt> Spanish </dt>
  <dd>- study of a language </dd> 
  <dt> Art Appreciation </dt>
  <dd>- study of art </dd>

</p>
</article>
<footer>
Copyright &copy; Evan Low 2015
</body>
</html>