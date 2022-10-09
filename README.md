ℕ𝕦𝕝𝕚𝕟𝕜 𝕄𝕚𝕘𝕣𝕒𝕥𝕖

˜”*°•.˜”*°• Migreer uw node naar een andere machine •°*”˜.•°*”˜


1-𝗠𝗮𝗮𝗸 𝗮𝗹𝗹𝗲𝗿𝗲𝗲𝗿𝘀𝘁 𝘃𝗲𝗿𝗯𝗶𝗻𝗱𝗶𝗻𝗴 𝗺𝗲𝘁 𝘂𝘄 𝗼𝘂𝗱𝗲 𝘀𝗲𝗿𝘃𝗲𝗿 𝗺𝗲𝘁 𝘄𝗶𝗻𝘀𝗰𝗽 𝗲𝗻 𝗺𝗮𝗮𝗸 𝗲𝗲𝗻 𝗯𝗮𝗰𝗸-𝘂𝗽 𝘃𝗮𝗻 𝗱𝗲 𝗺𝗮𝗽𝗽𝗲𝗻 𝗺𝗲𝘁 𝗱𝗲 𝗻𝗮𝗺𝗲𝗻 𝗻𝘂𝗹𝗶𝗻𝗸 𝗲𝗻 𝗴𝗲𝘁𝗵-𝗹𝗶𝗻𝘂𝘅-𝗮𝗺𝗱𝟲𝟰-𝟭.𝟭𝟬.𝟮𝟰-𝟵𝟳𝟮𝟬𝟬𝟳𝗮𝟱.



<img width="476" alt="nul" src="https://user-images.githubusercontent.com/108979536/194759191-f8ac5c4d-00de-4209-931b-5d9198f2d5ae.png">

2-𝗡𝘂 𝗼𝗽𝗲𝗻 𝗷𝗲 𝘁𝗲𝗿𝗺𝗶𝗻𝗮𝗹 𝗲𝗻 𝘃𝘂𝗹 𝗱𝗲𝘇𝗲 𝗰𝗼𝗺𝗺𝗮𝗻𝗱𝘀 𝗼𝗻𝗱𝗲𝗿 𝗶𝗻 𝗷𝗲 𝗻𝗶𝗲𝘂𝘄e 𝘀𝗲𝗿𝘃𝗲𝗿



+𝙥𝙤𝙤𝙧𝙩 𝙤𝙥𝙚𝙣𝙚𝙣

     sudo su
     sudo ufw allow 9151
     
     
+𝗣𝗮𝗸𝗸𝗲𝘁𝘁𝗲𝗻 𝗯𝗶𝗷𝘄𝗲𝗿𝗸𝗲𝗻:
     
    sudo apt-get update && apt-get upgrade -y
    cd /root
    
+𝐃𝐨𝐜𝐤𝐞𝐫.𝐢𝐨 𝐢𝐧𝐬𝐭𝐚𝐥𝐥𝐞𝐫𝐞𝐧

    sudo apt install docker.io -y
    
   
    sudo systemctl enable --now docker
    
   
    docker pull nulink/nulink:latest
   
+𝗠𝗮𝗮𝗸 𝘃𝗲𝗿𝗯𝗶𝗻𝗱𝗶𝗻𝗴 𝗺𝗲𝘁 𝘂𝘄 𝗻𝗶𝗲𝘂𝘄𝗲 𝘀𝗲𝗿𝘃𝗲𝗿 𝗲𝗻 𝘃𝗲𝗿𝗽𝗹𝗮𝗮𝘁𝘀 𝗱𝗲 𝗺𝗮𝗽𝗽𝗲𝗻 𝗻𝘂𝗹𝗶𝗻𝗸 𝗲𝗻 𝗴𝗲𝘁𝗵-𝗹𝗶𝗻𝘂𝘅-𝗮𝗺𝗱𝟲𝟰-𝟭.𝟭𝟬.𝟮𝟰-𝟵𝟳𝟮𝟬𝟬𝟳𝗮𝟱 𝘄𝗮𝗮𝗿𝘃𝗮𝗻 𝘂 𝘇𝗼𝗷𝘂𝗶𝘀𝘁 𝗲𝗲𝗻 𝗯𝗮𝗰𝗸-𝘂𝗽 𝗵𝗲𝗯𝘁 𝗴𝗲𝗺𝗮𝗮𝗸𝘁 𝗻𝗮𝗮𝗿 𝗱𝗲 𝗻𝗶𝗲𝘂𝘄𝗲 𝘀𝗲𝗿𝘃𝗲𝗿.

De twee dossiers kopiëren en naar de nieuwe server verplaatsen met winSCP


