<h1 align="center"> Ziesha Network | Tahdig Testnet </h1>

<div align="center">

![image](https://user-images.githubusercontent.com/108215275/230774400-08a2c51b-ee74-4884-95a9-de45d1bd8725.png)

#  [Twitter](https://twitter.com/ZieshaNetwork)|[Discord](https://discord.gg/zieshanetwork)|[Website](https://ziesha.network/)|[Telegram](https://t.me/ZieshaNetworkOfficial)|[Whitepaper](https://hackmd.io/_Sw5u2lUR9GfBV5vwtoMSQ)

</div>

> ### Ziesha'nın yeni testneti ***Tahdig***  ***Testnet*** başlıyor.
> ### Bu testnet, önceki testnetlerden farklı olarak PoS (Proof-of-Stake) konsensüs mekanizmasını kullanacak. 
> ### Tahdig Testnet, Ziesha topluluk üyelerinin ağı test etmesine ve geri bildirim sağlamasına olanak tanıyacak olan teşviksiz bir test ağıdır.
#
#
> ### Bazuka node çalıştımak için gereken minimum gereksinimler: `2CPU 2GB RAM 50GB SSD`
> ### Testnete, hazırladığım script ile tek komut kullanarak katılabilirsiniz.
> ### Komutu girin ve yönergeleri takip edin.
```
wget https://raw.githubusercontent.com/0xSocrates/Testnet-Rehberler/main/Ziesha-Network/ziesha.sh && chmod +x ziesha.sh && bash ./ziesha.sh
```
> ### Kurulumu tamamladıkran sonra, yapılacak diğer işlemler ve gelecek güncellemeler için Discord duyurularını takip etmeyi unutmatın.
> ### Sorularınız olursa yine discorddan sorabilirsiniz.

# Komutlar

> ### Logları görüntülemek
```
sudo journalctl -u bazuka -fo cat
```
> ### Restart
```
sudo systemctl restart bazuka
```
> ### Node durumunu görüntüleyin
```
bazuka node status
```

> ### Cüzdan bilgisi
```
bazuka wallet info
```
> ### Token gönderme
```
bazuka wallet send --amount <miktar> --from <adres> --to <hedefadres>
```
> ### Validatör oluşturma
```
bazuka wallet register-validator --commision <commision>
```
> ###  Delegate 
```
bazuka wallet delegate --amount <miktar> --fee <fee> --to <validatöradresi>
```
> ### ReClaim
```
bazuka wallet reclaim-delegate --amount <miktar> --fee <fee> --from <validatöradresi>
```
> ### Token oluşturma
```
bazuka wallet new-token --name <isim> --supply <supply> --symbol <sembol>
```
> ### Cüzdana token ekleme
```
bazuka wallet add-token --id <id>
```
> ### Pendingdeki işlmeleri tekrar gönderme
```
bazuka wallet resend-pending
```
> ### Wallet nonce sıfırlama
```
bazuka wallet reset
```

























