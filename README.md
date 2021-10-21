# ig.news

News subscription application using ReactJS developed in the Rocketseat Ignite course using stripe as a test payment method.

## Screenshots

<div align="center" id="top"> 
  <img src="./public/images/home-ignews.png" alt="Home ignews" />
</div>
<br/>
<br/>
<div align="center" id="top"> 
  <img src="./public/images/posts-ignews.png" alt="Posts ignews" />
</div>
<br/>
<br/>
<div align="center" id="top"> 
  <img src="./public/images/inside-posts-ignews.png" alt="Inside posts ignews" />
</div>
<br/>
<br/>
<div align="center" id="top"> 
  <img src="./public/images/posts-not-login-ignews.png" alt="Posts not login ignews" />
</div>
<br/>
<br/>

```bash
# Clone this project
$ git clone https://github.com/ewertonspezia/ignews

# Access
$ cd ignews

# Install dependencies
$ yarn

# Adjusting variables in the .env.local file
$ Copy .env.local.example to .env.local and fill the variables

# Stripe listen execute
$ stripe listen --forward-to localhost:3000/api/webhooks

# Run the project
$ yarn dev

# The server will initialize in the <http://localhost:3000>
```
