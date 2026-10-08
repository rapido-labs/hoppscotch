# Build Hoppscotch images locally
```
cp .env.example .env
docker build --platform linux/amd64 --target backend -t asia.gcr.io/staging-host-12358/hoppscotch-backend:2023.8.4 . -f prod.Dockerfile
docker build --platform linux/amd64 --target app -t asia.gcr.io/staging-host-12358/hoppscotch-frontend:2023.8.4 . -f prod.Dockerfile
docker build --platform linux/amd64 --target sh_admin -t asia.gcr.io/staging-host-12358/hoppscotch-admin:2023.8.4 . -f prod.Dockerfile
```
