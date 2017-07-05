# Autoload Lojas Virtuais BR

Precisa-se instalar o Node.js

Após isso, será necessário baixar o AutoloadLojasVirtuaisBR,
com: 

`git clone https://github.com/MuriloEduardo/AutoloadLojasVirtuaisBR.git`
 
 na pasta que desejar.

Depois, no terminal de comando, executar: 

`cd /Caminho/MeuComputador/Ate/AutoloadLojasVirtuaisBR/`

`npm install && npm start`

A pasta de trabalho, será layouts, nela irão as pastas de cada cliente e seu respectivo código.

Tal pasta deverá ter um nome de estrutura obrigatoria: `Cod_Loja="codigo_da_loja_cliente"`
Com isso sabe-se para qual cliente se esta trabalhando.

Para cada cliente se criará uma pasta.
O arquivo salvo dentro dela irá igual para esse cliente.

Dentro desta pasta `Cod_Loja="codigo_da_loja_cliente"`,
Só valerá o último arquivo lido, por isso usar um único arquivo para manipular o HTML do Layout Avançado é o mais indiciado.

## IMPORTANTE

Para que o layout seja salvo, você deverá estar logado nas Lojas Virtuais BR como Administrador, e, ter logado também com o codigo do cliente.