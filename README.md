<div align="center">

# Luís Carlos Barros
 
### Backend Developer · Node.js · TypeScript

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lu%C3%ADs-carlos-aquino-barros-41150117b/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/luiscarlos14)
![Backend](https://img.shields.io/badge/Focus-Backend-1f6feb?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Disponível-3fb950?style=for-the-badge)

</div>

---

```typescript
const luisCarlos = {
  name:      "Luís Carlos Barros",
  role:      "Backend Developer",
  stack:     ["Node.js", "TypeScript", "Express", "Prisma", "Firebase"],
  focus:     ["REST APIs", "Arquitetura modular", "Segurança"],
  mindset:   "Código limpo, responsabilidade única, entrega real",
  location:  "Brasil 🇧🇷",
  hello:     () => console.log("Bora construir algo incrível?"),
} as const;

type Philosophy = {
  code:         "limpo, tipado e testável";
  architecture: "modular, orientado a casos de uso";
  delivery:     "valor real para quem usa";
};
```

---

## ⚙️ Stack Principal — Backend

<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)

</div>

---

## 📐 Arquitetura Modular

```
src/
├── errors/              # Classes de erro customizadas e handler global
├── firebase/            # Config e integração isolada do Firebase
├── modules/             ← domínio
│   └── users/
│       ├── controller/  # Entrada HTTP · valida · delega
│       └── useCase/     # Regra de negócio · testável · isolada
├── prisma/              # Client e schema do banco
├── routes/              # Definição e agrupamento das rotas
├── utilities/           # Helpers e funções puras reutilizáveis
└── server.ts            # Entry point — inicializa a aplicação
```

| Camada | Responsabilidade |
|---|---|
| `modules/*/controller` | Recebe requisição HTTP, valida input e delega para o use case |
| `modules/*/useCase` | Regra de negócio isolada, sem dependência de framework |
| `errors/` | Tratamento padronizado — sem try/catch espalhado pelo código |
| `firebase/` | Configuração isolada do resto da lógica, fácil de manter |
| `prisma/` | Camada de dados limpa, schema como fonte única da verdade |

---

## 🖥️ Também domino — Frontend

<div align="center">

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats-sigma-five.vercel.app/api?username=luiscarlos14&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=3fb950&text_color=8b949e" />
<img height="165" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=luiscarlos14&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e" />

</div>

---

<div align="center">

> *"Ser desenvolvedor é uma viagem onde a próxima parada é a solução de um problema."*
> — **Thales Valentim**

<br/>

**Tem um projeto? Bora conversar.**

[![Falar no LinkedIn](https://img.shields.io/badge/Falar_no_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luiscarlos14/)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3fb950,100:1f6feb&height=120&section=footer" />

</div>
