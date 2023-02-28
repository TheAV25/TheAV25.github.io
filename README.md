# TheAV25.github.io
<!DOCTYPE html>
<html>
  <head>
    <title>ChatGPT-like Website</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        background-color: #f0f0f0;
      }
      
      h1 {
        color: #333;
      }
      
      #chat-container {
        height: 400px;
        overflow-y: auto;
        border: 1px solid #ccc;
        padding: 10px;
      }
      
      #message-form {
        margin-top: 20px;
      }
      
      input[type="text"], textarea {
        width: 100%;
        padding: 10px;
        margin-bottom: 10px;
        border: 1px solid #ccc;
        border-radius: 5px;
        box-sizing: border-box;
      }
      
      button {
        background-color: #333;
        color: #fff;
        border: none;
        padding: 10px 20px;
        border-radius: 5px;
        cursor: pointer;
      }
    </style>
  </head>
  <body>
    <header>
      <h1>ChatGPT-like Website</h1>
    </header>
    
    <main>
      <div id="chat-container">
        <p><strong>ChatGPT:</strong> Welcome to ChatGPT-like website. How can I assist you today?</p>
      </div>
      
      <form id="message-form">
        <input type="text" name="name" placeholder="Your Name">
        <textarea name="message" placeholder="Type your message here..."></textarea>
        <button type="submit">Send</button>
      </form>
    </main>
    
    <footer>
      <p>&copy; 2023 ChatGPT-like Website</p>
    </footer>
  </body>
</html>
