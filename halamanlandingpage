<!DOCTYPE html>
<html>
<head>
  <title>Halaman Landing Page Hotspot Putra Prawira Yohanes Puka</title>
  <style>
    /* CSS styling untuk halaman */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(45deg, #FFC107, #3F51B5, #E91E63, #4CAF50);
      background-size: 600% 600%;
      animation: gradientAnimation 15s ease infinite;
    }

    @keyframes gradientAnimation {
      0% {
        background-position: 0% 50%;
      }
      50% {
        background-position: 100% 50%;
      }
      100% {
        background-position: 0% 50%;
      }
    }

    .container {
      width: 800px;
      margin: 0 auto;
      padding: 20px;
      text-align: center;
    }

    h1 {
      color: #fff;
    }

    p {
      color: #fff;
    }

    .cta-button {
      display: inline-block;
      padding: 10px 20px;
      background-color: #f2f2f2;
      color: #333;
      text-decoration: none;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }

    .cta-button:hover {
      background-color: #e2e2e2;
    }

    .form-container {
      margin-top: 20px;
      text-align: center;
    }

    .form-container label {
      display: block;
      width: 100px;
      font-weight: bold;
      text-align: left;
      margin: 10px auto;
      color: #fff;
    }

    .form-container input {
      margin-bottom: 10px;
      padding: 5px;
      width: 200px;
    }

    .form-container input[type="submit"] {
      padding: 10px 20px;
      background-color: #f2f2f2;
      color: #333;
      text-decoration: none;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }

    .form-container input[type="submit"]:hover {
      background-color: #e2e2e2;
    }

    .error-message {
      color: red;
      margin-top: 10px;
      text-align: center;
    }
    
    .register-link {
      color: #FFC107;
    }

    .credentials-table {
      margin: 20px auto;
      background-color: #444;
      color: #fff;
      border-radius: 5px;
      padding: 10px;
    }

    .credentials-table td {
      padding: 5px 10px;
    }

    .credentials-table th {
      text-align: left;
      padding: 5px 10px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Selamat Datang di Halaman Landing Page Hotspot Putra Prawira Yohanes Puka</h1>
    <p>Ini adalah contoh halaman landing page sederhana.</p>

    <table class="credentials-table">
      <tr>
        <th>Username:</th>
        <td>putra</td>
      </tr>
      <tr>
        <th>Password:</th>
        <td>1</td>
      </tr>
    </table>

    <div class="form-container">
      <?php
      // Cek apakah form login sudah disubmit
      if ($_SERVER['REQUEST_METHOD'] === 'POST') {
        // Cek username dan password
        $username = $_POST['username'];
        $password = $_POST['password'];

        if ($username === 'putra' && $password === '1') {
          // Redirect ke halamanlogin.php
          header('Location: halamanlogin.php');
          exit;
        } else {
          // Tampilkan pesan kesalahan
          echo '<p class="error-message">Username atau password yang Anda masukkan salah.</p>';
        }
      }
      ?>

      <form action="#" method="POST">
        <label for="username">Username:</label>
        <input type="text" name="username" id="username" required><br>

        <label for="password">Password:</label>
        <input type="password" name="password" id="password" required><br>

        <input type="submit" value="Login">
      </form>
    </div>

    <p>Jika belum memiliki akun, silakan <a href="#" class="register-link">daftar</a> terlebih dahulu.</p>
  </div>
</body>
</html>
