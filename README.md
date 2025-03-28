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
[JetBrains/kotlin-playground: Self-contained component to embed in websites for running Kotlin code](https://github.com/JetBrains/kotlin-playground)
[Kotlin Playground examples](https://jetbrains.github.io/kotlin-playground/examples/)
[wasm-languages/kotlin/browser-hello-world at main · vmware-archive/wasm-languages · GitHub](https://github.com/vmware-archive/wasm-languages/tree/main/kotlin/browser-hello-world)
[Running Kotlin in the browser with Wasm - JDriven Blog](https://jdriven.com/blog/2021/04/running-kotlin-in-the-browser-with-wasm)
[Kotlin/WASM compiler as library : r/Kotlin](https://www.reddit.com/r/Kotlin/comments/z5t5hx/kotlinwasm_compiler_as_library/?rdt=52057)
[Parser Generator written in Kotlin common - Kotlin Discussions](https://discuss.kotlinlang.org/t/parser-generator-written-in-kotlin-common/16913)
[Parsing Kotlin code using Kotlin - Jitin Sharma](https://jitinsharma.com/posts/parsing-kotlin-using-code-kotlin/)
[GitHub - h0tk3y/better-parse: A nice parser combinator library for Kotlin](https://github.com/h0tk3y/better-parse)
[GitHub - Kotlin/grammar-tools: Tokenization and parsing Kotlin code using the ANTLR Kotlin grammar](https://github.com/Kotlin/grammar-tools)
