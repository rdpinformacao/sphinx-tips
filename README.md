
------------------------------------------------------------------------------------


# sphinx-tips

Repositório criado para mostrar como subir documentações com sphinx-theme.
No exemplo abaixo a execução ocorre no ambiente Centos release 7.9.2009 (Core) (RedHat)

_Obs: Vamos executar  alguns passos no virtualenv para evitar problemas._

## Necessário executar a instalação ( Centos 7 ) dos seguintes componentes antes de inciar:


###  Para clonar o repositório e obter o arquivo requirements.txt, é necessário instalar o git:

``` 
  sudo yum install git -y
```


### Instalar o python3 e pip caso não tenha instalado:

``` 
  sudo yum install epel-release -y
``` 

``` 
  sudo yum install python3 -y
``` 

```
  sudo yum install python3-pip -y 
```
 
 
 ## Agora precisamos iniciar um virtualenv, com usuário (não root) e no diretorio /home/$USER deste mesmo usuário, faça:
 
``` 
  cd /home/$USER
```
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
  pip3 install --upgrade setuptools
```
 
 
###  Por fim, ainda no virtualenv, faça a instalação dos "requirements.txt" e gere os arquivos HTML da documentação citada neste projeto :
 
 
``` 
  cd /home/$USER
```

```
  git clone https://github.com/rdpinformacao/sphinx-tips.git
``` 

```
  cd sphinx-tips
```
 
```
  pip3 install -r requirements.txt
``` 

```
  make html
``` 
 
 
 _Obs: Os arquivos "html" da sua documentação estão na pasta build/_
 
 
----------------------------------------------------------------------------------
