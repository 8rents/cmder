**[Cmder Docs](README.md)**

---

**previous:** [Installation](D:\Repo\Settings\OS\Windows\Apps\Active\Cmder\docs\01-installation.md)

# Cmder Directories & Versioning

> ***We take a look at the defaults, create a git repository, and redesign the directory structure***

---

## Default Directory Structure

The default directory structure and logic is as follows:

```bash
Cmder\ 
├───cmder.exe 
├───bin
│	# Place your binaries here. These will be injected into your PATH.
├───config
│	# Contains shell profiles for each shell type
│	# user_profile.cmd - CMD 
│	# user_profile.ps1 - PowerShell Profile
├───icons
│	# icons and images used for theming
├───opt
│	# Optional packages directory. Will not be injected in your PATH by default
└───vendor
	# Libraries used to make Cmder work. You don't need to directory edit this directory. If making a git repository make sure to ignore vendor directories
```

*While this is a cute directory structure, it’s a mess and illogical. Let’s Spruce it up a bit…*

---

## Making a Git Repository

Since we’re going to create a whole new directory structure, let’s first create a git repository, exclude unneeded folders and then push it to GitHub for backup.

### Excluding the `vendor` folder

Since the `vendor` folder is used to house 3rd party libraries and plugins, we don’t need to actually back it up.

In your `.gitignore` or your GitHub Desktop client ignore the `vendor` folder.

Then commit and push the repo up to GitHub.

## Redesigning Cmder Directory Structure

 Now that we have a back up

## 

---

**Next:** [Settings](03-settings.md)

