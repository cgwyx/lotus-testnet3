# lotus-testnet3
lotus-testnet3

docker run -d --restart=always --name lotus-testnet3 --gpus all -e BELLMAN_CUSTOM_GPU="GeForce GTX 1660:1408" \
-v /media/p300/lotuswork/:/root/ -v /media/p300/lotuswork/:/var/tmp/ -p "1234:1234"  -p "1235:1235" -p "2345:2345" \
cgwyx/lotus-testnet3:latest
