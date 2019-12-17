# Todo Starter

USE THIS TEMPLATE TO INIT YOUR TODO PROJECT!

**YOU NEED TO ADD SECRETS ENV(MAIL_USERNAME/MAIL_PASSWORD/MAIL_TO/MAIL_FROM) WHICH IN GITHUB SETTINGS -> ACTIONS TO MAKE EMAIL NOTIFY WORK**

# Use todo-plus-parser to generate html file
```bash
npm i todo-plus-parser -g
todo-plus-parser -i "./" -o "./out.html"
```
Then you get your doing(which you are doing now) && critical(which you think critical but not start to do) todo items and github actions will notify you everyday by email which you set.

![](assets/imgs/out.png?raw=true)
