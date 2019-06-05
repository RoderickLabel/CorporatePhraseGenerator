# CorporatePhraseGenerator

Uma forma f�cil de discutir em reuni�es corporativas, trata-se de uma API que pode gerar at� 10000 frases, portanto, ser� f�cil impressionar sua equipe.

## Requirements

	* NodeJS
	* Express

## Instala��o

Ap�s clonar o reposit�rio, acesse ele e rode o node com segundo armento app.js e o terceiro argumento o n�mero da porta desejada.

```sh
cd CorporatePhraseGenerator
node app.js 8080
```

Pronto, sua API j� est� pronta para consumo, para testar sua API vi curl:

```sh
curl -X GET \
  http://localhost:8080/get-phrase \
  -H 'Content-Type: application/json' \
  -H 'cache-control: no-cache'
```