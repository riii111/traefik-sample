# Traefikお試し

TraefikでNextCloudを構築してみた

## Traefik - Dashboard
![image](https://github.com/user-attachments/assets/b1bb8519-9dc8-4b19-8a2d-a0b15a62396b)

## NextCloud
![image](https://github.com/user-attachments/assets/39ffa296-cf75-4290-af32-ba0d66394d63)


## 備考

以下のように指定してシークレットファイルを作成してください

```
echo "XXXXX" > ${HOME}/nextcloud_secrets/.MYSQL_DATABASE
echo "your-user" > ${HOME}/nextcloud_secrets/.MYSQL_USER
echo "your-password" > ${HOME}/nextcloud_secrets/.MYSQL_PASSWORD
echo "your-root-password" > ${HOME}/nextcloud_secrets/.MYSQL_ROOT_PASSWORD
```