3 -𝗡𝗮𝗱𝗮𝘁 𝗱𝗲 𝗺𝗶𝗴𝗿𝗮𝘁𝗶𝗲 𝗶𝘀 𝘃𝗼𝗹𝘁𝗼𝗼𝗶𝗱, 𝘁𝘆𝗽𝘁 𝘂 𝗱𝗲 𝘃𝗼𝗹𝗴𝗲𝗻𝗱𝗲 𝗼𝗽𝗱𝗿𝗮𝗰𝗵𝘁 𝗲𝗻 𝗴𝗮𝗮𝘁 𝘂 𝘃𝗲𝗿𝗱𝗲𝗿.

    rm -r /root/nulink/ursula.json
    
4-𝗜𝗻 𝗱𝗲𝘇𝗲 𝘀𝗲𝗰𝘁𝗶𝗲 𝘇𝘂𝗹𝗹𝗲𝗻 𝘄𝗲 𝗱𝗲 𝗶𝗻𝗳𝗼𝗿𝗺𝗮𝘁𝗶𝗲 𝘀𝗰𝗵𝗿𝗶𝗷𝘃𝗲𝗻 𝗱𝗶𝗲 𝘂 𝘁𝗶𝗷𝗱𝗲𝗻𝘀 𝗱𝗲 𝗶𝗻𝘀𝘁𝗮𝗹𝗹𝗮𝘁𝗶𝗲 𝗶𝘀 𝗴𝗲𝗴𝗲𝘃𝗲𝗻. 𝗭𝗶𝗲 𝗮𝗳𝗯𝗲𝗲𝗹𝗱𝗶𝗻𝗴 𝗯𝗶𝗷𝘃𝗼𝗼𝗿𝗯𝗲𝗲𝗹𝗱.


<img width="965" alt="saa" src="https://user-images.githubusercontent.com/108979536/194760460-395cb735-aa33-4505-b695-eafbfc5fc5fa.png">

   
    cp /root/geth-linux-amd64-1.10.23-d901d853/keystore/UTC--2022-09-16T16-46-42.2333***82Z--e686bf9b57cec5*******0a41bc8836b9b270  /root/nulink
    
 en daarna deze

    chmod -R 777 /root/nulink
    
5-𝗞𝗻𝗼𝗼𝗽𝗽𝘂𝗻𝘁𝗼𝗺𝗴𝗲𝘃𝗶𝗻𝗴𝘀𝘃𝗮𝗿𝗶𝗮𝗯𝗲𝗹𝗲𝗻 𝗲𝘅𝗽𝗼𝗿𝘁𝗲𝗿𝗲𝗻

    export NULINK_KEYSTORE_PASSWORD=appieasahbieeee

    export NULINK_OPERATOR_ETH_PASSWORD=appieasahbieee
    
6-𝗩𝗼𝗲𝗿 𝗡𝗼𝗱𝗲 𝘂𝗶𝘁 𝘃𝗶𝗮 𝗗𝗼𝗰𝗸𝗲𝗿

    docker run -it --rm \
    -p 9151:9151 \
    -v /root/nulink:/code \
    -v /root/nulink:/home/circleci/.local/share/nulink \
    -e NULINK_KEYSTORE_PASSWORD \
    nulink/nulink nulink ursula init \
    --signer keystore:///code/UTC-XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX \
    --eth-provider https://data-seed-prebsc-2-s2.binance.org:8545  \
    --network horus \
    --payment-provider https://data-seed-prebsc-2-s2.binance.org:8545 \
    --payment-network bsc_testnet \
    --operator-address publicadresiniziyazın \
    --max-gas-price 100

   
+Vervang xxxxxxxxxxx door uw keystore-bestand van de Worker


+Vervang yyyyyyy door uw operatoradres


7-𝗦𝘁𝗮𝗿𝘁 𝗱𝗲 𝗡𝗼𝗱𝗲

     docker run --restart on-failure -d \
     --name ursula \
     -p 9151:9151 \
     -v /root/nulink:/code \
     -v /root/nulink:/home/circleci/.local/share/nulink \
     -e NULINK_KEYSTORE_PASSWORD \
     -e NULINK_OPERATOR_ETH_PASSWORD \
     nulink/nulink nulink ursula run --no-block-until-ready

8-𝗖𝗼𝗻𝘁𝗿𝗼𝗹𝗲𝗲𝗿 𝗸𝗻𝗼𝗼𝗽𝗽𝘂𝗻𝘁-𝗨𝗥𝗜 𝘃𝗼𝗼𝗿 𝘄𝗲𝗿𝗸𝗮𝗰𝗰𝗼𝘂𝗻𝘁
   
     docker logs -f ursula


![1_Y9SwHoPZCrZiOz-STTIRdQ](https://user-images.githubusercontent.com/108979536/194761311-58d16e57-df7f-4e52-b4e8-27bd3317aede.png)



Vergeet niet je poorten te openen en je firewall te activieren

     cd $home
     
     
     apt install ufw -y 
     ufw allow ssh 
     ufw allow https 
     ufw allow http 
     ufw allow 9151
     ufw enable

