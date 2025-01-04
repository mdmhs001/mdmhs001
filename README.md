<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Video & Chat App</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <div id="loginPage">
            <h2>Login with Gmail</h2>
            <button id="googleLoginButton">Login with Google</button>
        </div>

        <div id="chatPage" style="display:none;">
            <div id="videoContainer">
                <video id="localVideo" autoplay muted></video>
                <video id="remoteVideo" autoplay></video>
            </div>

            <div id="chatContainer">
                <div id="messageBox"></div>
                <input type="text" id="messageInput" placeholder="Type a message...">
                <button id="sendMessageButton">Send</button>
                <button id="unsendMessageButton">Unsend</button>
            </div>

            <button id="logoutButton">Logout</button>
        </div>
    </div>

    <script src="https://apis.google.com/js/platform.js" async defer></script>
    <script src="script.js"></script>
</body>
</html>

<!--
**mdmhs001/mdmhs001** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
