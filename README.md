🔹 Projeto para praticar HTML, CSS e JS criando uma página de biblioteca com dados da Open Library.  
✨ Ideal para treinar responsividade, manipulação do DOM e trabalhar com dados JSON.

---

# Desafio: Página de Biblioteca

Uma atividade para treinar HTML, CSS e JavaScript criando uma página com dados de livros da [Open Library](https://openlibrary.org/) (acesso aberto).

## 🎯 Objetivo:

Aplicar na prática o que sabemos, aprender coisas novas e se divertir durante o processo! Este projeto faz parte da jornada de aprendizado em desenvolvimento web (curso Full-Stack da [Toti](https://totidiversidade.com.br/), 2025).

## 🧩 Etapas do Projeto:

— Montar uma página responsiva com layout pré-definido.  
— Carregar dinamicamente livros (JSON + JS).  
— Implementar busca, filtros e marcação de livros favoritos.  

## 📁 Estrutura do Projeto

```
liveler/
├── assets/
│   ├── layout.png             # Layout da página
│   └── books.json             # Dados dos livros
├── src/
│   ├── index.html             # HTML da página
│   ├── style.css              # Estilos CSS
│   ├── script.js              # Funcionalidade JS
│   └── (outros arquivos...)   # Ex.: imagens, temas, etc.
└── README.md                  # Instruções do projeto
```

## 🔹 Layout e dados para livros:

- [Layout da página](https://github.com/Vat-ua/liveler/blob/main/assets/layout.png)
- [JSON com livros](https://github.com/Vat-ua/liveler/blob/main/assets/books.json)

## 🔹 Funcionalidades Esperadas

| Funcionalidade   | Descrição                               | Técnicas Utilizadas                |
|------------------|-----------------------------------------|------------------------------------|
| 📱 Responsivo    | Página adaptável a diferentes telas     | Flexbox/Grid + Media Queries       |
| 📦 Exibir        | Carregar e exibir livros do JSON        | `fetch()` + DOM manipulation       |
| 🔄 Atualização   | Atualização dinâmica da interface       | `innerHTML`/`appendChild()`, etc.  |
| 🔍 Busca         | Buscar livros por título e autor        | `Array.filter()` + `includes()`    |
| 🏷️ Filtros       | Filtros: "Quero ler", "Lendo", "Lido"   | `Array.filter()` + lógica          |
| ❤️ Favoritos     | Salvar/remover livros marcados          | API `localStorage`                 |

## 🔹 Dados dos livros da Open Library

- Capa: `https://covers.openlibrary.org/b/olid/{openlibrary_id}-M.jpg`
- Link: `https://openlibrary.org/book/{openlibrary_id}`
- O progresso de leitura pode ser representado por uma barra de progresso baseada nos dados abaixo:
  ```json
  "paginas": {
    "total": 870,
    "lidas": 120
   }
   ```

**Nota**: O `openlibrary_id` é o identificador único de cada livro na Open Library e está disponível no arquivo JSON.

## 🔹 Como Participar

- Escolha as funcionalidades que quer implementar.
- Personalize o layout se quiser.
- Foque em aprender, praticar e se divertir!

## 🗓️ Prazo Sugerido

**2 semanas** – até 12 de maio de 2025 (segunda-feira).

## 💡 Dicas

- Use `localStorage.setItem()` e `getItem()` para salvar dados localmente.
- Funções como `filter()` e `includes()` são úteis para buscas e filtros de livros.
- Organize os cards com Flexbox ou Grid.

---

Bom código e divirta-se!
