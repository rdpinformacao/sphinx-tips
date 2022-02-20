
------------------------------------------------------------------------------------


# sphinx-tips

Repositório criado para mostrar como subir documentações com sphinx-theme.
No exemplo abaixo a execução ocorre no ambiente Centos release 7.9.2009 (Core) (RedHat)

Obs: Vamos executar  alguns passos no virtualenv para evitar problemas.

## Necessário executar a instalação ( NO CENTOS ) dos seguintes componentes antes de inciar:


###  Para clonar o repositório e obter o arquivo requirements.txt, é necessário instalar o git:

``` 
  sudo yum install git -y
```


### Instalar o python3 e pip3 caso não tenha instalado:
``` 
  sudo yum install python3 -y
``` 

```
  sudo yum install python3-pip -y 
```
 
 
 ## Agora precisamos iniciar um virtualenv, com usuário (não root) e no diretorio home deste mesmo usuário, faça:
 
``` 
  pip3 install  virtualenv --user
```
``` 
  virtualenv myenvworksphinx
```
``` 
  source myenvworksphinx/bin/activate
```
``` 
  pip3 install --upgrade setuptools;
```

 
###  Ainda no virtualenv , é necessário efetuar a instalação do(s) componente(s) via pip3. Será feito da seguinte maneira (utilize o arquivo "requiriments.txt" disponibilizado neste repositório):
 
 
```
  pip3 install -r requirements.txt
``` 
   
   
   
----------------------------------------------------------------------------------
