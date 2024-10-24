### os arquivos que estão dentro de ./src não foi desenvolvido por mim, é basicamente o laravel que foi gerado dentro do container e trouxe para a pasta ./src; 

### Caso queira testar, pode fazer um git clone neste repositório e exectar o comando no mesmo diretório que está o arquivo docker-compose.yaml:

```bash
docker-compose run --rm composer create-project --prefer-dist laravel/laravel . 
```

### que este comando vai fazer a criação e a instalação das dependência do laravel; 
