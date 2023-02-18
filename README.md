https://www.youtube.com/watch?v=7UQBMb8ZpuE&t=235s
https://www.youtube.com/watch?v=cjqfF5hyZFg

# jwt-login-reg

nodemon start on server
npm start on client

Downgraded to "react-router-dom": "^5.2.0", instead of v6 to enable Switch (replace Routes) and Redirect (replace Navigate)

Downgraded Toastify to "react-toastify": "^8.1.0", due to weird bug


**Few Backend Notes:**

Authentication: check if you are the person you claim to be

Authorization: based on status and credentials, what can you do

JWT is used to make sure the person isn’t fake… It’s NOT to encrypt data (header [algorithm and token type] + payload [data] + secret_key [only accessible in backend hidden])
