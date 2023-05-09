# ssh-commands

## Copy key to server
ssh-copy-id -i ~/.ssh/[FILE_NAME].pub [YOUR_USER_NAME]@[IP_ADDRESS_OF_THE_SERVER]

## Connect to server
ssh -A [YOUR_USER_NAME]@[IP_ADDRESS_OF_THE_SERVER]

## Copy files to the server
scp -P 22 -r [FOLDER] [YOUR_USER_NAME]@[IP_ADDRESS_OF_THE_SERVER]:/[path]
