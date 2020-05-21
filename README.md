# My Personae

Web services want to know that users are real people. Users want privacy. We authenticate users, but give them the opportunity to create an alias, so that we know there is an actual person behind the account without exploiting their privacy. Then we generate one-time use hash passwords to login to other services.

By separating authorization from other services like using Facebook or Google to log in, we prevent privacy intrusion "creep" from services requesting more and more data. Besides data used to make it harder to create multiple accounts, we will store no other identifiable information about users.

## Built With

* [Node.js 10.14.2](https://nodejs.org/) - Javascript runtime
* [Express.js 4.16.0](https://expressjs.com/) - The web framework used

## Author

* **Jonathan Chang** - *Initial work* - [jachang820](https://github.com/jachang820)
