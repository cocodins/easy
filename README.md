# rock-paper-scissors
A simple machine learning to classification an image into three category rock, paper, or scissors.

---

## Built With

* [Google Colab](https://colab.research.google.com/) - Colab notebooks allow you to combine executable code and rich text in a single document, along with images, HTML, LaTeX and more.
* [TensorFlow](https://www.tensorflow.org/) - The core open source library to help you develop and train ML models. Get started quickly by running Colab notebooks directly in your browser.
* [Keras](https://keras.io/) - is an API designed for human beings, not machines. Keras follows best practices for reducing cognitive load: it offers consistent & simple APIs, it minimizes the number of user actions required for common use cases, and it provides clear & actionable error messages. It also has extensive documentation and developer guides.

## Getting Started

To run this project on your local system, you can follow these steps:

### Prerequisites

This application uses NPM as its package manager, make sure that your system has NPM installed, but if not you can install it with the following command

* npm
```sh
npm install npm@latest -g
```

### Installation

1. Clone the repo
```sh
git clone https://github.com/rasatmaja/kawruhe.rasio.dev.git
```
2. Install NPM packages
```sh
npm install
```
3. Create .env files on root directory
```
COVID_API_URL=https://api.kawalcorona.com
```
4. Run app on local environment
```sh
npm run dev
```

## What I Learn from this Project 
On my journey to building this project I learned a few things and I ran into some problems like:

1. Implement NuxtJS on prouction mode
2. Integrate tailwind with NuxtJS project
3. Make entering animation when object on view port using `Srcroll Observer`
4. Using proxy on axios
5. Learn how to deploy NuxtJS App on [Vercel](https://vercel.com/)
6. Can't use module @nuxt/content on vercel, my guest is vercel dosen fully suppport and optimize with all nuxt module
