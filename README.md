### Base on
https://github.com/ptrofimov/beanstalk_console

### Run as a Docker container
```shell
docker run -d -p 80:80 \
    --name beanstalk_console \
    -e APACHE_PORT=80
    -e BEANSTALKD_HOST=beanstalkd
    -e BEANSTALKD_PORT=11300
    ohmcoe/beanstalk_console
```
