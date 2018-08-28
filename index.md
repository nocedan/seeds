---
layout: default
---

Se você trabalha com educação, tecnologia, ou é um curioso sobre o tema, é muito provável que você consiga usar seu tempo livre para inspirar e desenvolver os talentos de crianças e jovens de sua comunidade ensinando programação e criatividade com a sugestão de roteiro e as ferramentas que apresentamos nesta página.

Aqui, você irá encontrar direções para se tornar um tutor de crianças e jovens da sua comunidade, criando um espaço para que desenvolvam suas potencialidades usando a tecnologia. Nas aulas deste projeto, pudemos observar que a criatividade e raciocínio lógico são naturais para jovens e gostaríamos de incentivá-los a reconhecer estes talentos e desenvolvê-los.

Se você não tem experiência com ferramentas didáticas de programação, o roteiro de aulas proposto aqui também poderá servir como ponto de partida para o seu aprendizado. 

# Scratch, code.org, Programaê e Raspberry pi

Estes são recursos que já foram testados em sala de aula. Em particular, o Scratch e o code.org são os principais referenciais para o roteiro sugerido nesta página.

## Scratch

Software gratuito (MIT Media Lab desde 2007) no qual jovens são encorajados a criar as suas próprias histórias, jogos e animações interativos. Permite a criança a se ver como alguém que constrói com tecnologia e não apenas consumidores. Atualmente, disponível em versões online e offline, inclusive para Raspberry pi e está disponível em Português.

> Scratch helps young people learn to think creatively, reason systematically, and work collaboratively — essential skills for life in the 21st century.


