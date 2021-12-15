# Webshell in Flask

![](/showtime.png)




like what you can see.


#tips

for use in tencent cloud serverless:

1.clone this repo and open it in your path.
2.for example /root/flask_webshell
```
cd /root/flask_webshell
pip3 install flask flask_socketio -t ./
```
3.create flask application on tencent cloud serverless,

make sure you got env variable ```LC_ALL = en_US.utf8```

choose upload folder,and choose the /root/flask_webshell to upload.

![](/1.png)

![](/2.png)

**after the deploy finished,you should able to use it.**