---
layout: null
---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ella Wood</title>
    <style>
        /* 1. Reset defaults to eliminate the top/side gaps */
        body, html { 
            height: 100%; 
            margin: 0; 
            padding: 0; 
            overflow: hidden; /* Prevents scrolling on the splash page */
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; 
            color: white; 
            background-color: #000; 
        }

        /* 2. The Full-Screen Background */
        .bg {
            /* Adjusted opacity to 0.5 for a stronger dark mode feel */
            background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), 
                              url('20240723_094701.jpg'); 
            height: 100vh; /* Takes up 100% of the viewport height */
            width: 100%;
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        /* 3. Typography & Branding */
        h1 { 
            margin: 0; /* Critical: removes default browser spacing at the top */
            font-size: 3.5rem; 
            letter-spacing: 8px; 
            text-transform: uppercase; 
            border-top: 1px solid rgba(255,255,255,0.8); 
            border-bottom: 1px solid rgba(255,255,255,0.8); 
            padding: 25px 0; 
            width: 70%; 
            font-weight: 300;
        }

        p { 
            margin: 30px 0 50px 0; 
            letter-spacing: 3px; 
            text-transform: uppercase; 
            font-size: 0.85rem; 
            opacity: 0.9;
        }

        /* 4. The Navigation Buttons */
        .nav-container { 
            display: flex; 
            border: 1px solid white; 
            background: rgba(0, 0, 0, 0.2); 
            backdrop-filter: blur(5px); /* Optional: adds a modern frosted glass effect */
        }

        .nav-item { 
            padding: 18px 35px; 
            text-decoration: none; 
            color: white; 
            border-right: 1px solid white;
            font-size: 0.75rem;
            letter-spacing: 3px;
            transition: all 0.3s ease;
        }

        .nav-item:last-child { 
            border-right: none; 
        }

        .nav-item:hover { 
            background: rgba(255, 255, 255, 0.15); 
            letter-spacing: 4px; /* Subtle expansion effect on hover */
        }

        /* 5. Basic Mobile Scaling */
        @media (max-width: 768px) {
            h1 { font-size: 2rem; width: 90%; }
            .nav-container { flex-direction: column; width: 200px; }
            .nav-item { border-right: none; border-bottom: 1px solid white; }
            .nav-item:last-child { border-bottom: none; }
        }
    </style>
</head>
<body>

<div class="bg">
    <h1>Ella Wood</h1>
    <p>PhD researcher | Remote Sensing | Python | Earth System Processes</p>

    <nav class="nav-container">
        <a href="/about/" class="nav-item">ABOUT</a>
        <a href="/cv/" class="nav-item">CV</a>
        <a href="/contact/" class="nav-item">CONTACT</a>
    </nav>
</div>

</body>
</html>
