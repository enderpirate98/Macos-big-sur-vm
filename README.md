download all the files provided in this project:

Virtual Box: https://bit.ly/3JAqNgF

Extension Pack: https://bit.ly/3H5FcQp

iso file: https://bit.ly/3oKMJxA

Downloading and Installing Virtual Box:

click the download links for both virtual box and the e extension pack (the extension pack is very important for a number of reasons)
 
dubble click the exe file and go through the installation

go into tools -> preferences -> extensions and add the extension pack going through any prompts necessary

Setting up the hardware:

create a new virtual machine and name it Big Sur (naming this is easier for later steps but you can name it something else if you like)

the type should be "MAC OS X" and the version should be "10.13 high sierra (64-bit)"

click next 

the amount of ram can be what you want it to be but do at least 8GB for a smooth experience (most moddern systems have 12 or 16 GB and if you less than that please upgrade)

create a new virtual hard disk and choose "VDH" the storage itself should be dynamically allocated

the disk size can be as big as you want it to be but it does have to be at least 80GB

hit create and exit virtual box

setting up the behind the scenes parts of virtual box:

go into the command prompt and run it as administrator

if you have an intel cpu then copy and paste the commands from intel-code.txt (if your vm name is not Big Sur then change Big Sur to what your vm name is)

if you have an amd cpu then copy and paste the commands from amd-code.txt (if your vm name is not Big Sur then change Big Sur to what your vm name is)

open virtualbox and go into the vm settings: general -> advanced and set the clipboard to bidirectional, click ok

mac os install:

open the vm

it will say that there is no start up disk to fix this just add the iso file provided in this project

choose your language and go into disk utility

choose the disk that says: "VBOX HARDDISK Media" and click erase

name the disk what you want

after that close the disk utility

click on install mac os big sur and agree to the software licence

go through the installation and setup like normal

you should then have a working macos big sur install in vmware

this guide was made with the help of this video: https://www.youtube.com/watch?v=LNsC2sUk26Y&t=225s all the files were provided by the author of the video and all rights belong to apple inc and the video auther, i do not own anything in this project, if you make a guide based off this one please mention Andrew E. Snow as an auther of the original guide author, this guide is simply a side project by Andrew E. Snow and he is not trying to make profit of it, thank you for following this guide for setting up a mac os virtual machine and making enderpirate98 known.
