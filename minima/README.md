# <h1 align="center">Minima testnet</h1>

![minima](https://user-images.githubusercontent.com/73015593/178371122-781308f3-35c7-448c-b62c-e26574dcd04b.jpg)


# Node kurulumu

## Minima scriptimizi çalıştırıyoruz.
```
wget -O minima_setup.sh https://raw.githubusercontent.com/minima-global/Minima/master/scripts/minima_setup.sh && chmod +x minima_setup.sh && sudo ./minima_setup.sh -r 9002 -p 9001
```
![minima](https://user-images.githubusercontent.com/73015593/178371579-d9417980-b614-4c3b-ae39-8dea04d119d6.PNG)


## Ardından https://incentive.minima.global/account/register?inviteCode=DAB1BLQC sayfasına giderek kayıt oluyoruz.
![mail](https://user-images.githubusercontent.com/73015593/178371795-7ca40d67-94e5-42f7-a96f-2da534892254.PNG)


## Logları ctrl c ile durdurduktan sonra incentive id'mizi sunucumuza bağlıyoruz. "INCENTIVE-ID" kısmına kendi id mizi giriyoruz.
```
curl 127.0.0.1:9002/incentivecash+uid:INCENTIVE-ID
```
![id](https://user-images.githubusercontent.com/73015593/178372682-2bd6eb63-cbea-492c-a7b9-e9fd0fbff7bd.jpg)


## Günlük ping atarak https://incentive.minima.global/ sitesinden kazandığımız ödülleri görebiliriz.
![reward](https://user-images.githubusercontent.com/73015593/178372486-c1825e50-5045-4f3e-8a91-f24820aa0ecf.PNG)
