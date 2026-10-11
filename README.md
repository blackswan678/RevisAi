# RevisAí — Conteúdo em Dia, Dúvida Zero

Jogo educativo de revisão do 3º trimestre, do 9º Ano do Ensino Fundamental à 3ª Série do Ensino Médio, com base no Currículo 2026 SEDUC/Piauí.

**Projeto da disciplina Game Design** — CETI Dona Maria Antonieta Torres Dos Reis Veloso, Valença do Piauí - PI, 2026.
Professor: Marco Antonio Marques Lima Filho.

## Como jogar

1. Abra o `index.html` no navegador (ou acesse a página do GitHub Pages).
2. Informe o nome, a turma, a disciplina e o nível.
3. Você começa com 3 vidas. Erro ou tempo esgotado tira 1 vida.
4. Acertos seguidos formam combo (até x5) e rendem mais pontos.
5. O ranking top 10 de cada turma fica salvo no navegador (`localStorage`).

## Conteúdo

- 4 turmas: 9º Ano, 1ª, 2ª e 3ª Séries
- 4 disciplinas por turma: Ciências (9º Ano) ou Biologia, Matemática, Geografia e Língua Portuguesa
- 10 questões por disciplina, em 4 níveis: Fácil, Normal, Mediano e Difícil
- Total: 160 questões, cada uma com explicação pedagógica

## Como adicionar questões

No `index.html`, procure o array `B`. Cada linha segue o formato:

```
[turma, disciplina, nível, enunciado, [opções], índice da correta, explicação]
```

- turma: `'9'`, `'1'`, `'2'` ou `'3'`
- disciplina: 0 Ciências, 1 Biologia, 2 Matemática, 3 Geografia, 4 Língua Portuguesa
- nível: 0 Fácil, 1 Normal, 2 Mediano, 3 Difícil
- índice da correta: posição da resposta certa, começando em 0

## Equipe

Izabella Suan, Aylla Gabrielle, Yara Dantas e Giovanna Leohanna.
