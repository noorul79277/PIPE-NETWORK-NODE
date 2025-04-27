# PIPE-NETWORK-NODE

  PIPE NETWORK NODE RUN

Minimum Req for This node is: 4GB Ram, 100GB Storage

ENTER THE COMMANDS ONE BY ONE , WATCH OUR VIDEO TUTORIAL IN YOUTUBE!

WINDOWS & LINUX & VPS

1.0  : sudo apt update
sudo apt upgrade -y

1.1  : apt install screen -y  [For VPS ONLY (Pc users skip this)]

1.2  : curl -L -o pop "https://dl.pipecdn.app/v0.2.8/pop"

1.3  : chmod +x pop

1.4  : screen -S pipe [For VPS ONLY (Pc users skip this)]

Make Directory (create folder to be used for download cache)

1.5  : mkdir download_cache


1.6  : ./pop --signup-by-referral-route 5fa391f2c7bfcdb1

1.7  : # Generate Your Referral
./pop --gen-referral-route

1.8  : ./pop --ram 4 --max-disk 300 --cache-dir /data --pubKey <KEY>

Note: Put your ram , disk & pubkey according to your actual Information. Retrieve the public key from your Solana wallet (e.g., Phantom) & Replace in <KEY> by Solana Address
(If above command shows error then use this command ,must replace the values of ram , disk and key accordingly).

sudo ./pop --ram 8 --max-disk 500 --cache-dir /data --pubKey <KEY>



Check and Save Node Info
1.9  : nano ~/node_info.json




Monitor your Node Status & Points

2.0  : ./pop --status
2.1  : ./pop --points


For Next Day Run This Command (pc users only)
Open WSL and Put this Command 

sudo ./pop --ram 8 --max-disk 500 --cache-dir /data --pubKey <KEY>

(must replace the values of ram , disk and key accordingly)



For Mobile Users Download Termux Application from Playstore
Link:Click Here

Download SSH Protocol in Termux & Login to Your VPS
Command to download ssh: 
1.1 pkg install openssh -y
1.2 ssh -V  (check version)

Now login to your VPS Using IP & Password
: ssh root@[your ip]
Now Follow Video Guide & Enter same command to run Node.
