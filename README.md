<!DOCTYPE html>
<html>
<head>
  <title>Contact Us - Professional Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f7f8;
      margin: 0;
      padding: 0;
    }
    .container {
      background: #fff;
      max-width: 400px;
      margin: 50px auto;
      padding: 30px 40px 25px 40px;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    h2 {
      text-align: center;
      color: #333;
      margin-bottom: 25px;
    }
    label {
      display: block;
      margin-bottom: 6px;
      color: #555;
      font-weight: bold;
    }
    input[type="text"],
    input[type="email"],
    textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 18px;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 15px;
      box-sizing: border-box;
      transition: border-color 0.2s;
    }
    input[type="text"]:focus,
    input[type="email"]:focus,
    textarea:focus {
      border-color: #007BFF;
      outline: none;
    }
    textarea {
      min-height: 80px;
      resize: vertical;
    }
    input[type="submit"] {
      background: #007BFF;
      color: #fff;
      border: none;
      padding: 12px 0;
      width: 100%;
      border-radius: 4px;
      font-size: 16px;
      font-weight: bold;
      cursor: pointer;
      transition: background 0.2s;
    }
    input[type="submit"]:hover {
      background: #0056b3;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>Contact Us</h2>
    <form>
      <label for="name">Name</label>
      <input type="text" id="name" name="name" placeholder="Your full name" required>

      <label for="email">Email</label>
      <input type="email" id="email" name="email" placeholder="you@example.com" required>

      <label for="message">Message</label>
      <textarea id="message" name="message" placeholder="Type your message here..." required></textarea>

      <input type="submit" value="Send Message">
    </form>
  </div>
</body>
</html>
