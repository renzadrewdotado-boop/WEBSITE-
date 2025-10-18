<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Interactive Website</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>My Basic Website</h1>
  </header>

  <main>
    <h2>Welcome!</h2>
    <p>Click the button below to change the background color:</p>
    <button onclick="changeBackground()">Change Background</button>

    <div class="form-container" id="loginForm">
      <h3>Login</h3>
      <input type="text" id="loginUsername" placeholder="Username" required>
      <input type="password" id="loginPassword" placeholder="Password" required>
      <button onclick="handleLogin()">Login</button>
      <p class="toggle-link" onclick="showSignUp()">Don't have an account? Sign Up</p>
    </div>

    <div class="form-container" id="signupForm" style="display:none;">
      <h3>Sign Up</h3>
      <input type="text" id="signupUsername" placeholder="Username" required>
      <input type="email" id="signupEmail" placeholder="Email" required>
      <input type="password" id="signupPassword" placeholder="Password" required>
      <button onclick="handleSignUp()">Sign Up</button>
      <p class="toggle-link" onclick="showLogin()">Already have an account? Login</p>
    </div>
  </main>

  <footer>
    &copy; 2025 My Website
  </footer>

  <script src="script.js"></script>
</body>
</html>
