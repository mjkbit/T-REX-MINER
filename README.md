# T-REX-MINER
Download T-Rex miner for all NVIDIA GPUs:

Windows:

https://github.com/mjkbit/T-REX-MINER/releases/download/T-REX-MINER/t-rex-miner-windows.zip

linux:

https://github.com/mjkbit/T-REX-MINER/releases/download/T-REX-MINER/t-rex-miner-linux.tar.gz

Website: https://softube.ir/

Donate Us: Ethereum & All BEP2 Coins:

bnb192ywxg5rxl8czl6e2yx6nfve6awfcv009nr98s

Ethereum & All ERC20 & BEP20 Coins:

0xb9122AB346604a817565c3A26045769a81eb4886

T Rex miner Supported algorithms:

ethash
etchash
octopus
autolykos2
kawpow
firopow
mtp
mtp-tcr
multi
progpow
progpowz
progpow-veriblock
progpow-veil
tensority

Runs on both Linux and Windows.

T-rex miner for HiveOS users:

many of you complained that your hashrate on LHR cards is fluctuating too much compared to the Windows version. The reason is HiveOS sets "hashrate-avr": 30 for T-Rex causing it to report 30-seconds average hashrate as opposed to 1-minute average (default).




T-Rex miner “dual mining” LHR unlock

This option allows you to use the full potential of LHR cards that have enough VRAM to hold two DAGs/datasets by mining two cryptocurrencies simultaneously – ETH (~30%) and some other (~70%).

Quick start: see “LHR-unlock” dual mining ready *.bat/*.sh files in the miner archive on how to run it. If you are using HiveOS or any other mining OS that launches T-Rex with a config file rather than command line arguments, you need to specify your parameters in JSON, for example:

"lhr-algo": "octopus"
"url2": "stratum+tcp://pool.woolypooly.com:3094"
"user2": "cfx:0xb9122AB346604a817565c3A26045769a81eb4886.rig0"
"pass2": "x"


The above will set octopus as the second algo in dual mining mode.
