# Commands - Online Shopping Protal

1. Cloning Repository
    ```powershell
    git clone REPOSITORY
    ```

2. Installing Docker and Docker Compose
    ```powershell
    chmod +x docker_installation.sh
    ./docker_installation.sh
    sudo usermod -aG docker $USER
    sudo systemctl start docker
    ```

3. Building Dockerfile
    ```powershell
    docker build -t online_shop:v1 .
    docker tag -t sumit2703/online-shop
    docker push sumit2703/online-shop
    ```
4. Implementing Docker Compose
    ```powershell
    docker-compose up -d
    ```
5. Using Docker Scout
    ```powershell
    docker scout cves online_shop:v1 --format markdown >> image_report.md
    ```
6. Testing and Checking

---
