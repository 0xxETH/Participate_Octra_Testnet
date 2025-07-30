# Participate_Octra_Testnet

All comands past in your terminal step by step

## Install pre-clint

Firstly need pre-clinet for operating with ur wallet : balance,tx,encrypt,decrypt etc.

1.Go to octra repository https://github.com/octra-labs/octra_pre_client 

2.Look a green bottom " **Code** " , u need " **Codespace** " 

3.Create own codesapce

**OR** open windows terminal with Windows + R > cmd + Enter

```
 git clone https://github.com/octra-labs/octra_pre_client.git
 cd octra_pre_client
 python3 -m venv venv
 source venv/bin/activate
 pip install -r requirements.txt
 cp wallet.json.example wallet.json
```

## Generate Wallet

> [!CAUTION] 
> All info from wallet generate file save in secure!

### To generate wallet past this comand in terminal
```
1.curl -fsSL https://octra.org/wallet-generator.sh | bash
```
After succes look at " **Ports** " or follow link in terminal

Press generate wallet bottom , write ur data.

### After generate 

Go to wallet.json file and replase : 

- Private key
- Adress 

Save file Ctr + S

```
{
  "priv": "private key here",
  "addr": "octxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
  "rpc": "https://octra.network"
}
```

## Operation with wallet

To run some GUI past this comand in terminal 

```
./run.sh
```

Dont panic when see blue screen . It is what it is.

For governent wallet use number on keyboards and Enter

### Send tx 

```
1.Write " 1 " on terminal + Enter 
```
```
2.Paste anyone adress 
Use my : octF7hE8cQLzSKnhd8CVt75Ydu9GBjLR4vDFgRKCkyXqmG5
```

```
3.Write an amout what u like send + Enter
```
```
4.U can add some message + Enter . For skip just Enter
```
```
5.Confirm transaction input y or n for reject.
```
## Faucet : 
[https://oct-faucet.xme.my.id/]([url](https://oct-faucet.xme.my.id/))
[https://faucet.octra.network]([url](https://faucet.octra.network))





