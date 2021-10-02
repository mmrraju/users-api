# users-api


This is a testing api. Where I store name and phone number in my json db.
we can call this api bellow the link

https://my-json-server.typicode.com/mmrraju/users-api/

https://my-json-server.typicode.com/mmrraju/users-api/users


Ready to deploy a api using Json server

steps 1: Create a folder "user-api-server"

steps 2: Create a package.json typing in your cmd promot 

```$ npm init -y```

steps 3: Install json server using cmd 

```$ npm install json-server```

steps 4: Create a file with name db.json and insert data suchs
```
[
  {
    "id": 1,
    "name": "Raju",
    "phone_number": "+8801734206885"
  },
  {
    "id": 2,
    "name": "Anamulgp",
    "phone_number": "+8801718234953"
  }
]
```
steps 5: Open package.json add bellow scripts
```
"scripts": {
  "start": "json-server db.json"
}
```

steps 6: Run 

```$ npm start```

Deploy in github...

Step 1: Create a repository in github

Step 2: Create git init in your local machine 

``` $ git init ```

Step 3: Add all files and comiit to git

``` 
$ git add .

$ git commit -m "initial commit"
```
Step 4: Push from local to remote
```
$ git push
```
