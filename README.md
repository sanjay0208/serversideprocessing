# Design a Website for Server Side Processing

## AIM:
To design a website to perform mathematical calculations in server side.

## DESIGN STEPS:

##Step 1:

Clone the repository from GitHub
##Step 2:

Create Django Admin project.
##Step 3:

create a New App.
##Step 4:

Create python programs for views and urls.
##Step 5:

Create a HTML file of forms.
##Step 6:

Publish the website in the given URL.

Publish the website in the given URL.

## PROGRAM :
~~~
<html>
<head>
<meta charset='utf-8'>
<meta http-equiv='X-UA-Compatible' content='IE=edge'>
<title>Area of Rectangle</title>
<meta name='viewport' content='width=device-width, initial-scale=1'>
<style type="text/css">
body 
{
background-color:cyan;
}
.edge {
width: 1080px;
margin-left: auto;
margin-right: auto;
padding-top: 200px;
padding-left: 300px;
}
.box {
display:block;
border: Thick dashed lime;
width: 500px;
min-height: 300px;
font-size: 20px;
background-color: purple;
}
.formelt{
color: Red;
text-align: center;
margin-top: 5px;
margin-bottom: 5px;
}
h1
{
color: yellow;
text-align: center;
padding-top: 20px;
}
</style>
</head>
<body>
<div class="edge">
<div class="box">
<h1>Area of a Rectangle</h1>
<form method="POST">
{% csrf_token %}
<div class="formelt">
Length : <input type="text" name="length" value="{{l}}"></input>(in m)<br/>
</div>
<div class="formelt">
Breadth : <input type="text" name="breadth" value="{{b}}"></input>(in m)<br/>
</div>
<div class="formelt">
<input type="submit" value="Calculate"></input><br/>
</div>
<div class="formelt">
Area : <input type="text" name="area" value="{{area}}"></input>m<sup>2</sup><br/>
</div>
</form>
</div>
</div>
</body>
</html>
~~~
## OUTPUT:
![WhatsApp Image 2023-05-30 at 2 04 12 PM](https://github.com/sanjay0208/serversideprocessing/assets/119406959/745c913b-a8b1-491b-90c4-b42b1213ac5c)

### Home Page:
![homepage](https://github.com/sanjay0208/serversideprocessing/assets/119406959/40de6241-1cc0-4390-b8f3-82748bc595c2)

## Result:
The program for implementing server side processing is completed successfully.
