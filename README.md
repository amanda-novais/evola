<h1 align="center">Evola 🎯</h1>

<p align="center"><em>Do ponto A ao ponto B — transforma uma meta com prazo em micro-tarefas diárias.</em></p>

---

## 🎯 Objetivo do projeto

**O problema:** quase todo mundo já definiu uma meta com prazo ("aprender inglês até
dezembro", "correr 10 km em 3 meses") e travou na primeira semana. Não por falta de vontade,
mas porque o objetivo é grande demais para virar ação *hoje*. Falta a ponte entre onde a
pessoa está e onde ela quer chegar.

**A solução:** o Evola pede quatro informações — objetivo, nível atual, destino e prazo — e
devolve um plano quebrado em micro-tarefas diárias, com acompanhamento de progresso,
celebração de marcos e histórico do que já foi conquistado.

**Objetivos da aplicação**

- Reduzir a meta a uma única pergunta por dia: *"o que eu faço agora?"*
- Tornar o progresso visível, para sustentar a motivação ao longo do prazo
- Garantir acessibilidade real (WCAG 2.1 AA) em todas as telas

Fluxo: `Início → Plano → Dashboard → Tarefas → Celebração → Conquistas → Histórico`

## 🛠️ Tecnologias utilizadas

| Camada | Stack |
|---|---|
| Interface | HTML5 semântico · CSS3 (Flexbox, Grid, variáveis) |
| Interatividade | JavaScript ES6+, sem frameworks ou dependências |
| Design | Design System próprio · protótipo de média fidelidade em 7 telas |
| Acessibilidade | WCAG 2.1 AA · contraste medido de 4,6:1 a 13,8:1 |
| Versionamento | Git e GitHub |

Aplicação *standalone*: basta abrir o arquivo HTML no navegador, sem build ou instalação.
Layout desenhado para iPhone 16 Pro Max (430×932 pt).

## 🧠 O que aprendi

- **Protótipo não é enfeite.** O teste de usabilidade com 2 participantes apontou 3 ajustes
  que eu não teria enxergado sozinha — e todos foram implementados.
- **Acessibilidade se mede, não se afirma.** Passei a calcular o contraste componente a
  componente, em vez de confiar na aparência da paleta.
- **CSS sem framework ensina o fundamento.** Sem atalhos, tive que entender box model,
  cascata e responsividade de verdade.
- **Documentar o processo vale tanto quanto o código.** Persona, jornada e decisões de
  design são o que tornam a solução defensável para outra pessoa.

---

<p align="center">
  Feito por <strong>Amanda Novais</strong> ·
  <a href="https://www.linkedin.com/in/amanda-novais1/">LinkedIn</a> ·
  <a href="mailto:amandasoouza2002@gmail.com">amandasoouza2002@gmail.com</a>
</p>
