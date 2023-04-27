<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8"
    <meta name="viewpoint" content="width=device-width, initial-scale=1.0">
       <title>Document</title>
       <style>
        *{
    padding: 0;
    margin: 0;
    outline: none;
    border: none;
    box-sizing: border-box;
}

html{
    font-size: 62.5%;
    overflow-x: hidden;
}
body{
    background-color: #111;
    overflow: hidden;
    padding-left: 35rem;
}

.heading{
    text-align: center;
    margin: 0 6rem;
    font-size: 4rem;
    padding-top: 6rem;
    border-bottom: .1rem solid #fff4;
    color: #fff;
}

.heading span{
    color: yellow;
}

.title{
    text-align: center;
    margin: 0 6rem;
    font-size: 4rem;
    padding-top: 6rem;
    border-bottom: .1rem solid #fff4;
    color: #fff;
}

.title span{
    color: yellow;
}

.head{
    text-align: center;
    margin: 0 6rem;
    font-size: 4rem;
    padding-top: 5rem;
    border-bottom: .1rem solid #fff4;
    color: #fff;
}
.head span{
    color: yellow;
}
.pro{
    text-align: center;
    margin: 0 6rem;
    font-size: 4rem;
    padding-top: 5rem;
    border-bottom: .1rem solid #fff4;
    color: #fff;
}
.pro span{
    color: yellow;
}
header{
    position:fixed;
    top: 0;
    left: 0;
    z-index: 1000;
    height: 100%;
    width: 35rem;
    background:#1a1a1a;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-flow: column;
    text-align: center;
}

header .user img{
    height: 13rem;
    width: 13rem;
    border-radius: 50%;
    object-fit: cover;
    border: .5rem solid;
}

header .user .nm{
    font-size:2rem;
    color: #fff;
}

header .user .jb{
    font-size:1rem;
    color: #fff;
}

header .nv{
    width: 100%;
}
header .nv ul{
    list-style: none;
    padding: 1rem ;
}

header .nv ul li a{
    display: block;
    padding: 1rem;
    margin: 1.5rem 0;
    background: #333;
    color: #fff;
    font-size: 2rem;
    border-radius: 5rem;
    text-decoration: none;  
}
header .nv ul li a:hover{
    background-color:yellowgreen;
}

.Details .Row{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    padding: 3rem 0;
}

.Details .Row .det{
    flex: 1 1 48rem;
    padding: 2rem 1rem;
    padding-left: 8rem;
}

.Details .Row .det h3{
    font-size: 2rem;
    color: yellow;
    padding: 1rem 0;
    font-weight: normal;
}

.Details .Row .det h3 span{
    color: #eee;
    padding: 0. 5rem;
}
table,th,td{
    border: 1px solid yellow;
    border-collapse: collapse;
}
td{
    color: white;
    padding: 1rem;
}
th{
    color: white;
    padding: 1rem;
}
table{
    text-align: center;
    margin: 0 6rem;
    font-size: 2rem;
    padding: 1rem;
    border-bottom: .1rem solid #fff4;
    color: #fff;
}
#lis li{
    margin: 0 9rem;
    color: white;
    font-size: medium;
    padding: .5rem 1rem;
}
.Project .Row{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    padding: 3rem 0;
}

.Project .Row .det{
    flex: 1 1 48rem;
    padding: 2rem 1rem;
    padding-left: 8rem;
}

.Project .Row .det h3{
    font-size: 2rem;
    color: yellow;
    padding: 1rem 0;
    font-weight: normal;
}

.Project .Row .det h3 span{
    color: #eee;
    padding: 0. 5rem;
}
       </style>
</head>
<body>
    <header>
       <div class="user">
       <img src="photo.jpg">
       <h5 class="nm">Jyoti</h5>
       <p class="jb">Student</p>
       </div>
       <nav class="nv">
          <ul>
             <li><a href="#Details">Details</a></li>
             <li><a href="#Education">Education</a></li>
             <li><a href="#Technical Skills">Technical Skills</a></li>
             <li><a href="#Project">Project</a></li>
          </ul>
       </nav>
    </header>
    <section class="Details" id="Details">
        <h1 class="heading"><span>Details about me</span></h1>
        <div class="Row">
        <div class="det">
             <h3><span>Name: </span>Jyoti Pathak</h3>
             <h3><span>Age: </span>23</h3>
             <h3><span>Gender: </span>Female</h3>
             <h3><span>Email: </span>jyotipathak3017@gmail.com</h3>
             <h3><span>Phone_no: </span>9752104237</h3>    
        </div>
    </div>
    </section>
<section class="Education" id="Education">
    <h1 class="title"><span>Education</span></h1><br><br><br>
    <table>
        <tr>
            <th>Cource</th>
            <th>Name of the institute</th>
            <th>University</th>
            <th>Percentage</th>
        </tr>
        <tr>
            <td>10th</td>
            <td>Shanti Niketan Public School</td>
            <td>StateBoard</td>
            <td>71.33%</td>
        </tr>
        <tr>
            <td>12th</td>
            <td>Colonel's Academy of Radient Education</td>
            <td>cbse</td>
            <td>54.6</td>
        </tr>
        <tr>
            <td>BE</td>
            <td>Lakhmi chand institute of Technology</td>
            <td>Chattisgarh,Bilaspur</td>
            <td>74.44%</td>
        </tr>
    </table>
</section>
<br><br><br><br><br><br>
<section class="Technical Skills" id="Technical Skills">
    <h1 class="head"><span>Technical Skills</span></h1>
    <div>
    <ul id="lis">
        <li>Java</li>
        <li>C</li>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>Oracle</li>
        <li>MySQL</li>
        <li>Manual Testing</li>
        
    </ul>
</div>
</section>
<section class="Project" id="Project">
    <h1 class="heading"><span>Project</span></h1>
    <div class="Row">
        <div class="det">
    <h3><span>Role: </span>Team Leader</h3>
    <h3><span>Title: </span>Automatic Irrigation System</h3>
    <h3><span>Description: </span>Automatic controlled irrigation is the use of soil moisture sensor in the field to collect or monitor soil information, field information, and crop growth information, and transmit the monitoring data to the head control center, and issue corresponding irrigation management instructions to the terminal under the corresponding system software analysis and decision. </h3>
            </div>
</div>
</section>
</body>
</html>
