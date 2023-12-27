# cc-materials Cookiecutter Template

[日本語版のREADMEはこちら](README_ja.md)

## Overview
`cc-materials` is a Cookiecutter template designed for quickly setting up a material management directory structure for media projects. This template helps you to efficiently create organized directories for different categories such as Audio, Image, Other, and Video.

## Prerequisites
To use this template, you must have Cookiecutter installed. If it is not already installed, you can install it using the following command:

```bash
pip install cookiecutter
```

Alternatively, Cookiecutter can also be installed using other package managers like HomeBrew, pipx, XBPS, etc. For more detailed instructions, please refer to the official documentation:

[Cookiecutter Installation Guide](https://cookiecutter.readthedocs.io/en/stable/installation.html)

## How to Use
1. **Generate the Template**:
   Execute the following command to generate a new project from the `cc-materials` template:

   ```bash
   cookiecutter gh:your-github-username/cc-materials
   ```

   Respond to prompts such as `directory_name` as required.

2. **Customize the Directory Structure**:
   Within the generated project directory, add, edit, or delete folders and files as needed.

3. **Start Using the Project**:
   Begin managing your materials using the created directory structure.

## Directory Structure
The directory structure generated will be as follows:

```
{{cookiecutter.directory_name}}/
├── Audio/
│   ├── Favorites/
│   ├── Music/
│   └── SoundEffects/
├── Image/
│   ├── BackgroundImages/
│   ├── Favorites/
│   ├── Illustrations/
│   └── Photographs/
├── Other/
│   ├── Documents/
│   ├── Favorites/
│   ├── Notes/
│   └── Templates/
└── Video/
    ├── Favorites/
    ├── FreeStockVideos/
    └── PaidStockVideos/
```

## Support
For questions or feedback regarding this template, please submit issues or pull requests through GitHub.
