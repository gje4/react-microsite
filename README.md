# React Microsite

> 🛍 Moltin powered microsite built with [Create React App](https://github.com/facebook/create-react-app)

## 🛠 Setup

This application uses demo Moltin credentials that has a prepopulated product catalog. You'll need to [signup for an account](https://dashboard.moltin.com/signup) if you want to customize it.

You can follow the instructions below to get the project running locally.

```bash
git clone https://github.com/moltin-examples/react-microsite.git
cd react-microsite
```

Once you've an account, create a `.env.local` file and add your own `REACT_APP_MOLTIN_CLIENT_ID`.

```bash
yarn # or npm install
yarn start # or npm start
```

## 🚀 Deploy

The Create React App [User Guide](https://github.com/facebook/create-react-app/blob/master/packages/react-scripts/template/README.md#deployment) has a great section on deployment. Deploy to Zeit Now, Heroku, Azure, GitHub Pages and many more.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy) [![Deploy to now](https://deploy.now.sh/static/button.svg)](https://deploy.now.sh/?repo=https://github.com/moltin-examples/react-microsite&env=MOLTIN_CLIENT_ID)
