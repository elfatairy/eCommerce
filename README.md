<a id="readme-top"></a>

[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![project_license][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<br />
<div align="center">
<h3 align="center">eCommerce</h3>

  <p align="center">
    eCommerce website using laravel and react
    <br />
    <br />
    <a href="https://github.com/elfatairy/eCommerce/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    &middot;
    <a href="https://github.com/elfatairy/eCommerce/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

### Built With

- [![HTML5][HTML5]][HTML5-url]
- [![CSS3][CSS3]][CSS3-url]
- [![JavaScript][JavaScript]][JavaScript-url]
- [![React][React.js]][React-url]
- [![PHP][PHP]][PHP-url]
- [![Laravel][Laravel.com]][Laravel-url]

<!-- Installation -->

## Installation

### Prerequisites
- PHP >= 8.1
- Composer
- Node.js & NPM (or Yarn/PNPM/Bun)
- MySQL or PostgreSQL

### Setup

1. Clone the repo
   ```sh
   git clone https://github.com/elfatairy/eCommerce.git
   cd eCommerce
   ```

2. Install PHP dependencies
   ```sh
   composer install
   ```

3. Install NPM packages for React (located in `resources/js`)
   ```sh
   # npm
   npm install

   # or with yarn
   yarn install

   # or with pnpm
   pnpm install

   # or with bun
   bun install
   ```

4. Set up environment file
   ```sh
   cp .env.example .env
   ```

5. Generate application key
   ```sh
   php artisan key:generate
   ```

6. Configure your database in `.env` file
   ```env
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=your_database_name
   DB_USERNAME=your_database_username
   DB_PASSWORD=your_database_password
   ```

7. Run database migrations
   ```sh
   php artisan migrate
   ```

8. (Optional) Seed the database
   ```sh
   php artisan db:seed
   ```

9. Build React assets or run development server
   ```sh
   # Development (with hot reload)
   npm run dev

   # Production build
   npm run build
   ```

10. Start the Laravel development server (in a separate terminal)
    ```sh
    php artisan serve
    ```

11. Visit `http://localhost:8000` in your browser

### Change git remote (optional)
```sh
git remote set-url origin your_github_username/your_repo_name
git remote -v # confirm the changes
```

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- CONTACT -->

## Contact

Omar Hassan - [@omar_elfat76510](https://x.com/omar_elfat76510) - elfatairy@omarhassan.net

Project Link: [https://github.com/elfatairy/eCommerce](https://github.com/elfatairy/eCommerce)

Portfolio: [https://omarhassan.net](https://omarhassan.net)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/elfatairy/eCommerce.svg?style=for-the-badge
[contributors-url]: https://github.com/elfatairy/eCommerce/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/elfatairy/eCommerce.svg?style=for-the-badge
[forks-url]: https://github.com/elfatairy/eCommerce/network/members
[stars-shield]: https://img.shields.io/github/stars/elfatairy/eCommerce.svg?style=for-the-badge
[stars-url]: https://github.com/elfatairy/eCommerce/stargazers
[issues-shield]: https://img.shields.io/github/issues/elfatairy/eCommerce.svg?style=for-the-badge
[issues-url]: https://github.com/elfatairy/eCommerce/issues
[license-shield]: https://img.shields.io/github/license/elfatairy/eCommerce.svg?style=for-the-badge
[license-url]: https://github.com/elfatairy/eCommerce/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/omar-hassan-81888320b/
[HTML5]: https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white
[HTML5-url]: https://developer.mozilla.org/en-US/docs/Web/HTML
[CSS3]: https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white
[CSS3-url]: https://developer.mozilla.org/en-US/docs/Web/CSS
[JavaScript]: https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black
[JavaScript-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript
[PHP]: https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white
[PHP-url]: https://www.php.net/
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Typescript.js]: https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=D9E8F5
[Typescript-url]: https://www.typescriptlang.org
[Supabase]: https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=ffffff
[Supabase-url]: https://supabase.com
[Tailwind]: https://img.shields.io/badge/Tailwind-3178C6?style=for-the-badge&logo=tailwindcss&logoColor=ffffff
[Tailwind-url]: https://tailwindcss.com
[Motion.dev]: https://img.shields.io/badge/motion-dev-black.svg?logo=data:image/svg+xml;base64,PHN2ZyB2ZXJzaW9uPSIxLjIiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgdmlld0JveD0iMCAwIDI0IDkiIHdpZHRoPSIyNCIgaGVpZ2h0PSI5Ij4NCiAgPHRpdGxlPk1vdGlvbjwvdGl0bGU+DQogIDxwYXRoIGZpbGw9IiNmZmY0MmIiDQogICAgZD0iTSA5LjA2MiAwIEwgNC4zMiA4Ljk5MiBMIDAgOC45OTIgTCAzLjcwMyAxLjk3MSBDIDQuMjc3IDAuODgyIDUuNzA5IDAgNi45MDIgMCBaIE0gMTkuNjU2IDIuMjQ4IEMgMTkuNjU2IDEuMDA2IDIwLjYyMyAwIDIxLjgxNiAwIEMgMjMuMDA5IDAgMjMuOTc2IDEuMDA2IDIzLjk3NiAyLjI0OCBDIDIzLjk3NiAzLjQ5IDIzLjAwOSA0LjQ5NiAyMS44MTYgNC40OTYgQyAyMC42MjMgNC40OTYgMTkuNjU2IDMuNDkgMTkuNjU2IDIuMjQ4IFogTSA5Ljg3MiAwIEwgMTQuMTkyIDAgTCA5LjQ1IDguOTkyIEwgNS4xMyA4Ljk5MiBaIE0gMTQuOTc0IDAgTCAxOS4yOTQgMCBMIDE1LjU5MiA3LjAyMSBDIDE1LjAxOCA4LjExIDEzLjU4NSA4Ljk5MiAxMi4zOTIgOC45OTIgTCAxMC4yMzIgOC45OTIgWiI+PC9wYXRoPg0KPC9zdmc+
[Motion-url]: https://motion.dev/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com
