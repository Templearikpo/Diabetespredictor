<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diabetes Predictor</title>
    <style>
        /* Global Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background: linear-gradient(to right, #f7f7f7, #e6e6e6);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 170vh;
            padding: 30px;
        }

        .container {
            width: 110%;
            max-width: 2000px;
            background: white;
            border-radius: 12px;
            box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.15);
            padding: 30px;
            text-align: center;
            transition: all 0.3s ease-in-out;
        }

        .container:hover {
            box-shadow: 0px 8px 25px rgba(0, 0, 0, 0.2);
        }

        .logo {
            font-size: 30px;
            font-weight: unbold;
            color: #c06c6c;
            display: flex;
            align-items: left;
            justify-content: left;
            gap: 10px;
            margin-bottom: 10px;
            margin-top: 10px;
        }

        .logo img {
            width: 50px;
            height: 35px;
        }

        h1 {
            font-size: 50px;
            margin: 10px 0;
            color: #333;
        }

        p {
            font-size: 16px;
            color: #555;
            margin-bottom: 20px;
            line-height: 1.6;
        }

        .image-container {
            margin: 20px 0;
        }

        .image-container img {
            width: 80%;
            border-radius: 10px;
            transition: transform 0.3s ease-in-out;
        }

        .image-container img:hover {
            transform: scale(1.05);
        }

        .btn {
            display: inline-block;
            background: linear-gradient(135deg, #c06c6c, #a85a5a);
            color: white;
            padding: 12px 24px;
            border-radius: 8px;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
            border: none;
            transition: background 0.3s ease-in-out, transform 0.2s ease-in-out;
            margin-top: 15px;
        }

        .btn:hover {
            background: linear-gradient(135deg, #a85a5a, #8c4646);
            transform: translateY(-3px);
        }

        .footer {
            font-size: 14px;
            color: #777;
            margin-top: 20px;
            padding: 15px 0;
            width: 100%;
            background: #333;
            color: white;
            text-align: center;
            border-radius: 8px;
        }

        .footer a {
            color: #ff9494;
            text-decoration: none;
            font-weight: bold;
        }

        .footer a:hover {
            text-decoration: underline;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .container {
                width: 95%;
                padding: 20px;
            }

            h2 {
                font-size: 22px;
            }

            p {
                font-size: 14px;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="logo">
            <img src="HealthPictures/Image 3.jpg" alt="Heart Icon">
            <span>DiabetesPredictor</span>
        </div>

        <h1>Welcome to DiabetesPredictor</h1>

        <p>Discover a proactive approach to managing your health with our state-of-the-art diabetes risk prediction system. Gain insights and take control of your well-being today.</p>

        <div class="image-container">
            <img src="HealthPictures/Diabetes1.jpeg" alt="Health Illustration">
        </div>

        <button class="btn" onclick="location.href='https://diabetes-prediction-app-43wbv7kqqdppvxfskjkuya.streamlit.app/'">
            Get Started
        </button>
    </div>

    <div class="footer">
        © 2025 <strong>Predictive Wellness Partners(PWP)</strong>. All rights reserved. | 
        Contact us: <a href="mailto:arikpotemple@gmail.com">arikpotemple@gmail.com</a>
    </div>

</body>
</html>
