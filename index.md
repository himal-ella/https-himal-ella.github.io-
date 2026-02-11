---
layout: null
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Ella Wood</title>
    <style>
        /* 1. Reset and Center */
        * { margin: 0; padding: 0; box-sizing: border-box; }
        
        body, html { 
            height: 100%; 
            background-color: #111; /* Dark outer background */
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: 'Helvetica', Arial, sans-serif;
            overflow: hidden;
        }

        /* 2. The Placed/Framed Background Container */
        .framed-bg {
            width: 92vw;  /* Slightly less than full width */
            height: 90vh; /* Slightly less than full height */
            background-image: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)), 
                              url('./20240723_094701.jpg'); 
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            border: 1px solid #333; /* Subtle frame border */
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
        }

        /* 3. Text Styling */
        h1 { 
            color: white;
            font-size: 3rem; 
            letter-spacing: 6px; 
            text-transform: uppercase; 
            border-top: 1px solid white; 
            border-bottom: 1px solid white; 
            padding: 20px 0; 
            margin-bottom: 15px; 
            font-weight: 300;
            width: 60%;
        }

        p { 
            color: white;
            letter-spacing: 2px; 
            text-transform: uppercase; 
            font-size: 0.9rem; 
            margin-bottom: 40px; 
            opacity: 0.9;
        }

        /* 4. Navigation Buttons */
        .nav-container { 
            display: flex; 
            border: 1px solid white; 
            background: rgba(0, 0, 0, 0.2);
        }
        
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

        /* Mobile Adjustments */
        @media (max-width: 768px) {
            h1 { font-size: 2rem; width: 85%; }
            .framed-bg { width: 95vw; height: 95vh; }
            .nav-container { flex-direction: column; }
            .nav-item { border-right: none; border-bottom: 1px solid white; }
        }
    </style>
</head>
<body>

<div class="framed-bg">
    <h1>Ella Wood</h1>
    <p>PhD researcher | Remote Sensing | Python | Earth System Processes</p>

    <div class="nav-container">
        <a href="./about/" class="nav-item">ABOUT</a>
        <a
