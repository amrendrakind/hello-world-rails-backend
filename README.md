![](https://img.shields.io/badge/Microverse-blueviolet)

# Hello World Rails-Backend

## Description

> This project implements a API from Ruby on Rails back-end for front-end

## Built With

- Ruby on Rails
- Postgress

## React Front-end App

- [React App PR Link](https://github.com/amrendrakind/hello-world-react-frontend/pull/1)

## React Frontendend development set up

- [Visit for frontend setup](https://github.com/amrendrakind/hello-world-react-frontend/tree/dev)

## Rails backend development set up

Clone Repository using

`git clone git@github.com:amrendrakind/hello-world-rails-backend.git`

Or using HTTPS

`git clone https://github.com/amrendrakind/hello-world-rails-backend.git`

Move into project directory

`cd hello-world-rails-backend`

### Setup Database 
- Make sure that your Postgres database is installed.
- Open the file config\database.yml
- Modify the connection parameters to point your Postgres database:

    `username: [your_user]`

    `password: [your_password]`

- If required drop existing database : `rake db:drop`
- Create databases: `rake db:create`
- Create db structure including tables : `rake db:migrate`
- If required seed initial data (stored in db\seeds.rb file): `rails db:seed`


### Run API
- Located in the root path run `rails server` to start the API
- Visit http://localhost:3000/ in your browser!
- Navigate to http://localhost:3000/api/v1/greetings to see random Greeting in the API

## Author

👤 **Amrendra K**

- GitHub: [@amrendrakind](https://github.com/amrendrakind)
- Twitter: [@amrendrak_](https://twitter.com/amrendrak_)
- LinkedIn: [amrendraakumar](https://linkedin.com/in/amrendraakumar)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/amrendrakind/hello-world-rails-backend/issues).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Hat tip to anyone whose code was used
- Inspiration and support from peer group

## 📝 License

This project is [MIT](./MIT) licensed.