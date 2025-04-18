# WebTech

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
    <style>
        .flex-container {
            background-color: rgb(79, 255, 30);
            margin: 100px;
            padding: 0px;
            display: flex;
            flex-direction: column; /* Stack items vertically */
            align-items: flex-start; /* Align both boxes to the left */
        }
        .yellow-box {
            background-color: rgb(255, 191, 0);
            height: 600px;
            width: 350px;
            padding: 20px;
            box-sizing: border-box;
            margin-bottom: 20px; /* Adds space between the yellow box and blue box */
        }
        .blue-box {
            background-color: rgb(4, 0, 255);
            height: 250px;
            width: 350px;
        }
    </style>
</head>
<body>
    <div class="flex-container">
        <!-- Yellow Box with Registration Form -->
        <div class="yellow-box">
            <form action="#" method="POST">
                <h2>Registration Form</h2>

                <!-- Full Name -->
                <label for="fullname">Full Name:</label>
                <input type="text" id="fullname" name="fullname" required placeholder="Enter full name" /><br><br>

                <!-- Email -->
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required placeholder="Enter email" /><br><br>

                <!-- Password -->
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required placeholder="Enter password" /><br><br>

                <!-- Confirm Password -->
                <label for="confirmpassword">Confirm Password:</label>
                <input type="password" id="confirmpassword" name="confirmpassword" required placeholder="Confirm password" /><br><br>

                <!-- Date of Birth -->
                <label for="dob">Date of Birth:</label>
                <input type="date" id="dob" name="dob" required /><br><br>

                <!-- User Country -->
                <label for="country">Country:</label>
                <select id="country" name="country" required>
                    <option value="">Select your country</option>
                    <option value="USA">USA</option>
                    <option value="Canada">Canada</option>
                    <option value="UK">UK</option>
                    <option value="India">India</option>
                    <option value="Australia">Australia</option>
                </select><br><br>

                <!-- Color Select -->
                <label for="color">Favorite Color:</label>
                <input type="color" id="color" name="color" /><br><br>

                <!-- Gender -->
                <label for="gender">Gender:</label><br>
                <input type="radio" id="male" name="gender" value="Male">
                <label for="male">Male</label><br>
                <input type="radio" id="female" name="gender" value="Female">
                <label for="female">Female</label><br>
                <input type="radio" id="other" name="gender" value="Other">
                <label for="other">Other</label><br><br>

                <!-- Terms and Conditions -->
                <input type="checkbox" id="terms" name="terms" required>
                <label for="terms">I agree to the <a href="https://example.com/terms" target="_blank">Terms and Conditions</a></label><br><br>

                <!-- Submit Button -->
                <input type="submit" value="Submit" />
            </form>
        </div>

        <!-- Blue Box (Empty) -->
        <div class="blue-box">
        </div>
    </div>
</body>
</html>

