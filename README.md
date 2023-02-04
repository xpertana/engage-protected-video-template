# engage-protected-video-template

This is a basic template for a PIN protected site to share one of more videos.


## Fluent

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
<div style="border-radius:20px"> 
<img width="261" alt="engageapp" src="https://user-images.githubusercontent.com/6747230/216770036-0d51550a-e974-42fd-b942-8c7f8e94a14f.png">
</div>

