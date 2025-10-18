# digiqash-agencies.github.io
<!DOCTYPE html>
<html>
<head>
  <title>Digiqash Agencies</title>
  <style>
    /* Style the popup box */
    .popup {
      display: none;
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      background: white;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 0 25px rgba(0, 0, 0, 0.3);
      text-align: center;
      z-index: 1000;
      width: 300px;
      font-family: Arial, sans-serif;
      animation: fadeIn 0.6s;
    }

    /* Dark background behind popup */
    .overlay {
      display: none;
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.5);
      z-index: 999;
    }

    /* Button inside popup */
    .popup button {
      margin-top: 15px;
      padding: 10px 20px;
      background: #007bff;
      border: none;
      color: white;
      border-radius: 5px;
      cursor: pointer;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translate(-50%, -60%); }
      to { opacity: 1; transform: translate(-50%, -50%); }
    }
  </style>
</head>
<body>
  <h1 style="text-align:center;">Welcome to Digiqash Agencies</h1>

  <!-- Overlay and popup box -->
  <div class="overlay" id="overlay"></div>
  <div class="popup" id="popup">
    <h2>Welcome to Digiqash Agencies</h2>
    <p>We’re glad to have you here!</p>
    <button onclick="closePopup()">OK</button>
  </div>

  <script>
    // Show popup automatically after 1 second
    window.onload = function() {
      setTimeout(openPopup, 1000);
    }

    function openPopup() {
      document.getElementById("popup").style.display = "block";
      document.getElementById("overlay").style.display = "block";
    }

    function closePopup() {
      document.getElementById("popup").style.display = "none";
      document.getElementById("overlay").style.display = "none";
    }
  </script>
</body>
</html>
