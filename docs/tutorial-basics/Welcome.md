---
sidebar_position: 2
---

# Bem-vindo ao Premium
Aqui será onde você saberá como dar seus primeiros passos como um membro da comunidade Pinto Brasil! 🐥

![image](https://github.com/user-attachments/assets/d8ccee03-08fe-46f6-aa49-71053703d803)


## Manual do Pinto iniciante
Este é o lar da Helen e de muitos entusiastas apaixonados por NFTs, criptomoedas e aquele bom papo. Aqui é onde informação, amizade e oportunidades se encontram! Vamos te ajudar a entender como tudo funciona para você aproveitar ao máximo nossa comunidade. 🚀

Documents are **groups of pages** connected through:

- a **sidebar**
- **previous/next navigation**
- **versioning**

## Create your first Doc

Create a Markdown file at `docs/hello.md`:

```md title="docs/hello.md"
# Hello

This is my **first Docusaurus document**!
```

A new document is now available at [http://localhost:3000/docs/hello](http://localhost:3000/docs/hello).

## Configure the Sidebar

Docusaurus automatically **creates a sidebar** from the `docs` folder.

Add metadata to customize the sidebar label and position:

```md title="docs/hello.md" {1-4}
---
sidebar_label: 'Hi!'
sidebar_position: 3
---

# Hello

This is my **first Docusaurus document**!
```

It is also possible to create your sidebar explicitly in `sidebars.js`:

```js title="sidebars.js"
export default {
  tutorialSidebar: [
    'intro',
    // highlight-next-line
    'hello',
    {
      type: 'category',
      label: 'Tutorial',
      items: ['tutorial-basics/create-a-document'],
    },
  ],
};
```
