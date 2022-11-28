 <h1 align="center">MantaNetwork </h1>

# TrustedSetupContribute
![unnamed](https://user-images.githubusercontent.com/100621008/204383868-7952c4c5-fd5e-4c86-aec1-0761f7045d2e.jpg)

second phase of Manta Network trustedsetup

if you have participated in the first stage, we will have completed the second stage by using our secret 12 word password that we received at that stage

*System Requirements*
|  CPU  |    RAM     |     SSD    |  
|-------|------------|------------|
|    2  |      4     | unspecified|

### update our server
```
sudo apt update && sudo apt upgrade -y
```
```
apt install screen -y
```
### install the requirements
```
sudo apt install pkg-config build-essential libssl-dev curl jq
```
### install Rust
```
curl https://sh.rustup.rs/ -sSf | sh -s -- -y
```
### specify the source
```
source $HOME/.cargo/env
```
### cloning Manta
```
git clone https://github.com/Manta-Network/manta-rs.git
```
###  create screen
```
screen -S manta
```
### entry manta folder
```
cd manta-rs
```
*this process will take a long time and at the end of the process, we will enter the contribution code, our 12 secret words*


