### Yarn comands
yarn dev

yarn build

### Adding dev dependencies
yarn add package-name -D

### Listar imagens
docker images

### Remover imagens
docker rmi image-id -f

### Baixar a imagem do Mongo
docker pull mongo

### Criar o container do Mongo
docker run -d -p 27017:27017 -e AUTH=no mongo