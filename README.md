# KEFFED Cyber Security Solution
Check any URL for scam/phishing

Features: Signup, Login, URL Scanner

Deploy: Upload to GitHub, then connect to Vercel.app

Future upgrade: Add VirusTotal API key in scanner.js for real-time threat intel.
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KEFFED Cyber Security Solution - Login</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<div class="container">
  <div class="logo">
    <h1>🛡️ KEFFED</h1>
    <p>Cyber Security Solution</p>
  </div>
  <div class="form-box">
    <h2>Login</h2>
    <input type="email" id="loginEmail" placeholder="Email Address">
    <input type="password" id="loginPassword" placeholder="Password">
    <button onclick="login()">Login</button>
    <p>Don't have an account? <a href="signup.html">Sign Up</a></p>
    <p id="message"></p>
  </div>
</div>
<script src="auth.js"></script>
</body>
</html>
