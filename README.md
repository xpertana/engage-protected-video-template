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
