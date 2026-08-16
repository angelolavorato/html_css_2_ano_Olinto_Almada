# HTML e CSS — 2º Ano | Curso Técnico em Informática

Repositório de apoio didático destinado ao estudo prático de **HTML e CSS**, com foco na construção e organização visual de páginas web por meio de exemplos progressivos, comentados e executáveis diretamente no navegador.

O material foi estruturado para demonstrar, de forma visual e aplicada, conceitos fundamentais de estilização e layout em CSS. Cada módulo apresenta uma página completa construída para permitir que o estudante observe o comportamento das propriedades, relacione o código ao resultado exibido no navegador e realize modificações para compreender seus efeitos na prática.

## Objetivo do repositório

Este repositório tem como principal objetivo servir como **material de apoio para aulas práticas de desenvolvimento web**, consolidando conceitos de CSS por meio de exemplos completos e organizados em uma sequência de aprendizagem.

A proposta é permitir que o estudante avance gradualmente por três etapas:

1. compreender como os elementos HTML se comportam como caixas e como a propriedade `display` interfere no fluxo da página;
2. utilizar **Flexbox** para alinhamento e distribuição de elementos em layouts unidimensionais;
3. utilizar **CSS Grid** para criação de estruturas em linhas e colunas, associando o layout à **responsividade** por meio de Media Queries.

Mais do que apresentar páginas prontas, os exemplos foram desenvolvidos para funcionar como um **laboratório de experimentação**, no qual propriedades e valores podem ser alterados e comparados diretamente no navegador.

## Organização do conteúdo

| Módulo | Diretório | Conteúdo principal |
|---|---|---|
| 1 | `1Box_Model_Display` | Box Model, `margin`, `padding`, `border`, dimensões e tipos de `display` |
| 2 | `2Layout_Flexbox` | Flexbox, eixos, alinhamento, distribuição, `gap`, `flex-wrap` e organização de cards |
| 3 | `3Grid_Responsividade` | CSS Grid, linhas, colunas, expansão de células, Media Queries e responsividade |

---

## Módulo 1 — Box Model e Display

O primeiro módulo utiliza um **catálogo de componentes de computador** para demonstrar como os elementos HTML são representados visualmente como caixas.

São trabalhados conceitos como:

- conteúdo do elemento;
- `padding`;
- `border`;
- `margin`;
- largura e altura;
- `box-sizing`;
- `display: block`;
- `display: inline`;
- `display: inline-block`;
- organização visual de cards;
- dimensionamento e posicionamento básico de imagens.

A página também possui uma seção específica de comparação entre `block`, `inline` e `inline-block`, permitindo visualizar claramente a diferença de comportamento entre esses tipos de exibição.

**Arquivos principais:**

```text
1Box_Model_Display/
├── assets/
├── index.html
└── style.css
```

---

## Módulo 2 — Layout com Flexbox

O segundo módulo apresenta uma página em formato de **portal educacional**, utilizando Flexbox em diferentes regiões da interface.

O exemplo demonstra que o Flexbox trabalha a partir de um **contêiner flexível** e permite controlar a disposição dos elementos filhos ao longo do eixo principal e do eixo cruzado.

Entre os conteúdos abordados estão:

- `display: flex`;
- `flex-direction`;
- `justify-content`;
- `align-items`;
- `align-content`;
- `flex-wrap`;
- `gap`;
- crescimento e redução de itens com `flex`;
- organização de menus;
- distribuição de cards;
- alinhamento interno de componentes;
- construção de layouts flexíveis;
- estados de interação com `:hover` e `:focus`.

O módulo inclui ainda um **laboratório visual de Flexbox**, com exemplos específicos de centralização, distribuição de espaço, alinhamento vertical e quebra automática de linha.

**Arquivos principais:**

```text
2Layout_Flexbox/
├── index.html
└── style.css
```

---

## Módulo 3 — CSS Grid e Responsividade

O terceiro módulo apresenta uma interface em formato de **painel**, demonstrando a organização bidimensional proporcionada pelo CSS Grid.

A página utiliza uma estrutura principal com conteúdo e área lateral, além de grades internas para cards e demonstrações visuais.

São trabalhados conceitos como:

- `display: grid`;
- `grid-template-columns`;
- unidade `fr`;
- função `repeat()`;
- `gap`;
- `grid-column`;
- `grid-row`;
- expansão de elementos por múltiplas linhas ou colunas;
- `place-items`;
- composição de layouts em duas dimensões;
- responsividade;
- Media Queries com `@media`;
- reorganização do layout para telas menores.

