# O que é API?
> API: Aplication Programming Interface (Interface de Programação de Aplicações)

É um conjunto de regras e definições que diferentes softwares usam entre si.

**É como um pedaço de código, um conector que deixa diferentes programas conversarem entre si**

Ao invés de entender tudo, os desenvolvedor a usam, na qual ela dá as regras de maneiras corretas de se comunicar com sistema e usar as informações que a API usar

![[funcionamentoAPI.png|600]]
## REST API
> É uma padronização que o navegador usa; a mais famosa atualmente
* Métodos HTTP
	* GET — Recuperar informações
	* POST — Cadastrar
	* PUT — Alterar
	* DELETE — Excluir

## JSON
> JavaScript Object Notation
 
É um formato de dados bastante utilizado por APIs para transferência de dados

Exemplo ([PokeAPI](https://pokeapi.co/api/v2/)):
```
URL: https://pokeapi.co/api/v2/pokemon/1/ — Bulbasaur

{

    "abilities": [

        {

            "ability": {

                "name": "overgrow",

                "url": "https://pokeapi.co/api/v2/ability/65/"

            },

            "is_hidden": false,

            "slot": 1

        },

        {

            "ability": {

                "name": "chlorophyll",

                "url": "https://pokeapi.co/api/v2/ability/34/"

            },

            "is_hidden": true,

            "slot": 3

        }

    ],

    "base_experience": 64,

    "cries": {

        "latest": "https://raw.githubusercontent.com/PokeAPI/cries/main/cries/pokemon/latest/1.ogg",

        "legacy": "https://raw.githubusercontent.com/PokeAPI/cries/main/cries/pokemon/legacy/1.ogg"

    },

    "forms": [

        {

            "name": "bulbasaur",

            "url": "https://pokeapi.co/api/v2/pokemon-form/1/"

        }

    ],

    "game_indices": [

        {

            "game_index": 153,

            "version": {

                "name": "red",

                "url": "https://pokeapi.co/api/v2/version/1/"

            }

        },

        {

            "game_index": 153,

            "version": {

                "name": "blue",

                "url": "https://pokeapi.co/api/v2/version/2/"

            }

        },

        {

            "game_index": 153,

            "version": {

                "name": "yellow",

                "url": "https://pokeapi.co/api/v2/version/3/"

            }

        },

        {

            "game_index": 1,

            "version": {

                "name": "gold",

                "url": "https://pokeapi.co/api/v2/version/4/"

            }

        },
      ]
	}
	(...)
}
```