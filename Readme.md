# Clone_Etherscan

personal.newAccount('3009')
"0xd055b8bc4c45c36c2920d8ce07f59a434ab47a3e"
하나더 생성

신규 생성 계좌 밸런스 확인
eth.getBalance("0xf54c44ef012d5e32a798e6846dfb97a9e885d9a0")

eth.coinbase

personal.sendTransaction({from:eth.coinbase,to:eth.accounts[1],value:web3.toWei(1,"ether")},"3009")
personal.sendTransaction({from:eth.coinbase,to:eth.accounts[1],value:web3.toWei(1,"ether")},"3009")
결과 : "0x8cb8ebe9bc842640a0b2fdd74dd6619cd420e1b77aabdf904978266cc81d891c"

다시확인 eth.getBalance('0x1222ab90553e7868571cea2d32bb17c4e05ebbe0')

근데 0찍혀있음

확인할려면 txpool 로 해야함

다시 miner.start(1)

eth.getBalance("0x58ead25dabd94b1d08f4e85a5e118647ccf7dce4")

# Geth

작업할 디렉토리하나 생성
datadir 로 사용할 예정

geth --datadir node account new

genesis.json

설치된 go-ethereum
make all // build/puppeth

geth
`puppeth` - 설정파일 도와주는 아이

source ~/.profile

geth --datadir node --http --http.addr "0.0.0.0" --http.port 9000 --http.corsdomain "\*" --http.api "admin,miner,txpool,web3,personal,eth" --syncmode full --networkid 3009
// 실제하고있는건 rpc래
geth attach http://127.0.0.1:9000

geth --datadir node --ws --ws.addr "127.0.0.1" --ws.port 9000 --http.corsdomain "\*" --ws.api "admin,miner,txpool,web3,personal,eth" --syncmode full --networkid 3009

geth.ipc // web3 admin/miner/등등 사용해서 호출한내용보기위해

geth --datadir node init ./genesis\_/pjnetwork.json

geth attach ./node/geth.ipc
? ? ?

# 폴더생성 explorer

1. npm init -y
2. npm install web3 jest

geth attach http://127.0.0.1:9000
0x94ef7f3773a5e8aaf31a3943b9ae6f0255c45905
personal.sendTransaction({from:eth.coinbase,to:eth.accounts[1],value:web3.toWei(10,"ether")},"3009")

0x03544de41e85dd27e02543f2e368bf687da95108bb1f9488fa16a47baf9c131b

eth.getBalance(eth.coin)
0x58ead25dabd94b1d08f4e85a5e118647ccf7dce4 <<
