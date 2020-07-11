* There is a hidden scoreboard on the OWASP Juice Shop, hosted by the Bay Cyber League. But it is carefully hidden - it is the goal of several competitors to find it. 
* I am one of those who can actually explain it for you. 
* And let me tell you: much of the information I used came from "https://pwning.owasp-juice.shop/".
* So the first step was to access the main-es2015.js file of the "Sources" tab in Chrome DevTools. 
* Next, I accepted pretty-print, which could've been also done with the "{}" button at the bottom.
* Then, throughout the code, I tried to find code that was a route-mapping section containing the word "score" within it.
* Finally, I navigated to "https://juiceshopper.baycyber.net/#/score-board" to solve the challenge. 
* Note: After you completed this, you should be able to go back to the Juice Shop Menu and find an option that says "Scoreboard". If you click on it, then you'll know you're in the right place.
