# README - Explained

Things to know about running this app:
1.  You need to run the script <python -m http.server> from terminal in order to activate D3 from server.
2.  The folder you need to run #1 above should be in your root folder (where your index.html file is).
    Running it from where your app.js file will cause the chart to not render.
3.  There were obvious delays in Chrome and sometimes in Firefox.  I can only assueme this was due to browser
    caching as when I cleared History in both, it took several minutes for the page to render the first time
    but would update sporadically after that.  Firefox generally worked better than Chrome but occasionally
    Chrome would surprise me and start working before not working again.  I recommend rendering the index.html
    from your local folder as well as open a tab with server running (#1 above), in which the url is
    http://localhost:8000/ (after you run #1 above) so that you can see if there is really an issue with the js
    or if it's the browser.  D3 does not do a good job  telling you where errors exist; it often just does not
    render your chart, so you really need to know what you are expecting to see. 