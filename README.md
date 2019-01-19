<p align="center">
    <strong>
        MULTI-CONVERT - LINUX (UBUNTU)
    </strong>
</p>

<p align="center">
    <img src="https://img.shields.io/badge/Apache-Virtualhost-red.svg" alt="Apache virtualhost">
</p>


## Introduction
Multi-Convert is a tool based on the ubuntu tool ``convert``. Multi-Convert simply helps in bulk conversion of your 
images.

## Installation
Clone repository into your `~/` directory

Go to your home directory on your terminal:

`$ cd ~`

Clone multi-convert into your home directory:

`$ git clone https://github.com/hfally/multi-convert.git`

Add `$HOME/multi-convert/bin` to your PATH.

#### How to add to your PATH
Run the command below. There is 70% chances you are using the default bash terminal, but if you happen to be using
another like `zsh` switch `.baschrc` for `.zshrc` in the command below.

`$ echo 'export PATH="$PATH:$HOME/multi-convert/bin' >> .bashrc`

You will need to source your .bashrc or logout/login (or restart the terminal) for the updates to take effect. 
To source your .bashrc, simply run:

`$ source ~/.bashrc`

**if you use zsh or any other shell, follow the same route (switching .bashrc as staeted previously)**

## Basic Usage
* Go to your workspace on the terminal

    `$ cd /path-to-images/` 
    
    ***REPLACE** `path-to-images` with the correct path to all your images*

* Run the command below to do the conversions

    `$ multi-convert EXT DEFAULT-CONVERT-ARGUMENTS`
    
    ***REPLACE** `EXT` with the file extension of the images you want to convert, e.g jpg, JPG, png, etc*
    
    ***REPLACE** `DEFAULT-CONVERT-ARGUMENTS` with the normal arguments you would have given the `convert` tool except the file path. You can give as many argument as you want. **EXCEPT** the file path*
    
    **Examples of `convert` Arguments:**
    *  -strip 
    * -interlace
    * -quality
    * -resize
    
    You can read more on the `convert` tool by running:
    
    `$ convert -help`
    
That's it! 

You can always get help through `$ multi-convert help`


## Supported OS
Ubuntu is the only supported distro for now, however, its likely it works on Debian too.

## License

Multi-Convert is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)

## Contribution
For contribution and personal bug reporting, send a mail to the author <a href='mailto:tofex4eva@yahoo.com'>tofex4eva@yahoo.com</a>