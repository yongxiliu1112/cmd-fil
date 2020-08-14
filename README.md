# cmd-fil
一些fil命令
lotus client query-ask

curl httpbin.org/ip

lotus-miner net listen

lotus-miner net peers

lotus client list-deals

lotus-miner storage-deals list

lotus-miner actor set-addrs /ip4/public-ip/tcp/10240

lotus-miner net connect 


./lotus-storage-miner init --owner=<bls-address-with-funds> --sector-size=[512MiB|32GiB|64GiB]
	

lotus-miner storage-deals set-ask --price 5000000 --verified-price 4000000 --max-piece-size 32GiB

lotus send --gas-price 700000000000 t01119 0.00001

lotus mpool stat --local

lotus mpool pending --local


存储路径

lotus-miner storage attach --store --init /data/path/to/storage

lotus-miner storage attach --seal --init /data/path/to/fast_cache


worker运行

lotus-worker run --address=192.168.1.244:2345

lotus-worker --workerrepo=/data/path/.lotusworker run --address=192.168.1.244:2345




https://calibration.spacerace.filecoin.io/check

lotus-miner sectors update-state --really-do-it 0 Removing


钱包导入导出

lotus wallet export <addr> > /somewhere/safe/wallet.keyinfo
	
lotus-shed keyinfo info /somewhere/safe/wallet.keyinfo

lotus wallet import /somewhere/safe/wallet.keyinfo


环境变量：

export FIL_PROOFS_MAXIMIZE_CACHING=1

export FIL_PROOFS_USE_GPU_COLUMN_BUILDER=1

export BELLMAN_CUSTOM_GPU="GeForce RTX 2060 SUPER:2176"

export RUSTFLAGS="-C target-cpu=native -g"

export FFI_BUILD_FROM_SOURCE=1



rustup override set nightly

