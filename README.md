# Widde API


## Instalação

Para instalar o plugin da Widde no seu sistema é simples: basta adicionar o arquivo javascript em seu public.


Install the dependencies and devDependencies and start the server.

```html
<script src"https://cdn.widde.io/widde-lib-1.0.0.js"><script/>
```

## Como utilizar

### Floating Player

Para utilizar o floating player de um evento é simples. Basta adicionar a class **wide-link** no elemento e adicionar os dados de identificação:

- **data-widde-event-key**: ID do Evento da Widde
- **data-widde-identify**: ID único do usuário 
- **data-widde-name**: Nome do usuário 

```html
<button
      class="widde-link"
      data-widde-event-key="123-10"
      data-widde-identify="IDENTIFICADOR ÚNICO DO USUÁRIO"
      data-widde-name="NOME DO USUÁRIO"
    >
      Abrir live
    </button>
```
