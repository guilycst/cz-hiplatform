# cz-hiplatform

## O que isso faz?
Ao commitar usando commitzen, uma série de promps são exibidos para coletar as informações que serão inseridas na mensagem do commit.

## E por que isso é útil?
Padronização das mensgens de commit, rastreabilidade do tipo e origem das alterações.

## Que padrão?
"tipo-mudanca(codigo-estoria-backlog): Mensagem do commit" => "feat(5444): created claudioformation"

## Requerimentos:
 - Node.js

## Passos instalação:

	npm install -g commitizen

	npm install -g cz-hiplatform
	
	echo '{ "path": "cz-hiplatform" }' > ~/.czrc

## Executando:
	
	git add .
	
	git cz

## Saber mais:

    https://github.com/commitizen/cz-cli

