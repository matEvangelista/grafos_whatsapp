# Grafos em grupos de WhatsApp

<img src="exemplo.png" alt="Exemplo">

## 1 - Como a rede é modelada
Cada membro do grupo será representado como um vértice no grafo. Uma aresta direcionada do membro A para o B é criada quando A menciona B numa mensagem, utilizando o @. Seu peso será igual à quantidade de vezes em que as menções ocorrem. Considere o exemplo abaixo.

<img src="exemplo_marcacao.png" alt="exemplo de marcação">

A mensagem acima será modelada como:

<img src="exemplo_grafo.png" alt="exemplo 2">

## 2 - Qual é a entrada

Em primeiro lugar, é necessário exportar a conversa do grupo para um arquivo .txt. Isso pode ser feito ao clicar no botão de opções do grupo e, depois, em "Mais". Selecione a opção de exportar sem mídia.
<img src="kebab.jpeg">

Além disso, você precisa de um outro arquivo .txt com o nome e número de telefone de cada membro do chat. Este arquivo deve estar na seguinte forma:
```
nome,numero
"Mateus","5521999999999"
"Lucas","5521888888888"
"Marcos","5521777777777"
"João","5521666666666"
```
