Para iniciar a utilizacao da propriedade precisamos de um container e aplicar a propriedade à mesma

PROPRIEDADE DOS CONTAINERS:

Display:flex;
ou
Display: inline-flex; (faz o mesmo, so q inline)

---

flex-direction: row; / row-reverse; (por padrao o display:flex ja vem como row, ou seja alinha os conteudos um do lado do outro)
e
flex-direction: column; (alinha os conteudos em coluna, colocando um a baixo do outro)

---

flex-wrap: nowrap; (O display flex sempre vai colocar todos os conteudos na mesma linha por ter essa propriedade por padrao)
e
flex-wrap: wrap; (Resolve a questao do nowrap, colocando o conteudo que nao couber na mesma linha do container na proxima linha)
e
flex-wrap: wrap-reverse; (mesmo que o wrap, porem os items sao distribuidos de baixo pra cima)

---

(define o alinhamento dos items em um container em relacao ao eixo principal/HORIZONTAL (X))
justify-content: flex-start; (alinha ao inicio do container)
justify-content: flex-end; (alinha ao final do container)  
justify-content: center; (alinha ao centro do container)  
justify-content: space-between; (cria um espacamento entre os elementos prenchendo todo container)  
justify-content: space-around; )
justify-content: space-evenly;

---

(funciona de forma parecida com justifycontent, porem com alteracoes em relacao a eixo TRANSVERSAL/VERTICAL (Y) do container)

align-items: flex-start; (posiciona os elementos na parte superior do container)

align-items: flex-end; (posiciona os elementos na parte inferior do container)

align-items: center; (posiciona os elementos ao centro do container)

align-items: stretch; (faz os conteudos preencherem todo o container verticalmente)

align-items: baseline; ()

---

(alinha as LINHAS de um container removendo sensacao de espaco sobrando no eixo TRANSVERSAL/VERTICAL (Y))

align-content: flex-start; (posiciona as linhas do container ao topo do mesmo)

align-content: flex-end; (posiciona as linhas do container a parte inferior do container)

align-content: center;

align-content: stretch;

align-content: space-between;

align-content: space-around;

---

PROPRIEDADES DOS ITEMS:

os items sao ordenados com base na forma que foram colocados no codigo

order: <integer>; (muda a ordem dos elementos no container)

flex-grow: <numero>; (define o espaco que o item ocupara do container)

flex-shrink: <numero>; (defini a habilidade de incolher no container)

flex-basis: ;

flex: none | [<'flex-grow'> <'flex-shrink'>? || <'flex-basis'>]

align-self: auto | flex-start | flex-end | etc (alinha apenas um elemento no container utlizando atribudos iguais os align-items)
