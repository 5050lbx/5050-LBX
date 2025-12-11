<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Mark | 5050 LBX | Founder's Story</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700;800&family=Poppins:wght@300;400;500&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #0A5C36; /* 5050 Green */
            --secondary: #D4AF37; /* Crown Gold */
            --dark: #0F1C2D; /* Night Blue */
            --accent: #00E5FF; /* Highlight Cyan */
            --light: #F8F9FA;
            --gray: #6C757D;
            --transition: all 0.3s ease;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            line-height: 1.6;
            color: #333;
            overflow-x: hidden;
        }
        
        h1, h2, h3, h4, h5 {
            font-family: 'Montserrat', sans-serif;
            font-weight: 700;
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }
        
        /* Header & Navigation */
        header {
            position: fixed;
            top: 0;
            width: 100%;
            background-color: rgba(10, 92, 54, 0.95);
            z-index: 1000;
            padding: 15px 0;
            transition: var(--transition);
        }
        
        header.scrolled {
            padding: 10px 0;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            display:
