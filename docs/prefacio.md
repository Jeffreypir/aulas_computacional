# Prefácio {-}

Esse material sempre tentará se adequar à ementa da disciplina de Estatística Computacional, sendo esta uma disciplina obrigatória do curso de bacharelado em estatística do Departamento de Estatística da UFPB. Dessa forma, trata-se de um material destinado à alunos do Departamento de Estatística da UFPB. Porém, esse material poderá vir a despertar interesse em pessoas que não alunos da instituição.

A ementa do curso de **Estatística Computacional**, que compõe a estrutura do curso como disciplina obrigatória, poderá ser obtida no [**link**](http://www.de.ufpb.br/graduacao/obrigatorias/EstatisticaComputacional.pdf). Como pode-se observar, a disciplina é dividida no uso de tecnologias (linguagem de marcação e linguagem de programação) e alguns aspectos teóricos que envolvem a teoria de estatística computacional. O bom uso dos conceitos abordados no curso estará alinhado ao perfeito entendimento das tecnologias e teorias apresentadas.

**Importante**: 

\BeginKnitrBlock{rmdimportant}<div class="rmdimportant"><div class=text-justify>
O tópico referente à tipografia científica em [**LaTeX**](https://www.latex-project.org/) não será abordado, visto que esse assunto atualmente está sendo apresentado na disciplina de Metodologia do Trabalho Científico, no início do curso de bacharelado em estatística da UFPB. Além disso, o tópico referente à programação em [**R**](https://www.r-project.org/) abordará aspectos mais avançados da linguagem, uma vez que a essa altura do curso, os alunos entendem os conceitos básicos da linguagem [**R**](https://www.r-project.org/). 

Para quem desejar revisar assuntos referente à programação em [**R**](https://www.r-project.org/), estou disponibilizando as aulas do meu curso introdutório de programação em [**R**](https://www.r-project.org/). As aulas estão divididas em dois arquivos.

**Curso de programação em R**:   
   
  1. Acesse o primeiro arquivo clicando [**aqui**](files/Aula_1.pdf);
  2. Acesse o segundo arquivo clicando [**aqui**](files/Aula_2.pdf).

> **O curso introdutório de programação em R é dividido em dois arquivos, mas você poderá optar em baixar um único arquivo PDF clicando no ícone na barra superior desse material.**

Note que o Curso de **Estatística Computacional** não é o material adequado para você, caso o seu enteresse seja aprender a linguagem de programação [**R**](https://www.r-project.org/). Em um futuro próximo, quando este material estiver concluído e caso você já considere um usuário avançado de [**R**](https://www.r-project.org/), talvez pular para os assuntos referentes aos aspectos teóricos de estatística computacional venha ser o caminho mais produtivo para o seu aprendizado.
</div></div>\EndKnitrBlock{rmdimportant}

## Tecnologias abordadas no curso {-}

1. Uso de [**git**](https://git-scm.com/) e [**GitHub**](https://github.com/prdm0/aulas_computacional) para versionamento de projetos;

2. ~~Linguagem de marcação: [**LaTeX**](https://www.latex-project.org/)~~;

3. Linguagem de marcação [**Markdown**](https://pt.wikipedia.org/wiki/Markdown) e o uso do [**R Markdown**](https://rmarkdown.rstudio.com/);

4. Linguagem de programação [**R**](https://www.r-project.org/) sob um olhar mais avançado:

    - Orientação à objeto utilizando funções genéricas (sistema S3 de orientação à objeto);
    
    - Sistema R6 de orientação à objeto;
    
    - Expressões regulares (**regex**);
    
    - Uso de funcionais. Nessa parte será revisado os funcionais do **base r** bem como serão apresentados novos funcionais;
    
     - Construção de pacotes em R;
     
     - Uso de pacotes que incorporam características novas à linguagem R, entre eles, alguns dos pacotes da comunidade do [**RStudio**](https://www.rstudio.com/);
  
     - Closures;
     
     - Checando a peformance do código e identificando gargalos;
     
     - Conceitos de metaprogramação;
     
     - Paralelismo em R [(**OpenMP**)](https://pt.wikipedia.org/wiki/OpenMP).

Em substituição ao item 2, trataremos do pacote [**rmardkown**](https://rmarkdown.rstudio.com/), em especial, do uso do pacote [**bookdown**](https://bookdown.org/) para a construção de relatórios e livros dinâmicos utilizando a linguagem de marcação [**markdown**](https://en.wikipedia.org/wiki/Markdown). Por exemplo, esse material foi construído utilizando essas ferramentas.

**Nota**:

\BeginKnitrBlock{rmdnote}<div class="rmdnote"><div class=text-justify>
Um bom material em língua portuguesa sobre o [**LaTeX**](https://www.latex-project.org/) poderá ser obtido no [**aqui**](files/latex_lenimar.pdf). Trata-se do curso intitulado [**Breve Introdução ao LaTeX2$\varepsilon$**](files/latex_lenimar.pdf), do Prof. [Lenimar Nunes de Andrade](http://www.mat.ufpb.br/lenimar/) do Departamento de Matemática da UFPB.

Para começar a estudar o [**LaTeX**](https://www.latex-project.org/), você precisará instalar em seu computador um compilador do código de [**LaTeX**](https://www.latex-project.org/) e um editor para seus textos que serão escritos utilizando a linguagem de marcação [**LaTeX**](https://www.latex-project.org/). Abaixo listo os programas que você deverá instalar em seu computador para poder iniciar o estudo do [**material**](files/latex_lenimar.pdf) de [**LaTeX**](https://www.latex-project.org/). 

1. [**TeX Live**](https://www.tug.org/texlive/): Trata-se de uma distribuição do TeX padrão para a maior parter dos sistemas ***nix** (derivados de Unix, incluindo o Linux e macOS). O [**TeX Live**](https://www.tug.org/texlive/) também está disponível para o sistema operacional Windows. Clique [**aqui**](http://mirror.ctan.org/systems/texlive/tlnet/install-tl-windows.exe) para baixar o arquivo de instalação. No processo de instalação você precisará estar conectado à internet, uma vez que o instalador precisará baixar diversos arquivos nos espelhos de distribuição do [**TeX Live**](https://www.tug.org/texlive/). Uma das vantagens [**TeX Live**](https://www.tug.org/texlive/) é a sua velocidade na compilação de um arquivo com extensão **.tex**.

2. [**TeXstudio**](https://www.texstudio.org/): O [**TeXstudio**](https://www.texstudio.org/) é um editor de texto para o sistema [**LaTeX**](https://www.latex-project.org/). Um outro bom editor que você poderá considerá para utilizar em seus estudos é o [**Texmaker**](https://www.xm1math.net/texmaker/), que assim como o [**TeXstudio**](https://www.texstudio.org/), está disponível para os sistemas operacionais Linux, macOS e Windows.
</div>  </div>\EndKnitrBlock{rmdnote}

## Teorias abordadas no curso {-}

1. Geração de números pseudo-aleatórios:

    - Método da inversão;

    - Método da aceitação-rejeição;

    - Método da transformação.

2. Métodos de Monte Carlo;

3. Métodos de reamostragem:
  
    - Jackknife;

    - Bootstrap: estimação de erro-padrão, correção de viés, construção de intervalos aleatórios, testes de hipóteses, bootstrap de Wu (bootstrap selvagem). Algumas dessas metodologias serão apresentadas em esquemas simples (um nível de bootstrap) e duplo (dois níveis de bootstrap).

4. Métodos de otimização não-linear em estatística: métodos de Newton e quasi-Newton.

## Sugestões de passos para revisão da linguagem R {-} 

\BeginKnitrBlock{rmdimportant}<div class="rmdimportant"><div class=text-justify>
É aconselhado que antes de prosseguir nesse material o leitor faça uma revisão básica da linguagem [**R**](https://www.r-project.org/about.html). Entre os princiapis conceitos necessários para uma boa progressão nesse curso, destacam-se:

1. Entender as diferenças do funcionamento de um compilador para um interpretador. Lembre-se, **[**R**](https://www.r-project.org/about.html) é uma linguagem de programação interpretada**;

2. Revise os principais tipo de dados: **character**, **double**, **integer** e **logical**. Lembre-se que por regra de coerção, os tipos mais flexíveis em R seguem a seguinte regra de flexibilidade: **character > double > integer > lógico**. Isso quer dizer, por exemplo, que se `a` é um vetor que possui elementos do tipo character e double, então todos os elementos do vetor serão coagidos para o tipo mais flexível, que nesse caso é o tipo character. **Exemplo**: `a <- c(1, letters[1:5]); is.character(a[1])` retornará `TRUE`.

3. Lembre-se que [**R**](https://www.r-project.org/about.html) "não possui" constantes. Constantes são tratadas como vetores atômicos de comprimento 1. Esses são chamados de **atômicos** por serem a estrutura básica da linguagem, uma vez que [**R**](https://www.r-project.org/about.html) é uma linguagem vetorial. Além disso, lembres-se que listas também são vetores, porém, não-atômicos. Veja que, por exemplo, `is.vector(list(1))` retornará `TRUE`. 

4. Por falarmos em uma estrutura de dados denominada de vetor vetor atômico que aqui chamaremos simplesmente de vetores, revise as principais **estruturas de dados** em [**R**](https://www.r-project.org/about.html): vetores (`c()`), fatores (`factor()`), listas (`list()`), matrizes (`matrix()`), sequência de matrizes (`arrays()`) e tabelas (`data.frames()`). Note que uma matriz é um array de comprimento 1. Não confunda estrutura de dados com tipo de dados. Estruturas de dados refere-se ao mecanismo de organização de dados, já o tipo de dados refere-se ao tipo básico das informações que são organizadas nessas estruturas;

5. Entenda o uso das funções `is.troque()` e `as.troque()`, em que `troque` poderá ser ser substituido por: 
  
     - **Um Estrutura de dados**: `vector`, `factor`, `list`, `numeric`, `data.frame`, `matrix`, `array`, etc.  

     - **Um Tipos de dados**: `integer`, `double`, `numeric`, `character`, `logical`, etc.
  
6. Revise os operadores relacionais e lógicos:
  
    - **Operadores Relacionais**: `==`(igual), `<` (menor), `<=` (menor ou igual), `>` (maior), `>=` (maior ou igual), `!=` (diferente);

    - **Operadores Lógicos**: `||` (**OU** lógico), `&&` (**E** lógico), `!` (**NÃO** lógico). Esses são operadores não vetorizados. Os operadores `|` e `&` são as versões vetorizadas dos operadores `||` e `&&`, ou seja, por exemplo, `c(2,3) < c(1,1)) | (c(2,1) >= c(2,3))` retornará o vetor c(`TRUE`, `FALSE`) e  `(c(2,3) < c(1,4)) | (c(2,1) >= c(2,3)) ` retornará c(`TRUE`, `TRUE`), respectivamente. Perceba que utilizar o operador `|` **OU** lógico é realizado sobre a ordem das posições dos elementos nos vetores; </br></br>
  
7. Revise as estruturas de condições: `if`, `else`, `switch` e `ifelse`. Lembre-se, a função `ifelse()` equivale à estrutura `(condição) ? retorno 1 : retorno 2` das linguagens C/C++; 

8. Revise as estruturas de repetições: `while`, `for` e `repeat`. Entenda o uso das instruções `break` e `next` quando utilizadas dentro dessas estruturas.

9. Revise a definição de funções. Tente entender a flexibilidade embutida em funções que retornam uma lista. Isso se deve ao fato de uma lista ser uma estrutura heterogênea que poderá retornar qualquer estrutura de dados, incluindo outra(s) lista(s). Isso é interessante, uma vez que normalmente desejamos que uma função retorne mais de um objeto, sendo estes objetos quaisques, podendo ter as mais variadas estruturas e tipos de dados.

10. Se achar necessário, revise algumas funções úteis: `ls()`, `rm()`, `length()`, `sum()`, `abs()`, `mean()`, `median()`, `var()`, `sd()`, `cor()`, `summary()`, `sqrt()`, `exp()`, `expm1()` (fornece uma boa proximação para `exp(x) - 1`, quando `x` é pequeno), `log()`, `log10()`, `log1p()` (fornece uma boa aproximação para `log(x+1)` quando `x` é pequeno), `round()`, `union()`, `intersect()`, `choose()`, `factorial()`, `dim()`, `ncol()`, `nrow()`, `diag()`, `%*%`, `t()`, `solve()`, `det()`, `eigen()`, `print()`, `cat()`, `paste()`, `paste0()`, `substring()`,`str()`, `sort()`, `quantile()`, `match()` e `%in%`. Lembre-se que quando os operadores `+`, `-`, `*`, `/`, `%%` (módulo / resto da divisão) e `^` são aplicados entre matrizes, ou entre matrizes e vetores de comprimento 1 ("constantes"), as operações serão realizadas elemento à elemento.
</div></div>\EndKnitrBlock{rmdimportant}
Diversas outras características da linguagem [**R**](https://www.r-project.org/about.html) são importantes e serão lembradas, aos poucos, na medida que for necessário. Ficará a cargo do leitor fazer as sugestões de revisões acima.

O Capítulo que inicia esse material é dedicado à apresentação de exercício que o leitor deverá resolver. Trata-se de um Capítulo em que os exercícios envolvem as sugestões de revisão da linguagem [**R**](https://www.r-project.org/about.html) apresentadas acima. Os exercícios para serem resolvidos poderão exigir revisões de outros conceitos que não foram listados na proposta de revisão acima. No entanto, se esses exercícios forem bem resolvidos, utilizando-se de boas práticas de programação em [**R**](https://www.r-project.org/about.html), a leitura desse material será a mais agradável possível. Considere as aulas de [**R**](https://www.r-project.org/about.html) disponibilizadas como um ponto de apoio.

-----
