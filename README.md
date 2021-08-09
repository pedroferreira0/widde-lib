# Widde API


[![Widde Logo](https://cdn.discordapp.com/attachments/802325339195441152/874334443106627675/Captura_de_Tela_2021-08-09_as_13.52.38.png)](https://widde.io)

## Instalação

Para instalar o plugin da Widde no seu sistema é simples: basta adicionar o arquivo javascript em seu html.


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
