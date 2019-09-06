# aws-polly-playground

learn [aws polly]() text-to-speech (TTS)

## Running

based on <https://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/getting-started-browser.html#getting-started-browser-scenario>

update js code in [`polly.html`](polly.html) with the following

```js
AWS.config.region = '<YOUR_REGION>';
AWS.config.credentials = new AWS.CognitoIdentityCredentials({ IdentityPoolId: '<YOUR_IDENTITY_POOL_ID>' });
```

```sh
open polly.html
```