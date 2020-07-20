# Início do lab
Faça o upload dos scripts para o servidor.

**Ps:** Em ambos os scripts têm uma variável chamada “IP”.

**Ps:** Esta variável deve ser o ip da maquina que ira ser utilizada como teste.

**Ps:** Se o ambiente for na AWS deixe a variavel como localhost.

### Versão do SO
Distributor ID: Ubuntu
Description:    Ubuntu 18.04.4 LTS
Release:        18.04
Codename:       bionic

### Script de recovery do SO
O script foi criado com Shell Script.

Basicamente funciona via menu ou de forma expressa.

Basta dar permissão de execução
```bash
chmod 755 recovery_system.sh
```

E chamar conforme o exemplo abaixo:
```bash
./ recovery_system.sh
```
Se quiser apenas seguir com o recovery escolha a opção número 4.

#Exemplo:

 Recovery System

```bash
 Escolha as opcoes abaixo:

 Digite "1" para instalar os requisitos do app.
 Digite "2" para criar o bucket.
 Digite "3" para efetuar o deploy do app.
 Digite "4" para recovery completo de modo expresso.

 Digite "5" Para sair.

 (Case Sensitive) -->
```

### Script de deploy.
Basta dar permissão de execução

```bash
chmod 755 deploy.sh
```

E copiar para um diretório que esteja no path.
```bash
cp deploy.sh /usr/local/bin
```

Ele precisa estar acessível para o usuário travis.
