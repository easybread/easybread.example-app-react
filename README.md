# easybread.example-app-react

This app demonstrates how you can use EeasyBREAD in the real life application.

### Requirements
Make sure you've got the latest stable node and yarn installed.

### Install
Run from project root:

```bash
$ yarn install
$ yarn build
```

### Configuration for google oauth

In order to allow Google Contacts and GSuite adapters use Google OAuth2.0 flow in the example app,
you need to configure it.

Copy the example env file .env.example:

```bash
$ cp ./.env.example ./.env
```

Then, edit it following recommendations in the comments.

### Run the server

```bash
$ yarn start:server 
```

This should start the server on `http://localhost:8080`;
