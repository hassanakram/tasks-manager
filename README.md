# Tasks Manager App
Test App for Tasks Manager

### Setup

```bash
git clone git@github.com:hussainakram/tasks-manager.git
cd tasks-manager
```

### Check your Ruby and rails version

```shell
ruby -v
```
The output should be like **ruby 2.7.2**

```shell
rails -v
```
The output should be like **Rails 6.1.3.2**

### Install dependencies

Install [PostgreSQL](https://www.postgresql.org/download/)

Using [Bundler](https://github.com/bundler/bundler) and [Yarn](https://github.com/yarnpkg/yarn):

```shell
bundle && yarn
```

### Initialize the database

```shell
rails db:create db:migrate db:seed
```

### Serve

```shell
rails s
```
