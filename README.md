# rasachatbot


1. https://youtu.be/eJMT2FovZsM for integration and edit chatbot looks
2. https://github.com/JiteshGaikwad/Chatbot-Widget/blob/main/docs/gallery.md sources to add into chatbot ui
3. for the ```index.html``` , line 6 use either 1.0.0 or 1.0.1
4. trouble shooting video and forum :

- https://forum.rasa.com/t/rasa-webbot/41319/7?u=jiteshgaikwad

- https://www.youtube.com/watch?v=B1Z-lM7daAg&t=314s


Steps:

Run rasa in your virtual env

```code . ```

copy paste ```domain.yml``` ```nlu.yml``` ```stories.yml``` and save

```rasa train``` 

```rasa shell```

copy paste ```index.html``` , code source from : https://github.com/botfront/rasa-webchat

```rasa run -m models --enable-api --cors "*" --debug```

make sure socket url port number in terminal == coding at ```index.html```




