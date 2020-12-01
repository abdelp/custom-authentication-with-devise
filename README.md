# Customize Devise authentication with Active Storage

> This repo is to have the source code of my [tutorial](https://hackernoon.com/how-to-customize-devise-authentication-with-active-storage-5t1b34wz) about how to customize the Devise Gem authentication using Active Storage with a few extra improvements to the UX.

## Built With

- Ruby >= 2.6.5
- Rails >= 6.0.3
- Javascript
- HTML5
- CSS3

## Prerequisites

- Sign up to [Cloudinary](www.cloudinary.com)

### Setup

Clone or download the repo:

```
$ git clone https://github.com/abdelp/custom-authentication-with-devise.git
```

### Install

```
$ cd custom-authentication-with-devise
$ bundle
$ rails db:create
$ rails db:migrate
```

### Usage

Inside the root folder run:

```
rails s
```

#### Register

![register](./app/assets/images/register.png)

To register a new user you:

1. Can optionally select an image as an avatar of the user.
2. Need to input the full name of your user.
3. Need to select a username, the username cannot be already taken by another user.
4. Need to indicate your email.
5. A password of at least 6 characters.

#### Login

![login](./app/assets/images/login.png)

To login, it is only required to specify the username.

#### Profile

![profile](./app/assets/images/profile.png)

## Authors

👤 **Abdel Perez**

- Github: [@abdelp](https://github.com/abdelp)
- Twitter: [@AbdelPerez11](https://twitter.com/AbdelPerez11)
- Linkedin: [abdel-perez](https://www.linkedin.com/in/abdel-perez)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](issues/).

## Show your support

Give a ⭐️ if you like this project!

## 📝 License

This project is [MIT](lic.url) licensed.
