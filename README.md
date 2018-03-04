# curldiff
Not sure why a network request seems to be working, while another seemingly similar request stubbornly refuses to? 

`curldiff` them!

`curldiff` is an interactive utility to compare two curl requests, and tell you what exactly you're screwing up.

It can be used either on the web or as a command line utility (experimental).

## Web
https://pastelsky.github.io/curldiff

<img width="600" src="https://raw.githubusercontent.com/pastelsky/curldiff/master/www/public/curldiff-web.png" />

## Command line (Experimental)

### Installation
```bash
npm i -g curldiff
```

### Usage 
<img width="600" src="https://raw.githubusercontent.com/pastelsky/curldiff/master/www/public/curldiff-cli.png" />

## How do I generate a curl request?
The easiest way to generate a curl request is by selecting "Copy as CURL" in Chrome
for any network request generated by your app.

<img width="400" src="https://raw.githubusercontent.com/pastelsky/curldiff/master/www/public/copy-as-curl.png" />

## Todo
- Add support for diffing response body and headers
- Better error Handling
