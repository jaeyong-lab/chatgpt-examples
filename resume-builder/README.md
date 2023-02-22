# resume builder

- [Creating a resume builder with React, NodeJS and AI 🚀](https://dev.to/novu/creating-a-resume-builder-with-react-nodejs-and-ai-4k6l)


### How to run

#### server
- `./resume-builder/server/index.js`: set openAI(chatGTP) api key: https://platform.openai.com/account/api-keys
    ```javascript
    const configuration = new Configuration({
      apiKey: '',
    });

    ```

- run server
    ```bash
    $ cd ./resume-builder/server

    $ npm install

    # create uploads directory
    $ mkdir uploads

    $ npm run start
    ```

#### client
- run client
  ```bash
  $ cd ./resume-builder/client

  $ npm install

  $ npm run start
  ```
