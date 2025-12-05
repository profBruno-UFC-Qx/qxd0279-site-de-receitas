# Exercício 2 – Site de Receitas com Vue Router

## 🎯 Objetivo
Praticar a navegação de páginas usando o Vue Router, incluindo rotas estáticas, dinâmicas e páginas de erro.

## 📝 Descrição
Implemente um **site de receitas** onde os dados são fornecidos por um JSON Server.  
O site deve conter pelo menos as seguintes páginas:

- `/` → Lista de todas as receitas com paginação. Dez no máximo por página.
  - [Formato da URL com paginação](https://github.com/typicode/json-server?tab=readme-ov-file#paginate)
- `/receitas/:id` → Página de detalhes de uma receita
- `/sobre` → Página "Sobre o projeto"
- Rota para página 404

Para executar o JSON server, entre na pasta **receitasAPI** e execute os seguintes comandos:

```
npm install
npm run server
```

## 🚀 Requisitos
1. Usar o Vue Router com pelo menos **3 páginas reais**.
2. Implementar rotas dinâmicas para acessar receitas por ID.
3. Implementar uma rota "Not Found" para URLs inexistentes.
4. A página de detalhes deve mostrar título, ingredientes e modo de preparo.

## 🌟 Desafio extra
- Criar uma rota que permita adicionar novas receitas.

