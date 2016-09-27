# Sending SMS from Web

This is a simple web app written in Node.js with Express and Socket.io.

## Running This Demo Locally on Your Machine

1. Install dependencies

```bash
$ npm install
```

2. Set up a config.js with Your Credentials

Sign up at [Nexmo](https://nexmo.com) to get your own API keys and a virtual number.

Create `config.js` in the root dir of the app. The file should include the credentials.

```javascript
module.exports = {
  api_key: 'f321a...',
  api_secret: '18e9aad...',
  number: '14155551234'
};
```

3. Run the Node App

```bash
$ node server/send-sms.js
```

4. Launch it on Browser

Go to http://localhost:4000
