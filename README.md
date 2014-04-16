## 下記の gist を /etc/motd に貼り付けることで可能です
※debian系なら /etc/motd.tail にどうぞ

### アルベルト (Romancing Saga)
![](./images/albert.png)

[gist:albert.txt](https://gist.githubusercontent.com/makocchi-git/9775443/raw/de30d7cf0b399a5ad854c4da955198ebb40db6a4/albert.txt)

### 最終皇帝・男 (Romancing Saga 2)
![](./images/last-emperor.png)

[gist:koutei.txt](https://gist.githubusercontent.com/makocchi-git/9775443/raw/e1c82d89a97aa4e8dc62f69f411d6087554cbb1a/koutei.txt)


### ミカエル (Romancing Saga 3)
![](./images/michael.png)

[gist:michael.txt](https://gist.githubusercontent.com/makocchi-git/9775443/raw/1d3cb60a227495df0acbd62747801c6c86be3ce7/michael.txt)

### こんな感じでどうぞ
```bash
$ curl -s <gistのurl> | sudo tee -a /etc/motd
```
