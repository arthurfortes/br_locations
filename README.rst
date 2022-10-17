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

list_uf (@property)
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


:Authors:
    Arthur Fortes

:Version: 0.0.0 of 10/2022
