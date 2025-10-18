# ⚔️ Jogo de Batalha RPG (Python)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

Um simples jogo de batalha em turnos, estilo RPG, desenvolvido inteiramente em Python. Este projeto foi criado para demonstrar e praticar conceitos fundamentais de **Programação Orientada a Objetos (OOP)**.

 
## 💡 Conceitos Demonstrados

O foco principal deste projeto é a aplicação correta da Programação Orientada a Objetos.

* **Classes e Objetos:** O código é estruturado em classes (`Personagem`, `Heroi`, `Inimigo`, `Jogo`) que modelam as entidades do jogo.
* **Herança:** As classes `Heroi` e `Inimigo` herdam da classe base `Personagem`, reutilizando atributos (`nome`, `vida`, `nivel`) e métodos (`atacar`, `receber_ataque`).
* **Encapsulamento:** Atributos principais (como `__nome` e `__vida`) são definidos como privados, com seus valores acessados através de métodos *getters* (`get_nome()`, `get_vida()`).
* **Polimorfismo:** O método `exibir_detalhes()` é implementado na classe mãe (`Personagem`) e sobrescrito (overridden) nas classes filhas (`Heroi` e `Inimigo`) para adicionar comportamentos específicos (como exibir a "Habilidade" ou o "Tipo").
* **Composição:** A classe `Jogo` "tem" (é composta por) uma instância de `Heroi` e uma de `Inimigo`, orquestrando a batalha.

## 🛠️ Tecnologias Utilizadas

* **Python 3**
* Módulo `random` (da biblioteca padrão do Python) para calcular o dano.

## 🚀 Como Rodar

1.  Clone este repositório:
    ```bash
    git clone [https://github.com/arthurluna05/python-rpg-batalha.git](https://github.com/arthurluna05/python-rpg-batalha.git)
    ```
2.  Navegue até a pasta do projeto:
    ```bash
    cd python-rpg-batalha
    ```
3.  Execute o script Python:
    ```bash
    python jogo.py
    ```
    *(Se `python` não funcionar, tente `python3 jogo.py`)*

4.  Siga as instruções no terminal para jogar!

## 👨‍💻 Autor

Feito por **Arthur Luna**.

* [GitHub](https://github.com/arthurluna05)
* [LinkedIn](https://linkedin.com/in/seu-usuario-aqui) *(Substitua pelo seu LinkedIn!)*
