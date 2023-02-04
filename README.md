# engage-protected-video-template

```javascript
[init]
app.id 66
app.user guest "guest" pincode 123456
set.icon !authorize !home.fa

[start | Acme Studio Video]
must.have guest else [login]

.video.youtube "23232244234"


[login | Enter Authorization Code]
!authorize9
enteredpin = ?pin "Enter Auth Code"
```

<img width="261" style="border-radius:20px" alt="image" src="https://user-images.githubusercontent.com/6747230/216770036-0d51550a-e974-42fd-b942-8c7f8e94a14f.png">

