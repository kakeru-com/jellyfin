## 1　下準備
ディレクトリ内に tvshows　config moviesのフォルダを作成する

## 2　docker compose
docker composeを行う
`docker-compose up -d`

## 3　kubernetesでdeployとserviceの作成
`kubectl apply -f jellyfin-deployment.yaml`
`kubectl apply -f jellyfin-service.yaml`
