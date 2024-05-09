<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Landing Page</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }

        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h1 {
            text-align: center;
            color: #333;
        }

        p {
            text-align: center;
            color: #666;
            line-height: 1.6;
        }

        .btn {
            display: block;
            width: 200px;
            margin: 20px auto;
            padding: 10px 20px;
            text-align: center;
            color: #fff;
            background-color: #007bff;
            border: none;
            border-radius: 5px;
            text-decoration: none;
            transition: background-color 0.3s;
        }

        .btn:hover {
            background-color: #0056b3;
        }

        .features {
            margin-top: 50px;
            display: none; /* Initially hidden */
            justify-content: space-around;
        }

        .feature {
            text-align: center;
            padding: 20px;
            border-radius: 8px;
            background-color: #f9f9f9;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .feature h2 {
            color: #007bff; /* Blue */
            font-family: 'Arial', sans-serif;
        }

        .feature p {
            color: #444; /* Dark Gray */
            font-family: 'Arial', sans-serif;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Welcome to Our Website</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed gravida felis ut ex molestie, ut varius enim varius. Aenean eget risus nec tortor consectetur.</p>
        <a href="#" class="btn" id="learnMoreBtn">Learn More</a>
    </div>

    <div class="features" id="featuresSection">
        <div class="feature">
            <h2>Feature 1</h2>
            <p>with 108 MP + 16 MP + 12 MP <br> + 8 MP Rear Camera.</p>
        </div>
        <div class="feature">
            <h2>Feature 2</h2>
            <p>MediaTek Dimensity 1300 MT6893Z <br> Processor.</p>
        </div>
        <div class="feature">
            <h2>Feature 3</h2>
            <p>5100 mAh Battery and 12 GB RAM.</p>
        </div>
    </div>

    <script>
        document.getElementById("learnMoreBtn").addEventListener("click", function(event) {
            event.preventDefault(); // Prevent default behavior of the link
            var featuresSection = document.getElementById("featuresSection");
            if (featuresSection.style.display === "none") {
                featuresSection.style.display = "flex"; // Show the features section
            } else {
                featuresSection.style.display = "none"; // Hide the features section
            }
        });
    </script>
</body>
</html>
# task
