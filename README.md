## JoininBox - Build a dedicated JoinMarket Box remotely connected to a full node

* Testing on
  * Hardkernel Odroid XU4 with Armbian (more boards to come - pending testing)
  * Debian Buster desktop
  * Ubuntu 18.04 desktop
  * Connected to a RaspiBlitz 1.4 (any Bitcoin Core node can work, including previous RaspiBlitz versions)

### Install and set up the base image
* [Set up Armbian on the Hardkernel Odroid XU4](https://github.com/openoms/joininbox/blob/master/FAQ.md#set-up-armbian-on-the-hardkernel-odroid-xu4)
* [Download and verify Raspbian SDcard image for a Raspberry Pi](https://github.com/openoms/joininbox/blob/master/FAQ.md#download-and-verify-raspbian-sdcard-image-for-a-raspberry-pi)

### Set up JoininBox
* Continue work as the `root` user.
* Continue with the [manual building steps](build_joininbox.md)  
or
* download and run the build script:  
```bash 
$ wget https://raw.githubusercontent.com/openoms/joininbox/master/build_joininbox.sh && sudo bash build_joininbox.sh --with-tor
```

---

## More info:

* How to [prepare a remote node to accept the JoinMarket connection](prepare_remote_node.md)
* Manual instructions on how to [build the JoininBox](build_joininbox.md)
* [Frequently Asked Questions and notes](FAQ.md)
* [JoinMarket on the RaspiBlitz guide](https://github.com/openoms/bitcoin-tutorials/blob/master/joinmarket/README.md)
* [Connect JoinMarket running on a Linux desktop to a remote node](https://github.com/openoms/bitcoin-tutorials/blob/master/joinmarket/joinmarket_desktop_to_blitz.md)

## Forums:

* Keybase: https://keybase.io/team/raspiblitz#joinmarket  
* Telegram: https://t.me/joinmarketorg  
* IRC: #joinmarket on Freenode  
* Reddit: https://www.reddit.com/r/joinmarket/  

--- 

There is a terminal based GUI in the works.

**Work In Progress** - suggestions and contributions are welcome

<p align="left">
  <img width="400" src="/images/mainmenu.png">
  <img width="400" src="/images/darkmenu.png">
</p>

### Rough plan

- [x] INFO "Wallet information" 
- [ ] PAY "Pay with a coinjoin" 
- [ ] TUMBLER "Run the Tumbler" 
- [x] YG "Run the Yield Generator" 
- [x] HISTORY "Show report" 
- [x] OBWATCH "Show the offer book" 
- [ ] EMPTY "Empty a mixdepth" 
- [x] CONF_YG "Configure the Yield Generator" 
- [x] STOP "Stop the Yield Generator" 
- [ ] GEN "Generate a wallet" 
- [ ] RESTORE "Restore a wallet" 
- [x] INSTALL "Install an configure JoinMarket" 
- [x] UP_JIB "Update JoininBox"