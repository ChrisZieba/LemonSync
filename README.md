#LemonSync

**LemonSync** will listen for changes in the folder you configure, and automatically push updates to your store theme.

## nstallation

You must have python 2.7.x or higher for `LemonSync` to work. Also, please make sure you have the needed libraries installed. If you have `pip` already installed on your system you can run the following commands to install them.

`sudo pip install watchdog`  
`sudo pip install boto`

If you do not have pip installed, you can also install those libraries using `easy_install`. 

## Configuration

You need to set your configuration values, which are located in `config.cfg`.

- `aws_access_key`
- `aws_secret_key`
- `bucket`
- `name` 
- `theme`

You need to set the directory that will watch for changes.
- `watch` Remember to add a trailing slash.

## Usage

Once you have cloned this repository onto your machine, you can simply run `python LemonSync.py` from your command line. To stop the program type `Ctrl-C`.
