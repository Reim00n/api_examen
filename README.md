# README

Instalar ruby y ruby on rails 


```bash
sudo apt install git curl libssl-dev libreadline-dev zlib1g-dev autoconf bison build-essential libyaml-dev libreadline-dev libncurses5-dev libffi-dev libgdbm-dev
```


```bash
curl -fsSL https://github.com/rbenv/rbenv-installer/raw/HEAD/bin/rbenv-installer | bash
```


```bash
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
```


```bash
echo 'eval "$(rbenv init -)"' >> ~/.bashrc
```


```bash
source ~/.bashrc
```


```bash
rbenv install 3.0.1
```


```bash
rbenv global 3.0.1
```


```bash
gem install bundler
```

    

```bash
gem install rails -v 7.0.4
```


Para iniciar el servidor


entrar en una terminal en la raiz del proyecto y correr
bundle install

acto seguido 

rails s para iniciar el servidor 

y el endpoint de fifo se encuentra en
http://localhost:3000/api/v1/fibo?n=3

podrian usarse gemas que serian lo equivalente a librerias para 

agregar algun login en forma de endpoint y en algun formulario html 

una gema famosa para esto es devise y active admin
