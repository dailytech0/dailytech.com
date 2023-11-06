# dailytech.com
"El proyecto " CHAT PERSONAL " 
Usa tres tecnologías principales para funcionar: HTML, CSS y JavaScript. Es una herramienta útil y divertida para aprender y compartir conocimientos relacionados con programación. 
Ofrece un ambiente seguro y amigable donde los usuarios pueden interactuar y construir una comunidad de aprendizaje entre ellos. 

- COPIA Y PEGA EL CODIGO EN VISUAL CODE STUDY (VS)
- DEJAME TU COMENTARIO
- SIGUEME PARA MÀS

#HTML

* @DailyTech.com */

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
  <title> CHAT APP </title>
</head>

<body>
  <header>
    <h1><center> CHAT APP </center></h1>
  </header>
  <div class="container">
    <div class="chat-window">
      <div class="chat-area">
        <div class="chat-messages">
          <!-- Chat Messages -->
        </div>
      </div>
      <div class="user-input">
        <input type="text" id="message-input" placeholder=" Escriba su mensaje...">
        <button id="send-button"> ENVIAR </button>
      </div>
    </div>
  </div>

  <script src="script.js"></script>
</body>

</html>

#CSS

/* @DailyTech.com */

/* Global Styles */
body {
    margin: 0;
    padding: 0;
    font-family: Agency FB, sans-serif;
  }
  
  header {
    background-color: #00eeff;
    color: #fff;
    padding: 20px;
  }
  
  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }
  
  /* Chat Window Styles */
  .chat-window {
    width: 500px;
    background-color: #f0f0f0;
    border-radius: 8px;
    overflow: hidden;
  }
  
  .chat-area {
    height: 400px;
    overflow-y: scroll;
    padding: 20px;
  }
  
  .chat-messages {
    display: flex;
    flex-direction: column;
  }
  
  .message {
    margin-bottom: 10px;
    background-color: #fff;
    padding: 10px;
    border-radius: 4px;
  }
  
  .user-input {
    display: flex;
    align-items: center;
    padding: 20px;
    background-color: #fff;
  }
  
  #message-input {
    flex-grow: 1;
    padding: 8px;
    border: 1px solid #ccc;
    border-radius: 4px;
  }
  
  #send-button {
    padding: 8px 16px;
    margin-left: 10px;
    background-color: #007bff;
    border: none;
    border-radius: 4px;
    color: #fff;
    cursor: pointer;
  }
  
  #send-button:hover {
    background-color: #0056b3;
  }

  #JAVASCRIPT

  /* @DailyTech.com */

/* Global Styles */
body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
  }
  
  header {
    background-color: #007bff;
    color: #fff;
    padding: 20px;
  }
  
  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }
  
  /* Chat Window Styles */
  .chat-window {
    width: 500px;
    background-color: #f0f0f0;
    border-radius: 8px;
    overflow: hidden;
  }
  
  .chat-area {
    height: 400px;
    overflow-y: scroll;
    padding: 20px;
  }
  
  .chat-messages {
    display: flex;
    flex-direction: column;
  }
  
  .message {
    margin-bottom: 10px;
    background-color: #fff;
    padding: 10px;
    border-radius: 4px;
  }
  
  .user-input {
    display: flex;
    align-items: center;
    padding: 20px;
    background-color: #fff;
  }
  
  #message-input {
    flex-grow: 1;
    padding: 8px;
    border: 1px solid #ccc;
    border-radius: 4px;
  }
  
  #send-button {
    padding: 8px 16px;
    margin-left: 10px;
    background-color: #007bff;
    border: none;
    border-radius: 4px;
    color: #fff;
    cursor: pointer;
  }
  
  #send-button:hover {
    background-color: #0056b3;
  }
