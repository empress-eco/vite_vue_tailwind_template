<div align="center">
![Project Logo](https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png
<p align="center">
A comprehensive boilerplate for building custom frontend for Empress apps using Vue 3, Vue Router, TailwindCSS, and Empress UI.
<br />
<a href="https://v3.vuejs.org/guide/introduction.html">Explore the Vue 3 Docs</a>
·
<a href="https://next.router.vuejs.org/guide/">Learn more about Vue Router</a>
·
<a href="https://github.com/Empress/Empress-ui">Discover Empress UI</a>
·
<a href="https://tailwindcss.com/docs/utility-first">Explore TailwindCSS</a>
·
<a href="https://vitejs.dev/guide/">Check out Vite</a>
·
<a href="https://github.com/empress-eco/vite_vue_tailwind_template/issues">Report a Bug</a>
·
<a href="https://github.com/empress-eco/vite_vue_tailwind_template/issues">Request a Feature</a>
</p>
</div>

## About The Project

### 📖 Overview
The Vite Vue Tailwind Template is a robust starting point designed for developers who wish to build custom frontend for Empress apps. It comes pre-configured with Vue 3, Vue Router, TailwindCSS, and Empress UI, along with a basic frontend authentication setup. This project aims to provide a streamlined development experience, promoting productivity without compromising on the power and flexibility of the tools involved.

### 🌟 Key Features
- **Vue 3 and Vue Router**: Leverage the power of Vue 3 and Vue Router for a dynamic, modern web development experience.
- **TailwindCSS**: Create unique, responsive, and high-performing user interfaces with the help of the utility-first CSS framework TailwindCSS.
- **Empress UI**: Seamlessly integrate with Empress apps, benefiting from the cohesive, well-designed UI elements of Empress UI.
- **Frontend Authentication**: Get started quickly with a basic frontend authentication system included out of the box.

### 🛠 Built With
This project utilizes the following powerful frameworks and libraries:
- [Vue 3](https://v3.vuejs.org/guide/introduction.html)
- [Vue Router](https://next.router.vuejs.org/guide/)
- [Empress UI](https://github.com/Empress/Empress-ui)
- [TailwindCSS](https://tailwindcss.com/docs/utility-first)

## Getting Started

### Prerequisites
This template is designed to be cloned within an existing Empress App.

### Installation
Follow these steps for a smooth setup of your development environment:

```sh
# Navigate to the root folder of your app
cd apps/your_app_name
# Clone this template using `degit`
npx degit NagariaHussain/doppio_Empressui_starter frontend
# Move to the frontend directory
cd frontend
# Install the dependencies
yarn
# Start the development server
yarn dev
```

## Usage
For a development environment, include the following key-value pair in your `site_config.json` file to prevent CSRFToken errors:

```sh
"ignore_csrf": 1
```

The Vite dev server will start on port `8080`, which can be adjusted in `vite.config.js`. The dev server is set to proxy your Empress app (typically running on port `8000`).

## Contributing
We welcome and appreciate contributions! Here's how you can contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Please read the [contribution guidelines](https://github.com/empress-eco/vite_vue_tailwind_template/blob/main/CONTRIBUTING.md) for more information.

## License and Acknowledgements
This project is licensed under the MIT License. Your contributions will also be licensed under the MIT License.

Special thanks to the Empress Community for their invaluable contributions to the foundational tools that power this project. Their innovative work and continuous support have significantly influenced the development and functionalities of this project. We are deeply grateful for their pioneering efforts.