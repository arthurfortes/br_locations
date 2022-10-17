`br_locations`` - Cities and States of Brazil Python Lib (IBGE Info)
#######################################################


Description
***********

Cities and States of Brazil Python Lib  based on IBGE Info.


Requirements
************

::

    Python 3


Install:
########

::

    pip install br_locations


Usage
#####

>>> from br_locations.base import br_locale_info

list_states (@property)
*********************
Returns a list of all states in alphabetical order (abbreviations)

|

Syntax:

- br_locale_info.list_states

|

*Exemple:*

>>> print (br_locale_info.list_states)
['AC', 'AL', 'AM', 'AP', 'BA', 'CE', 'DF', 'ES', 'GO', 'MA', 'MG', 'MS', 'MT',
 'PA', 'PB', 'PE', 'PI', 'PR', 'RJ', 'RN', 'RO', 'RR', 'RS', 'SC', 'SE', 'SP', 'TO']

----

list_all_cities (@property)
*********************
Returns a list of all cities in all states

|

Syntax:

- br_locale_info.list_all_cities

|

*Exemple:*

>>> print (br_locale_info.list_all_cities)
[['Acrelândia', 'Assis Brasil', 'Brasiléia', 'Bujari', 'Capixaba', 'Cruzeiro do Sul', 'Epitaciolândia', ...]


----

list_cities (method)
*******************
Returns a list of all cities in a state.

|

Syntax:

- br_locale_info.list_cities('XX'),
- br_locale_info.list_cities(abbr='XX'),
- br_locale_info.list_cities(code='NN')

|

where:


abbr = State abbreviation, e.g.: São Paulo = SP, Rio de Janeiro = RJ
code = State code at IBGE, e.g.: Amapá = 12,  Acre = 16

|

*Exemple:*

>>> print(br_locale_info.list_cities('AC'))
['ACRELÂNDIA', 'ASSIS BRASIL', 'BRASILÉIA', 'BUJARI', 'CAPIXABA', 'CRUZEIRO DO SUL', ...]

------


Lib Dev Information
#####

:Authors:
    Arthur Fortes

:Version: 0.0.0 of 10/2022
