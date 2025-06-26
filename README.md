# Apresentação sobre Reúso de Software

Este repositório contém o código-fonte de uma apresentação em formato de slides sobre **Reúso de Software**, desenvolvida para a disciplina de Engenharia de Software I.

## 🎯 Objetivo do Projeto

O objetivo deste trabalho é explorar e apresentar diferentes estratégias e abordagens para o reúso de software, analisando suas vantagens, desvantagens e contextos de aplicação, com base na bibliografia de referência da área.

A apresentação é construída como uma página web única (`index.html`) utilizando HTML, Tailwind CSS e JavaScript para criar uma experiência de navegação interativa.

## 🚀 Como Visualizar a Apresentação

Para visualizar os slides, não é necessário instalar nenhum servidor ou dependência complexa. Basta seguir os passos:

1.  **Clone o repositório** para a sua máquina local:
    ```bash
    git clone [URL_DO_SEU_REPOSITORIO]
    ```
2.  Navegue até a pasta do projeto.
3.  Abra o arquivo `index.html` diretamente no seu navegador de preferência (Google Chrome, Firefox, etc.).

Você pode navegar pelos slides usando os botões **"Anterior"** e **"Próximo"** ou as **setas direcionais** do teclado (← e →).

## 🤝 Como Contribuir

Este repositório foi criado para que todos os membros do grupo possam colaborar. Para adicionar ou editar o conteúdo:

1.  **Abra o arquivo `index.html`** em um editor de código (como VS Code, Sublime Text, etc.).
2.  **Localize o slide** que você deseja editar. Os slides são `divs` com a classe `.slide` e um `id` sequencial (ex: `<div id="slide-4" class="slide ...">`).
3.  **Faça as alterações** necessárias no conteúdo HTML dentro da `div` do slide. Você pode alterar textos, adicionar imagens, ou ajustar o layout usando as classes do Tailwind CSS.
4.  Após fazer suas alterações, **faça o commit** e **envie (push)** para o repositório no GitHub para que os outros membros possam ver suas contribuições.

```bash
# Exemplo de fluxo de contribuição
git add index.html
git commit -m "feat: adiciona conteúdo ao slide de Componentização"
git push origin main
```

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Para a estrutura e conteúdo dos slides.
* **Tailwind CSS:** Para a estilização visual e layout responsivo.
* **JavaScript:** Para a lógica de navegação interativa entre os slides.

## 📚 Bibliografia

O conteúdo da apresentação foi baseado nas seguintes obras:

* Czarnecki, K.; Eisenecker, U. W. **Generative Programming: Methods, Tools, and Applications**. Addison-Wesley, 2000.
* Pressman, Roger S. **Engenharia de Software**. 6ª ed., Bookman, 2006.
* Sommerville, Ian. **Engenharia de software**. 9. ed. São Paulo: Pearson Addison Wesley, 2011.
* Sommerville, Ian. **Engenharia de software**. 10. ed. São Paulo: Pearson, 2019.

---
*Este README foi gerado para facilitar a colaboração do grupo.*
