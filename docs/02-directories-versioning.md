**[Cmder Docs](README.md)**

---

**previous:** [Installation](D:\Repo\Settings\OS\Windows\Apps\Active\Cmder\docs\01-installation.md)

# Cmder Directories & Versioning

> ***We take a look at the defaults, create a git repository, and redesign the directory structure***

---

## Cmder Directory Structure

**The default directory structure and logic is as follows:**

```bash
Cmder
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
	# Libraries used to make Cmder work. You don't need to directory edit this directory.
```

*While this is a cute layout, it’s a mess and illogical. Let’s Spruce it up a bit…*

---

## Making a Git Repository

Since we’re going to create a whole new directory structure, let’s first create a git repository, exclude unneeded folders and then push it to GitHub for backup.

## Redesigning Cmder Directory Structure

**Let's move things around a little bit:**

```bash
Cmder
├───config          
│   ├───images      
│   │   └───icons   
│   └───profile.d   
├───docs   # documents         
├───shells     
│   ├───cmd         
│   │   ├───logs    
│   │   ├───plugins 
│   │   └───profiles
│   └───powershell  
│       ├───logs    
│       ├───plugins 
│       └───profiles
└───vendor          
```

There's still a lot of stuff that we will be using in the `vendor` directory. I'll make a goal to clean this out and rearrange this later.

---

**Next:** [Settings](03-settings.md)

