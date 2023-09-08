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

rails db:create para crear la db

rails db:seed para inicializar el usuario por defecto


acto seguido 

rails s para iniciar el servidor 

y se puede iniciar por localhost:3000

y el endpoint de fifo se encuentra en
post localhost:3000/api/v1/fibo

y en un json 

n=3

actualmente posee un panel de administracion que seria con la gema

active admin similar al admin de django

y para la seguridad del endpoint tiene un token de usuario

anexo en una carpeta llamada imagen en la raiz los datos del postman y del admin

el archivo .env seria las claves de mi postgres alojado localmente
