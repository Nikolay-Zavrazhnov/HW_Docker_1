
## 1. Building image

```
docker build ./3.2-crud  --tag=stocks_products:0.1
```

## 2. Running the container

```
docker run --name=test_stocks_products -d -p 8000:8000 stocks_products:0.1
```
