### Documentação do Projeto

# Refatoração do Site "Agrinho Conhecer Guarapuava"

Este projeto refatora o site **Agrinho Conhecer Guarapuava**, utilizando **TwindCSS**, **HTML** e **JavaScript**, com foco em performance, responsividade e experiência do usuário. Além disso, uma nova estrutura de pastas foi criada para garantir escalabilidade e facilidade de manutenção.

📄 **[GitHub Pages do Projeto](https://klsio22.github.io/agrinho-com-cell/)**

---

## Tecnologias Utilizadas

- **[TwindCSS](https://tailwindcss.com/)**: Para gerenciamento eficiente e modular dos estilos, usando o sistema utilitário do TailwindCSS.
- **HTML**: Para estruturar o conteúdo de forma semântica.
- **JavaScript**: Para funcionalidades interativas e dinâmicas.

---

## Objetivos da Refatoração

1. **Melhorar a Performance**  
   Utilizar as vantagens do TwindCSS para reduzir o tamanho dos arquivos CSS, resultando em maior eficiência e carregamento mais rápido.

2. **Responsividade**  
   Garantir uma experiência uniforme e otimizada para usuários em dispositivos móveis, tablets e desktops.

3. **Organização Modular**  
   Reestruturar pastas para maior organização e escalabilidade, facilitando futuras alterações e expansões.

4. **Melhoria da Experiência do Usuário (UX)**  
   Tornar o site mais intuitivo, atrativo e fácil de navegar, alinhando-se a padrões de design moderno.

---

## Estrutura do Projeto

A nova estrutura de pastas promove clareza e facilita o desenvolvimento contínuo:

```
/public
    /assets           # Imagens, fontes e outros arquivos estáticos
    /css              # Arquivos CSS gerados pelo TwindCSS
    /js               # Scripts JavaScript do site
/index.html          # Página inicial
/src
    /pages            # Páginas específicas do site
README.md             # Documentação do projeto
```

### Detalhamento dos Diretórios

- **/public**: Contém os recursos estáticos acessíveis publicamente.
  - **/assets**: Inclui imagens, ícones, fontes e outros arquivos estáticos.
  - **/css**: Arquivos CSS gerados pelo TwindCSS.
  - **/js**: Scripts JavaScript responsáveis pela interatividade do site.
  
- **/src**: Contém o código-fonte do projeto.
  - **/pages**: Arquivos HTML organizados por página (homepage, contato, etc.).

---

## Funcionalidades e Alterações Implementadas

1. **Estilização com TwindCSS**  
   O TwindCSS permite a geração de estilos dinâmicos e reduz o tamanho final do CSS. Ele foi configurado para personalizar cores, fontes e componentes específicos.

2. **Estrutura Modular**  
   A separação de arquivos em diretórios específicos organiza melhor o projeto, promovendo reutilização e manutenibilidade.

3. **Design Responsivo**  
   Utilizando breakpoints e grids do TwindCSS, o design foi ajustado para funcionar em qualquer dispositivo, de smartphones a telas maiores.
