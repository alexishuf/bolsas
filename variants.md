---
title: Aspectos da resolução de distribuíção de bolsas
author: Student

---
## Aspectos

### Dinamismo do Ranking

O ranking de bolsas, deve ser **recomputado** conforme alunos realizam atividades que atribuem pontuação (e.g., publicações, prêmios, ...)?

1. **Estático** (computado no momento da seleção) <br>
   [Diff na redação dos discentes](https://github.com/alexishuf/bolsas/commit/e410b6549a9870819159644a45591403df5af88c?diff=split)
2. **Dinâmico** dentro de uma **janela** de tempo <br>
   [Proposta dos discentes: janela é o período de ingresso do edital](https://github.com/alexishuf/bolsas/blob/master/redacao.txt)
3. **Dinâmico** sem janela de tempo
4. **Dinâmico**, **zerando** a pontuação da seleção (todos são iguais)
5. Outro: _____

### Dinamismo por modalidade

1. O ranking dinâmico deve se aplicar apenas ao **doutorado** <br>
   [Proposta dos discentes](https://github.com/alexishuf/bolsas/blob/master/redacao.txt)
2. O ranking dinâmico deve se aplicar apenas ao **mestrado** <br>
   [Diff na redação dos discentes](https://github.com/alexishuf/bolsas/commit/5e81dca7e2e9d9ad04b9e5097852deffa57dbee6?diff=split)
3. O ranking dinâmico deve se aplicar a **ambas** modalidades <br>
   [Diff na redação dos discentes](https://github.com/alexishuf/bolsas/commit/05ae5eaad2a3c2f12442c61573e575fef3294246?diff=split)
4. Outro: _____

### Re-usar critérios da seleção

1. Uso integral do ranking de seleção <br>
   [Diff na redação dos discentes](https://github.com/alexishuf/bolsas/commit/722b8c75492a22fc6acc816053c190e8ba9deaef?diff=split)
2. Uso apenas de critérios mecanizáveis <br>
   [Proposta dos discentes](https://github.com/alexishuf/bolsas/blob/master/redacao.txt)
3. Uso apenas de critérios relativos a publicação <br>
   [Diff na redação dos discentes](https://github.com/alexishuf/bolsas/commit/8f80d795c40d21d0ef7f5271fd84ae165607739d?diff=split)
4. Criar novos critérios para o ranking
5. Outro: _____

### Solicitação tardia de bolsa dentro do período

O aluno cujo edital pelo qual foi aceito previa ingresso em um certo período (ex: 1º e 2º semestres de 2018) e o aluno não solicitou bolsa durante o processo seletivo. Agora ele solicita bolsa dentro do período de ingresso do edital (qualquer momento entre o resultado da seleção e 31/12/2018)

1. Aluno é inserido **antes** de qualquer aluno ingressante no mesmo período <br>
   ![exempplo](imgs/tardio2-antes_ingresso.png)
2. Aluno é inserido como se tivesse solicitado bolsa **durante** a seleção <br>
   [Proposta dos discentes](https://github.com/alexishuf/bolsas/blob/master/redacao.txt) <br>
   ![exempplo](imgs/tardio2-ingresso.png)
3. Aluno é inserido **após** todos os alunos ingressante no mesmo período <br>
   [Diff na redação dos discentes](https://github.com/alexishuf/bolsas/commit/4152370305809681436d7cc2939abf06e0232e7f?diff=split) <br>
   ![exempplo](imgs/tardio2-apos_ingresso.png)
4. Outro: _____


### Solicitação tardia de bolsa

O aluno cujo edital pelo qual foi aceito previa ingresso em um certo período (ex: 1º e 2º semestres de 2018) e o aluno não solicitou bolsa durante o processo seletivo. Agora ele solicita bolsa **após o período de ingresso do edital**, ou seja, após 1/1/2019 se o período do edital era o **ano** de 2018.

1. Aluno é inserido como se tivesse solicitado **durante** o processo seletivo <br>
   [Diff na redação dos discentes](https://github.com/alexishuf/bolsas/commit/e3fd8ef66afc6b40554eea09c06fd1be5a745151?diff=split) <br>
   ![exempplo](imgs/tardio-ingresso.png)
2. Aluno é inserido **após** os alunos do seu período de **ingresso** <br>
   [Diff na redação dos discentes](https://github.com/alexishuf/bolsas/commit/fcd3a546c8e30d1005cfb84d6d03bdc7a6dfdbec?diff=split) <br>
   ![exempplo](imgs/tardio-apos_ingresso.png)
3. Aluno é inserido **antes** dos alunos do período **corrente** <br>
   [Diff na redação dos discentes](https://github.com/alexishuf/bolsas/commit/6be5675ded1122f3907c72d4c311c99d4f5acd94?diff=split) <br>
   ![exempplo](imgs/tardio-antes_atual.png)
4. Aluno é inserido **após** os alunos do período **corrente** <br>
   [Proposta dos discentes](https://github.com/alexishuf/bolsas/blob/master/redacao.txt) <br>
   ![exempplo](imgs/tardio-apos_atual.png)
5. Outro: _____

### Regularmente matriculado mas inapto ao recebimento de bolsa

Há uma bolsa disponível e pela fila um aluno **regularmente matriculado** foi selecionado para recebê-la. Por qualquer motivo que seja, o aluno não está apto a receber a bolsa (vínculo empregatício, em viagem, des-interesse temporário, discordância com regras do órgão de apoio, ou *não respondeu à notificação em X dias*)

1. Aluno é removido da fila.
2. Aluno permanece na fila. <br>
   [Proposta dos discentes](https://github.com/alexishuf/bolsas/blob/master/redacao.txt)
3. Aluno permanece na fila, mas na Xª notificação de bolsa disponível rejeitada é removido da fila
4. Após a primeira notificação rejeitada, o aluno pode permanecer rejeitando notificações por até X meses. Após esse prazo, uma notificação de bolsa não aceita implicará em sua remoção da fila.
5. Outro: _____


