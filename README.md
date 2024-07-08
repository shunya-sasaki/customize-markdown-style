# Customize Markdown Style

This project aims to develop style files for Markdown.

## Requirements

- Visual Studio Code

## Setup

### Clone this project

First, clone this project to your computer by running the following command in your terminal.

```sh
git clone https://github.com/shunya-sasaki/marp-templates.git
```

### Add an alias to your shell environment configuration file

Open your shell environment configuration file (e.g., `.bashrc`) in a text editor,
and add the following line. Replace `YOUR_DIRECTORY` with the directory where
you cloned this project. This allows you to run the `markdown-init` command.

```sh
alias markdown-init=YOUR_DIRECTORY/customize-markdown-style/bin/markdown-init.sh
```

## Usage

### Add style files and templates to the current directory

If you add style files and template files to the current directory,
just run `markdown-init`. After running this command, the `assets` and
`docs` directories are created as follows.

```diff
  your_directory
+ |- assets
+ |  `- css
+ |     `- report.css
+ |- docs
+ |  `- report.md
  `- ...
```

### Create a new Marp project directory

If you create a new directory that has subdirectories (`assets` and `docs`),
run the `markdown-init` command with an argument that is the directory name.
After running this command, a directory with the specified name will be created.

## License

[MIT](./LICENSE)

## Author

Shunya Sasaki &lt;<shunya.sasaki1120@gmail.com>&gt;