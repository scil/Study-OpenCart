
# ����nginx��ֱ���� php-fpm ͨ��
```
# ���޸�����ĵ�ַ
./cgi.sh
```

# ʹ��nginx�����У�����nginx����

```
# run nginx:
cd  /vagrant/www/opencart/  &&  sudo nginx -c `pwd`/nginx/nginx-site.conf -p "`pwd`"
# then:
curl localhost:8080/install
```

