# Pramação Orientada a Objeto com C#.

### Programação orientada a objetos (**POO**) é um paradigma de programação baseado no conceito de "*objetos*", que podem conter dados na forma de campos, também conhecidos como *atributos, e códigos, na forma de procedimentos, também conhecidos como métodos*.

E precisamos falar também dos 4 Pilares da **POO**. 
- Abstração;
- Encapsulamento;
- Herança; e
- Poliformismo.

## Abstração
O conceito de abstração consiste em esconder os detalhes de algo, no caso, os detalhes desnecessários.
No mundo real, utilizamos abstrações o tempo todo. Tudo que não sabemos como funciona por baixo dos panos pode ser considerado uma abstração.
Para exemplificar melhor, vamos tomar como exemplo a concessionária que realiza manutenções no seu carro. Você leva ele até lá com um problema e ele volta funcionando.
Em suma, pouco importa os detalhes do que aconteceu durante a manutenção do seu carro, o que importa é que ele voltou funcionando.

## Encapsulamento
Ainda usando a analogia do carro, sabemos que ele possui atributos e métodos, ou seja, características e comportamentos. Os métodos do carro, como acelerar, podem usar atributos e outros métodos do carro como o tanque de gasolina e o mecanismo de injeção de combustível, respectivamente, uma vez que acelerar gasta combustível.

No entanto, se alguns desses atributos ou métodos forem facilmente visíveis e modificáveis, como o mecanismo de aceleração do carro, isso pode dar liberdade para que alterações sejam feitas, resultando em efeitos colaterais imprevisíveis. Nessa analogia, uma pessoa pode não estar satisfeita com a aceleração do carro e modifica a forma como ela ocorre, criando efeitos colaterais que podem fazer o carro nem andar, por exemplo.

Dizemos, nesse caso, que o método de aceleração do seu carro não é visível por fora do próprio carro. Na POO, um atributo ou método que não é visível de fora do próprio objeto é chamado de "privado" e quando é visível, é chamado de "público".

Mas então, como sabemos como o nosso carro acelera? É simples: não sabemos. Nós só sabemos que para acelerar, devemos pisar no acelerador e de resto o objeto sabe como executar essa ação sem expor como o faz. Dizemos que a aceleração do carro está *encapsulada*, pois sabemos o que ele vai fazer ao executarmos esse método, mas não sabemos como - e na verdade, não importa para o programa como o objeto o faz, só que ele o faça.
  
>A **POO** surgiu como uma alternativa de aproximar o manuseio das estruturas de um programa ao manuseio das coisas do mundo real, daí o nome "objeto" como algo genérico, que pode representar qualquer coisa tangível. Esse novo paradigma se baseia principalmente em dois conceitos chave: *classes e objetos*. Todos os outros conceitos, igualmente importantes, são construídos em cima desses dois.

### Referência
Aqui temos uma ótima matéria sobre **POO**, que explica muito bem em detalhes alguns dos pilares. 
Recomendo a leituraa da matéria [clicando aqui.](https://www.alura.com.br/artigos/poo-programacao-orientada-a-objetos)

