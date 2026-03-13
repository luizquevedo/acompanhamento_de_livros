# Acompanhamento de Livros
Meu pai tem mais de 2000 livros, mas zero gerenciamento e zero controle. Vou montar uma solução como serviço de TI (ITIL 4).
----
## Sobre serviço de TI em ITIL 4 
## Muitos livros - o contexto 
## From Zero (controle) to Hero - efeitos e atos da solução
## A Stack
## Contato
----
## Sobre serviço de TI em ITIL 4 

Serviço de TI é, de cabeça, um ato ou performance que uma parte ou cliente deseja ou precisa para ter benefício ou gerar valor, entregue através de um grupo de ativos e demais recursos de TI, **sem que o cliente incorra nos custos** disso. Veja, eu sou ativeiro de TI de Banco. Meu dia a dia é contratos e licenças e fluxos de valor e ações IMAC (implement., movimentar, adicionar, _change_). Porém, também estudo soluções de TI como estudante de computação. Assim, ao enxergar uma questão aqui dentro de casa, tenho pensado em como puxar essa sardinha pra mim, juntando a fome com a vontade de comer.

## Muitos livros - o contexto 
Por 19 anos, meu pai não teve televisão (nem streaming). Então, ele sempre foi de ler muito e comprar muitos livros - inclusive repetidos. Juro - dos 2000 uns 500 devem ser repetidos (estimação sem base nenhuma). Em termos de escopo, não é um problema particular dele, visto que todos os livros repetidos são ou para presente, ou os preferidos dele.
Já minha namorada não tem tantos livros físicos, mas tem Kindle, então ela lê muito e muito além da coleção dela. Dessa forma, ela tem dezenas e dezenas de livros na "lista". Aliás, ela gostaria de ter uma lista estruturada das próximas leituras, que possa consultar e escolher fugindo da ressaca literária.
No fim das contas, a solução que imagino (mais detalhes em outro tópico) poderia ser estendida (extensão|expansão em Belk) para integrar coleções, bibliotecas ou editoras.

## From Zero (controle) to Hero - efeitos e atos propostos da solução

Se pudesse ver os títulos que já tem, meu pai ou qualquer pessoa convidada poderia comprar mais e comprar com confiança e sem culpa, talvez até com _smart shopper feelings_; poderia localizar os livros que já tem, reler, emprestar e presentear. Além de tudo isso, minha namorada, como uma pessoa que tem muitos títulos para ler (seja por vontade, seja por necessidade) pode passar menos tempo escolhendo o que ler, menos tempo planejando como ler, e mais tempo lendo efetivamente, mais tempo se envolvendo e até consumindo mais material de redes sociais]
Ainda, tudo isso tem um efeito final: compras. 
Minha tese é que ao eu fazer essa stack eu ganho muito com um projeto pessoal, meus leitores ganham muito com mais tempo de leitura, mais dinheiro e mais satisfação, confiança e demais efeitos psicológicos; e até grupos e empresas ganham marginalmente com mais compras e mais uso dos seus ecossistemas. Marginalmente porque não pretendo que isto seja um serviço formal, ainda que consiga ver um futuro em que isso seja atrativo para ganhar dinheiro.

## A Stack

1. Ler metadados via Skoob camera (um leitor de código de barras puxa ISBN & + )
2. Exportar JSON via busca:"skoob exportar csv"
3. IMAC via miniaplicação de linha de código (fazer protótipo; achar alguém pra ajudar com front)
4. Visualizar via Painel de acompanhamento via dashboard, pode ser com Python mesmo (acessável via endpoint na miniaplicação)

leitora adquire um livro
leitora escaneia o código de barras do livro
scanner extrai metadados do livro
metadados são CRUD na base de dados
base de dados aguarda programa
leitora abre programa
programa intermedia ações (1. instalar 2. mover 3. adicionar 4. alterar 5. painel)
leitora escolhe cadastrar livro novo
programa lê base de dados
programa prompta info (metadados + status)
leitora insere info
programa escreve base de dados
programa avisa leitora
leitora escolhe painel
programa lê base de dados
programa mostra dashboard
leitore escolhe alterar
programa programa prompta info (metadados + status)
leitora altera qualquer coisinha
programa escreve base de dados

Nota: por enquanto a pessoa, eu, cadastro manualmente. No futuro o programa faz sozinho.gfysgafygdfuyudfg

## Contato
