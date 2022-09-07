# Rails budget

> A Mobile Web App made with Rails that takes care of your expenses. You can have a record of your expenses by date, category, amount, and others. Has feature and system tests with RSpec and Capybara. Implements authentication with Devise and authorization with CanCanCan. Deployed to Heroku. Uses PostgreSQL and ActiveRecord.


## Built With

- Ruby `3.1.2`
- Rails `7.0.3`


## Getting Started

### Prerequisites

- Ruby

### Setup

To get a local copy up and running follow this simple step:

- Clone repository to your local machine: 
`git@github.com:jrosario19/rails-budget.git`
This will create a directory in the name of the project folder.

- Navigate to project folder using `cd rails-budget`

### Install

- Run `bundle install` to install all gems for the project.

### Usage

- Run `rails s` to start the server
- Open `http://127.0.0.1:3000/` in your browser to use the app

### Tests
- Run `rspec` to run the tests

### Troubleshooting
In case you face a problem with the gem bootsnap due to the platform you run the project, follow the next instructions:
- In order for you to be able to run the project successfully in windows platform you have to change the bootsnap gem to `gem 'bootsnap', '>= 1.1.0', '< 1.4.2', require: false`.
- In order for you to be able to run the project successfully in Ubuntu platform you have to change the bootsnap gem to `gem "bootsnap", "~> 1.13", require: false`.

## Authors

👤 **Juan Francisco Rosario Suli**

- GitHub: [@jrosario19](https://github.com/jrosario19)
- Twitter: [@jrosario19](https://twitter.com/jrosario19)
- LinkedIn: [Juan Fco. Rosario](https://linkedin.com/in/juan-francisco-rosario-suli-44595051)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Thanks to all the Micromates and the Ruby on Rails community for their support.
- Original design idea by [Gregoire Vella on Behance](https://www.behance.net/gregoirevella).

## 📝 License

This project is [MIT](./MIT.md) licensed.
