# FBfetch
Fetches posts from csi nsit fb page and displays in order of likes and shares.

## Setting Up The App

### Step-1
In the directory of saved files, open terminal and run following commands: 
```
npm init
npm install
```

### Step-2
* Option-1
Run following commands in mysql client.
```
create user fbuser identified by 'password';
create database dbfbfetch;
grant all privileges on dbfbfetch.* to fbuser;
flush privileges;
```
* Option-2
Create your own mysql database and set its details in config.js file under DB object

### Step 3
Enter the following fields in config.js file
1. CLIENT_ID (APP ID from facebook)
2. CLIENT_SECRET (APP SECRET from facebook)
3. EXPRESS_SECRET (express secret for express session)

### Step 4
Run following command in your terminal in directory of saved files.
```
node app.js
```

### Step-5
Now you can access the website at http://localhost:8000

*If it does not work, send an email at anshul98ks123@gmail.com*