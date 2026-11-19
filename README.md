# Sudoku

Jogo de Sudoku com dificuldade progressiva, num único arquivo. Abra `index.html` no navegador.

- Toque numa casa e escolha o número na fileira inferior (1–9).
- Cada número de 1 a 9 tem uma cor própria. Os avisos aparecem na cor de fundo da casa.
- Número proibido (repetido na linha, coluna ou bloco): casa com fundo vermelho.
- Quando os 9 de um número estão no tabuleiro, as casas dele ficam com fundo verde e o botão ganha ✓.
- O botão 💡 Solução (toque duas vezes para confirmar) corrige os números errados (fundo laranja) e completa o resto (fundo roxo), mostrando a lógica de cada número: a varredura da linha, coluna e bloco que elimina os outros candidatos, ou o único lugar onde o número cabe. Durante a animação o botão vira ⏩ Rápido e depois ⏭ Pular.
- Ao completar um puzzle, o tabuleiro comemora, se limpa e passa para o próximo nível. O jogo sempre começa no nível 1, e os botões ◀ e ▶ acima do tabuleiro voltam ou avançam um nível.
- A dificuldade de cada nível é medida pelo raciocínio que o puzzle exige (como uma pessoa resolveria):

  | Nível | Dificuldade | O que o puzzle exige |
  |---|---|---|
  | 1–3 | Fácil | só "único número possível na casa" (45 → 39 pistas) |
  | 4–6 | Médio | também "único lugar na linha/coluna/bloco" (35 → 29 pistas) |
  | 7–8 | Difícil | candidatos travados entre bloco e linha/coluna |
  | 9–10 | Muito difícil | pares e trios de candidatos |
  | 11+ | Especialista | técnicas ainda mais avançadas |

  Os puzzles são gerados em segundo plano (Web Worker), e o próximo nível já fica pronto enquanto se joga.
- Cada puzzle começa mostrando o nível no centro do tabuleiro, seguido de "Iniciar!". Depois o puzzle se desenha em espiral, do centro para fora.
