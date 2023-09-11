# BHARATINTERN-TASK1
## Task - 3 
Video conferencing website 

### Features

- Real-time Video Conferencing
- Customizable User Interface

### Steps

1 - **Sign Up and Get Your APP ID:**
   - Register on [Agora.io](https://www.agora.io/).
   - Create an Agora app to generate an APP ID.
     
2 - **Configure Your APP_ID:**
   - Create a `config.js` file in your project directory.
   - Add your Agora.io APP_ID to `config.js`:
```javascript
   const config = {
     APP_ID: 'YOUR-APP-ID',
   };
```
3 - **Use Your APP_ID:**
   - In your JavaScript file, declare a variable referencing your APP_ID:
```javascript
const app_id = config.APP_ID;
```
4 - **Git Ignore Configuration:**
   - Create a .gitignore file.
   -Add config.js to .gitignore to keep it out of version control
```javascript
config.js
```
