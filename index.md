---
layout: null
---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Ella Wood</title>
    <style>
        /* 1. Global background (the black area you see in your screenshot) */
        body, html { 
            margin: 0; 
            padding: 0; 
            height: 100%; 
            background-color: #000; 
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: 'Helvetica', Arial, sans-serif;
            overflow: hidden;
        }

        /* 2. The 'Placed' Image Frame */
        .framed-bg {
            width: 90vw;   /* Keeps it 5% away from left/right edges */
            height: 85vh;  /* Keeps it away from top/bottom edges */
            background-image: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)), 
                              url('./20240723_094701.jpg'); 
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            border: 1px solid #333; 
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        h1 { 
            color: white;
            font-size: 3rem; 
            letter-spacing: 6px; 
            text-transform: uppercase; 
            border-top: 1px solid white; 
            border-bottom: 1px solid white; 
            padding: 20px 0; 
            margin: 0 0 15px 0;
            width: 70%;
        }

        p { 
            color: white;
            letter-spacing: 2px; 
            text-transform: uppercase; 
            font-size: 0.9rem; 
            margin: 0 0 40px 0; 
        }

        /* 3. Navigation Buttons */
        .nav-container { display: flex; border: 1px solid white; }
        .nav-item { 
            padding: 15px 30px; 
            text-decoration: none; 
            color: white; 
            border-right: 1px solid white;
            font-size: 0.8rem;
            letter-spacing: 2px;
        }
        .nav-item:last-child { border-right: none; }
        .nav-item:hover { background: rgba(255,255,255,0.2); }
    </style>
</head>
<body>

<div class="framed-bg">
    <h1>Ella Wood</h1>
    <p>PhD researcher | Remote Sensing | Python | Earth System Processes</p>

    <div class="nav-container">
        <a href="./about/" class="nav-item">ABOUT</a>
        <a href="./cv/" class="nav-item">CV</a>
        <a href="./contact/" class="nav-item">CONTACT</a>
    </div>
</div>

</body>
</html>
