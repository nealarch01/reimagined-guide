# electron-nodeinteg-sample
Electron utilizing Node processes. Sample for CS441 2022 Point-of-Sale System

Testing exec child process with echo redirection

Instructions on how to setup: https://www.electronjs.org/docs/latest/tutorial/quick-start


https://user-images.githubusercontent.com/73256760/197429379-2b78f083-c27c-4443-916b-e7202455510e.mov


```
                        renderer.js
                            |
app.js -> preload.js -> index.html
            | 
    require("node-proc.js")
```