# Instashell v1.5.4

Instashell é um Shell Script para executar ataques de força bruta multithread contra o Instagram; esse script pode ignorar
limite de login e ele pode testar um número infinito de senhas com uma taxa de +400 senhas / min usando 20 threads.

## Contrato:
O uso do InstaShell para atacar alvos sem consentimento mútuo prévio é ilegal. É de responsabilidade do usuário final
obedecer a todas as leis locais, estaduais e federais aplicáveis. Os desenvolvedores não assumem nenhuma responsabilidade e não são responsáveis por nenhum
uso indevido ou danos causados por este programa

![isntashell](https://user-images.githubusercontent.com/15244775/68085529-97298500-fe20-11e9-9b59-5e0b82565cab.png)

### Recursos
- Multi-thread (400 pass/min, 20 threads)
- Salve/Resume sessions
- Anonymous attack through TOR
- Check nomes de usuário válidos
- Lista de senhas padrão (best +39k 8 letters)
- Verifique e instale todas as dependências

### Uso:
```
git clone https://github.com/marrocamp/instashell
cd instashell
chmod +x instashell.sh
service tor start
sudo ./instashell.sh
```

### Requisitos de instalação (Curl, Tor, Openssl):

```
chmod +x install.sh
sudo ./install.sh
```

### Como funciona?

O script usa um Android ApkSignature para executar a autenticação, além de usar o TOR e girar o endereço IP para
evitar bloquear.
O script usa o algoritmo py-Instagram


