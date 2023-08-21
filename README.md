Este exemplo é um código feito com HTML, CSS e JavaScript que permite alterar a folha de estilos da página com base no clique no botão (lua para o modo darkmode e sol para o modo ligthmode). Além disso, ele utiliza a funcionalidade do armazenamento local do navegador para salvar as preferências do usuário e manter a seleção mesmo após a página ser atualizada ou fechada.

A mudança de estilo é realizada por meio da alteração da propriedade href do elemento link que faz referência à folha de estilos. O JavaScript adiciona um ouvinte de eventos ao botão, que, quando clicado, chama uma função que alterna entre dois estilos diferentes. Essa função também usa a funcionalidade do localStorage para salvar a preferência do usuário.

Ao salvar as preferências do usuário no localStorage, o código garante que a seleção do usuário seja mantida mesmo após a página ser atualizada ou fechada. Isso significa que o usuário não precisa selecionar o estilo desejado toda vez que visitar a página, tornando a experiência do usuário mais agradável e eficiente.

Demo: https://dpelissari.github.io/Darkmode.HTML.CSS.JS/
