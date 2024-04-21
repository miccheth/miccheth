<h2 align="center">Me</h2>

```python
from typing import Tuple, List, Dict

class micch:
    pass

class Attributes(micch):
    @property
    def contact(self) -> Tuple[str, str, str]:
        email    = "pm@micch.dev"
	    
	    return email

    @property
    def life(self) -> Tuple[List[str], List[str], int]:
        langs = ['Italian', 'English']
        passions = ['science', 'computer-science', 'tech', 'sport']
        age   = 21
		
        return langs, passions, age
	
    @property
    def coding(self) -> Tuple[Dict[str, List[str]], List[str], List[str], Dict[str]]:
        langs = {
            'expert'      : none,
            'intermediate': ['python', 'java'],
            'learning'    : ['c', 'c++', 'go', 'julia', 'rust']
        }
        specialities  = none
        ide           = ['vscode', 'pycharm-community', 'idea-community']
        pc            = {
            'Windows': {
                'custom': {
                    'processor': 'I5 7500 | 4 cores :(',
                    'ram'      : '16gb',
                    'gpu'      : 'GTX 1050 ti'
                }
            }
        }

	return langs, specialities, ide, pc
