# jscloneof.github.io
Clone of GitHub Created Using JavaScript ft. WhollyAPI & WebScrapperJS

---

## GitHub :- https://github.com/jscloneof/jscloneof.github.io

## Demo :- https://jscloneof.github.io/

## Article :- https://dev.to/sh20raj/i-created-a-github-clone-using-javascript-webscrapperjs-3pn0

## Deploy on Vercel :- ![https://vercel.com/button](https://vercel.com/new/clone?repository-url=https://github.com/jscloneof/jscloneof.github.io)

main.js File 
```javascript
  var url = "https://github.com"+location.pathname+''+location.search;
  document.write(WebScrapper.get(url)) ;
  
  function getparam(a,e){return e||(e=window.location.href),new URL(e).searchParams.get(a)}
  ```
