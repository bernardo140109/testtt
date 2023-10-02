## Installation tutorial WoofedCRM

#### Requeriments for project:

> python 2.7.13
> ruby 3.0.0
> nodejs 16.16.0

#### 1 - Clone repository:
```
git clone https://github.com/douglara/woofed-crm.git
cd woofed-crm
```
#### 2 - Install dependencies:
```
bundle install
yarn build
```

#### 3 - Create .env file:
```
cp .env.sample .env
```
#### 4 - Up containers:
```
docker-compose up -d
```
#### 5 - Configure database:
```
rails db:create
rails db:migrate
rails db:seed
```

#### 6 - Start applications:
```
./bin/dev
```
###### Access `http://127.0.0.1:3001` and use user `user1@email.com` password: `123456`
