<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.css">
<script src="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.min.js"></script>
<div id="gitalk-container"></div>
var gitalk = new Gitalk({
  "clientID": "880ebb465daa0f8e756e",
  "clientSecret": "56545397456bc6570dc63d060925c4f634824e05",
  "repo": "https://github.com/haoxincheng/test",
  "owner": "haoxincheng",
  "admin": ["haoxincheng"],
  "id": location.pathname,      
  "distractionFreeMode": false  
});
gitalk.render("gitalk-container");
