# NeokulApp
Login system to allow users to securely access learning resources.
git clone https://github.com/MembathisiM/auth-demo.git
cd auth-demo
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>User Authentication Demo</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>Welcome to the Firebase Authentication Demo</h1>
  
  <div id="user-container">
    <button id="login-btn">Login with Google</button>
    <button id="logout-btn" style="display:none;">Logout</button>
  </div>
  
  <div id="welcome-msg" style="display:none;">
    <h2>Welcome, <span id="user-name"></span>!</h2>
  </div>
  
  <script src="script.js"></script>
</body>
</html>
