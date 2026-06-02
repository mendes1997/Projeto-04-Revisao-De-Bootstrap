# ByteBlog | Tech & Help Center

Portal de notícias de tecnologia com central de ajuda (FAQ), desenvolvido com Bootstrap 5. Toda a interatividade é feita exclusivamente por atributos `data-bs-*`, sem JavaScript personalizado.

## Funcionalidades

- **Navbar** com links para Home, Blog, FAQ e botão de Login (abre modal)
- **Seção Blog** com cards de artigos, badges de categoria e alerta de feedback
- **Paginação** estática simulando múltiplas páginas
- **Accordion FAQ** com quatro perguntas frequentes
- **Modais** de Login e de Assinatura de Newsletter (controlados por `data-bs-toggle`)
- **Alert** dismissable no topo da página
- **Botão flutuante** para assinar newsletter (abre modal)
- **Ícones** do Bootstrap Icons integrados à interface

## Tecnologias Utilizadas

- HTML5
- CSS3
- [Bootstrap 5.3.3](https://getbootstrap.com/)
- [Bootstrap Icons 1.11.3](https://icons.getbootstrap.com/)

Nenhum JavaScript adicional foi escrito — apenas o bundle do Bootstrap é carregado para que os atributos `data-bs-*` funcionem.

## Estrutura de Arquivos

│ index.html
│ style.css


## Como Executar

1. Clone ou baixe os arquivos do repositório.
2. Abra o arquivo `index.html` em qualquer navegador moderno.

Não são necessárias dependências locais, pois todos os recursos são carregados via CDN.

## Destaques Técnicos

O foco do projeto é demonstrar componentes interativos do Bootstrap sem escrever uma linha de JavaScript. Os seguintes atributos são utilizados:

- `data-bs-toggle="collapse"` com `data-bs-target` → Accordion da FAQ
- `data-bs-toggle="modal"` e `data-bs-target` → Abertura dos modais
- `data-bs-dismiss="alert"` / `data-bs-dismiss="modal"` → Fechamento de alertas e modais
- `data-bs-parent` → Comportamento de grupo no accordion (apenas um item aberto por vez)

## Personalização

O arquivo `style.css` contém ajustes leves, como:

- Animação nos cards de posts
- Cores do accordion no estado ativo
- Estilo da navbar e badges

Para alterar o conteúdo dos posts, FAQ ou categorias, edite diretamente o HTML.

---

Desenvolvido no curso de Front-End
