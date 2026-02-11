---
layout: null
---
<!DOCTYPE html>
<html>
<head>
    <style>
        /* This kills all possible margins from the browser or Jekyll */
        html, body {
            margin: 0 !important;
            padding: 0 !important;
            height: 100% !important;
            width: 100% !important;
            overflow: hidden !important;
            background-color: #000;
        }

        .background-container {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            /* The image will now fill the screen regardless of its dimensions */
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), 
                        url('20240723_094701.jpg') no-repeat center center fixed;
            background-size: cover !important;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            z-index: -1;
        }

        .content {
            text-align: center;
            color: white;
            font-family: 'Helvetica', sans-serif;
            z-index: 1;
        }

        h1 { 
            font-size: 3.5rem; 
            letter-spacing: 8px; 
            text-transform: uppercase; 
            border-top: 1px solid white; 
            border-bottom: 1px solid white; 
            padding: 20px 0; 
            margin: 0 auto 10px auto;
            width: fit-content;
            min-width: 300px;
        }

        p { 
            letter-spacing: 2px; 
            text-transform: uppercase; 
            font-size: 0.9rem; 
            margin: 20px 0 40px 0; 
        }

        .nav-container { display: flex; border: 1px solid white; background: rgba(0,0,0,0.3); }
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

<div class="background-container"></div>

<div class="content">
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
