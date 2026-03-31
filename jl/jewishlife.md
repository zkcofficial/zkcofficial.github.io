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
  <a href="/ar/art.html">Art</a>
  <a href="/#about" class="split">About</a>
</div>

<hr>

<div class="row">
  <div class="left" style="background-color:#bbb;">
    <h2>Menu</h2>
    <input type="text" id="mySearch" onkeyup="myFunction()" placeholder="Search.." title="Type in a category">
  <ul id="myMenu">
          <li><a href="/jl/articles/tefillin1.html">Putting on Tefillin (English)</a></li>       
          <li><a href="/jl/articles/shemaprayer(english)1.html">Shema prayer (English)</a></li>
          <li><a href="/jl/articles/03222026.html">Week of 03/22/2026</a></li>
          <li><a href="/jl/articles/03132026wl.html">Inaugural post; Weekly recap: 03/14/2026</a></li>

  </ul> 
  </div>
  
  <div class="right" style="background-color:#ddd;">
    <h2>Page Content</h2>
    <p>Start to type for a specific article you wish to view.</p>
    
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
<img width="400" height="301" alt="Screenshot 2026-03-13 4 51 42 AM" src="https://scontent-lga3-2.xx.fbcdn.net/v/t39.30808-6/662563290_122289329918199570_5204720484525280287_n.jpg?stp=dst-jpg_p180x540_tt6&amp;_nc_cat=100&amp;ccb=1-7&amp;_nc_sid=13d280&amp;_nc_ohc=yY1nLXqC9ugQ7kNvwEK9MrO&amp;_nc_oc=Adox2QK5E-WN2mtqkOdDF2WY3UoFv5kstSaOwAaxpbByzlIgOffQU7aOkGdFpeKbRfKwfX6tEVXJbSljlH5miOOu&amp;_nc_zt=23&amp;_nc_ht=scontent-lga3-2.xx&amp;_nc_gid=7geOfckgNhrNn3Pm4j8LvA&amp;_nc_ss=7a3a8&amp;oh=00_Af2GI0ABQwAhEOgmfU6rOYllIA-fRbx_yTabKBFCWYsdfA&amp;oe=69D21256" alt="No photo description available." />
<a href="/jl/articles/03222026.html">Weekly recap: 03/22/2026</a>
</div>
</div>
<br>

<div class="main1">
<iframe width="400" height="341" src="https://www.youtube.com/embed/mxS7aK00Nsg?si=sh-bpqOYipJuaJGP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
<br>

<div class="main1">
<iframe width="400" height="341" src="https://www.youtube.com/embed/ViFT59oESkU?si=Ld4b02mssDbtlbeL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
<br>

<div class="main1">
<div class="div1">
<img width="400" height="301" alt="Screenshot 2026-03-13 4 51 42 AM" src="https://github.com/user-attachments/assets/3aae95a7-2f57-45c6-a5d6-32b88e4546e3" />
<a href="/jl/articles/03222026.html">Weekly recap: 03/22/2026</a>
</div>
</div>
<br>

<div class="main1">
<div class="div1">
<img width="400" height="301" alt="Screenshot 2026-03-13 4 51 42 AM" src="https://github.com/zkcofficial/zkcofficial.github.io/blob/main/jl/imagedump/attachment%20(41).jpeg?raw=true" />
<a href="/jl/articles/03132026wl.html">Weekly recap: 03/14/2026</a>
</div>
</div>
<br>





