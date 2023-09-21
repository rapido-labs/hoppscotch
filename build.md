# Build Hoppscotch images locally 
```
cp .env.example .env
docker build --target backend -t asia.gcr.io/staging-host-12358/hoppscotch-backend:2023.8.1 . -f prod.Dockerfile
docker build --target app -t asia.gcr.io/staging-host-12358/hoppscotch-frontend:2023.8.1 . -f prod.Dockerfile
docker build --target sh_admin -t asia.gcr.io/staging-host-12358/hoppscotch-admin:2023.8.1 . -f prod.Dockerfile
```


