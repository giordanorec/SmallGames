# SmallGames

Plataforma central de joguinhos pessoais + clone do Wordle (Palavrim) em português.

## Estrutura

```
/
├── index.html       Página central com cards de cada jogo
└── wordle/
    ├── index.html   Palavrim (clone do Wordle)
    └── words.js     Dicionário em português
```

Tudo é estático — pode ser servido por qualquer host. Configurado pra deploy
único no Vercel:

- `/`           → página central
- `/wordle/`    → Palavrim

## Deploy

1. Vá em https://vercel.com/new
2. Importe o repositório `giordanorec/SmallGames`
3. Use os valores padrão (framework: Other, root: `/`, build vazio)
4. Deploy

O nome do projeto vira o subdomínio. Ex.: `smallgames.vercel.app`.

## Jogos existentes

- Lenine Quiz — https://lenine-quiz.vercel.app/
- Quiz Pianistas — https://quiz-pianistas.vercel.app
- Aries Quiz — https://aries-quiz.vercel.app/
