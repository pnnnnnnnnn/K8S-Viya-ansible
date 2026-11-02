***Harbor需要設置的***
1. Harbor需間建立兩個專案名稱 : sas_repos_lts_202x.xx、base
2. 新增使用者 : sas,sas@example,sas,P@ssw0rd,P@ssw0rd
3. sas_repos_lts_202x.xx建立機器人帳戶 : sas-mirror-manager，永不到期、權限全選、紀錄token




***ansible內要設置的***
2. images.txt內k8s版本需改成客戶版本