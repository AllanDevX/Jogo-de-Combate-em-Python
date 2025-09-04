 🛡️ Batalha RPG em Python

Este é um projeto simples de RPG em Python que simula uma batalha entre um herói e um inimigo. O jogador controla o herói e pode escolher entre ataques normais ou especiais para derrotar o inimigo em turnos.

🎮 Funcionalidades

- Sistema de combate por turnos
- Ataques normais com dano aleatório baseado no nível
- Ataque especial com dano fixo
- Exibição de detalhes dos personagens
- Lógica de vitória e derrota

 🧠 Estrutura do Código

O projeto é composto por quatro classes principais:

| Classe      | Descrição                                                                 |
|-------------|---------------------------------------------------------------------------|
| `Personagem`| Classe base para todos os personagens. Contém atributos como nome, vida e nível. |
| `Heroi`     | Herói controlado pelo jogador. Possui uma habilidade especial.            |
| `Inimigo`   | Inimigo controlado pelo sistema. Possui um tipo (ex: voador, terrestre).  |
| `Jogo`      | Classe que gerencia a batalha e a interação entre os personagens.         |

 📦 Requisitos

- Python 3.x
- Nenhuma biblioteca externa é necessária
 
🚀 Como executar

1. Clone ou baixe este repositório
2. Execute o arquivo principal:

bash
python nome_do_arquivo.py


3. Siga as instruções no terminal para jogar

✨ Exemplo de Gameplay


Iniciando a batalha...

Detalhes dos Personagens:
Nome: Heroi
Vida: 100
Nivel: 5
Habilidade: Super Força

Nome: Morcego
Vida: 80
Nivel: 5
Tipo: voador

Escolha (1 - Ataque Normal, 2 - Ataque Especial):


## 🛠️ Melhorias Futuras

- Adicionar múltiplos inimigos
- Sistema de experiência e evolução de nível
- Interface gráfica com `tkinter` ou `pygame`
- Inventário e itens de cura
📄 Licença

Este projeto é livre para uso educacional e pessoal. Sinta-se à vontade para modificar e expandir!
