# Grafos em grupos de WhatsApp

<img src="imagens readme/exemplo.png" alt="Exemplo">

## 1 - Como a rede é modelada
Cada membro do grupo é representado como um vértice no grafo. Uma aresta direcionada do membro A para B é criada quando A menciona B numa mensagem, utilizando o @. Seu peso é igual à quantidade de vezes em que essas menções ocorrem. Considere o exemplo abaixo.

<img src="imagens readme/exemplo_marcacao.png" alt="exemplo de marcação">

A mensagem acima é modelada como:

<img src="imagens readme/exemplo_grafo.png" alt="exemplo 2">

## 2 - Entrada

Em primeiro lugar, é necessário exportar a conversa do grupo para um arquivo .txt. Isso pode ser feito ao clicar no botão de opções do grupo e, depois, em "Mais". Selecione a opção de exportar sem mídia.
<img src="imagens readme/kebab.jpeg">

Além disso, é necessário outro arquivo .txt com o nome e número de telefone de cada membro do chat. Este arquivo deve estar na seguinte forma:
```
nome,numero
"Mateus","5521999999999"
"Lucas","5521888888888"
"Marcos","5521777777777"
"João","5521666666666"
```

## Saída
A saída é um grafo direcionado com arestas cujos pesos são iguais à quantidade de vezes em que as marcações ocorreram. Para ver exemplos de métricas de vértice, acesse o arquivo .ipynb

Obrigado por ler até aqui :)
