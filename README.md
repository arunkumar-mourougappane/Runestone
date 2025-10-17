# Runestone

This repository contains a collection of utility scripts and bash functions to streamline your workflow.

## Scripts

- [add_to_path](scripts/add_to_path) - Add a directory to the PATH environment variable, avoiding duplicates.
- [check_and_source](scripts/check_and_source) - Source a file if it exists and is readable.
- [comic_repacker](scripts/comic_repacker) - Convert a ZIP archive of images into a CBR archive of PNG files.
- [git-key-add](scripts/git-key-add) - Starts ssh-agent and adds keys, or simply re-adds expired keys.
- [git-key-del](scripts/git-key-del) - Removes keys and ends the ssh-agent process.

## Installation

To use these scripts, clone the repository and add the `scripts` directory to your `PATH`.

```bash
git clone https://github.com/your-username/runestone.git
cd runestone
export PATH=$PWD/scripts:$PATH
```

## Usage

### add_to_path

Add a directory to the PATH environment variable.

```bash
add_to_path <directory> [after]
```

If `after` is specified, the directory is added to the end of the PATH. Otherwise, it is added to the beginning.

### check_and_source

Source a file if it exists and is readable.

```bash
check_and_source <file>
```

### comic_repacker

Convert a ZIP archive of images into a CBR archive of PNG files.

```bash
comic_repacker -i <input_file> -o <output_directory>
```

### git-key-add

Starts ssh-agent and adds keys, or simply re-adds expired keys.

```bash
git-key-add
```

### git-key-del

Removes keys and ends the ssh-agent process.

```bash
git-key-del
```

> [!NOTE]
> All scripts are written for bash 5.1.16(1) and python 3.10.XX.
