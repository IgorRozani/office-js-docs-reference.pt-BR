# <a name="onenote-javascript-api-overview"></a>Visão geral da API do JavaScript OneNote

Aplica-se a: OneNote Online

Os links a seguir mostram os objetos do OneNote de alto nível disponíveis na API. Cada link de página do objeto contém uma descrição dos eventos, propriedades e métodos disponíveis no objeto. Acesse esses links para saber mais. 
    
- [Application](/javascript/api/onenote/onenote.application): o objeto de nível superior usado para acessar todos os objetos do OneNote globalmente endereçados, como o bloco de anotações ativo e a sessão ativa.

- [Notebook](/javascript/api/onenote/onenote.notebook): um bloco de anotações. blocos de anotações contêm grupos de seções e seções.
    - [NotebookCollection](/javascript/api/onenote/onenote.notebookcollection): uma coleção de blocos de anotações.

- [SectionGroup](/javascript/api/onenote/onenote.sectiongroup): um grupo de seções. Os grupos de seções contêm seções e grupos de seções.
    - [SectionGroupCollection](/javascript/api/onenote/onenote.sectiongroupcollection): uma coleção de grupos de seção.

- [Section](/javascript/api/onenote/onenote.section): uma seção. As seções contêm páginas.
    - [SectionCollection](/javascript/api/onenote/onenote.sectioncollection): uma coleção de seções.

- [Page](/javascript/api/onenote/onenote.page): uma página. As páginas contêm objetos PageContent.
    - [PageCollection](/javascript/api/onenote/onenote.pagecollection): uma coleção de páginas.

- [PageContent](/javascript/api/onenote/onenote.pagecontent): uma região de nível superior em uma página que contém os tipos de conteúdo como estrutura de tópicos ou imagem. Um objeto PageContent pode ser atribuído a uma posição na página.
    - [PageContentCollection](/javascript/api/onenote/onenote.pagecontentcollection): uma coleção de objetos PageContent, que representam os conteúdos da página.

- [Outline](/javascript/api/onenote/onenote.outline): um contêiner para objetos Paragraph. Uma estrutura de tópicos é um filho direto do objeto PageContent.

- [Image](/javascript/api/onenote/onenote.image): um objeto Image. Um Image pode ser um filho direto de um objeto PageContent ou Paragraph.

- [Paragraph](/javascript/api/onenote/onenote.paragraph): um contêiner para o conteúdo visível em uma página. Um parágrafo é um filho direto de uma estrutura de tópicos.
    - [ParagraphCollection](/javascript/api/onenote/onenote.paragraphcollection): uma coleção de objetos Paragraph em uma estrutura de tópicos.

- [RichText](/javascript/api/onenote/onenote.richtext): um objeto RichText.

- [Table](/javascript/api/onenote/onenote.table): um contêiner para objetos TableRow.

- [TableRow](/javascript/api/onenote/onenote.tablerow): um contêiner para objetos TableCell.
    - [TableRowCollection](/javascript/api/onenote/onenote.tablerowcollection): um conjunto de objetos TableRow em uma Table.
 
- [TableCell](/javascript/api/onenote/onenote.tablecell): um contêiner para objetos Paragraph.
    - [TableCellCollection](/javascript/api/onenote/onenote.tablecellcollection): um conjunto de objetos TableCell em uma TableRow.

## <a name="onenote-javascript-api-reference"></a>Referência da API JavaScript do OneNote

Para obter informações detalhadas sobre a API do JavaScript OneNote, consulte a [documentação de referência de API do JavaScript OneNote](/javascript/api/onenote).

## <a name="see-also"></a>Veja também

- [Visão geral da programação da API JavaScript do OneNote](https://docs.microsoft.com/office/dev/add-ins/onenote/onenote-add-ins-programming-overview)
- [Crie seu primeiro suplemento do OneNote](https://docs.microsoft.com/office/dev/add-ins/onenote/onenote-add-ins-getting-started)
- [Amostra de Rubric Grader](https://github.com/OfficeDev/OneNote-Add-in-Rubric-Grader)
- [Visão geral da plataforma Suplementos do Office](https://docs.microsoft.com/office/dev/add-ins/overview/office-add-ins)