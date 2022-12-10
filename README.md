# s322112022
Repositório da turma de Java 3 (22/11/2022)

# Exercício Prático

Crie o seguinte endpoint (rota): **/calculadora/operacao**

Seu endpoint deve receber a entrada abaixo:

```
{
    "operandoA": 2,
    "operandoB": 2,
    "operador": "+"
}
```

Seu endpoint deve devolver a resposta abaixo:

```
{
    "operandoA": 2,
    "operandoB": 2,
    "operador": "+",
    "descricaoOperacao": "soma",
    "resultado": 4,
    "binario": 10
}
```

Para converter um número em binário utilize o método **toString** da interface **IBinario**: 

- Adicione a lib fuctura.jar no seu classpath
- Adicione a dependência:

```
<groupId>br.com.fuctura</groupId>
<artifactId>fucturaUtils</artifactId>
<version>0.0.1-SNAPSHOT</version>
```
- Crie um bean do tipo IBinario


Caso o operador seja diferente de: +, -, / e *; **retorne uma mensagem no response 
informando que não é permitido essa operação**.

Utilize a arquitetura de divisão em camadas que vimos em sala de aula.


## Formulário para Envio da Atividade

https://forms.gle/rrKHfDQNug1CP7Y8A


# Exercício Teórico

https://forms.gle/xkJ3zjffHZKTAETh6


## Prazo: 05/12/2022
