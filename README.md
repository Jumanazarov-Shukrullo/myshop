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

> :warning: **If you are using mobile browser**: Be very careful here!

docker run -it --rm --name redis -p 6379:6379 redis

docker run -d --name some-rabbit -p 5672:5672 -p 5673:5673 -p 15672:15672 rabbitmq:3-management  


celery -A myshop worker -l info
stripe listen --forward-to localhost:8000/payment/webhook/
