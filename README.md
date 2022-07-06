# bash-webp-converter

A simple bash script to convert all images files with one command in a directory into webp file.

(Work on linux)

## Requirement

- [Webp](https://developers.google.com/speed/webp/) converter already installed.

## Usage

### Simple way:

Past the script in the target directory and in a terminal launch:

```
$ ./webpC
```

### Other way:

Paste the script in the root directory, add alias to bashrc.

Open bashrc file in a terminal, or with a file editor:

```
$ sudoedit ~/.bashrc
```

At the end of the file add the alias:

```
$ alias webpC=~/webpC
```

Save and refresh bashrc file:

```
$ source ~/.bashrc
```

#### Alternative one command:

```
echo "alias webpC=~/webpC" >> ~/.bashrc && source ~/.bashrc
```

Now you can launch `webpC` command from every directory you want to convert images.
