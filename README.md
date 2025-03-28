```
fetch("https://api.kotlinlang.org/api/2.1.20/compiler/run", {
  "headers": {
    "accept": "*/*",
    "accept-language": "en-US,en;q=0.9",
    "cache-control": "no-cache",
    "content-type": "application/json; charset=UTF-8",
    "pragma": "no-cache",
  },
  "referrer": "https://play.kotlinlang.org/",
  "referrerPolicy": "strict-origin-when-cross-origin",
  "body": "{\"args\":\"\",\"files\":[{\"name\":\"File.kt\",\"text\":\"/**\\n * You can edit, run, and share this code.\\n * play.kotlinlang.org\\n */\\nfun main() {\\n    println(\\\"Hello, world!!!\\\")\\n}\",\"publicId\":\"\"}],\"confType\":\"java\"}",
  "method": "POST"
}).then(a => a.json()).then(a => {debugger});
```
