<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Always an Answer</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      text-align: center;
      padding: 40px;
      margin: 0;
    }

    h1 {
      font-size: 3em;
      color: #333;
      margin-bottom: 20px;
    }

    .description {
      font-size: 1.3em;
      margin-bottom: 40px;
      color: #333;
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
    }

    form {
      margin-bottom: 30px;
    }

    input[type="text"],
    input[type="email"] {
      width: 60%;
      padding: 10px;
      font-size: 1em;
      margin-bottom: 10px;
      display: block;
      margin-left: auto;
      margin-right: auto;
    }

    button {
      padding: 10px 15px;
      font-size: 1em;
      cursor: pointer;
      background-color: #007BFF;
      color: white;
      border: none;
      margin-left: 5px;
      transition: background-color 0.3s ease;
      display: inline-block;
    }

    button:hover {
      background-color: #0056b3;
    }

    .donate {
      margin-top: 50px;
    }

    .donate a {
      display: inline-block;
      text-decoration: none;
      color: white;
      background: #28a745;
      padding: 10px 20px;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }

    .donate a:hover {
      background: #218838;
    }
  </style>
</head>
<body>
  <h1>Always an Answer</h1>

  <p class="description">
    The purpose of the site is to give answers about Christianity, The Bible, and Jesus. So far, there are two people running this site, God bless!
  </p>

  <form action="https://formspree.io/f/myzjlyqg" method="POST">
    <input type="text" name="question" placeholder="Type your question here..." required />
    <input type="email" name="email" placeholder="Your email" required />

    <!-- Optional: redirect after submission -->
    <input type="hidden" name="_redirect" value="https://example.com/thank-you.html" />

    <!-- Optional: email subject -->
    <input type="hidden" name="_subject" value="New Question from Website" />

    <button type="submit">Send</button>
  </form>

  <div class="donate">
    <p>If you'd like to support us, you can donate via Cash App:</p>
    <a href="https://cash.app/$JMacias100" target="_blank" rel="noopener noreferrer">Donate on Cash App</a>
  </div>
</body>
</html>
