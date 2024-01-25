# Blockchain Tabanlı API

Bu proje, Hyperledger Fabric blockchain teknolojisini kullanarak bir blockchain ağı üzerinde işlem yapan bir API oluşturmayı amaçlar. API, varlık transfer işlemlerini gerçekleştiren akıllı kontrat içerir. API, gateway aracılığıyla akıllı kontrata bağlanır ve işlemler gerçekleştirilir.

## Başlangıç

Aşağıdaki adımları takip ederek projeyi ayağa kaldırabilirsiniz.

### Önkoşullar

- [Docker](https://www.docker.com/get-started) ve [Docker Compose](https://docs.docker.com/compose/install/) yüklü olmalıdır.
- Hyperledger Fabric için test ağı konfigürasyonu. (önemli)

### Kurulum

1. Proje dosyalarını bilgisayarınıza indirin.

    

2. Proje dizinine gidin.

    ```bash
    cd blockchain-rest-api
    ```

3. Docker compose ile ağı ayağa kaldırın.

    ```bash
    docker-compose up -d
    ```

4. API'yi başlatın.

    ```bash
    npm install
    npm start
    ```

5. API şimdi `http://localhost:3000` üzerinden erişilebilir durumda.

## Kullanım

API'ye erişmek ve blockchain üzerinde işlemler yapmak için demo.http dosyasını inceleyin.

## Lisans

Bu proje [MIT lisansı](LICENSE) altında lisanslanmıştır.
