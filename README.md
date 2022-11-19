# Aula 02
- Envio de informações para o PHP 
- Operadores lógicos
- Operadores relacionais.
- Estrutura de decisão
- Redirecionamento de página


## Envio de informações para o PHP
- no arquivo do formulario é importante o *action* do form estar configurado para o arquivo do php que irá receber as informações.
- Importante escolher os métodos *get* e *post* qual o mais adequado para usar, lembrando que:
-- Get: envia as informações na URL
-- Post: envia as informações de forma oculta
- exemplo de formulário:
<form action="validar.php" method="post">
    Usuário:<input name="usuario"><br>
    Senha:<input name="senha" type="password"><br>
    <button type="submit">Entrar</button>
    <button type="reset">Limpar</button>
</form>

## Estrutura de decisão
-serve para você tomar uma decisão de acordo com o resultado de uma condição, caso o resultado seja TRUE você pode executar uma ação, caso seja FALSE pode executar outra ação

## Operadores relacionais
- `> maoir`
- `< menor`
- `>= maior igual`
- `<= menor igual`
- `!= diferente`
- `== igual`


### if simples
```php
if(condição){
    resposta verdadeira
}else{
    resposta falsa
}
```

### if else
```php
if(condição){
    resposta verdadeira
}else{
    resposta falsa
}
```
### if, else if, else
```php
if(condição){
    resposta verdadeira do if
}else if(condição){
    resposta verdadeira do else if
}else{
    resposta falsa
}
```

### redirecionamento de página
- 'header('Locaion: arquivo.php')'