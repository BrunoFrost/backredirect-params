# backredirect-params
O objetivo, é definir uma página de redirecionamento caso haja intenção de sair da página atual, além de manter os parâmetros da URL da página atual, na próxima página ou página redirecionada..

# utilização
Todas as páginas que tiverem o script, poderão definir uma 2º página de redirecionamento e também irão passar a 'carregar' os parâmetros para as próximas páginas.
A função de backredirect poderá ser desativada a qualquer momento, mantendo apenas o keep-params.
No backRedirect também poderá ser habilitado a função intentExit. Nesse caso apenas movendo o mouse para fora da página, será feito o redirecionamento. 

Para isto, basta criar um: 
```<script src="https://brunofrost.github.io/backredirect-params/backredirect-params.js"></script>``` 
ao final da tag body.

# mas porque eu utilizaria isto?
Simples! Ser redirecionado para uma 2º página após uma intenção de saída, aumenta ainda mais a chance de conversão em venda. Já em relação aos parâmetros, plataformas de afiliados, utilizam os parâmetros (utm_sources) para identificar a origem da venda.
Ao utilizar o keep-params, os parâmetros seguirão o usuário por todas as páginas do site. Ou seja, ele vai chegar no checkout ainda com seus parâmetros, tornando fácil às plataformas de afiliados determinarem de onde o lead veio.

