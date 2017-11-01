# Docker-rails

## Clone source

* Clone with SSH: <br>
```
git clone git@github.com:saiury92/docker-rails.git /path/to/docker-rails
```
* Clone with HTTPS: <br>
```
git clone https://github.com/saiury92/docker-rails.git /path/to/docker-rails
```

## Create new rails app

* Nếu máy bạn cài sẵn rails
```
cd /path/to/docker-rails && rails new rails_app
```

* Nếu máy bạn không cài rails
```
cd /path/to/docker-rails && git checkout app_exist
```

## Build image demo

```
docker build -t demo .
```
## Run a new container with name is hello

```
docker run -it --name hello demo
```
