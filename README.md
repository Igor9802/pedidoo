# Quiz Game

Um jogo de quiz desenvolvido em Python onde você pode testar seus conhecimentos gerais.

## Versões Disponíveis

O jogo está disponível em duas versões:
1. Versão Console (`quiz_game.py`)
2. Versão com Interface Gráfica (`quiz_game_gui.py`)

## Requisitos

- Python 3.6 ou superior
- Tkinter (já incluído na instalação padrão do Python)

## Como Jogar

### Versão Console
1. Execute o arquivo `quiz_game.py`:
   ```
   python quiz_game.py
   ```
2. Responda às perguntas digitando o número correspondente à sua resposta (1-4)

### Versão com Interface Gráfica
1. Execute o arquivo `quiz_game_gui.py`:
   ```
   python quiz_game_gui.py
   ```
2. Clique nos botões para selecionar suas respostas

## Características

- Perguntas aleatórias
- Sistema de pontuação
- Feedback imediato sobre respostas corretas e incorretas
- Interface amigável (versão GUI)
- Design moderno e responsivo (versão GUI)

## Personalização

Você pode adicionar mais perguntas editando a lista `questions` no arquivo desejado. Cada pergunta deve seguir o formato:

```python
{
    "pergunta": "Sua pergunta aqui?",
    "opcoes": ["Opção 1", "Opção 2", "Opção 3", "Opção 4"],
    "resposta_correta": "Opção correta"
}
``` 