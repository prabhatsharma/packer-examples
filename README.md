# sample packer files for creating AMIs on AWS

make sure that you have following environment variables set:

> AWS_ACCESS_KEY_ID

> AWS_SECRET_ACCESS_KEY


To create a ubuntu based image run:

> packer build ubuntu.json

To create a windows based image:



> packer build windows.json

You can install additional tools in windows by modifying the scripts/SetUpWinRM.ps1 file.
