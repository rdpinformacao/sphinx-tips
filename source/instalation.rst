exemplo de formatação da documentação no Sphinx(título nível 1)
==================================================================

Exemplos de formatações utilizando markdown (título nível 2)
--------------------------------------------------------------------


Exemplo de títulos:

# Título nível 1 <h1>
## Título nível 2 <h2>
### Título nível 3 <h3>
#### Título nível 4 <h4>
##### Título nível 5 <h5>
###### Título nível 6 <h6>


Colocando texto em negrito:

**Texto em negrito pra destacar alguma palavra**


*Texto em Itálico pra destacar alguma palavra*


Caso seja necessário colocar um comando dentro de um box, faça desta forma:

::
	
	sudo apt-get update
	
::

	apt-get install nmap	


Adicionar listas, faça dessa forma:

1. Item 1
2. Item 2
3. Item 3

Caso necessário colocar uma tabela faça dessa forma:

Alinhado a esquerda | Centralizado | Alinhado a direita
:--------- | :------: | -------:
Valor | Valor | Valor



`google <http://google.com.br>`_



Adicionando BOX (título nível 2)
------------------------------------------------

.. warning::
	         
			 Esta é a maneira para utilizar um !warning na sua documentação sphinx, como maneira de alertar alguma situação.
	
.. caution::
             
			 Esta é a maneira para utilizar um !warning na sua documentação sphinx, como maneira de alertar alguma situação.
			
.. note::
           
		   Esta é a maneira para utilizar uma nota na sua documentação sphinx.
	

.. danger::
            
			Esta é a maneira para expressar algo que pode oferecer danos, indisponibilidades, etc.

.. error::
           
		   Esta é a maneira para utilizar uma descrição de possíveis erros 

.. important::
               
			   Esta é a maneira para utilizar uma descrição  que julgue importante.

.. tip::
         
		 Esta é a maneira para utilizar dica  que julgue importante.  
