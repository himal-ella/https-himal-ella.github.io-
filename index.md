---
layout: null
---
<!DOCTYPE html>
<html>
<head>
    <title>Ella Wood</title>
    <style>
        /* This kills the gap at the top and bottom */
        * { 
            margin: 0 !important; 
            padding: 0 !important; 
            box-sizing: border-box; 
        }

        html, body { 
            height: 100%; 
            width: 100%; 
            overflow: hidden; 
            background-color: #000; 
            font-family: 'Helvetica', sans-serif; 
        }

        .bg {
            background-image: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)), 
                              url('20240723_094701.jpg'); 
            height: 100vh; 
            width: 100vw;
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        h1 { 
            font-size: 3rem; 
            color: white;
            letter-spacing: 5px; 
            text-transform: uppercase; 
            border-top: 1px solid white; 
            border-bottom: 1px solid white; 
            padding: 20px 0; 
            margin-bottom: 10px !important; /* Forces spacing below title */
            width: 60%; 
        }

        p { 
            color: white;
            letter-spacing: 2px; 
            text-transform: uppercase; 
            font-size: 0.9rem; 
            margin-bottom: 40px !important; 
        }

        .nav-container { display: flex; border: 1px solid white; }
        
        .nav-item { 
            padding: 15px 30px; 
            text-decoration: none; 
            color: white; 
            border-right: 1px solid white;
            font-size: 0.8rem;
            letter-spacing: 2px;
            transition: 0.3s;
        }
        
        .nav-item:last-child { border-right: none; }
        .nav-item:hover { background: rgba(255,255,255,0.2); }
    </style>
</head>
<body>

<div class="bg">
    <h1>Ella Wood</h1>
    <p>PhD researcher | Remote Sensing | Python | Earth System Processes</p>

    <div class="nav-container">
        <a href="/about/" class="nav-item">ABOUT</a>
        <a href="/cv/" class="nav-item">CV</a>
        <a href="/contact/" class="nav-item">CONTACT</a>
    </div>
</div>

</body>
</html>

