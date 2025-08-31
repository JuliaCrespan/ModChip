# ModChip
Modchip em verilog em uma CPU simples
Nos anos 2000, os modchips ficaram famosos em consoles como o PlayStation 2, onde eram usados para burlar restrições e permitir rodar jogos piratas.
Na prática, esses circuitos faziam algo simples e poderoso: interceptavam sinais do processador e da ROM, alterando instruções em tempo real.

Neste projeto, recriei esse conceito em Verilog de forma didática:

PC (Program Counter): conta os endereços sequenciais.

ROM: entrega instruções originais (simuladas como o valor do PC).

Modchip: quando ativado, altera as instruções antes de chegarem ao processador.

📊 No GTKWave é possível ver:

O PC contando normalmente (pc_addr).

A ROM entregando as instruções originais (rom_instr).

O modchip modificando essas instruções (instr_mod) quando habilitado.

Esse trabalho mostra como conceitos clássicos de hardware e arquitetura digital podem ser aplicados em simulações modernas, além de resgatar uma parte curiosa da história dos videogames.
link da simulação aqui: https://www.edaplayground.com/x/Tu2Z
