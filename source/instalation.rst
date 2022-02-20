exemplo de formatação da documentação no Sphinx(título nível 1)
==================================================================


Exemplos de formatações utilizando markdown (título nível 2)
--------------------------------------------------------------------


Exemplo de níveis de títulos:


for subsections
--------------------

Este é um exemplo de subsections


for paragraphs
""""""""""""""""""

Este é um exemplo de paragraphs


with overline, for parts
###############################

Este é um exemplo de parts


with overline, for chapters
**********************************

Este é um exemplo de chapters




for subsubsections
^^^^^^^^^^^^^^^^^^^^

Este é um exemplo de subsubsections



for sections
=========================

Este é um exemplo de sections






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


Caso necessário colocar  tabelas faça dessa forma:


+------------------------+------------+----------+----------+
| Header row, column 1   | Header 2   | Header 3 | Header 4 |
| (header rows optional) |            |          |          |
+========================+============+==========+==========+
| body row 1, column 1   | column 2   | column 3 | column 4 |
+------------------------+------------+----------+----------+
| body row 2             | ...        | ...      |          |
+------------------------+------------+----------+----------+


=====  =====  =======
A      B      A and B
=====  =====  =======
False  False  False
True   False  False
False  True   False
True   True   True
=====  =====  =======





**Abaixo temos um exemplo de hiperlink**


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
