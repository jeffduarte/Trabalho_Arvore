Descrição

Programa que demonstra o funcionamento da estrutura de dados Árvore.
Programa que constrói uma árvore binária e demonstra o seu funcionamento.
Inserindo pessoas e formando automaticamente laços familiares entre elas,
seguindo restrições postas pelo professor como casamento apenas entre pessoas de sexo oposto 
e impossibilidade de relações incestuosas(Com pessoas da mesma família).

Ele tem 3 arquivos de cabeçalho: Arvore.h, metodos.h e Nomes.h

Arvore.h, tem as funções mais intrínsecas da estrutura, como buscar, inserir
deletar(Embora não usada), imprimir em órdem, pós órdem ou pré órdem, além
de ser onde é declarado as funções e variáveis globais além da própria struct
da árvore binária de busca.

Em metodos.h, existem funções mais avançadas e específicas para o funcionamento do nosso programa
Funções que qualifica os nomes em órdem alfabética como ela é ordenada, função que muda os
sobrenomes das pessoas em caso de casamento, que imprime pessoas com parentesco, que casa pessoas,
cria nomes, cria os filhos dos casais, etc. É o cerne do funcionamento do programa.

Por fim, Nomes.h, onde ficam as variáveis Nomes_femininos, Nomes_masculinos, Sobre_nomes, onde
cada uma tem nomes para serem usados na construção das pessoas na árvore, tendo 40 femininos
40 masculinos e 60 sobrenomes, podendo assim obter 2400 nomes femininos diferentes e 2400 nomes
masculinos diferentes, totalizando até 4800 combinações de nome.

O programa funciona da seguinte forma, primeiro ele cria os promogênitos da árvore geneológica,
casais esses que são o início de cada família a ser gerada dali, sem pais, ou qualquer outro
parente além da esposa, e deles são derivados filhos, onde podem ser gerados de 1 a 4 aleatóriamente,
o programa casa esses filhos com os de outro casal primogênito, assim derivando mais filhos
e mais parentescos, sendo que o sobrenome do conjuge masculino, o marido, é o que
passa para os filhos, com esses casamentos e criação de filhos a árvore vai sendo preenchida
até chegar ao limite de 300 pessoas.

Funcionamento


Primeiro é exibido um menu com as seguintes opções:

1 - Busca: Procura uma pessoa na árvore e mostra seus parentescos.
2 - Enche a Árvore: Preenche a árvore com um número determinado de famílias iniciais.
3 - Imprime Famílias: Mostra o nome de todas famílias geradas.
4 - imprime em Ordem: Imprime o nome de todas pessoas armazenadas em ordem.
5 - Printa número de nós da arvore: Mostra quantas pessoas tem armazenadas na árvore.
6 - Sai do Programa: Sái do programa

É um programa interessante que exemplifica muito bem como funciona a estrutura de árvore binária de busca.


Atividade de Estrutura de dados I, MATA40 UFBA 2014.2
Atividade do professor Danilo Silva dos Santos.

					Implementado completamente por Jeferson Duarte de Oliveira Barbosa Filho.
							2014.
