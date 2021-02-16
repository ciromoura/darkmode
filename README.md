# darkmode
Dark mode para Bootstrap com JQuery.


Este é um simples modelo de página feita com [Bootstrap](https://getbootstrap.com/) e que utiliza JQuery para alterar o modo de cores, do claro para o modo escuro (dark mode).

Para realizar essa alteração, basta utilziar o método [.toggleClass()](https://api.jquery.com/toggleclass/) do JQuery, por exemplo:

```
<button class="btn btn-dark toggle-button" onclick="myFunction()"><i class="fas fa-magic"></i></button>
<script>
   function myFunction() {
      $("body").toggleClass("dark-mode-bg");
   }
</script>
```

Os estilos utilizados são os existentes no próprio Bootstrap além de outros adicionais que estão no arquivo ```custom.css```.Você pode altera-los para que fiquem de acordo com as suas necessidades.

Leia mais sobre o assunto [aqui](https://www.ciromoura.com.br/usando-jquery-para-alterar-tema-no-bootstrap/) e você pode ver o exemplo [aqui](https://ciromoura.github.io/darkmode/). 
