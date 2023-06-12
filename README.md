# How to get Spotify refresh token?


---
##Getting client id and client secret

1.First of all go to [Spotify developer Dashboard](https://developer.spotify.com/dashboard) and click on create app

2.Name your app Anything and give it any description you like.....

3.Add `http://localhost:3000/` as redirect uri.....

> As below


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/hgtol7fpxcung294526i.png)

---
##Setting up Environment

1.just open cmd prompt in any folder and run this cmd

> `git clone https://github.com/MannuVilasara/get-Spotify-refresh-token.git`

2.then open it in vs code

run this
```bash
npm install
```
3.open `app.js` and replace client id and client secret with your client id and client secret 


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/biodxe84nywqg9jzvyox.png)

-----

##Getting refresh token

now just only few things are left.....

1.type this cmd
```bash
npm start
```
and open this [link](http://localhost:3000/) in your browser....

2.enter your client id and client secret in the text boxes


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/j45bub2zjbnl9265smxv.png)

3. Click on Request Authorization

4. Complete the authorization on next page

5.Click F12 or developer tools in the browser and go to application => local storage => `http://localhost:3000/`

> There You will get refresh token and access token....


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/jh71ypj6qc10fp3uurl4.png)



enjoy.....

Give it a star if it helps

-----






