<template>
<div id="wrap">
    <div class="head">
    <h1 style="margin:0;"> Web Programming </h1>
    <p> Membuat Layout Website</p>
    </div>
   
        <ul>
        <li><a href="">Home</a></li>
        <li><a href="">News</a></li>
        <li><a href="">Contact</a></li>
        <li><a href="">About</a></li>
        </ul>
  
        <div class="sidebar">
            <ul>
                <li> <a href=""> Belajar HTML Dasar</a></li>
                <li> <a href=""> Belajar CSS Dasar</a></li>
                <li> <a href=""> Belajar JavaScript Dasar</a></li>
                <li> <a href=""> Belajar Jquery Dasar</a></li>
            </ul>
        </div>
        <div class="content">
            <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, 
            sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
            Arcu odio ut sem nulla pharetra diam sit amet. 
            Vel pretium lectus quam id leo in vitae turpis. 
            Nisi lacus sed viverra tellus in hac habitasse. 
            Commodo ullamcorper a lacus vestibulum sed. 
            Viverra suspendisse potenti nullam ac tortor vitae purus faucibus ornare. 
            Est pellentesque elit ullamcorper dignissim. Adipiscing enim eu turpis egestas. 
            Sit amet massa vitae tortor condimentum lacinia quis. 
            Ut faucibus pulvinar elementum integer enim neque volutpat ac. 
            Elementum integer enim neque volutpat ac. 
            Sapien et ligula ullamcorper malesuada. 
            Cursus euismod quis viverra nibh cras pulvinar mattis. 
            Consectetur adipiscing elit duis tristique sollicitudin nibh. 
            Tincidunt nunc pulvinar sapien et ligula ullamcorper malesuada proin libero.
        </p>
      
        <p>
            Risus viverra adipiscing at in tellus integer. 
            Mollis nunc sed id semper risus in hendrerit gravida rutrum. 
            Massa enim nec dui nunc mattis enim ut tellus.
             Sit amet commodo nulla facilisi nullam vehicula. 
             Rhoncus est pellentesque elit ullamcorper dignissim cras tincidunt. 
             Amet mauris commodo quis imperdiet massa. 
             Tempor orci eu lobortis elementum. 
             Nunc vel risus commodo viverra maecenas accumsan lacus. 
             Hac habitasse platea dictumst quisque sagittis. 
             Amet porttitor eget dolor morbi. 
             Id diam vel quam elementum pulvinar etiam non quam.
        </p>
        
        <p>
            Risus viverra adipiscing at in tellus integer. 
            Mollis nunc sed id semper risus in hendrerit gravida rutrum. 
            Massa enim nec dui nunc mattis enim ut tellus.
             Sit amet commodo nulla facilisi nullam vehicula. 
             Rhoncus est pellentesque elit ullamcorper dignissim cras tincidunt. 
             Amet mauris commodo quis imperdiet massa. 
             Tempor orci eu lobortis elementum. 
             Nunc vel risus commodo viverra maecenas accumsan lacus. 
             Hac habitasse platea dictumst quisque sagittis. 
             Amet porttitor eget dolor morbi. 
             Id diam vel quam elementum pulvinar etiam non quam.
        </p>
        </div>
        <div id="footer">
        <p>&reg; Rizky Aldi Saputra </p>
        
        
    </div>
   
</div>
</template>
<script>
export default {
    name : 'helloWoerld'
}
</script>
<style>
#wrap{
  padding: 5%;

}
.head{
    text-align: center;
    background:pink;
    height: 150px;
    width: 100%;
    color: blue;
    

}



.menu{
    margin-top: 10px;
    background: #0458e0;
    height: 100px;
}
ul {
 
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* Change the link color to #111 (black) on hover */
li a:hover {
  background-color: #111;
}
.sidebar {
    
    width: 30%;
    display: block;
   height: 100%;
   float: left;
   
}    


.sidebar li a{
   
  display: block;
  color:black;

  text-decoration: none;
  font-size: 20px;
  padding-top: 20px;
  margin: 20px;
  


/* Change the link color on hover */


}.sidebar li a:hover{
  
  color:pink;
  
  
  
}
.sidebar ul{
    list-style-type: none;
  margin: 0;
  padding: 0;
  width: 100%;
  background-color:yellow;
  height: 100%;
  display: block;

}
.content{
 
    width: 70%;
    height: 388px;
    text-align: justify;
    background-color: #0458e0;
    float:right;
    
    
}
#footer{
    color:black;
    text-align: right;
    background-color:yellow;
    height: 50px;
    padding: 1%;
    clear: both;
    float: bottom;
    
}
</style>



