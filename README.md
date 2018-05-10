# serverless-nodejs

### Requirements
- Node
  * `>=4 <=9`

- [Serverless](https://serverless.com/framework/docs/) CLI
  * To install:
    - `yarn global add serverless`
    - `npm install -g serverless`
      
### Get Started
 
#### Offline Usage
To hit the ground running without even configuring your AWS creds.

```
$ yarn install     # or use npm install
$ serverless offline start
```

Now, you can visit `localhost:3000/hello` and should see a simple message!
