# Conceitos de computação I

## Aula 1 - História e desenvolvimento da TI
Condições, Conceitos, princípios e nomes asssociados a origem da Tecnologia da informação:
- [Princípio da computabilidade - David Hilbert](https://pt.wikipedia.org/wiki/David_Hilbert)
- [Alan Turing](https://pt.wikipedia.org/wiki/Alan_Turing)
- [Trasistor e componentes integrados]()
- [Curva de Gartner](https://youtu.be/dTSvJnORvaY)

Ao longo do século XX houve grande avanço no papel da tecnologia da informação na sociedade como um todo. O que antes estava restrito ao meio impresarial passou a ser adotado em diversos campos da sociedade transformando a tecnologia da informação em um setor econômico, um tipo de negócio, e não mais apenas uma ferramenta para empresas.

A miniaturização e o barateamento do custo de produção de componentes eletrônicos possibilitou a disseminação do uso de sofwares e hardwares por amplos estratos da sociedade. Os computadores pessoáis tornaram-se cada vez mais acessíveis e o volume de dados gerados cada vez maior.

Dentro de sistemas TI dados são armazenados, processados e transformados em informações, que por sua vez são interpretadas, produzindo conhecimento. Por exemplo: graças aos sistemas de TI é possível que possamos mapear e identificar variações históricas nas estátísticas de emprego por setor econômico e cíclos de evolução de tecnologias, como na Curva de Gartner.

Até o o século XIX houve uma série de tentativas de criação de maquinas de calcular. Embora algumas dessas máquinas tenham se tornado operacionais, elas possuíam falhas que dificultavam a adoção. Esses são alguns nomes envolvidos na criação dessas máquinas:

- Wilhelm Schickard
- Blaise Pascal
- Gottfried Wilhelm Leibniz

O salto tecnológico para a modelagem digital de problemas do mundo físico só fol possível a partir do desenvolvimento da lógica formal e matemática, utilizando o sistema binário, lançada pelo matémático [Gottfried Wilhelm Leibniz]("https://pt.wikipedia.org/wiki/Gottfried_Wilhelm_Leibniz"), e plea criação da lógica booleana ( [George Boole]("https://pt.wikipedia.org/wiki/George_Boole") ), que possibilitou a contrução dos circuitos lógicos.

O desenvolvimento da computação no séculos XX e XXI é fruto do trabalho conjunto de diversos pesquisadores de diferentes campos do saber.

## Aula 2 - A transformação do dado à criação do conhecimento

## Aula 3 - Sitemas de numeração binário, decimal e hexadecimal

O surgimento de cada sistema numérico e de medidas é correlacionamdo à uma necessidade.

### Referências fundamentos e complementos:
- (Teoria dos conjuntos)[https://www.todamateria.com.br/teoria-dos-conjuntos/]
- (Conjuntos numéricos)[https://www.todamateria.com.br/conjuntos-numericos/]
- (Funções matemáticas)[https://pt.wikipedia.org/wiki/Fun%C3%A7%C3%A3o_(matem%C3%A1tica)]
- (Espaço euclidiano)[https://pt.wikipedia.org/wiki/Espa%C3%A7o_euclidiano]

### Agrupamento de bits e seus nomes

| Nº de bit | Nome |
| --------- | ---- |
| 4 | nible |
| 8 | byte |
| 16 | word |
| 32 | double word |
| 64 | quad word |

### Sistema BCD e conversão direta entre decimais e binários
BCD = decimal codificado como binário

| Decimal | BDC | Binário convertido |
| ---- | -------------- | ---------------- |
| 953 | 1001 0101 0011 | 1110111001 |
| 9381 | 1001 0011 1000 0001 | 10010010100101 |

### Operações numéricas
O nº de possibilidades binárias expressas em decimais: de 0 a 2^n – 1

Conversão de Dcimal para bináro MSb e LSB (p = posição; b = base):

25(b10) = 16 + 8 + 1 = 2(p4) + 2(p3) + 0(p2) + 0(p1) + 2(p0) = 11001(b2)

Primeiro vamos procurar o número mais próximo de 25(b10) que seja uma potência de 2, encontraremos 16(b10) que é 2^8. Em seguida vamos procurar as próximas potências de 2 que somadas a 16(b10) resultem em 25(b10). Temos: "25(b10) = 16 + 8 + 1". Agora vamos para as posições dos bits encontrar o MSB. Observe que 16(b10) é um número de 5 bits, pois com 4 bits só podemos contar decimais de 0 a 15. Cinco bits significa cinco posições para colocar valores de 0 a 1. As posições são contadas a partir de 0: "25(b10) = 16 + 8 + 1 = 2(p4) + 2(p3) + 0(p2) + 0(p1) + 2(p0)". O valor do MSB na posição 4 é 1, pois 16(b10) = 10000(b2). Vamos agora para o LSB que é 1(b10) = 00001(b2), logo p(0) = 1. Lembrando 8(b10) foi o outro encontrado, vamos converte-lo para binário: 1000(b2). Agora basta somar os binários: 10000 + 1000 + 00001 = 11001. 

## Aula 4 - 