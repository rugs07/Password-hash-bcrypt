# Password-hash-bcrypt
This is password hashing code used for hashing password using salt so that attacker after even having access to databse
cannot have our password. In this we have used Rest Clinet extension so we have no need to use Postman or Mongodb database.
use npm run devStart to start
we created 3 method here 
1) get user data
2)  post user data
3)  compare user data from the databse and to the login page user using bcrypt.compare()

We generated salt using bcrypt.genSalt() (We can pass here paramter like 10,20... higher the number more the time it will take
to generate salt but more the security)
