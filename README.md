# Configuração do ambiente de desenvolvimento

# Dependencias Ubuntu 20.04.5 LTS

```bash
sudo apt install curl git
```

# Instalação ASDF

[Repositório asdf](https://github.com/asdf-vm/asdf)

```bash
git clone https://github.com/asdf-vm/asdf.git ~/.asdf --branch v0.10.2
```

# NodeJS

[Repositório asdf-nodejs](https://github.com/asdf-vm/asdf-nodejs)

```bash
asdf plugin add nodejs https://github.com/asdf-vm/asdf-nodejs.git
```

```bash
asdf nodejs update-nodebuild
```


# PHP

[Repositório asdf-php](https://github.com/asdf-community/asdf-php)

```bash
sudo apt-get install -y autoconf bison build-essential curl gettext git libgd-dev libcurl4-openssl-dev libedit-dev libicu-dev libjpeg-dev libmysqlclient-dev libonig-dev libpng-dev libpq-dev libreadline-dev libsqlite3-dev libssl-dev libxml2-dev libzip-dev openssl pkg-config re2c zlib1g-dev
```

```bash
asdf plugin-add php https://github.com/asdf-community/asdf-php.git
```

```bash
asdf install php 8.4.2
```

```bash
asdf install php 8.3.15
```

```bash
asdf install php 8.2.27
```

```bash
asdf install php 8.1.31
```

```bash
asdf install php 8.0.30
```

```bash
asdf install php 7.4.33
```
[Fix error Install PHP 7.4 openssl version 1.1.1i](https://github.com/asdf-community/asdf-php/issues/131)

# Java

[Repositório asdf-java](https://github.com/halcyon/asdf-java)

```bash
asdf plugin-add java https://github.com/halcyon/asdf-java.git
```

```bash
asdf install java openjdk-19
```

# Pnpm

[Repositório asdf-pnpm](https://github.com/jonathanmorley/asdf-pnpm)

```bash
asdf plugin add pnpm https://github.com/jonathanmorley/asdf-pnpm.git
```

```bash
asdf install pnpm latest
```
