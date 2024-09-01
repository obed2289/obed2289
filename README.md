<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mr. Omariba Company - Sign Up / Log In</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="container" id="signupContainer">
    <h1>Sign Up</h1>
    <form id="signupForm">
        <input type="text" id="signupPhone" placeholder="Phone Number" required>
        <input type="password" id="signupPassword" placeholder="Password" required>
        <input type="password" id="signupConfirmPassword" placeholder="Confirm Password" required>
        <button type="submit">Sign Up</button>
    </form>
    <div class="message" id="signupMessage"></div>
</div>



<div class="container" id="loginContainer">
    <h1>Log In</h1>
    <form id="loginForm">
        <input type="text" id="loginPhone" placeholder="Phone Number" required>
        <input type="password" id="loginPassword" placeholder="Password" required>
        <button type="submit">Log In</button>
    </form>
    <div class="message" id="loginMessage"></div>
</div>



<div class="container" id="dashboard" style="display:none;">
    <h1>Dashboard</h1>
    <div id="userInfo">
        <h2>My Info</h2>
        <p id="userPhoneDisplay"></p>
    </div>
    <div id="careerPaths">
        <h2>My Career Paths</h2>
        <p>Explore career opportunities and guidance here.</p>
    </div>
    <div id="investmentPlans">
        <h2>Investment Plans</h2>
        <p>Invest and grow your money with 1% interest per day.</p>
        <input type="number" id="investmentAmount" placeholder="Enter amount to invest">
        <button onclick="invest()">Invest</button>
        <h3>Current Investment: Ksh <span id="investmentTotal">0</span></h3>
    </div>
</div>

<script src="script.js"></script>
</body>
</html>
- 👋 Hi, I’m @obed2289
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
obed2289/obed2289 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