A Media Query utilizada no exemplo modifica a estrutura quando a largura da tela chega a **700 px ou menos**, transformando áreas originalmente distribuídas em múltiplas colunas em uma organização de coluna única.

**Arquivos principais:**

```text
3Grid_Responsividade/
├── index.html
└── style.css
```

---

## Estrutura geral do repositório

```text
html_css_2_ano_Olinto_Almada/
├── 1Box_Model_Display/
│   ├── assets/
│   ├── index.html
│   └── style.css
│
├── 2Layout_Flexbox/
│   ├── index.html
│   └── style.css
│
├── 3Grid_Responsividade/
│   ├── index.html
│   └── style.css
│
└── README.md
```

## Tecnologias utilizadas

- **HTML5** — estrutura e organização semântica do conteúdo;
- **CSS3** — estilização, Box Model, layouts e responsividade;
- **Flexbox** — organização unidimensional de componentes;
- **CSS Grid** — construção de layouts bidimensionais;
- **Media Queries** — adaptação da interface a diferentes tamanhos de tela.

Os exemplos utilizam HTML e CSS sem dependência de frameworks ou bibliotecas externas, favorecendo a compreensão direta dos recursos nativos da plataforma web.

## Como utilizar os exemplos

Não é necessário instalar dependências para executar os projetos.

### Opção 1 — Abrir diretamente no navegador

1. Faça o download ou clone deste repositório.
2. Acesse o diretório do módulo desejado.
3. Abra o arquivo `index.html` em um navegador web moderno.
4. Mantenha o arquivo `style.css` no mesmo diretório do respectivo `index.html`.

### Opção 2 — Clonar com Git

```bash
git clone https://github.com/angelolavorato/html_css_2_ano_Olinto_Almada.git
```

Depois, abra a pasta clonada em um editor como **Visual Studio Code** e execute o `index.html` correspondente ao conteúdo que deseja estudar.

## Proposta de estudo

Para obter melhor aproveitamento, recomenda-se utilizar os exemplos de maneira experimental:

1. execute inicialmente a página sem modificar o código;
2. observe como os elementos estão organizados no navegador;
3. localize no CSS a propriedade responsável pelo comportamento observado;
4. altere apenas uma propriedade ou valor por vez;
5. atualize a página e compare o resultado;
6. reverta a alteração e teste novas possibilidades;
7. redimensione a janela do navegador nos exemplos que trabalham Flexbox e Grid;
8. utilize os comentários presentes nos arquivos CSS como apoio para relacionar cada declaração ao seu efeito visual.

Essa abordagem permite compreender CSS não apenas pela leitura da sintaxe, mas principalmente pela relação entre **propriedade, valor e resultado visual**.

## Progressão de aprendizagem

O repositório segue uma sequência intencional de complexidade:

```text
Box Model e Display
        ↓
     Flexbox
        ↓
CSS Grid e Responsividade
```

O Box Model estabelece a compreensão do espaço ocupado por cada elemento. O Flexbox amplia esse conhecimento para a organização de conjuntos de elementos em uma direção principal. Por fim, o CSS Grid permite trabalhar com linhas e colunas simultaneamente, enquanto a responsividade adapta essas estruturas a diferentes dispositivos.

## Finalidade educacional

Este material foi desenvolvido para fins de **ensino, demonstração e prática em ambiente educacional**, especialmente para estudantes em processo de aprendizagem dos fundamentos de desenvolvimento web.

Os códigos possuem comentários explicativos e exemplos visuais deliberadamente construídos para facilitar a observação dos conceitos apresentados em aula. Por esse motivo, algumas soluções priorizam a **clareza pedagógica** em vez da redução máxima de código.

## Sugestões de prática

Após compreender cada exemplo, o estudante pode utilizar a estrutura existente como ponto de partida para novos exercícios, como:

- modificar cores, espaçamentos e dimensões dos componentes;
- acrescentar novos cards;
- alterar a direção de um contêiner Flexbox;
- testar diferentes valores de `justify-content` e `align-items`;
- modificar a quantidade de colunas de uma grade;
- criar novas áreas utilizando `grid-column` e `grid-row`;
- alterar o breakpoint da Media Query;
- adaptar os exemplos para telas de diferentes tamanhos;
- reconstruir as páginas utilizando uma identidade visual própria.

## Licença e uso

Repositório destinado prioritariamente ao uso educacional e à demonstração dos conteúdos apresentados em aula.

---

**Curso Técnico em Informática — Desenvolvimento Web**  
Material de apoio para estudo prático de HTML e CSS.