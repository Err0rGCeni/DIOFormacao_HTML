# Criando Tabelas

    <table>
        <thead>
            <tr>
                <th colspan="2">The table header</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>The table body</td>
                <td>with two columns</td>
            </tr>
        </tbody>
    </table>

- `<table></table>`: Representação de dados tabulares.
  - _align_: Como a tabela deve ser alinhada dentro do documento.
    - Utilizar _margin-left_ e _margin-right_ como _auto_ ou _margin_ como _0 auto_ para obter um efeito semelhante ao atributo align.
  - _border_: Tamanho do quadro ao redor da tabela.
    - Utilizar css.
  - _cellpading_: Define o espaço entre o conteúdo de uma célula e sua borda, exibida ou não.
    - Utilizar a propriedade _border-collapse_ ao `table`, com seu valor configurado para 'collapse', e a propriedade _padding_ aos elementos `td`.
  - _cellspacing_: Define o tamanho do espaço entre duas células em um valor percentual ou pixels.
    - Utilizar a propriedade _border-spacing_ ao elemento `table`.
  - _summary_: Define um texto alternativo que resume o conteúdo da tabela.
    - Utilizar o elemento `caption`.
- `<tr></tr>`: Define uma linha de células em uma tabela.
- `<th></th>`: Define uma célula como cabeçalho de um grupo de células.
- `<td></td>`: Define uma célula de uma tabela.
- `thead`, `tbody` e `tfoot`: Definem blocos da tabela. Navegador renderiza independente da ordem do código.
