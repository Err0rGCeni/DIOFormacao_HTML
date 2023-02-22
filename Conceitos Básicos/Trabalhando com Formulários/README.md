# Trabalhando com Formulários

- `<form></form>`: Representa uma seção de um documento que contém controles interativos que permitem ao submeter informações a um determinado servidor web.
  - _name_: Nome do formulário, deve ser único.
  - _autocomplete_: Indica se o navegador pode completar automaticamente seus campos.
  - _action_: URI/URL.
  - _method_: Método HTTP para submissão (POST, GET, ...).
  - _target_: Onde exibir a resposta após submissão (Contexto de Browser: tab, window, iframe).
- `<label></label>`: Representa uma legenda para um item em uma interface de usuário.
  - Ele pode estar associado com um elemento de controle, colocando este dentro do elemento _label_, ou usando o atributo _for_.
  
        <label>Click me <input type="text" id="User" name="Name" /></label>

    ou

        <label for="User">Click me</label>
        <input type="text" id="User" name="Name" />
- `<input>`: Entrada ou seleção de dados.
  - _type_: Tipo do _input_. O padrão é _text_.
    - _text_, _number_, _range_, etc;
    - _checkbox_: Utilizado para múltiplas seleções;
    - _radio_: Utilizado para selecionar apenas uma opção;
      - Para _checkbox_ e _radio_, utilizar name para indicar o campo, e value para indicar valores dos itens relacionado ao campo.
        - Utilizando método post, utilizar [] para indicar que se trata de um array de itens, etc.
- `<button></button>`: Um botão.
  - button: Botão básico, clicável (onClick, onMouseOver, ...);
  - reset: Limpar formulário em que está inserido;
  - submit: Enviar o formulário em que está inserido;
    - Pode-se utilizar com o _onsubmit_ do `form`;
  - disabled: Butão desabilitado;
- `<select><option></option></select>`: Caixa de seleção de opções previamente definidas.
  - `select` possui o campo _name_, e `option` os campos de _value_;
  - Pode-se utilizar um `option` com _value_ vazio como placeholder;
- `<textarea></textarea>`: Permite um texto extenso em formato livre.
  - Apesar da forma livre, pode ser limitada utilizando _rows_ e _cols_.
