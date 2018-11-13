## 目录结构
```
.
├── app
│   └── info.php
├── files
│   ├── docker-compose.yml
│   ├── nginx
│   │   ├── conf.d
│   │   │   └── default.conf
│   │   ├── dockerfile
│   │   └── nginx.conf
│   └── php
│       ├── dockerfile
│       ├── php-dev.ini
│       ├── php-fpm.conf
│       ├── php.ini
│       └── pkg # 这里可以放自己想多加的拓展，我放了redis
│           └── redis.tgz
└── logs
    ├── nginx
    │   └── error.log
    └── php
```

