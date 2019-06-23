### "FAQ"

#### Can I use this script to install just one masternode ?

Yes, this script can install any amount of masternodes, as much as your server can handle.

#### Do I need to buy extra IP addresses to be able to run multiple masternodes ?

No, this script requares only one IP address and significantly decreases your hosting cost.

#### Ok guys, but I need to pay for a big server with a lot of RAM and a huge hard drive, this will probably cost me even more than Hadron Collider ?

No, actually you don't need Hadron Collider, if you plan to run up to 3 VPS we recommend Vultr 3.50$ or contabo ("S SSD" 4.99$) if doing up to 40 instances.

#### Seriously I can run 40 masternodes on just one IP for 5$ a month ?

Absolutely right Sir!

#### So this script use IPv6 ?

No, this script use IPv4

#### All this things requare a lot of technical knowledge, should I be some sort of hacker to be able to use it ?

No, this script is specially designed to help people achive their goal without the need of any technical knowledge.

#### I have already 100 masternodes running, do I need to shutdown them first ?

No, you don't need to shutdown them, this script is a beast and can transfer your masternodes to one server, no new start needed. Just replace **LINE FROM MASTERNODE.CONF** with your masternode line from your desktop **masternode.conf**, the script'll automatically copy private keys and configuration:

```
bash -ic "$(wget -4qO- -o- raw.githubusercontent.com/matsuro-hadouken/multi-mn-installation/master/multi-nodes-installer.sh)" -- LINE FROM MASTERNODE.CONF; source ~/.bashrc
```
#### But I'm ok with servers cost, I run my own hosting company, why should I need such a big script ?

This script such a big one, and have absolutely no competition across all PoS scene, this thing gives you amazing control across all of your masternodes, can make chain match, check sync and do enormous amount of things, just have a look on some of the commands at the end of the FAQ.

## INSTALLATION:
Paste this line into console and press ENTER.

```
bash -ic "$(wget -4qO- -o- raw.githubusercontent.com/matsuro-hadouken/multi-mn-installation/master/multi-nodes-installer.sh)" ; source ~/.bashrc
```


## "all_mn_run" - Run Same Command on All Masternodes


#### all_mn_run **daemon**
Get the daemon name for all the masternodes running on this VPS.

#### all_mn_run **DAEMON_NAME pivxd update_daemon force**
Update the masternode binary code for all masternodes that have a daemon called pivxd.

#### all_mn_run **ONE_DAEMON explorer**
Get the explorer URL for every masternode running on this VPS.

## Popular Commands
#### dogecash-cli **blockcheck**  
Compare the local getblockcount and the explorers block count.

#### dogecash-cli **getmasternodestatus**
Get masternode status on vps.

#### dogecash-cli **mninfo**
Get masternode from masternode list.

#### dogecash-cli **mnping**
Get last masternode ping thats been sent out.

#### dogecash-cli **ps**
Get process info on the node.

#### dogecash-cli **privkey**
Get the masternode private key.

#### dogecash-cli **uptime**
Get how long the daemon has been running for in seconds.

#### dogecash-cli **restart**
Restart the daemon.

#### dogecash-cli **dl_blocks_n_chains**
Download the blocks and chainstake folders if old; fairly close to a new install.

#### dogecash-cli **dl_blocks_n_chains force**
Download the blocks and chainstake folders even if newly downloaded; fairly close to a new install.

#### dogecash-cli **sync**
Show inital block sync progress.

#### dogecash-cli **update_daemon**
Check github for a new version.

#### dogecash-cli **update_daemon force**
Update daemon to the latest version on github.

#### dogecash-cli **remove_daemon**
Delete the masternode off of the VPS.

## All Other Commands 

#### dogecash-cli **addnode_console**
Generate an addnode list of peers that have the same blockcount as the explorer. List is in the format for adding via the debug console.

#### dogecash-cli **addnode_list**
Generate an addnode list of peers that have the same blockcount as the explorer. List is in the format for adding via the wallet configuration file.

#### dogecash-cli **addnode_remove**
Remove any addnode= lines in the VPS wallet configuration file. 

#### dogecash-cli **addnode_to_connect**
Change the addnode= lines to connect= in the VPS wallet configuration file.  

#### dogecash-cli **chaincheck**
#### dogecash-cli **checkchain**
Compare the local getblockchaininfo and the explorers block chain info.

#### dogecash-cli **checksystemd**
#### dogecash-cli **systemdcheck**
See if systemd is enabled active and running.

#### dogecash-cli **log_daemon**
#### dogecash-cli **daemon_log**
Print the contents of debug.log

#### dogecash-cli **daemon_log loc**
Print the location of debug.log

#### dogecash-cli **daemon_log grep** ***"Search Term"***
Search the logs for that exact text string.

#### dogecash-cli **explorer** 
Get the block explorers URL.

blockcount_explorer
#### dogecash-cli **explorer_blockcount** 
Get the block explorers blockcount.

#### dogecash-cli **explorer_peers**
Get the peers connected to the block explorer.

#### dogecash-cli **explorer_peers**
Get the peers connected to the block explorer.

#### dogecash-cli **getmasternodever**
See what versions the masternodes in masternode list are running.


blockcount_explorer  
chaincheck  
checkblock  
checkchain  
checkpeers  
checksystemd  
cli  
conf  
connect_to_addnode  
console_addnode  
crontab  
daemon  
daemon_in_good_state  
daemon_log  
daemon_remove  
daemon_update  
dl_addnode  
dl_blocks_n_chains  
dl_bootstrap  
dl_bootstrap_reindex  
explorer  
explorer_blockcount  
explorer_peers  
failure_after_start  
forcestart  
getmasternodever  
getmasternodeversion  
getpeerblockcount  
getpeerblockver  
getpeerver  
getpeerversion  
githubrepo  
lastblock  
lastblock_time  
list_addnode  
log_daemon  
log_system  
masternode.conf  
mnaddr  
mnbal  
mncheck  
mnfix  
mninfo  
mnlocal  
mnping  
mnver  
mnwin  
peercheck  
peers_remove  
pid  
port  
privkey  
ps  
ps-short  
reindex  
reindexzerocoin  
remove_addnode  
remove_daemon  
remove_peers  
rename  
restart  
start  
start-nosystemd  
status  
stop  
sync  
systemdcheck  
system_log  
update_daemon  
uptime  
