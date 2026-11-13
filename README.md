<div align="center">

# 🌐 Web Responsivo

### Um layout, diferentes ecrãs.

**Site educativo sobre o Google, desenvolvido com HTML e CSS**

`HTML5` · `CSS3` · `CSS Grid` · `Flexbox` · `Media queries`

</div>

## Sobre o projeto

Exercício de desenvolvimento web focado na construção de um site com várias páginas e adaptação a diferentes tamanhos de ecrã. O conteúdo apresenta o Google, a sua história e alguns dos seus serviços.

O objetivo foi praticar a estruturação de páginas HTML, a organização do layout com CSS e a navegação em computador, tablet e telemóvel.

## Páginas

| Página | Conteúdo |
| --- | --- |
| `Home.html` | Apresentação geral e curiosidades sobre o Google. |
| `Sobre.html` | História, evolução e impacto da empresa. |
| `Serviços.html` | Apresentação dos principais produtos e serviços. |
| `Contactos.html` | Interface de um formulário com nome, email e mensagem. |

## Funcionalidades e layout

- Navegação entre as quatro páginas.
- Menu lateral móvel, com abertura e fecho através de um checkbox e seletores CSS.
- Camada escura atrás do menu; um pequeno evento JavaScript permite fechá-lo ao clicar nessa área.
- Layout principal organizado com **CSS Grid** e cabeçalho e navegação com **Flexbox**.
- Barra lateral com conteúdos complementares em cada página.
- Formulário com campos obrigatórios, validação de email pelo navegador e botão para limpar os campos.

### Adaptação aos ecrãs

| Largura do ecrã | Comportamento definido no CSS |
| --- | --- |
| Até 600 px | Menu lateral e conteúdo numa coluna. |
| A partir de 601 px | Navegação horizontal no cabeçalho. |
| A partir de 1025 px | Conteúdo principal e barra lateral lado a lado. |

**Formulário de contacto:** esta versão contém apenas a interface. O código aponta para `/submeter`, mas o projeto não inclui um servidor para receber ou enviar mensagens.

## Tecnologias utilizadas

| Tecnologia | Utilização |
| --- | --- |
| HTML5 | Estrutura das páginas, navegação e formulário. |
| CSS3 | Cores, tipografia, espaçamento e apresentação. |
| CSS Grid | Organização das áreas da página e das colunas do conteúdo. |
| Flexbox | Alinhamento do cabeçalho e dos links de navegação. |
| Media queries | Alteração do layout consoante a largura do ecrã. |
| JavaScript inline | Fecho do menu ao clicar na camada de fundo. |

## Como executar

1. Descarrega o repositório ou clona-o:
   ```bash
   git clone https://github.com/jay-braga/web-responsivo.git
   ```
2. Mantém os ficheiros HTML, a folha de estilos e a pasta `imgs` na mesma estrutura.
3. Abre **`Home.html`** no navegador.

O site é estático: não precisa de instalação de pacotes, base de dados ou servidor PHP.

Opcionalmente, com Python instalado, podes servir a pasta localmente:

```bash
cd web-responsivo
python -m http.server 8000
```

Depois, abre `http://localhost:8000/Home.html`.

## Organização dos ficheiros

| Ficheiro ou pasta | Responsabilidade |
| --- | --- |
| `Home.html`, `Sobre.html`, `Serviços.html`, `Contactos.html` | Páginas do site. |
| `styles_responsive.css` | Estilos partilhados e regras de adaptação. |
| `imgs/google.png` | Logótipo apresentado no cabeçalho. |
| `imgs/teste2.jpg` | Imagem de fundo do cabeçalho. |

## Aprendizagens

- Utilizar elementos como `header`, `nav`, `main`, `aside` e `footer`.
- Partilhar uma folha de estilos entre várias páginas.
- Combinar Grid e Flexbox num mesmo layout.
- Trabalhar com posicionamento, camadas e transições de um menu.
- Adaptar a navegação e o conteúdo com media queries.
- Construir um formulário com os recursos de validação do HTML.

---

**Desenvolvido por [Jayelli Braga](https://github.com/jay-braga).**  
Projeto educativo independente sobre o Google, sem afiliação com a empresa.