Veja uma demonstração [aqui](https://youtu.be/-SjuiawRMU4).

## code.org

O code.org é uma instituição sem fins lucrativos, que visa incentivar pessoas a dar os primeiros passos com programação. No site, encontramos diversos jogos e ferramentas didáticas, disponíveis também em português. As aulas frequentemente são introduzidas com vídeos onde personalidades como Mark Zuckerberg e Bill Gates, que falam sobre sua experiência pessoal com os tópicos presentes naquele módulo, por exemplo.

## Programaê

O Programaê! é um portal que reúne recursos para incentivar jovens a entrar em contato com a tecnologia. Entre os recursos estão disponíveis trilhas de aprendizado e planos de aula. Em geral, os recursos fazem referência a terceiras partes como o Scratch, code.org ou Codeacademy, ajudando na navegação do usuário pela grande variedade de recursos disponíveis para aprender a programar.


## O Raspberry Pi

O [Raspberry Pi](https://www.raspberrypi.org/) é um computador pequeno e barato, que pode ser utilizado para aprender a programar. Além de abrir a possibilidade de muitos projetos que envolvem automação e robótica, no nosso contexto atual é uma forma acessível de ensinar programação, introduzir o ambiente Linux e também mostrar as crianças o potencial enorme desta pecinha fofinha de hardwere.

Para completar o roteiro, é sugerida mas não mandatória a utilização do Raspberry Pi, como uma forma de baixar os custos de montagem da turma e também como demonstração deste hardwere que possibilida muitas possibilidades.

No Brasil, é possível comprar o um Pi homologado pela anatel na loja [flipe-flope](https://www.filipeflop.com/)

# Roteiro de aulas

Este roteiro, já foi testado e melhorado de forma iterativa a partir das observações em sala de aula. Consiste em 5 aulas, que cobrem o básico da programação de computadores através da linguagem Blockly, utilizada pelo Scratch e pelo code.org.

Na primeira aula, programação com blocos é introduzida através de exercícios do code.org. Em seguida, migramos para o Scratch, que permite a exploração de recursos mais avançados da programação para a criação de animações e jogos.

Cada aula da sequência abaixo tem em média 50min a 1h de duração e foram testadas em turmas de 2 a 4 alunos.

### Aula #1: Familiarização com a linguagem de blocos

#### A. O que é o Scratch? Aquecendo os motores com a Hora do Código.

* Neste tópico, faça uma breve introdução ao curso, que terá 5 aulas de aproximadamente 1h. "Neste curso, iremos produzir animações e jogos de nossa autoria utilizando um softwere chamado Scratch...". Utilize os Slides 1 e 4 [desta apresentação](https://docs.google.com/presentation/d/1dkvSEHCMYBlGNXV8NyX8ZepeL31WmDHjnhy5MjPJkSM/edit?usp=sharing). 	e dê o play no vídeo do Slide 4.

* Mostre e deixe que manuzeiem o Raspberry Pi. Fale um pouco sobre ele, quanto custa, possibilidades de projetos... etc.


#### B. Programando com Blocos

* "Para aquecer os motores iremos iniciar com a Hora do código". O foco desta aula, será a programação por blocos, proposta na seleção de atividades do code.org, feita pela [Hora do código](http://programae.org.br/horadocodigo/).

* Inicie pela siga pela trilha do [labirinto](https://studio.code.org/hoc/1?utm_source=programae&utm_campaign=HoraDoCodigo&utm_term=AngryBirds). Esta trilha contém atividades com os personagens do Angry Birds, Plants and Zombies e Era do Gelo.

* Não é necessário que sejam completados todos os estágios, sendo o objetivo apenas a familizarização com a programação por blocos e os conceitos propostos.

* Como os vídeos são em inglês, e muitas crianças não tem familiaridade ou paciência com as legendas, fica para o tutor a missão de introduzir os conceitos necessários para cada etapa do labirinto.

* Uma possibilidade é que ao completar a parte do Angry Birds (1/3 do labirinto) ou a Plants and Zombies (2/3) inicie-se a atividade do [Star Wars](https://studio.code.org/s/starwarsblocks/stage/1/puzzle/1?utm_source=programae&utm_campaign=HoraDoCodigo&utm_term=StarWarsBlocos), que têm forte apelo para os fãns da série.

* Se houver alguma criança com dificuldade de leitura, é recomendado um [labirinto](https://studio.code.org/s/course1/stage/7/puzzle/1) especial para crianças que não foram alfabetizadas.

#### C. Até a próxima!

* Para se despedir, dar o play na seguinte [animação do Scratch](https://scratch.mit.edu/projects/223410020/) como forma de inspirar e motivar as próximas aulas.

### Aula #2: Primeiro projeto no Scratch!

#### Introdução: algoritmos e tecnologia

* Na aula anterior, utilizamos uma sequencia de blocos de instruções para gerar um comportamento mais complexo dos personagens no labirinto. A esta sequência de instruções que tem um objetivo, chamamos de algoritmo.

```
Algoritmo
substantivo masculino

 1.matemática
 Sequência finita de regras, raciocínios ou operações que, 
 aplicada a um número finito de dados, permite solucionar
 classes semelhantes de problemas.
    
 2.informática
 Conjunto das regras e procedimentos lógicos perfeitamente
 definidos que levam à solução de um problema em um número
 finito de etapas.

(Dicionário do Google)
```
* Os algoritmos estão presentes na maioria das aplicações mais excitantes da tecnologia. Aqui, seguem dois videos, para motivar o inicio da aula. [Ping pong robótico](https://www.youtube.com/watch?v=tIIJME8-au8) e [Atlas (terminator)](https://www.youtube.com/watch?v=fRj34o4hN4I).

#### Corrida Olímpica

* Chame os alunos em sequência para competir na [Corrida Olímpica](https://scratch.mit.edu/projects/241855361/) Os alunos geralmete se divertem quando descobrem que você está utilizando a tecla 't' para ganhar todas as partidas. Geralmente replicam esse tipo de truque nos projetos deles.

* Se você não tem familiaridade com o Scratch. No editor online, basta seguir o seguinte [tutorial](https://cdn.scratch.mit.edu/scratchr2/static/__0e83330413f7a7b5731284573c98ccdc__/help/en/howto/racegame-intro.html). Caso você prefira, clicando no botão de ajuda do scratch (?) e depois em "All Tips" há uma variedade de tutoriais, inclusive este.

* Agora com o Scratch aberto, passo a passo, vá guiando os alunos na construção de um análogo da Corrida Olímpica de sua propria autoria. Primeiro você pede para que escolham um fundo de tela, depois dois personagens e logo em seguida ensina os comandos de movimento de cada personagem. Não esqueça de escolher uma trilha sonora inspiradora!

* Sugerimos que isso seja feito junto com os alunos e no tempo deles. Como a experimentação faz parte do aprendizado, não é aconselhavel apressar as coisas ou se manter rigidamente no escopo da Corrida Olímpica.

* Segue um exemplo interessante de uma aluna que substituiu a competição por um [passeio de amigos com personagens de sua criação](https://scratch.mit.edu/projects/241859454/).

### Aula #3: If Else Dragon (ou Dragão Se Senão)

#### Projeto If Else Dragon
* [Este projeto](https://scratch.mit.edu/projects/230247777/) permite que o aluno aprenda maneiras de introduzir movimentações mais complexas dos personagens. Inicie a aula convidando os alunos a interagirem com os movimentos do dragão e mostrando a decomposição destes movimentos em duas partes: o movimento pelas setas e o movimento de zig zag que ele faz o tempo todo.

* A sugestão para esta aula, é que os alunos sejam guiados passo a passo, a começar pela escolha dos personages e fundos de tela.

* Na escolha dos personagens, é interessante que estes possuam mais de uma fantasia (ou seja, tenham movimentação). Assim, quando for apertada uma certa tecla, a movimentação inicia e termina com a tecla sendo solta, com o mecanismo If Else (Se Senão).

* Assim como na aula anterior, o output pelos alunos pode ser muito diferente do que foi proposto. Essa experimentação criativa é muito saudável e os mantém motivados.

* Este é um [exemplo](https://scratch.mit.edu/projects/241860300/), no qual um aluno desviou bastante da proposta, e criou um projeto muito interessante. Ele manteve algumas das movimentações complexas presentes no Dragão e adicionou outras que substituiram o bloco If Else. 

### Aula #4: Remix

#### Inspiração

* A [animação OvO](https://scratch.mit.edu/projects/144875945/#player) é um belissimo exemplo de projeto no Scratch. Começamos a aula com esta inspiração. Vale abrir o 'see inside' e clicar em Costumes (Fantasias) para visualizar a mudança de fantasias do personagem em tempo de execução. 

#### Remixando um projeto

* Um remix, é algo que os programadores fazem com frequência. Utilizar um código ou projeto pronto para modificar de forma que atenda seus objetivos. Também é uma forma excelente de aprender com o código de outros programadores.

* Nesta aula, o aluno é encorajado a utilizar o conhecimento que já possui e também experimentar com novos blocos enquanto faz um remix de um projeto a sua escolha (nossa sugestão é o próprio OvO).

* Entre as mudanças estão o tamanho dos personagens, seu movimento e velocidade, o Fundo de Tela, a música, etc...

* No Scratch online, basta clicar no botão de remix. Se estiver offline, basta carregar o projeto e começar a alterá-lo.

* [Um exemplo de remix]() do proejeto acima.

### Aula #5: Polígonos

#### Desafio: Polígonos

* Objetivos: Trabalhar com geometria e funções utilizando um projeto que desenha [polígonos com a quantidade de lados dada pelo usuário](https://scratch.mit.edu/projects/241897074/#player).

* Inicie a uma demonstração, pedindo aos alunos que dêem um número de lados para que vejam o resultado. O que acontece quando o número de lados fica muito alto, como 100? Notaram que os lados do polígono possuem diferentes cores?

* O passo a passo consiste em introduzir para eles a caneta e o apagador, mudar a espessura do desenho e também as cores.

* Pedir para que desenhem um zigue zague, introduzindo o movimento de girar e também ensinando como funcionam os ângulos.

* Com um bloco de repetição, desenhar um quadrado.

* Extender o quadrado para um polígono de número fixo de lados

* Introduzir a variável com a resposta do usuário e com isso criar uma função que executa o desenho para um número qualquer de lados.

* Reduzir o tamanho dos lados do polígono, conforme aumentam o número de lados, para que a função seja escalável.
