- O JOGO tem como função gerar numeros aleatorios para que o usuario acerte-o usando JavaScript.
tomei a liberdade e adcionei a função que ao apertar a tecla ENTER, voce ative a opção CHUTAR sem que necessite do clique.

```
 document.querySelector('input').addEventListener('keydown', function (event) {
    if (event.key === 'Enter') {
        verificarChute();
    }
});
