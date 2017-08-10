# Dummy http forward proxy

## Usage

1. Install requirements.

- docker
- docker-compoase

2. Start the container


```
cd /path/to/clone
docker-compose up
```

3. Change your hosts file

Change your hosts file to override the http-proxy IP address.
For example:


```
127.0.0.1 localhost proxy.example.com
```

