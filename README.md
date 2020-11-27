# rock-paper-scissors
A simple machine learning to classification an image into three category rock, paper, or scissors.

---

## Built With

* [NuxtJS](https://nuxtjs.org/) - The Intuitive Vue Framework
* [TailwindCSS](https://tailwindcss.com/) - A utility-first CSS framework for rapid UI development.
* [Vercel](https://vercel.com/dashboard) - Deploy web projects with the best frontend developer experience and highest end-user performance.

## Assets

* [Story by freepik](https://stories.freepik.com/) - Awesome illustrations for your next project
* [Corona Live Data by kawalconorna.com](https://kawalcorona.com/api/) - Coronavirus Global & Indonesia Live Data

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
