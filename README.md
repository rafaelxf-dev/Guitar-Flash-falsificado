# 🎸 Guitar Flash Falsificado (Python + Tkinter GUI)

Um clone interativo e funcional do clássico jogo rítmico *Guitar Flash*, desenvolvido do zero em Python utilizando a biblioteca gráfica **Tkinter** e gerenciamento de execução paralela com **Threads**.

---

## 📌 Funcionalidades e Mecânicas

- **Mecânica de Jogo Rítmica:** Notas coloridas descem em tempo real por 4 pistas distintas, exigindo reflexos e precisão nos botões correspondentes (`A`, `S`, `J`, `K`).
- **Sistema de Pontuação e Multiplicadores (Streak):** 
  - Acumulação de combo a cada nota acertada consecutivamente.
  - Multiplicadores de pontos dinâmicos (1X, 2X, 3X, 4X) ativados conforme o tamanho do combo atinge marcos de 10, 20 e 30 acertos.
- **Barra de Desempenho e Vida (*Rock Meter*):** Indicador visual lateral que monitora o desempenho do jogador (erros ou notas perdidas aumentam a penalidade, enquanto acertos recuperam a barra). O jogo é encerrado automaticamente se a barra esgotar.
- **Estatísticas Finais de Partida:** Ao término ou saída do jogo (`ESC`), o terminal exibe um relatório detalhado com a pontuação total, combo máximo, notas acertadas, erradas e perdidas.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Python 3
- **Interface Gráfica (GUI):** [Tkinter](https://docs.python.org/3/library/tkinter.html)
- **Concorrência:** `threading` para rodar o loop principal de animação e descida das notas sem congelar a janela de comandos.

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
Certifique-se de ter o Python 3 instalado no seu computador. Como o jogo utiliza exclusivamente bibliotecas nativas, **nenhuma instalação de pacotes externos via pip é necessária**.

### 1. Clonar o repositório
```bash
git clone https://github.com/rafaelxf-dev/Guitar-Flash-falsificado.git
cd Guitar-Flash-falsificado
```

### 2. Executar o jogo
Execute o script principal diretamente pelo terminal:

```
python guitar_flash.py
```

## 🎮 Controles do Jogo
- **Trilha 1 (Verde):** Tecla A
- **Trilha 2 (Vermelho):** Tecla S
- **Trilha 3 (Amarelo):** Tecla J
- **Trilha 4 (Azul):** Tecla K
- **Sair / Encerrar:** Tecla ESC
