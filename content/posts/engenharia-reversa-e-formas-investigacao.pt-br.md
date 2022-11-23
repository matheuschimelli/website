---
title: "Engenharia Reversa e Outras Formas de Investigação Tecnológica"
author: "Matheus Chimelli"
date: "2022-11-04T12:00:00"
brief: "Diante das transformações da sociedade e com o surgimento de novas tecnologias, a engenharia reversa acabou passando por transformações para se adaptar às inovações da sociedade. O presente artigo busca de forma objetiva contextualizar a engenharia reversa realizando uma breve retrospectiva histórica desde sua utilidade no período da segunda guerra mundial até sua aplicação no campo tecnológico em especial na área de softwares. Não obstante, nesse sentido será apresentado de forma simples mas compreensível como funciona um programa de computador, o que são linguagens de programação e como um processador executa um programa de computador e além disso, este artigo buscará explicar como é feita a engenharia reversa em programas de computador de forma superficial mas profundamente concisa. Ainda assim, o presente artigo apresentará breves análises jurisprudenciais de casos envolvendo engenharia reversa e seus aspectos referentes à legalidade do seu uso."

tags:
    - engenharia-reversa
    - investigação-forense
    - jurisprudencia
---


---

[PDF do artigo](https://drive.google.com/file/d/1R_5_kMiC2BvlbqwLiPveecPE_79FzI0L/view?usp=sharing)

---

**Engenharia Reversa e Outras Formas de Investigação Tecnológica** 

*Reverse Engineering and Other Forms of Technological Research* 




**Matheus Chimelli[1]**


**RESUMO**

Diante das transformações da sociedade e com o surgimento de novas tecnologias, a engenharia reversa acabou passando por transformações para se adaptar às inovações da sociedade. O presente artigo busca de forma objetiva contextualizar a engenharia reversa realizando uma breve retrospectiva histórica desde sua utilidade no período da segunda guerra mundial até sua aplicação no campo tecnológico em especial na área de softwares. Não obstante, nesse sentido será apresentado de forma simples mas compreensível como funciona um programa de computador, o que são linguagens de programação e como um processador executa um programa de computador e além disso, este artigo buscará explicar como é feita a engenharia reversa em programas de computador de forma superficial mas profundamente concisa. Ainda assim, o presente artigo apresentará breves análises jurisprudenciais de casos envolvendo engenharia reversa e seus aspectos referentes à legalidade do seu uso. 


**Palavras chaves**: *Engenharia Reversa; Investigação Tecnológica, Jurisprudência*

**ABSTRACT**

In face of society's transformations and with the emergence of new technologies, reverse engineering ended up going through transformations to adapt to society's innovations. This article aims to contextualize reverse engineering by making a brief historical retrospective from its usefulness in the period of the second world war until its application in the technological field, especially in the area of software. Nevertheless, in this sense, it will be presented in a simple but understandable way how a computer program works, what programming languages are and how a processor executes a computer program. Besides that, this article will try to explain how reverse engineering is done in computer programs in a superficial but deeply concise way. Still, this article will present brief jurisprudential analyses of cases involving reverse engineering and its aspects concerning the legality of its use. 


**Keywords**:*Reverse Engineering; Technological Research, Jurisprudence*






**1 INTRODUÇÃO**


O termo engenharia reversa pode ser definido como técnica que permite realizar o descobrimento das idéias e princípios fundamentais que estão presentes em algo já existente[2]. A engenharia reversa pode possuir inúmeros objetivos, desde apenas descobrir como algo funciona ou até mesmo para extrair idéias e conceitos existentes em algo já feito para criar um produto mais competitivo.[3] 

Ao realizar uma análise histórica, observa-se que a engenharia reversa não é algo recente, a exemplo podendo-se citar a engenharia reversa realizada por militares soviéticos durante a segunda guerra mundial[4] e também durante o período da guerra fria, onde os mesmos utilizam de técnicas de engenharia reversa para descobrir como as aeronaves americanas funcionavam e então poderem reproduzir as mesmas.

Porém, com o passar do tempo houve o surgimento de novas tecnologias, podendo-se citar a exemplo o surgimento de computadores e o surgimento da internet. Não obstante, com o aparecimento de novas ferramentas e produtos, houve também a criação de técnicas de engenharia reversa que pudessem ser aplicadas a esse novo contexto.
No campo da tecnologia da informação, a engenharia reversa tem papel fundamental para realizar a análise de funcionamento, vulnerabilidade, bugs, anti-pirataria e adição de recursos em softwares e malwares.[5] Em todos esses casos, não há acesso ao código fonte original do software, e portanto por isso se faz necessário se utilizar de técnicas de engenharia reversa para realizar tais ações.

E em relação aos softwares, a engenharia reversa ajuda a descobrir os conceitos e princípios presentes em software compilado ou transpilado onde não há acesso ao código fonte original do mesmo. Não obstante, a engenharia reversa de malwares permite aos pesquisadores obterem conhecimento sobre como determinado malware age e atua dentro de computadores fazendo com que os mesmos possam criar soluções que inibam a ação de softwares maliciosos.




**2 ENGENHARIA REVERSA DE SOFTWARE **


Conforme abordado por Canfora, Penta e Cerulo[6], a engenharia reversa de softwares surgiu com a necessidade de realizar mudanças em softwares existentes onde não havia acesso ao código fonte original do mesmo. As origens remontam ao padrão IEEE-1219[7], onde há a recomendação de que seja realizada a engenharia reversa de softwares quando não existe a documentação ou a mesma seja insuficiente para realizar a análise de algum software. 
Engenharia reversa é um termo amplo, utilizado para representar uma lista de ferramentas e métodos que permitem extrair informações sobre o funcionamento de um software. Conforme explicam Chikofsky e Cross[8], a engenharia reversa consiste no processo da realização de análise de um sistema do seguinte modo: (1) acontece a identificação dos componentes do sistema e as inter relações entre eles e (2) a representação dos sistema em outra forma ou em uma forma de abstração de alto nível. Ainda segundo Chikofsky e Cross, engenharia reversa de softwares não inclui a mudança ou alteração de alguma forma, mas apenas a sua análise. 




**3 COMO FUNCIONA A ENGENHARIA REVERSA DE SOFTWARES**

Levando-se em conta que a engenharia reversa de softwares acontece nos softwares onde não se há o acesso ao código fonte original, se faz mister entender como estes funcionam e como são feitos.

Primeiramente, o software é um tipo de código que funciona em cima de um hardware. Essa relação pode ser comparada a um pianista e uma música. O pianista se equipara ao hardware, pois este executa, ou melhor toca uma música, e portanto, a música é comparada ao software, pois necessita de um lugar para ser executada[9].

Os softwares são feitos a partir de código. Os códigos por vez são feitos utilizando-se linguagens de programação. No campo da Ciência da Computação existem diferentes tipos de linguagens de programação, entre elas as compiladas e interpretadas. As linguagens interpretadas funcionam por meio de um programa que lê linha por linha certo código interpreta e executa o código, a exemplo pode-se citar Javascript, que é uma linguagem de programação interpretada que está presente em navegadores web. Assim sendo, se um software for escrito em uma linguagem de programação interpretada, para que o mesmo seja executado é necessário utilizar um outro programa que irá interpretar a mesma e executar. Por outro lado, as linguagens compiladas não possuem um interpretador, pois essas são convertidas diretamente para código de máquina sendo executadas por um processador. Antes de ser propriamente executado em um processador, um programa chamado de compilador é responsável por traduzir o código escrito em uma linguagem de programação de alto nível para código de máquina que será então executado em um processador. Softwares feitos em linguagens compiladas tendem a ser mais rápidos e mais eficientes do que os feitos em linguagens interpretadas. [10]

Tanto os softwares desenvolvidos em linguagens compiladas como os em interpretadas são passíveis de engenharia reversa. Como já mencionado, o presente artigo focará na engenharia reversa de softwares desenvolvidos em linguagens compiladas. Assim sendo, levando-se em conta que softwares desenvolvidos em linguagens compiladas são executados no processador faz-se mister saber como ocorre esse processo.
Um computador pode executar um software que serve para realizar determinada função, a exemplo pode-se citar um navegador de internet, que nada mais é do que um programa de computador que tem como propósito permitir acesso a rede mundial de computadores. Além disso, um computador é formado por diversas peças, entretanto, uma peça vital, se não a mais importante, é a CPU, sigla para central process unit ou unidade de processamento central. A função da CPU é processar, ou seja, executar instruções para realizar determinadas ações para determinados fins de um software. É como se fosse o cérebro de um computador, pois realiza todo o processamento da máquina.

A CPU irá executar as instruções contidas em um software, cabe relembrar que um software é feito por código e que a CPU também interpreta um código, porém este é diferente do primeiro. A CPU apenas executa machine code (código de máquina), por outro lado, os softwares são escritos em linguagens de programação que traduzem uma escrita léxica legível lógica em código de máquina. Essa diferença se faz necessária pois é muito mais fácil um software ser escrito utilizando uma linguagem de programação de alto nível como Python, C ou C++. Por outro lado, é muito mais fácil para uma CPU interpretar uma abstração mais baixa de código, no caso o código de máquina[11].


Figura 1 - Exemplo de código em linguagem de programação de alto nível, no caso C. O código a seguir retorna uma mensagem em um console com o texto “Hello World”.
  

Fonte: YURICHEV, 2016


Figura 2 - Exemplo da tradução do código acima em C para machine code (assembly) utilizando o compilador Microsoft Visual Code 2010 para processadores com arquitetura x86-x64
  

Fonte: YURICHEV, 2016


Assim como é possível observar nas imagens acima, desenvolver um software utilizando uma linguagem de alto nível torna o processo menos trabalhoso em comparação a escrever o mesmo utilizando código de máquina, além de permitir uma leitura fácil e clara sobre o que o código está executando. 




**4 ENGENHARIA REVERSA DE SOFTWARE NA PRÁTICA**


Para realizar engenharia reversa de software na prática é necessário utilizar alguns programas que ajudam a realizar esse trabalho. A exemplo, no presente caso, este artigo utilizará o software gratuito IDA Free - The interactive disassembler na versão 7.6. Ademais, a título exemplificativo será compilado um simples programa na linguagem C utilizado o compilador GCC versão 11.2.0 provido pelo programa MSYS2. O software será compilado utilizando o sistema operacional Windows com processador baseado na arquitetura x64 Intel. O código a ser compilado será o seguinte: 


Figura 3 - Trecho de código a ser compilado para exemplificação de como funciona engenharia reversa de softwares na prática. A linguagem de programação do código de imagem é C.
  

Fonte: Compilação do autor[12]


O código acima será compilado utilizando o seguinte comando: “gcc .\exemplo.c -o exemplo.exe”. Esse comando irá retornar um arquivo binário executável Windows® no formato “exe”. 
Após o software ter sido compilado será utilizado, conforme já mencionado, o programa IDA para realizar o dissassembly, isto é, transformar o resultado final do software, um executável, em um assembly. O dissassembly faz com que um executável binário, no qual somente a CPU consegue ler e entender, possa ser revertido em uma linguagem que permita a leitura humana.
Para tanto, foi aberto o programa IDA, e selecionando a opção New, para iniciar um novo projeto.

Figura 4 - Tela inicial do programa IDA.


  

Fonte: Compilação do autor[13]
Na tela inicial foram selecionadas as configurações padrões e então em seguida na navegação superior do software foram selecionadas as opções File > Open para abrir o menu de seleção de arquivos e então foi selecionado o executável compilado “exemplo.exe”.


  Figura 5 - Tela de seleção do software que será realizado o disassembly.
  

Fonte: Compilação do autor[14]
Em seguida foi aberto automaticamente um novo menu de seleção de opções e novamente, foram mantidas as opções padrões.


Figura 6 - Tela de opções de disassembly do programa IDA.
  

Fonte: Compilação do autor[15]




Figura 7 - Tela de opções de disassembly do programa IDA.
  

Fonte: Compilação do autor[16]




Após as configurações iniciais, o programa IDA retornou o assembly inicial do trecho de código acima exposto.


Figura 8 - Resultado do disassembly do código compilado exemplo.c utilizando gcc para Microsoft Windows® . A imagem abaixo apresenta o código assembly compilado em um processador x64 Intel.
  

Fonte: Compilação do autor


O código retornado descompilado se chama assembly. Conforme abordado por Wong, o código assembly funciona da seguinte maneira:


Figura 9 - Explicação detalhada de um código assembly
  

Fonte: WONG, Mastering Reverse Engineering


Começando da esquerda pela direita a legenda fica da seguinte maneira: primeiro há o rótulo ou indicação do endereço onde os dados vão ser processados ou armazenados na memória, o segundo item é o mnemônico, ou seja, uma abreviação da operação que será executada. O próximo item se chama operandos. É nessa parte que são definidas as instruções que especificam quais dados devem ser manipulados ou operados.[17] O último item é um comentário, não tendo efeito na execução do código.

Após o resultado da descompilação em assembly, começa-se a realizar a engenharia reversa por identificar o que cada mnemônico está fazendo e o que está sendo manipulado e então tentar transformar as instruções em assembly novamente para uma linguagem de alto nível, como por exemplo, transformar novamente em C.
Deste modo, a engenharia reversa de softwares não se limita a apenas analisar algo feito e tentar voltar ao início, mas se aplica também a descobrir como certo software funciona ou se comporta, e sempre, em todos esses casos, não há acesso ao código fonte original, sendo portanto, necessário a utilização de tais técnicas. 




**5 ENGENHARIA REVERSA E DIREITO À PROPRIEDADE INTELECTUAL**


Realizar engenharia reversa, como já mencionado, significa tentar  recriar algo pronto. Porém, nesse sentido, faz-se necessário saber o cerne no que tange os direitos do autor e engenharia reversa dentro do direito brasileiro.

A legislação não trata especificamente sobre engenharia reversa, mas a mesma abre margem para interpretações.

A lei nº 9.609/98[18] é a responsável por tratar da propriedade intelectual de programas de computador e conforme expresso no artigo 2° da mesma, à propriedade intelectual de programa de computador é o conferido às obras literárias pela legislação de direitos autorais. Logo, para verificar se realizar engenharia reversa sobre determinado programa de computador se caracteriza como quebra de propriedade intelectual é necessário recorrer à lei 9.610/98[19] que trata sobre a consolidação da legislação sobre direitos autorais. No artigo 46 da mesma se observa que a reprodução, desde que não visando a violação dos direitos do autor conforme previsto no artigo 184 do Código Penal[20], não se enquadra como violação dos direitos do autor, logo  reproduzir um software a partir do seu produto final, ou seja, do binário executável, desde que não se configure cópia, não se trata de violação ao direito do autor.




**6 ENGENHARIA REVERSA E INVESTIGAÇÕES E CASOS JUDICIAIS**


De acordo com Samuelson e Scotchmer, nos Estados Unidos da América, a engenharia reversa é o meio legal pelo qual se pode conseguir saber como certo produto foi feito.[21] O entendimento majoritário das cortes norte-americanas é consolidado no sentido de permitir a engenharia reversa. Ainda, em 1989 uma decisão da suprema corte norte-americana caracterizou a engenharia reversa como parte essencial da inovação, pois “mesmo que a engenharia reversa não retorne uma nova inovação, ela providencia aos consumidores produtos competitivos com preço baixo”. [22]

No âmbito nacional, ao realizar uma breve busca jurisprudencial nos tribunais brasileiros, pode-se encontrar casos relacionados a engenharia reversa e a posição do judiciário em relação a tais casos. Na Apelação Cível nº 0149214-47.2009.8.26.0100 do Tribunal de Justiça do Estado de São Paulo, o lide em suma era referente a uma suposta cópia de um software de home broker que determinada empresa havia lançado que se parecia muito com um outro software já presente no mercado. Nesse caso o perito judicial se utilizou de engenharia reversa para realizar a análise dos referidos softwares, e assim foi fundamentado o VOTO Nº 30016 do acórdão 0149214-47.2009.8.26.0100-SP[23]:

Engenharia reversa, conforme explicitado pelo perito judicial, é “procedimento utilizado para conhecer o funcionamento ou lógica de um programa (no caso de um software)”, ou seja, “não é sinônimo de pirataria, de cópia ilegal ou qualquer coisa nesse sentido, principalmente quando sua finalidade é experimental ou está relacionada a estudos, pesquisas científicas ou tecnológicas” (fls. 3.627). Vale dizer, o processo de engenharia reversa, por si só, não pode ser considerado ilícito, desde que não seja utilizado para a violação de direitos autorais.

[...]

sem que fosse revelado o código original do software da apelante, de modo que não se vislumbra qualquer ilegalidade do procedimento adotado pelo perito


Assim sendo, conforme observado na referida apelação cível é possível observar que a engenharia reversa é um meio utilizado para investigação para solução de lides e ainda não é um meio ilegal desde que não seja utilizado para violação de direitos autorais.

Em outro caso envolvendo engenharia reversa agora na Apelação Cível Nº 70050795517/2012 – RS[24], o acórdão foi assim expresso:
No caso do sistema UNIPDV, a autora pretendeu usar uma técnica denominada 'Engenharia Reversa', para produção do mesmo. Ou seja, a partir de uma funcionalidade conhecida pela equipe da ré, do funcionamento do sistema Softbox, a mesma procurou desenvolver programas semelhantes que cumprissem a mesma finalidade. É muito comum no mercado programas semelhantes, onde notadamente se usou engenharia reversa, as as linguagens de programação são diferentes, o que necessariamente leva a um desenvolvimento novo, embora com as ideias do original. Entretanto, a engenharia reserva só tem amparo legal quando as funcionalidades são as mesmas, mas os códigos usados para obter essas funcionalidades são diferentes. No caso em lide, até a linguagem de programação usada é a mesma e conforme demonstrado nesse laudo, muitos trechos têm coincidência de 100%, o que é comprovadamente cópia do original. (Grifo nosso)

No caso em tela, observa-se que pode-se considerar engenharia reversa quando as funcionalidades de determinado software são as mesmas, mas o código utilizado é diferente, caso contrário trata-se de cópia conforme observado no acórdão.

Nos breves casos judiciais envolvendo engenharia reversa de softwares analisados neste trabalho, observa-se que o entendimento dos tribunais é que engenharia reversa não se trata de uma ilegalidade desde que não haja a cópia do original ou violações de direitos autorais, sendo que a técnica até mesmo é utilizada por peritos judiciais. 




**7 OUTRAS FORMAS DE INVESTIGAÇÃO TECNOLÓGICA**

A engenharia reversa é apenas uma das diversas formas de investigação tecnológica existentes para solucionar casos. Em especial no campo criminal investigativo, diante da evolução da técnica utilizada por criminosos para cometerem delitos, o campo investigativo que atua na seara da inibição de tais delitos também precisa estar em inovação para inibir tais práticas. Conforme abordado por Soares[25], alguns dos mais recentes recursos tecnológicos alcançados foram:

cães farejadores, interceptações, câmeras e escutas variadas, aparelhos de raios-X, microfones direcionais, gravações, filmagens, fotografias, rastreadores de frequência, rastreamentos através de ground positioning system (GPS), monitoramentos de dados informáticos (IPs, programas espiões, e-mails, participações em salas de debate e comunidades virtuais), análises psicológicas, polígrafos, detectores variados, análises genéticas, perícias cada vez mais sofisticadas, acesso a cadastros públicos e privados. [26]

As formas de investigação acima apresentadas se mostram como avanços tecnológicos que contribuem para solucionar e inibir potenciais delitos. A exemplo, pode-se citar, conforme abordado novamente por Soares, o uso de interceptações telefônicas, acesso a dados bancários e fiscais para investigação de tráfico de drogas ou até mesmo de grandes esquemas de desvio.[27] Deste modo, as diferentes formas de investigação tecnológica podem ser aplicadas antes da consumação de um delito ou até mesmo durante a consumação do mesmo como forma de investigação.




**8 CONSIDERAÇÕES FINAIS**


O breve ensaio apresentado buscou sintetizar de forma clara e objetiva as diferentes formas de investigação tecnológica mas com foco principal na engenharia reversa como forma de investigação.         
     
Observou-se, portanto, que a engenharia reversa tem sido utilizada por vários anos e por diversos países e indústrias como forma de inovação ou até mesmo de reprodução total ou parcial de produtos ou funcionalidades presente em algo feito.

Além disso, o presente ensaio demonstrou de forma sintetizada o que é e como funciona a engenharia reversa de softwares, meio esse no qual a engenharia reversa precisou se atualizar para criar novos métodos que permitissem sua aplicabilidade com o surgimento de novas tecnologias.

Não obstante, foi explicado o que é e como funciona um software e como uma CPU (ou processador) interpreta e executa as funções presente em um software. Ademais, foi demonstrado de forma condensada como é possível realizar de forma básica e inicial a engenharia reversa de um programa de computador.

Outrora, foi abordado questões legais pertinentes e relacionados ao direito do autor e engenharia reversa além de uma análise jurídico-doutrinária relacionado a casos de engenharia reversa nos Estados Unidos da América e em Tribunais de Justiça do Brasil, onde verificou-se que a engenharia reversa não se constitui ilegalidade desde que não seja uma cópia de algo já feito, pois a mesma possibilita a inovação. 

Ainda, foi considerado de forma breve a aplicabilidade de outras formas de investigação tecnológica e suas relações com investigações e soluções de casos criminais.

Dessarte, conclui-se primeiro que a engenharia reversa possui aplicabilidade em diversos campos da ciência e no que tange a ciência jurídica, possui sua aplicabilidade tanto em na área cível para perícia de casos entre outros tanto na área penal no que tange a investigação forense. No mesmo sentido caminha a aplicabilidade das outras formas de investigação tecnológica brevemente apresentadas neste ensaio, onde as mesmas também possuem sua aplicabilidade em especial na área jurídico-criminal. 



**REFERÊNCIAS**


JORGE, Higor Vinícius Nogueira. **Tratado de investigação criminal tecnológica**. Salvador: JusPodivm, 2021. 


SOARES, Gustavo Torres.** Investigação criminal e inovações técnicas e tecnológicas** - Dezembro de 2014. 307 páginas. Tese de Doutorado. Faculdade de Direito, Universidade de São Paulo, São Paulo, 2014.


DANG, Bruce; GAZET, Alexandre; BACHAALANY, Elias. **Practical Reverse Engineering: x86, x64, ARM, Windows® Kernel, Reversing Tools, and Obfuscation. [S. l.]**: Ohn Wiley & Sons, Inc., Indianapolis, Indiana, 2014.


YURICHEV, Dennis. **Reverse Engineering for Beginners**. 2016.


WONG, Reginald. **Mastering Reverse Engineering**: Re-engineer your ethical hacking skills . 2016. [S. l.]: Packt Publishing., Livery Place, Birmingham, 2018.


MAUEL, Volker. **Reverse Engineering**: An exemplary approach to the fundamentals of reverse engineering (Bachelor Thesis). 2014. 


CANFORA, Gerardo; PENTA, Massimiliano Di; CERULO, Luigi. **Achievements and Challenges in Software Reverse Engineering**. Communication of the ACM. Vol. 54. No. 4. April 2011. 


SCHIRRU, Luca.** A viabilidade legal da engenharia reversa de programas de computador no Brasil sob a legislação autoral e o seu potencial como fonte de inovação**. Rio de Janeiro, 2015. Dissertação (Mestrado em Políticas Públicas, Estratégias e Desenvolvimento) – Instituto de Economia, Universidade Federal do Rio de Janeiro, Rio de Janeiro, 2015.


CHIKOFSKY, Elliot; CROSS, James. **Reverse engineering and design recovery**: a taxonomy. IEEE Software. P. 13–17. 1990. Disponível em: https://www.cs.cmu.edu/~aldrich/courses/654-sp05/ReengineeringTaxonomy.pdf. Acesso em: 27 out. 2021


SAMUELSON, Pamela; SCOTCHMER, Suzanne. **The law and economics of reverse engineering**. Yale Law Journal, 111.7, May, .p.1576-1663, 2002. Disponível em: https://digitalcommons.law.yale.edu/cgi/viewcontent.cgi?article=4591&context=ylj. Acesso em: 28 out. 2021.


SUBEDI, Kul Prasad; BUDHATHOKI, Daya Ram; DASGUPTA, Dipankar.** Forensic Analysis of Ransomware Families using Static and Dynamic Analysis**. 2018 IEEE Symposium on Security and Privacy Workshops, USA, 2018. Disponível em: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8424649. Acesso em: 28 out. 2021.


STANFORD (Estados Unidos). Software: **Running Programs. [S. l.: s. n.], 2015**?. Disponível em: https://web.stanford.edu/class/cs101/software-1.html. Acesso em: 16 out. 2021.


MERCÊS, Fernando. **Áreas de aplicação da engenharia reversa de software**. ln: Mente Binária. Mente Binária. [S.l.]. 27 out. 2020. Disponível em: https://mentebinaria.gitbook.io/engenharia-reversa/introducao. Acesso em: 27 out. 2021.


DOWLING, Stephen. **O barulhento bombardeiro russo há 60 anos na ativa.** ln: BBC. BBC. [S.l.]. 18 mar. 2015. Disponível em: https://www.bbc.com/portuguese/noticias/2015/03/150316_vert_fut_tupolev_ml. Acesso em: 27 out. 2021.


FreeCodeCamp. ln: FreeCodeCamp. FreeCodeCamp. [S.l.]. 10 jan. 2020. Disponível em: https://www.freecodecamp.org/news/compiled-versus-interpreted-languages/. Acesso em: 28 out. 2021.


x64 Cheat Sheet. ln: **CSCI0330 Intro Computer Systems**. x64 Cheat Sheet. [S.l.]. 1 jan. 2019. Disponível em: https://cs.brown.edu/courses/cs033/docs/guides/x64_cheatsheet.pdf. Acesso em: 28 out. 2021.


MOTTA JUNIOR, José Octavio Araújo.** Limitações ao direito do autor, cópia privada e engenharia reversa**. ln: José Octavio Araújo Motta Junior. SEDEP. [S.l.]. 2021?. Disponível em: http://www.sedep.com.br/artigos/limitacoes-ao-direito-do-autor-copia-privada-e-engenharia-reversa/. Acesso em: 28 out. 2021.


**LEI Nº 9.609 , DE 19 DE FEVEREIRO DE 1998**.. LEI Nº 9.609 nº 9.609, Dispõe sobre a proteção da propriedade intelectual de programa de computador, sua comercialização no País, e dá outras providências.. LEI Nº 9.609 , DE 19 DE FEVEREIRO DE 1998.. Brasília, 19 fev. 1998. Disponível em: http://www.planalto.gov.br/ccivil_03/leis/l9609.htm. Acesso em: 28 out. 2021.


LEI Nº 9.610, DE 19 DE FEVEREIRO DE 1998. **LEI Nº 9.610 nº 9.610**, Altera, atualiza e consolida a legislação sobre direitos autorais e dá outras providências.. LEI Nº 9.610, DE 19 DE FEVEREIRO DE 1998. Brasília, 19 fev. 1998. Disponível em: http://www.planalto.gov.br/ccivil_03/leis/l9610.htm. Acesso em: 28 out. 2021.


BRASIL. Código Penal nº 2.848, **Código Penal.. Código Penal.**. Rio de Janeiro, 7 dez. 1940. Disponível em: http://www.planalto.gov.br/ccivil_03/decreto-lei/del2848compilado.htm. Acesso em: 30 out. 2021.


BRASIL. Tribunal de Justiça do Estado de São Paulo (1° Câmara de Direito Privado). Apelação Cível 0149214-47.2009.8.26.0100-SP. DIREITO AUTORAL Software Eventual responsabilidade das empresas contratadas pela ré por danos causados a esta depende de prova de culpa ou dolo Impossibilidade de ampliação do objeto da demanda em sede de denunciação da lide, em prejuízo ao autor A ré já protocolara laudo parcialmente divergente de seu assistente técnico quando interpôs o agravo retido da decisão que indeferira o pedido de prorrogação do prazo para a sua entrega Preclusão lógica Art. 533, parágrafo único do CPC - Agravos retidos tirados da decisão que rejeitara pedido de denunciação da lide e da decisão que indeferira pedido de prorrogação do prazo para a entrega do laudo do assistente técnico da ré impróvidos - Demais agravos retidos não conhecidos, por falta de reiteração nas razões de apelação Preliminares de nulidade da sentença por julgamento extra e ultra petita, ilegitimidade ativa, cerceamento de defesa e ilegitimidade da prova pericial rejeitadas - Titularidade do software pertence à autora - Art. 4º, caput, da lei 9.609/98 - A prova pericial identificou inúmeras semelhanças entre os softwares desenvolvidos pelas partes, que claramente extrapolam semelhanças decorrentes da mera utilização da mesma ferramenta de desenvolvimento ou de especificações técnicas da bolsa de valores O software da ré é derivado do software da autora, embora tenham sido efetuadas pequenas alterações Violação de direito autoral Pedido procedente Condenação da ré a se abster de utilizar qualquer versão do software derivado do programa da autora Indenização dos custos suportados pela autora com o desenvolvimento do programa copiado pela ré e lucros cessantes equivalentes ao lucro obtido com a utilização do programa copiado e versões posteriores Sucumbência da ré Verba honorária mantida no importe de 15% do valor da condenação, tendo em vista a elevada complexidade da causa Sentença ratificada, por seus próprios fundamentos (art. 252 do RITJSP), aos quais se aliam os ora lançados - Agravos retidos não reiterados não conhecidos, improvidos os demais recursos.(TJ-SP - APL: 01492144720098260100 SP 0149214-47.2009.8.26.0100, Relator: Paulo Eduardo Razuk, Data de Julgamento: 05/08/2014, 1ª Câmara de Direito Privado, Data de Publicação: 05/08/2014). 05 de Agosto de 2014. Apelação Cível. São Paulo, 2014. Disponível em: https://esaj.tjsp.jus.br/cjsg/getArquivo.do?conversationId=&cdAcordao=7738724&cdForo=0&uuidCaptcha=sajcaptcha_afd2e760b9d1475e903b47c605607eec&g-recaptcha-response=03AGdBq26W7tQgDTW4BbezptOdKVmDUlGscQXINgbC2NKtEyqr-vi0_gYK6ycXBQHDeQIFBs8WimqZs67ZTmwu0yT9SLQ9vkH6PWUf4CDWnam5vFypuFQG59Syteacv4liwRthpqSwXcVzDYg8hihmWCdJKk10_FceOtDJnCkj93f5JGcqsbrzwaAyvjM1dKnWyNNAnGZJJZqQjVPzIA5eehc5mBL4lStXODjO7tm_zT7ZUSO_40b2vryF4ya597za5jdCpPEe3Zi8ddXx926FJug1uyIuW8Cw0ERjd6hiRekygG51nhOopnM6R4WWMwuaeLXAGejLcHRdLBV6dETTG0n8-ZT1OFSXWJ4QhSc2tuwjwWEaKDC5fB4ywmA_Lk2v7N7BlR1T33qDKAtun3Nq91NZWBDTSIswVVLXBbAGGS8J4CqJtv4yf46I0IH7s999gVs8eAfApf3rnkU4rj_srhcHkH8lyfAzHA. Acesso em: 28 out. 2021.


BRASIL. Tribunal de Justiça do Rio Grande do Sul (Sexta Câmara Cível). Apelação 70050795517.Apelação cível. Ação condenatória. Direito autoral. Programa de informática. Matéria de fato. Caso concreto. Análise da prova. Correta valoração do conjunto probatório na fundamentação da sentença. Conclusão no sentido que os programas de informática foram desenvolvidos sob encomenda para as empresas apeladas. Logo, como não houve disposição nos contratos em sentido contrário, é dos contratantes do serviço de desenvolvimento a titularidade dos programas. Aplica-se, com isso, o disposto no art. 4º da Lei n. 9.609/98, que assim determina. Recurso não provido.(Apelação Cível, Nº 70050795517, Sexta Câmara Cível, Tribunal de Justiça do RS, Relator: Ney Wiedemann Neto, Julgado em: 21-03-2013)[0]. Relatora: Ney Wiedemann Neto,21 de Março de 2013. Apelação. SÃO LEOPOLDO, 2013. Disponível em: https://esaj.tjsp.jus.br/cjsg/getArquivo.do?conversationId=&cdAcordao=7738724&cdForo=0&uuidCaptcha=sajcaptcha_afd2e760b9d1475e903b47c605607eec&g-recaptcha-response=03AGdBq26W7tQgDTW4BbezptOdKVmDUlGscQXINgbC2NKtEyqr-vi0_gYK6ycXBQHDeQIFBs8WimqZs67ZTmwu0yT9SLQ9vkH6PWUf4CDWnam5vFypuFQG59Syteacv4liwRthpqSwXcVzDYg8hihmWCdJKk10_FceOtDJnCkj93f5JGcqsbrzwaAyvjM1dKnWyNNAnGZJJZqQjVPzIA5eehc5mBL4lStXODjO7tm_zT7ZUSO_40b2vryF4ya597za5jdCpPEe3Zi8ddXx926FJug1uyIuW8Cw0ERjd6hiRekygG51nhOopnM6R4WWMwuaeLXAGejLcHRdLBV6dETTG0n8-ZT1OFSXWJ4QhSc2tuwjwWEaKDC5fB4ywmA_Lk2v7N7BlR1T33qDKAtun3Nq91NZWBDTSIswVVLXBbAGGS8J4CqJtv4yf46I0IH7s999gVs8eAfApf3rnkU4rj_srhcHkH8lyfAzHA. Acesso em: 28 out. 2021.




MasteringMastering Reverse Engineering Re-engineer your ethical hacking skills by Reginald Wong (z-lib.org).pdf
 Reverse Engineering Re-engineer your ethical hacking skills by Reginald Wong (z-lib.org).pdf
Mastering Reverse Engineering Re-engineer your ethical hacking skills by Reginald Wong (z-lib.org).pdf


Mastering Reverse Engineering Re-engineer your ethical hacking skills by Reginald Wong (z-lib.org).pdf
Mastering Reverse Engineering Re-engineer your ethical hacking skills by Reginald Wong (z-lib.org).pdf


________________
[1] Graduando de Direito da Pontifícia Universidade Católica do Paraná. Email: matheus@chimelli.com
[2] MAUEL, Volker. Reverse Engineering: An exemplary approach to the fundamentals of reverse engineering (Bachelor Thesis). 2014. p. 14


[3] SAMUELSON, Pamela; SCOTCHMER, Suzanne. The law and economics of reverse engineering. Yale Law Journal, 111.7, May, .p.1582, 2002


[4] DOWLING, Stephen. O barulhento bombardeiro russo há 60 anos na ativa. ln: BBC. BBC. [S.l.]. 18 mar. 2015. Disponível em: https://www.bbc.com/portuguese/noticias/2015/03/150316_vert_fut_tupolev_ml. Acesso em: 27 out. 2021.


[5] MERCÊS, Fernando. Áreas de aplicação da engenharia reversa de software. ln: Mente Binária. Mente Binária. [S.l.]. 27 out. 2020. Disponível em: https://mentebinaria.gitbook.io/engenharia-reversa/introducao. Acesso em: 27 out. 2021.
[6] CANFORA, Gerardo; PENTA, Massimiliano Di; CERULO, Luigi. Achievements and Challenges in Software Reverse Engineering. Communication of the ACM. Vol. 54. No. 4. April 2011. 


[7]  The IEEE Standard for Software Maintenance.


[8] ARRUMAR CHIKOFSKY, Elliot; CROSS, James. Reverse engineering and design recovery: a taxonomy. IEEE Software. P. 13–17. 1990.


[9] STANFORD (Estados Unidos). Software: Running Programs. [S. l.: s. n.], 2015?. Disponível em: https://web.stanford.edu/class/cs101/software-1.html. Acesso em: 16 out. 2021.
[10]FreeCodeCamp. ln: FreeCodeCamp. FreeCodeCamp. [S.l.]. 10 jan. 2020. Disponível em: https://www.freecodecamp.org/news/compiled-versus-interpreted-languages/. Acesso em: 28 out. 2021.
[11] YURICHEV, Dennis. Reverse Engineering for Beginners. 2016.
[12] Montagem feita a partir de captura de tela do computador do autor utilizando o software Microsoft ® Visual Studio Code.
[13] Montagem feita a partir de captura de tela do computador do autor utilizando o software IDA Free
[14] Montagem feita a partir de captura de tela do computador do autor utilizando o software IDA Free


[15] Montagem feita a partir de captura de tela do computador do autor utilizando o software IDA Free
[16] Montagem feita a partir de captura de tela do computador do autor utilizando o software IDA Free
[17] WONG, Reginald. Mastering Reverse Engineering: Re-engineer your ethical hacking skills . 2016. [S. l.]: Packt Publishing., Livery Place, Birmingham, 2018. p.36


[18] LEI Nº 9.609 , DE 19 DE FEVEREIRO DE 1998.. LEI Nº 9.609 nº 9.609, Dispõe sobre a proteção da propriedade intelectual de programa de computador, sua comercialização no País, e dá outras providências.. LEI Nº 9.609 , DE 19 DE FEVEREIRO DE 1998.. Brasília, 19 fev. 1998. Disponível em: http://www.planalto.gov.br/ccivil_03/leis/l9609.htm. Acesso em: 28 out. 2021.


[19] LEI Nº 9.610, DE 19 DE FEVEREIRO DE 1998. LEI Nº 9.610 nº 9.610, Altera, atualiza e consolida a legislação sobre direitos autorais e dá outras providências.. LEI Nº 9.610, DE 19 DE FEVEREIRO DE 1998. Brasília, 19 fev. 1998. Disponível em: http://www.planalto.gov.br/ccivil_03/leis/l9610.htm. Acesso em: 28 out. 2021.




[20] BRASIL. Código Penal nº 2.848, Código Penal.. Código Penal.. Rio de Janeiro, 7 dez. 1940. Disponível em: http://www.planalto.gov.br/ccivil_03/decreto-lei/del2848compilado.htm. Acesso em: 30 out. 2021.
[21] SAMUELSON, Pamela; SCOTCHMER, Suzanne. The law and economics of reverse engineering. Yale Law Journal, 111.7, May, .p.1576-1663, 2002


[22] 30. 489 U.S. 141,160 (1989); see also infra Section II.C (discussing this case); cf MATTHEW JOSEPHSON, EDISON 91 (1959) ("When the devices of others were brought before him for inspection, it was seldom that [Edison] could not contribute his own technical refinements or ideas for improved mechanical construction. As he worked constantly over such machines, certain original insights came to him; by dint of many trials, materials long known to others, constructions long accepted, were 'put together in a different way'-and there you had an invention.").


[23] BRASIL. Tribunal de Justiça do Estado de São Paulo (1° Câmara de Direito Privado). Apelação Cível 0149214-47.2009.8.26.0100-SP.DIREITO AUTORAL Software Eventual responsabilidade das empresas contratadas pela ré por danos causados a esta depende de prova de culpa ou dolo Impossibilidade de ampliação do objeto da demanda em sede de denunciação da lide, em prejuízo ao autor A ré já protocolara laudo parcialmente divergente de seu assistente técnico quando interpôs o agravo retido da decisão que indeferira o pedido de prorrogação do prazo para a sua entrega Preclusão lógica Art. 533, parágrafo único do CPC - Agravos retidos tirados da decisão que rejeitara pedido de denunciação da lide e da decisão que indeferira pedido de prorrogação do prazo para a entrega do laudo do assistente técnico da ré impróvidos - Demais agravos retidos não conhecidos, por falta de reiteração nas razões de apelação Preliminares de nulidade da sentença por julgamento extra e ultra petita, ilegitimidade ativa, cerceamento de defesa e ilegitimidade da prova pericial rejeitadas - Titularidade do software pertence à autora - Art. 4º, caput, da lei 9.609/98 - A prova pericial identificou inúmeras semelhanças entre os softwares desenvolvidos pelas partes, que claramente extrapolam semelhanças decorrentes da mera utilização da mesma ferramenta de desenvolvimento ou de especificações técnicas da bolsa de valores O software da ré é derivado do software da autora, embora tenham sido efetuadas pequenas alterações Violação de direito autoral Pedido procedente Condenação da ré a se abster de utilizar qualquer versão do software derivado do programa da autora Indenização dos custos suportados pela autora com o desenvolvimento do programa copiado pela ré e lucros cessantes equivalentes ao lucro obtido com a utilização do programa copiado e versões posteriores Sucumbência da ré Verba honorária mantida no importe de 15% do valor da condenação, tendo em vista a elevada complexidade da causa Sentença ratificada, por seus próprios fundamentos (art. 252 do RITJSP), aos quais se aliam os ora lançados - Agravos retidos não reiterados não conhecidos, improvidos os demais recursos.(TJ-SP - APL: 01492144720098260100 SP 0149214-47.2009.8.26.0100, Relator: Paulo Eduardo Razuk, Data de Julgamento: 05/08/2014, 1ª Câmara de Direito Privado, Data de Publicação: 05/08/2014). 05 de Agosto de 2014. Apelação Cível. São Paulo, 2014. Disponível em: https://esaj.tjsp.jus.br/cjsg/getArquivo.do?conversationId=&cdAcordao=7738724&cdForo=0&uuidCaptcha=sajcaptcha_afd2e760b9d1475e903b47c605607eec&g-recaptcha-response=03AGdBq26W7tQgDTW4BbezptOdKVmDUlGscQXINgbC2NKtEyqr-vi0_gYK6ycXBQHDeQIFBs8WimqZs67ZTmwu0yT9SLQ9vkH6PWUf4CDWnam5vFypuFQG59Syteacv4liwRthpqSwXcVzDYg8hihmWCdJKk10_FceOtDJnCkj93f5JGcqsbrzwaAyvjM1dKnWyNNAnGZJJZqQjVPzIA5eehc5mBL4lStXODjO7tm_zT7ZUSO_40b2vryF4ya597za5jdCpPEe3Zi8ddXx926FJug1uyIuW8Cw0ERjd6hiRekygG51nhOopnM6R4WWMwuaeLXAGejLcHRdLBV6dETTG0n8-ZT1OFSXWJ4QhSc2tuwjwWEaKDC5fB4ywmA_Lk2v7N7BlR1T33qDKAtun3Nq91NZWBDTSIswVVLXBbAGGS8J4CqJtv4yf46I0IH7s999gVs8eAfApf3rnkU4rj_srhcHkH8lyfAzHA. Acesso em: 28 out. 2021.


[24] BRASIL. Tribunal de Justiça do Rio Grande do Sul (Sexta Câmara Cível). Apelação 70050795517.Apelação cível. Ação condenatória. Direito autoral. Programa de informática. Matéria de fato. Caso concreto. Análise da prova. Correta valoração do conjunto probatório na fundamentação da sentença. Conclusão no sentido que os programas de informática foram desenvolvidos sob encomenda para as empresas apeladas. Logo, como não houve disposição nos contratos em sentido contrário, é dos contratantes do serviço de desenvolvimento a titularidade dos programas. Aplica-se, com isso, o disposto no art. 4º da Lei n. 9.609/98, que assim determina. Recurso não provido.(Apelação Cível, Nº 70050795517, Sexta Câmara Cível, Tribunal de Justiça do RS, Relator: Ney Wiedemann Neto, Julgado em: 21-03-2013)[0]. Relatora: Ney Wiedemann Neto,21 de Março de 2013. Apelação. SÃO LEOPOLDO, 2013. Disponível em: https://esaj.tjsp.jus.br/cjsg/getArquivo.do?conversationId=&cdAcordao=7738724&cdForo=0&uuidCaptcha=sajcaptcha_afd2e760b9d1475e903b47c605607eec&g-recaptcha-response=03AGdBq26W7tQgDTW4BbezptOdKVmDUlGscQXINgbC2NKtEyqr-vi0_gYK6ycXBQHDeQIFBs8WimqZs67ZTmwu0yT9SLQ9vkH6PWUf4CDWnam5vFypuFQG59Syteacv4liwRthpqSwXcVzDYg8hihmWCdJKk10_FceOtDJnCkj93f5JGcqsbrzwaAyvjM1dKnWyNNAnGZJJZqQjVPzIA5eehc5mBL4lStXODjO7tm_zT7ZUSO_40b2vryF4ya597za5jdCpPEe3Zi8ddXx926FJug1uyIuW8Cw0ERjd6hiRekygG51nhOopnM6R4WWMwuaeLXAGejLcHRdLBV6dETTG0n8-ZT1OFSXWJ4QhSc2tuwjwWEaKDC5fB4ywmA_Lk2v7N7BlR1T33qDKAtun3Nq91NZWBDTSIswVVLXBbAGGS8J4CqJtv4yf46I0IH7s999gVs8eAfApf3rnkU4rj_srhcHkH8lyfAzHA. Acesso em: 28 out. 2021.


[25] JORGE, Higor Vinícius Nogueira. Tratado de investigação criminal tecnológica. Salvador: JusPodivm, 2021. 
[26]  JORGE, Higor Vinícius Nogueira. Tratado de investigação criminal tecnológica. Salvador: JusPodivm, 2021. p. 207
[27]   JORGE, Higor Vinícius Nogueira. Tratado de investigação criminal tecnológica. Salvador: JusPodivm, 2021. p. 212