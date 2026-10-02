# README Maker

![HTML](https://img.shields.io/badge/-HTML-1c1f4a) ![CSS](https://img.shields.io/badge/-CSS-1c1f4a) ![JavaScript](https://img.shields.io/badge/-JavaScript-1c1f4a) ![Licence](https://img.shields.io/badge/licence-MIT-ff7a1a)

Generate a clean `README.md` in seconds. Fill in a form, see the Markdown update live, then copy or download it.

No install, no dependencies. Everything runs in your browser.

## Features

- Live Markdown preview as you type
- Optional sections: badges, installation, usage, contributing, license
- Automatic badges for your technologies and license
- Copy to clipboard or download as `README.md`
- You can edit the generated text directly

## Usage

1. Open `index.html` in your browser.
2. Fill in the form (project name, description, technologies, and so on).
3. Copy the Markdown or download the file.
4. Put it at the root of your repository.

## Run it online with GitHub Pages

1. Push this project to a GitHub repository.
2. Go to **Settings → Pages**.
3. Choose **Deploy from a branch**, then `main` and `/ (root)`.
4. Your site will be live at `https://YOUR-USERNAME.github.io/readme-maker/`.

## Customize

Everything is in a single `index.html` file. Edit the `make()` function in the script to change the generated template, or the CSS variables at the top to change the colors.

## Contributing

Ideas and fixes are welcome:

1. Fork the project
2. Create a branch (`git checkout -b my-feature`)
3. Commit your changes
4. Open a pull request

## License

Distributed under the MIT License.
