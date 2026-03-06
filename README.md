# Counter-Strike Icons

![GitHub Actions](https://img.shields.io/github/actions/workflow/status/Juknum/counter-strike-icons/cs2-update-detector.yml?label=CS2%20Update%20Detector)
![GitHub Actions](https://img.shields.io/github/actions/workflow/status/Juknum/counter-strike-icons/cs2-extract-media.yml?label=CS2%20Media%20Extraction)

A collection of icons and media assets automatically extracted from **Counter-Strike 2**.

## 📖 About

This repository serves as an up-to-date archive of icons and media files from Counter-Strike 2. Assets are automatically detected and extracted and pushed to the repository the following days after an update.

## ⚙️ How It Works

The project relies on two GitHub Actions workflows:

### 1. CS2 Update Detector (`cs2-update-detector.yml`)

- Periodically checks for new Counter-Strike 2 updates.
- Triggers the extraction pipeline when a new update is detected.

### 2. CS2 Extract Media (`cs2-extract-media.yml`)

- Extracts icons and media assets from the latest CS2 game files.
- Commits and pushes the updated assets to this repository.

## 📄 License

All Counter-Strike 2 assets are the property of **Valve Corporation**. This repository is intended for community and educational use only.

## 🤝 Contributing

Since this repository is automatically maintained via CI/CD workflows, manual contributions to the asset files are not necessary. However, if you have suggestions for improving the extraction workflows or repository structure, feel free to open an issue or pull request.