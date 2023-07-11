# How setup Web_Quasar Template

Tools Required: postgresql, Quasar Framwork

## Install the dependencies
1.	Open Folder in vs code:
2.	Install Quasar
```bash
npm install -g @quasar/cli
```

### Install Node for Client Side
```bash
npm i
```

### Run command to install node in Server Folder : AS server and client parts of application have different dependencies and requirements.
```bash
npm i
```

### HOW Run Project
First Run Client Side. Then Run Server Side  on two different CMD
a.	Client Side:
```bash
quasar dev
```
b.	Server side:
```bash
node .\server.js
```
### After Postgress Installation uncomment: To Create User In DB

// API("auth.createUser", { username: "sample", password: "123", role: "user" });
