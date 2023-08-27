# 📗 Table of Contents

- [📗Table of Contents](#-table-of-contents)
- [📖Hello Rails Front End](#hello-rails-front-end)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
    - [🚀 Live Demo](#live-demo)
  - [💻Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Setup](#setup)
    - [Install](#install)
    - [Usage](#usage)
  - [Author](#author)
    - [👤**Agu Lugard**](#agu-lugard)
  - [🔭Future Features](#future-features)
  - [🤝Contributing](#contributing)
  - [⭐️Show your support](#support)
  - [🙏Acknowledgments](#acknowledgements)
  - [📝License](#license)

<!-- PROJECT DESCRIPTION -->

# 📖 Hello Rails Front End <a name="hello-rails-front-end"></a>

**Hello Rails Front End** This project demonstrates the integration of both frontend and backend functionalities using Ruby on Rails and React within a two application system. The application stores the messages in the postgresql database which is retrieved by the front en react app linked to it for the display of random greetings as stored in the backend database, highlighting the seamless interaction between the two applications.

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

[Back End repository](https://github.com/lugard1/hello-rails-back-end)

<details>
  <summary>Client</summary>
  <ul>
    <li>React</li>
  </ul>
</details>

<!-- Features -->

### Key Features <a name="key-features"></a>

- **Frontend Addition**
- **Backend Addition**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

# 🚀 Live Demo <a name="live-demo"></a>

- N/A

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->

## 💻 Getting Started<a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites <a name="prerequisites"></a>

In order to run this project you need the following installed in your local system

- Ruby
- Rails
- Posgresql
- Node.js
- Yarn
- Git CLI
- Github account

Run this command to install **Rails**

```bash
$ npx create-react-app app-name
```

### Setup <a name="setup"></a>

Clone this repository to your desired folder:

```sh
  cd <desired-folder>
  git clone https://github.com/lugard1/hello-rails-front-end.git
```
**Link to database** <br>
- [ ] Rails Back End do
- Uncomment the block: Rails.application.config.middleware.insert_before 0, Rack::Cors do, in config/initializers/cors.rb
- Update the origins in config/initializers/cors.rb, with '*'
- Install gem rack-cors in Gemfile
- Run rails Back End app on port: 3000
- [ ] React App Front End do
- Create .env
- REACT_APP_API_ENDPOINT=http://127.0.0.1:3000
- Run React Front End App at different port with: npm start

### Install <a name="install"></a>

```sh
  npx create-react-app hello-rails-front-end
  cd hello-rails-front-end
  npm start
  git init

```

### Usage <a name="usage"></a>

```sh
  npm start
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- AUTHORS -->

## 👤Author<a name="author"></a>

### 👤 **Lugard Agu**<a name="agu-lugard"></a>

- GitHub: [@lugard1](https://github.com/lugard1)
- Twitter: [@Dsn3kings](https://twitter.com/Dsn3kings)
- LinkedIn: [@LugardAgu](https://www.linkedin.com/in/lugardagu)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FUTURE FEATURES -->
 
## 🔭 Future Features <a name="future-features"></a>

- [ ] **[Add button to generate greeting]**
- [ ] **[Add navigation]**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

If you like this project please give it a Star!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

I would like to thank Microverse for providing us learning materials and my peers that assisted in this success, especially Mahabub Alam.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is contributed under [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>