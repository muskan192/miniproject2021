# miniproject2021
college mini project (fooodie-bot)
here is the code snippet for lanbot 
for full page bot:
<html>
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, height=device-height, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Landbot | Convert a Landing Page into a Chatbot</title>
  </head>
  <body>
    <script SameSite="None; Secure" src="https://static.landbot.io/landbot-3/landbot-3.0.0.js"></script>
    <script>
      var myLandbot = new Landbot.Fullpage({
        configUrl: 'https://chats.landbot.io/v3/H-865649-PUBKJTXCTWUK2F4C/index.json',
      });
    </script>
  </body>
</html>

for embedded bot::

<script SameSite="None; Secure" src="https://static.landbot.io/landbot-3/landbot-3.0.0.js"></script>
<div id="myLandbot" style="width: 100%; height: 1000px"></div>
<script>
  var myLandbot = new Landbot.Container({
    container: '#myLandbot',
    configUrl: 'https://chats.landbot.io/v3/H-865649-PUBKJTXCTWUK2F4C/index.json',
  });
</script>

here is the link for bot::
for embedded one:
https://chats.landbot.io/v3/H-865649-PUBKJTXCTWUK2F4C/index.html

for full page bot::
https://chats.landbot.io/v3/H-865649-PUBKJTXCTWUK2F4C/index.html

for understanding the flow of bot refer the picture attached below::
![Product Recommendation_2021-05-04-19_15](https://user-images.githubusercontent.com/53381921/117013305-5eb48100-ad0d-11eb-8328-b34fb66c937f.png)
