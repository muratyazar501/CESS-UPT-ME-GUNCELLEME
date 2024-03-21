# CESS-UPT-ME-0.0.5-GUNCELLEME



![image](https://github.com/Volkan081/CESS-UPT-ME-0.0.5-GUNCELLEME/assets/95221293/a15292a4-b9a5-45b7-8577-3d371e00a741)

# [Website](https://www.cess.cloud/) | [Twitter](https://twitter.com/CESS_Storage) | [Discord](https://discord.gg/DyEzq6Js) | [Github](https://github.com/CESSProject) | [Docs](https://docs.cess.cloud/cess-build-book/)
     
 </div>

#


## Linkler

 [volkanberra twitter](https://twitter.com/BerraVolkan)

 [volkanberra github](https://github.com/Volkan081)


Önce tüm seervisleri durduralım

```
sudo cess stop
sudo cess down

```

eski sürümdeki bazı detayların silinmesi gerekli.Aşağıdaki kodu uygulayalım

```
sudo cess purge


```

Güncelleme yapalım

```
wget https://github.com/CESSProject/cess-nodeadm/archive/v0.5.5.tar.gz
tar -xvf v0.5.5.tar.gz
rm -rf v0.5.5.tar.gz
cd cess-nodeadm-0.5.5/
./install.sh --skip-dep



```

servis güncellemesi yapalım

```

sudo cess pullimg


```

-nodemizi tekrar çalışır duruma getirelim



```

sudo cess start


```


 ### Chain log kontrol
 
 > `best` ulaştığınız blok yüksekliğiir [exploreri](https://cloudflare-ipfs.com/ipns/dotapps.io/?rpc=wss%3A%2F%2Ftestnet-rpc0.cess.cloud%2Fws%2F#/explorer) yakalayana kadar bekleyin farklı rpc [explorer](https://testnet.cess.cloud/?rpc=wss%3A%2F%2Ftestnet-rpc2.cess.cloud%2Fws%2F#/accounts)

```
docker logs -f chain
```

-Aşağıdaki gibi çıktı almanız gerek

![image](https://github.com/Volkan081/CESS-UPT-ME-0.0.5-GUNCELLEME/assets/95221293/4f887362-9067-4557-8eef-de98b466b8d8)

