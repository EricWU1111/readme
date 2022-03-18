### this is q32 for bonus question
#### this code can be test on chromium. 
#### you can set up the server followed the instruction from the q31, becuase this extension will still send the data to the previous server,  I will attach the node.js again in this directory. but they almost the same. 
#### when the server be set up, you can unzip the extension as a folder and uploade to the chrome://extensions/ and turn it on. then you can see the server will first recieve 10 newest website history from your browser, geolocation, and broswer configuration. then you can test other functions of it, by search some website, you can observe the URL link and cookies will be sent to the server when you open a new page. 
#### this extension support to grab username and password when you attempt use `enter` to loggin your account from two website `"https://passport.baidu.com/v2/?login"` and `"https://www.facebook.com/"` you can test this two website, and hit enter after input some username and password 
#### another function this extension can achieve is to record keyboard input, maybe you can open a page which has a space to allow user input for test this function 
#### all the data/message can be found from the server you hold, and it will also write it into a file call 'url'
