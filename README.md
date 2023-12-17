# Simple Online Shop Application

## Project was built using Python&Django

### You can see used libraries inside requirements.txt file


### How to run program

```bash
    git clone https://github.com/Jumanazarov-Shukrullo/myshop.git
```

```bash
   python3 -m venv venv 
```

```bash 
   source venv/bin/activate
```

```bash 
   pip install -r requirements.txt
```

> :warning: **Docker should be installed**: Install docker!

```bash 
   sudo docker run -it --rm --name redis -p 6379:6379 redis
```



```bash 
   sudo docker run -d --name some-rabbit -p 5672:5672 -p 5673:5673 -p 15672:15672 rabbitmq:3-management
```

```bash
    celery -A myshop worker -l info
```
```bash
  stripe listen --forward-to localhost:8000/payment/webhook/
```

