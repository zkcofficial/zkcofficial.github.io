# Jewish Life

<hr>



<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  font-family: Arial, Helvetica, sans-serif;
}

* {
  box-sizing: border-box;
}

/* Create a column layout with Flexbox */
.row {
  display: flex;
}

/* Left column (menu) */
.left {
  flex: 35%;
  padding: 15px 0;
}

.left h2 {
  padding-left: 8px;
}

/* Right column (page content) */
.right {
  flex: 65%;
  padding: 15px;
}

/* Style the search box */
#mySearch {
  width: 100%;
  font-size: 18px;
  padding: 11px;
  border: 1px solid #ddd;
}

/* Style the navigation menu inside the left column */
#myMenu {
  list-style-type: none;
  padding: 0;
  margin: 0;
}

#myMenu li a {
  padding: 12px;
  text-decoration: none;
  color: black;
  display: block
}

#myMenu li a:hover {
  background-color: #eee;
}
    
  .main1 {
    display: flex;
  justify-content: center;
  align-items: center;
    
  }
   
  .div1 {
    height: 341px;
    text-align: center;
    width: 400px;
    background-color: lightgrey;
    border-style: solid;
    border-color: lightgrey;

    }


 a:link {
  text-decoration: none;
}

a:visited {
  text-decoration: none;
}

a:hover {
  text-decoration: none;
}

a:active {
  text-decoration: none;
}


 .topnav {
  overflow: hidden;
  background-color: #333;
}

.topnav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

/* Create a right-aligned (split) link inside the navigation bar */
.topnav a.split {
  float: right;
  background-color: grey;
  color: white;
}
</style>

<div class="topnav">
  <a class="active" href="https://zkcofficial.github.io/">Home</a>
  <a href="/jl/jewishlife.html">Jewish Life</a>
  <a href="/ei/ethnographicinterests.html">Ethnographic Interests</a>
  <a href="#contact">S(not done)</a>
  <a href="#contact">A(not done)</a>
  <a href="#about" class="split">About(not done)</a>
</div>

<hr>

<div class="row">
  <div class="left" style="background-color:#bbb;">
    <h2>Menu</h2>
    <input type="text" id="mySearch" onkeyup="myFunction()" placeholder="Search.." title="Type in a category">
  <ul id="myMenu">
          <li><a href="/jl/articles/03222026.html">Week of 02/22/2026</a></li>
          <li><a href="/jl/articles/03132026wl.html">Inaugural post; Weekly recap: 03/14/2026</a></li>
   
  </ul>
  </div>
  
  <div class="right" style="background-color:#ddd;">
    <h2>Page Content</h2>
    <p>Start to type for a specific category inside the search bar to filter the search options.</p>
    
  </div>
</div>

<script>
function myFunction() {
  var input, filter, ul, li, a, i;
  input = document.getElementById("mySearch");
  filter = input.value.toUpperCase();
  ul = document.getElementById("myMenu");
  li = ul.getElementsByTagName("li");
  for (i = 0; i < li.length; i++) {
    a = li[i].getElementsByTagName("a")[0];
    if (a.innerHTML.toUpperCase().indexOf(filter) > -1) {
      li[i].style.display = "";
    } else {
      li[i].style.display = "none";
    }
  }
}
</script>

<hr>
<div class="main1">
<div class="div1">
<img width="400" height="301" alt="Screenshot 2026-03-13 4 51 42 AM" src="https://github.com/user-attachments/assets/3aae95a7-2f57-45c6-a5d6-32b88e4546e3" /><br>
<a href="/jl/articles/03222026.html">Weekly recap: 03/22/2026</a>
</div>
</div>
<br>

<div class="main1">
<div class="div1">
<img width="400" height="301" alt="Screenshot 2026-03-13 4 51 42 AM" src="https://github.com/zkcofficial/zkcofficial.github.io/blob/main/jl/imagedump/attachment%20(41).jpeg?raw=true" /><br>
<a href="/jl/articles/03132026wl.html">Weekly recap: 03/14/2026</a>
</div>
</div>
<br>










