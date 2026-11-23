# Flamengo — Projeto de Desenvolvimento Web

Site acadêmico com o tema **Clube de Regatas do Flamengo**, desenvolvido com **HTML5 e CSS3** para praticar estruturação de páginas, navegação, formulários e organização de conteúdo com Flexbox.

## Sobre o projeto

O projeto apresenta páginas com identidade visual em vermelho, preto e branco, menu de navegação e cards sobre títulos do clube. Também inclui um formulário visual de contato.

É uma página de estudos, sem vínculo oficial com o Flamengo.

## Páginas

| Arquivo | Conteúdo atual |
| --- | --- |
| `index.html` | Página de entrada que, nesta versão, apresenta o formulário “Fale com a Nação” |
| `sobre.html` | Cards com informações sobre títulos e competições do clube |
| `contato.html` | Formulário com campos de nome, e-mail e mensagem |

O menu permite navegar entre Home, Sobre (Títulos) e Contato.

## Recursos utilizados

- Tags HTML como `header`, `nav`, `section`, `article` e `footer`.
- Estilos compartilhados em um arquivo CSS.
- Flexbox na organização do cabeçalho, dos cards e do formulário.
- Quebra de linha dos cards com `flex-wrap`.
- Campos obrigatórios com o atributo `required`.
- Campo de e-mail com `type="email"`.
- Efeitos de passagem do mouse nos links e no botão.
- Cards com bordas, cantos arredondados e sombras.

## Tecnologias

- **HTML5:** estrutura das páginas e formulário.
- **CSS3:** cores, espaçamentos, tipografia e estilos.
- **Flexbox:** distribuição e alinhamento dos elementos.

O projeto não utiliza JavaScript, frameworks ou bibliotecas externas.

## Estrutura dos arquivos

| Arquivo | Responsabilidade |
| --- | --- |
| `index.html` | Página de entrada |
| `sobre.html` | Página de títulos |
| `contato.html` | Página de contato |
| `style.css` | Estilos compartilhados |
| `README.md` | Documentação do projeto |

## Como visualizar

1. Clique em **Code → Download ZIP** neste repositório.
2. Extraia o arquivo baixado.
3. Abra `index.html` no navegador.
4. Use o menu para acessar as outras páginas.

Não é necessário instalar dependências, iniciar um servidor ou configurar banco de dados.

## Sobre o formulário de contato

O formulário faz parte da interface de estudo e possui validação nativa do navegador para campos obrigatórios e formato de e-mail.

**Não há envio real de mensagens, integração com e-mail ou armazenamento de dados.** O formulário utiliza `action="#"` e `method="post"`, sem um backend para receber os dados. Por isso, o botão de envio não representa um serviço de contato funcional.

## Escopo atual

- A página inicial e a página de contato apresentam conteúdo semelhante.
- Não existe backend, banco de dados ou autenticação.
- O CSS permite a reorganização dos cards, mas ainda não possui media queries específicas para ajustar o cabeçalho em telas pequenas.
- As informações esportivas fazem parte do conteúdo do projeto e podem precisar de atualização.

## Objetivo acadêmico

Praticar os fundamentos de desenvolvimento web por meio da criação de páginas conectadas, aplicação de estilos em CSS e construção de um formulário HTML.

## Autor

**Enzo Ramos de Almeida**  
[GitHub — ExKN1](https://github.com/ExKN1)

