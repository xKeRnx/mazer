<h1 align="center">Mazer Dashboard</h1>

![Mazer Screenshot](https://user-images.githubusercontent.com/45036724/167523601-9d20fb17-1989-488f-b619-cb53c0db8898.png)

<p align="center">Mazer is an Admin Dashboard Template that can help you develop faster. Made with Bootstrap 5. No jQuery dependency.</p>
<div align="center">

[![License](https://img.shields.io/github/license/zuramai/mazer.svg)](LICENSE)

</div>

## Usage

#### Building yourself

- Clone the repository `git clone https://github.com/zuramai/mazer`
- Install dependencies using the node package manager of your choice. For example run `npm install` 
- Files are bundled by Laravel Mix to the dist folder.
    - Either run `npm run hot` and open `http://localhost:8080` to see a hot-reloading copy of the generated files.
    - Or run `npm run watch`  (rebuilds on file changes) or `npm run production` and open `index.html` in from the dist folder.

### Building with Docker

- Clone the repository `git clone https://github.com/zuramai/mazer`
- Make sure you have Docker installed and run:
    - `docker build -t mazer-frontend .`
    - `docker run -it -d -p 8080:80 --name mazer mazer-frontend`
    - Open `http://localhost:8080`

## Contributing

Please follow [Contributing Guide](./CONTRIBUTING.md) before contributing.

## License

Mazer is under [MIT License](./LICENSE).
