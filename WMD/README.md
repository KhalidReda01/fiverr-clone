# Building the Nav bar 

index.html



```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Fiverr Home page clone</title>
    <!-- Google fonts link for icons  -->
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@24,400,0,0&icon_names=language" />
</head>
<body>
    <header>
        <!-- building the navbar -->
        <nav class="navbar">
            <a href="" class="logo">
                <img src="images/logo.svg" alt="fiver Logo">
            </a>
            <!-- li*6>a -->
            <ul class="menu-links">
                <li><a href="">Fiver Business</a></li>
                <li><a href="">Explore</a></li>
                <li class="language-item"><a href=""><span class="material-symbols-outlined">
                    language
                    </span>English</a></li>
                <li><a href="">Become a seller</a></li>
                <li><a href="">sign In</a></li>
                <li class="join-btn"><a href="">join us</a></li>
                <li><a href=""></a></li>
            </ul>
        </nav>
    </header>
</body>
</html>
```

style.css

```css
@import url('https://fonts.googleapis.com/css2?family=Fira+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Fira+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

* {
   margin:0;
   padding:0;
   box-sizing: border-box;
  
}
body{
    background:#1b1b1d;
    font-family: 'Fira Sans',sans-serif;  
}
header {
    position:fixed;
    left:0;
    top:0;
    width:100%;
    padding :20px
}
header .navbar {
  max-width: 1400px;  
  margin:0 auto;
  display:flex;
  align-items:center;
  justify-content: space-between;
}
.navbar .menu-links {
    display: flex;
    align-items :center;
    list-style: none;
    gap:30px;
}

.navbar .menu-links a {
 color:#fff;   
 text-decoration: none;
}
.navbar .menu-links a:hover{
    color:#19a463;
   

}
.navbar .menu-links .language-item a {
    display: flex;
    gap:8px;
    align-items: center;

}
.navbar .menu-links .language-item span {
    font-size:1.3rem;
}
.navbar .menu-links .join-btn a{
border:1px solid #fff;
border-radius:4px ;
padding:8px 15px;
}
.navbar .menu-links .join-btn a:hover {
    color:#fff;
    background:#19a463  ;
    border-color: transparent;
}

body{
    background:#1b1b1d;
    font-family: 'Fira Sans',sans-serif;  
}

header {
    position:fixed;
    left:0;
    top:0;
    width:100%;
    padding :20px
}
header .navbar {
  max-width: 1400px;  
  margin:0 auto;
  display:flex;
  align-items:center;
  justify-content: space-between;
}
.navbar .menu-links {
    display: flex;
    align-items :center;
    list-style: none;
    gap:30px;
}

.navbar .menu-links a {
 color:#fff;   
 text-decoration: none;
}
.navbar .menu-links a:hover{
    color:#19a463;
   

}
.navbar .menu-links .language-item a {
    display: flex;
    gap:8px;
    align-items: center;

}
.navbar .menu-links .language-item span {
    font-size:1.3rem;
}
.navbar .menu-links .join-btn a{
border:1px solid #fff;
border-radius:4px ;
padding:8px 15px;
}
.navbar .menu-links .join-btn a:hover {
    color:#fff;
    background:#19a463  ;
    border-color: transparent;
}
```

