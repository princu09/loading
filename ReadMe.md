## Loading... CSS Layout Free Source Code By NorthFox Developers

##### 📫 Connect with me here:<br />
 <br />
 <p>
  <a target="_blank" href="https://www.instagram.com/princu.09">
    <img src="https://img.shields.io/badge/princu.09-386938188?style=flat&logo=instagram&color=black">
  </a> &nbsp; 
  <a target="_blank" href="https://twitter.com/princu09">
    <img src="https://img.shields.io/badge/@princu09-30302f?style=flat&logo=twitter&color=black">
  </a>&nbsp; 
  <a target="_blank" href="https://github.com/princu09">
    <img src="https://img.shields.io/badge/@princu09-30302f?style=flat&logo=github&color=black">
  </a>&nbsp;
    <a target="_blank" href="https://www.t.me/proghub09">
    <img src="https://img.shields.io/badge/ProgHub09-386938188?style=flat&logo=telegram&color=black">
  </a>
</p>

![Video Here](Loading.gif)

#### HTML File

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loading...</title>
    <link rel="shortcut icon" href="https://princu09.github.io/nfwebbuilder/img/logo.png" type="image/png">
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="container">
        <h2>
            <span>L</span>
            <span>O</span>
            <span>A</span>
            <span>D</span>
            <span>I</span>
            <span>N</span>
            <span>G</span>
            <span>.</span>
            <span>.</span>
            <span>.</span>
        </h2>
    </div>
</body>

</html>
```

#### CSS File

```
@import url('https://fonts.googleapis.com/css2?family=Recursive:wght@500&display=swap');
* {
    margin: 0;
    padding: 0;
    font-family: 'Recursive', sans-serif;
    box-sizing: border-box;
}

body {
    height: 100vh;
    width: 100vw;
    background: #000;
}

.container {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}

h2 {
    color: #000;
    font-size: 6em;
}

h2 span {
    margin-right: 50px;
    animation: animate 7s linear infinite;
}

h2 span:nth-child(1) {
    animation-delay: 0.5s;
}

h2 span:nth-child(2) {
    animation-delay: 1s;
}

h2 span:nth-child(3) {
    animation-delay: 1.5s;
}

h2 span:nth-child(4) {
    animation-delay: 2s;
}

h2 span:nth-child(5) {
    animation-delay: 2.5s;
}

h2 span:nth-child(6) {
    animation-delay: 3s;
}

h2 span:nth-child(7) {
    animation-delay: 3.5s;
}

h2 span:nth-child(8) {
    animation-delay: 4s;
}

h2 span:nth-child(9) {
    animation-delay: 4.5s;
}

h2 span:nth-child(10) {
    animation-delay: 5s;
}

@keyframes animate {
    0%,
    100% {
        color: #fff;
        filter: blur(1px);
        text-shadow: 0 0 10px #00b3ff, 0 0 15px #00b3ff, 0 0 20px #00b3ff;
    }
    25%,
    75% {
        color: #000;
        filter: blur(0px);
        text-shadow: none;
    }
}

@media screen and (max-width:1369px) {
    h2 {
        font-size: 4em;
    }
}

@media screen and (max-width:1020px) {
    h2 {
        font-size: 3em;
    }
    h2 span {
        margin-right: 30px;
    }
}

@media screen and (max-width:786px) {
    h2 {
        font-size: 2em;
    }
    h2 span {
        margin-right: 20px;
    }
}

@media screen and (max-width:486px) {
    h2 {
        font-size: 1.5em;
    }
    h2 span {
        margin-right: 15px;
    }
}

@media screen and (max-width:299px) {
    h2 {
        font-size: 1em;
    }
    h2 span {
        margin-right: 10px;
    }
}
```
