# how-to-install-erlang-ubuntu
how to install erlang ubuntu


## Step 1: Import Erlang GPG Key
```
wget -O- https://packages.erlang-solutions.com/ubuntu/erlang_solutions.asc | sudo apt-key add -
```

## Step 2: Add the Erlang Repository to Ubuntu 20.04
```
echo "deb https://packages.erlang-solutions.com/ubuntu focal contrib" | sudo tee /etc/apt/sources.list.d/rabbitmq.list
```

## Step 3: Install Erlang
```
sudo apt update
sudo apt install erlang
```

## Step 4: Check isSucces
```
erl --version
```
