***Harbor需要設置的***
1. Harbor需間建立兩個專案名稱 : sas_repos_lts_202x.xx、base
2. 新增使用者 : sas,sas@example,sas,P@ssw0rd,P@ssw0rd
3. sas_repos_lts_202x.xx建立機器人帳戶 : sas-mirror-manager，永不到期、權限全選、紀錄token


***ansible內要設置的***
1. all.yaml內的檔案都需要改
2. host.ini內須改機器名稱

***Viya需要設置的***
1. /nfsshare01/sas_open_access放置python版本
2. images.txt內k8s版本需改成客戶版本
3. unzip的檔案須放置lts_xxx.xx內