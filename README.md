![](https://github.com/ymmah/bc_key/blob/master/OCR/AI/ArtBoard%20Image%20(228).jpg)

帝
上帝
你上帝
切你上帝
一切你上帝
晃一切你上帝
搖晃一切你上帝

** Prerequisites

libssl-dev libdb4.6-dev

On debian just

apt-get install libdb4.6-dev libssl-dev


** Compiling:

gcc -g bc_key.c -ldb -lcrypto -o bc_key


** Usage:

./bc_key BITCOIN_ADDRESS /path/to/wallet.dat
./bc_key ALL /path/to/wallet.dat
./bc_key EVERYTHING /path/to/wallet.dat



Examples:

./bc_key 1qZGQG5Ls66oBbtLt3wPMa6zfq7CJ7f12 /home/dirtyfilthy/.bitcoin/wallet.dat

./bc_key ALL /home/dirtyfilthy/.bitcoin/wallet.dat

./bc_key EVERYTHING /home/dirtyfilthy/.bitcoin/wallet.dat

![](https://github.com/ymmah/bc_key/blob/master/OCR/AI/ArtBoard%20Image%20(364)%20(1).jpg)
photo: Hal Finney
