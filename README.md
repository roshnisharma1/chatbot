Description: This program creates a functioning chatbot by using PircBot, the most popular Java IRC API. It makes REST calls by parsing JSON script in Java via the GSON library. It also uses the Java.NET library to create a chat server through which you can interact with the bot.

IDE used: Eclipse

Before you run this program, you must:
  - Download PircBot 1.5.0 from http://www.jibble.org/pircbot.php
  - Download Gson 2.6.2 from https://search.maven.org/artifact/com.google.code.gson/gson/2.6.2/jar
  - Add both these external archives (.jar files) to project's build path
  - Obtain an access token to send web requests to Twitter. Information & instructions on how to do this at https://developer.twitter.com/en/docs/basics/authentication/guides/access-tokens.html
  - Sign up for OpenWeatherMap to obtain API key to make REST calls at https://home.openweathermap.org/users/sign_up
  - More information about how to use OpenWeatherMap API at https://openweathermap.org/appid#get

IRC used: PircBot 1.5.0

Chat server used: FreeNode

Libraries used: java.io.BufferedReader, java.io.InputStreamReader, java.io.HttpURLConnection, java.net.URL, java.text.DecimalFormat, 

External libraries used: org.jibble.pircbot.*, com.google.gson.JsonArray, com.google.gson.JsonElement, com.google.gson.JsonObject, com.google.gson.JsonParser

Files included: my-bot, my-bot-main

