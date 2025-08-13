# web-sitem1
/*body {
    background-color:white;
    font-family:"Playwrite AU QLD";
}

.momo {
    background-color: aqua;
    width: 300px;
    padding: 15px;
    border-radius:30px;
    text-align:start;
    margin:15px ;
    box-shadow: 10px 8px 22px 10px rgba(0, 0, 0, 0.51);
}

.momo img {
    width: 150px;
    border-radius:15px;
    box-shadow:10px 8px 22px 10px rgb(0, 0, 0) ;
}

.momo h1 {
    font-size: 25px;
    margin: 15px 0;
    color: rgb(0, 0, 0);
}

.momo p {
    color:black;
}

.sosyal a {
    text-decoration: none;
    color: rgb(0, 0, 0);
    background-color: #ff0000;
    padding:5px 10px ;
    margin: 10px;
    border-radius: 10px;
}

input:hover a{
    box-shadow: 10px 8px 22px 10px rgb(255, 0, 0);
}*/

/* GENEL AYARLAR */
* {
    margin: 0;
    padding: 1px;
    box-sizing: border-box;
    font-family: "poppins" , sans-serif ;

}

body  {
    line-height: 1.6;
 }
 
 /*ÜST MENÜ */
 header {
    background: linear-gradient(to right #0066ff);
    padding: 20px 0;
 } 

 header nav {
    display: flex;
    justify-content:space-between;
    align-items: center;
    max-width: 1100px;
    margin: auto;
    color: rgb(0, 136, 255);
 }

 nav ul {
    display: flex;
    list-style: none;
 }

 nav ul li {
     margin:  0 10px;
 }

 nav ul li a {
    text-decoration: none;
    color: rgb(0, 136, 255);
    font-weight:bold ;
 }

 nav ul li a:hover {
    text-decoration: underline 2px;
    color: blue;
    
 }

 /* ANA KISIM */

.hero {
    text-align: center;
    padding: 25px;
    background-color: rgb(0, 136, 255);
}
.hero {
    border-radius: 100px;
}

/* BÖLÜM BAŞLIKLARI */
section {
    padding: 20px;
    max-width: 1000px;
    margin: auto;
}

nav ul li a:hover {
    transform: scale(1.2);
    transition: all 0.7s ease;
    box-shadow: 7px 5px 25px 7px  rgba(0, 0, 0, 0.66);
    padding: 7px;
}

/*PROJELER */

.projects .project-list {
    display: flex;
    gap: 20px;
}

.project-card {
    flex: 1;
    padding: 20px;
    background: #00d9ff;
    border-radius: 25px;
    box-shadow: 5px 3px 12px 10px rgb(0, 0, 0);
}

.project-card h3 {
    margin-bottom: 15px;
}

/* FOOTER */ 

footer {
    background: #00d9ff;
    color: rgb(0, 0, 0);
    text-align: center;
    padding: 15px 0;
    border-radius: 100px;
    max-width: 500px;
    margin: auto;
}

footer a {
    color: black ;
    text-decoration: none;
}

footer a:hover {
    text-decoration: underline;
    color: blue;
}
