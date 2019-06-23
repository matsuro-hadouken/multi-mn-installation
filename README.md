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
