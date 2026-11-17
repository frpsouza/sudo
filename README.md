# Sudoku

Jogo de Sudoku com dificuldade progressiva, num único arquivo. Abra `index.html` no navegador.

- Toque numa casa e escolha o número na fileira inferior (1–9).
- Cada número de 1 a 9 tem uma cor própria. Os avisos aparecem na cor de fundo da casa.
- Número proibido (repetido na linha, coluna ou bloco): casa com fundo vermelho.
- Quando os 9 de um número estão no tabuleiro, as casas dele ficam com fundo verde e o botão ganha ✓.
- O botão 💡 Solução (toque duas vezes para confirmar) corrige os números errados (fundo laranja) e completa o resto (fundo roxo), mostrando a lógica de cada número: a varredura da linha, coluna e bloco que elimina os outros candidatos, ou o único lugar onde o número cabe. Durante a animação o botão vira ⏩ Rápido e depois ⏭ Pular.
- Ao completar um puzzle, o tabuleiro comemora, se limpa e passa para o próximo nível. A cada nível há menos pistas: do Fácil (≈45 pistas) até o Muito difícil (≈25 pistas, a partir do nível 11). O nível fica salvo no navegador.
- Cada puzzle começa mostrando o nível no centro do tabuleiro, seguido de "Iniciar!". Depois o puzzle se desenha em espiral, do centro para fora.
