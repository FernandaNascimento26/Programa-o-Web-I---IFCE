### CSS Interno
O CSS interno ou incorporado requer que você adicione a tags <style> na seção <head> do seu documento HTML.

Este estilo de CSS é um método efetivo de estilizar uma única página. Contudo, usar esse estilo em múltiplas páginas pode consumir muito tempo, já que você precisa definir as regras CSS para cada página do seu site.

## Vantagens de CSS Interno:

Classes e seletores de IDs podem ser usados ​​por stylesheet interno. Confira um exemplo abaixo:
.class {
    property1 : value1; 
    property2 : value2; 
    property3 : value3; 
}

#id {
    property1 : value1; 
    property2 : value2; 
    property3 : value3; 
}
Não há necessidade de carregar vários arquivos. HTML e CSS podem estar no mesmo arquivo.

## Desvantagens de CSS Interno:
Adicionar o código para o documento HTML pode aumentar o tamanho da página e o tempo de carregamento.