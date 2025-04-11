<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>TweetLinker</title>
</head>
<body style="font-family: Arial, sans-serif; line-height: 1.6; max-width: 800px; margin: auto; padding: 2rem;">

  <h1>TweetLinker 🐦🔗</h1>
  <p><strong>TweetLinker</strong> is a lightweight Node.js Twitter bot that automatically posts website links to Twitter with built-in rate limiting. Ideal for simple automation or promotional tweeting.</p>
  <p>🔗 <strong>GitHub:</strong> <a href="https://github.com/Riotcoke123/TweetLinker">Riotcoke123/TweetLinker</a></p>

  <h2>🚀 Features</h2>
  <ul>
    <li>✅ Tweets out a custom message with a website link</li>
    <li>✅ Tracks tweet count in-memory</li>
    <li>✅ Enforces a daily limit of 50 tweets</li>
    <li>✅ Easy to configure with a <code>config.json</code> file</li>
  </ul>

  <h2>📦 Installation</h2>
  <pre><code>git clone https://github.com/Riotcoke123/TweetLinker.git
cd TweetLinker
npm install
  </code></pre>

  <h2>⚙️ Configuration</h2>
  <p>Create a <code>config.json</code> file in the root directory with your Twitter API credentials:</p>
  <pre><code>{
  "API_KEY": "your-api-key",
  "API_KEY_SECRET": "your-api-key-secret",
  "ACCESS_TOKEN": "your-access-token",
  "ACCESS_TOKEN_SECRET": "your-access-token-secret"
}
  </code></pre>

  <h2>🛠 Usage</h2>
  <pre><code>npm start</code></pre>
  <p>Inside <code>app.js</code>, change the message or link like this:</p>
  <pre><code>postTweet('Check out this awesome site: https://example.com');</code></pre>

  <h2>📄 License</h2>
  <p>This project is licensed under the <strong>GNU General Public License v3.0</strong> - see the LICENSE file for details.</p>

  <h2>👤 Author</h2>
  <p><strong>riotcoke</strong><br>
  🔗 GitHub: <a href="https://github.com/Riotcoke123">@Riotcoke123</a></p>

  <h2>☕ Contribute / Feedback</h2>
  <p>Pull requests and stars are welcome! Feel free to fork the project and submit improvements or ideas.</p>

</body>
</html>
