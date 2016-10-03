# Boas Práticas da Programação - pequenas notas
### Uma coleção de citações e frases para desenvolvedores na rede

Use seu próprio juízo na aplicação dessas práticas e conselhos[.](http://www.reddit.com/r/programming/comments/1bcebh/programming_best_practices/c95y6la)

* * *

## Nunca construa aplicações gigantes

O segredo para construir grandes aplicações é nunca construir aplicações grandes. Quebre suas aplicações em pequenas peças. Então, monte essas peças de maneira testável, como pequenos módulos em uma grande aplicação.

– Justin Meyer, autor de JavaScript MVC

[Fonte](http://bitovi.com/blog/2010/11/organizing-a-jquery-application.html)

## Qualidade importa

Quando eu ouço "Um código que apenas chute pro gol, rode e funcione" eu penso em todos os aplicativos que eu não uso mais porque eles foram gradualmente perdendo a capacidade de iteração. 

– Avdi Grimm

[Fonte](https://twitter.com/#!/avdi/status/180747721852985344)

## Não escreva código! 

Não escreva código (só escreva código novo quando tudo mais que existe estiver falhando) é a mais importante lição que todo desenvolvedor deveria aprender. A quantidade de duplicidade, de código mal feito por aí, atualmente é enorme. Em muitos caso, os desenvolvedores não se incomodam em olhar ao redor [para usar o que é bom]. Eles apenas querem escrever código. 

[Fonte](http://blogs.agilefaqs.com/2009/10/19/biggest-stinkers/)

#### Reduzir a quantidade de código em seu projeto deveria ser um objetivo.

"Eu odeio código, e eu quero o menos possível em nosso projeto"
– Jack Diederich

[Fonte](http://pyvideo.org/video/880/stop-writing-classes)

#### Mantenha dependência enxutas

O velho ditado "não reinvente a roda" não se aplica quando a roda vem acoplada a um motor de locomotiva.

[Fonte](http://www.reddit.com/r/programming/comments/1bcebh/programming_best_practices/c9616mn)

#### Não espere que uma reescrita seja melhor que o original

É importante lembrar que quando você inicial algo a partir do zero não há absolutamente nenhuma razão para acreditar que você fará um trabalho melhor do que fez pela primeira vez. Em primeiro lugar, você provavelmente ainda tem a mesma equipe de programação que trabalhou na versão inicial, então na verdade vocês não tem necessariamente "mais experiência". Você só vai fazer a maioria dos antigos erros novamente, e introduzir alguns novos problemas que não estavam na versão original.

– Joel Spolsky

[Fonte](http://www.joelonsoftware.com/articles/fog0000000069.html)

## Pare de escrever classes

A assinatura que diz "isso deveria ser uma classe" existe quando a classe tem dois métodos, e um deles é o constructor. Se a qualquer hora você ver esses sinais, você provavelmente deveria ter escrito apenas uma função.

– Jack Diederich

[Fonte](http://pyvideo.org/video/880/stop-writing-classes)

## Esqueça novas funcionalidades, melhore as coisas que já existem

O problema: é muito fácil perder de vista o que os usuários se importam com mais frequência, isto é, a performance e a usabilidade da aplicação e das funcionalidades que eles já usam cotidianamente. 

– Tim Anderson

[Fonte](http://www.itjoblog.co.uk/2011/06/making-better-software.html)

## Reinvente a roda

Inventar suas próprias rodas dá a você um profundo saber e entendimento sobre como as rodas funcionam e o que as faz boas.

[Fonte](http://nodejs.debuggable.com/2011-02-26.txt)

## Não faça coisas difícies, faça coisas fáceis! 

* Simples é melhor do que complexo.
* Complexo é melhor que complicado. 
* Plano é melhor que aninhado.
* Legibilidade conta. 
* Se a implementação é dificil de explicar, é uma ideia ruim. 
* Se a implementação é fácil de explicar, pode ser uma boa ideia. 

– The Zen of Python

[Fonte](http://www.python.org/dev/peps/pep-0020/)

Pequena lista extraída da [Palestra "Pare de Escrever Classes" por Jack Diederich](http://pyvideo.org/video/880/stop-writing-classes)

## Reescrever > Refatorar

Se você está mudando mais de 25% de uma classe ou método, considere simplesmente rescrevê-lo. Você irá escrever o código mais claramente. 

## Refatorando > Reescrevendo

#### Desculpas comuns para a reescrita de um software
1. O código é uma porcaria
2. "Nós estamos melhores agora"
3. Nós escolhemos a plataforma/linguagem errada

#### Porque reescrever é (quase) nunca uma boa ideia
1. [Sempre demora mais do que você imagina](http://en.wikipedia.org/wiki/Hofstadter's_law)
2. Os mercados mudam
2. Clientes já existentes ficam frustrados
3. Refatoração pode limpar o código
4. Você não controla a reescrita, ela controla você

[Fonte](http://onstartups.com/tabid/3339/bid/2596/Why-You-Should-Almost-Never-Rewrite-Your-Software.aspx)


## Aceite que você não tem ideia de como isso irá crescer

A chave é reconhecer desde o início que você não tem idéia de como isso irá crescer. Quando você aceita que você não sabe tudo, você começa a projetar o sistema defensivamente ... Você deveria gastar a maior parte do seu tempo pensando sobre interfaces em vez de implementações.

– Nicholas Zakas, autor de "Alta performance em websites Javascripts"

[Fonte](http://radar.oreilly.com/2011/06/big-javascript-apps-teams.html)

[Agradecimentos a Addy Osmani](http://addyosmani.com/largescalejavascript/)

## Evite o "cheiro de código"

[Fonte](http://www.codinghorror.com/blog/2006/05/code-smells.html)
[Fonte](http://web.archive.org/web/20120130234037/http://stackoverflow.com/questions/114342/what-are-code-smells-what-is-the-best-way-to-correct-them)


## Escreva testes unitários

Cada programador sabe que deve escrever testes para o seu código. Poucos fazem. A resposta universal para "Por que não?" é "Eu não tenho tempo." Isto rapidamente cria um ciclo vicioso: quanto mais mais pressão você sente, menos testes que você escreve. Com os poucos testes que você escreve, menos produtivo você fica e menos estável o seu código se torna. E quanto menos produtivo e preciso você for, maior a pressão que você sente. Programadores ficam esgotados com esses ciclos. 

Quebrar esse ciclo vicioso requer uma influencia externa. É possível encontrar a influência externa que precisávamos em um simples framework de testes que nos ajuda fazendo pequenos testes que fazem uma grande diferença.

[Fonte](http://junit.sourceforge.net/doc/testinfected/testing.htm)


#### [Sem testes unitários] Você não está refatorando, você está apenas mexendo na merda. — Hamlet D'Arcy

## Para esquecer testes unitários efetivos, você precisa escrever código testável

### Falha #1: Contrutores fazem trabalho real
#### Sinais de perigo

* Nova palavra chave em um construtor ou em um campo declarado
* Método estático chama algo em um construtor ou em uma declaração de campo
* Qualquer coisa além de um campo declarado em um construtor
* Objeto não totalmente inicializado após a conclusão do construtor (observer a inicialização dos métodos)
* Controle de fluxo (condicional ou looping) em um construtor
* Código fazendo a construção de um objeto gráfico dentro de um construtor ao invés de usar um método Factory
* Adição ou uso de um bloco de inicialização

### Falha #2: Digging into Collaborators
#### Warning Signs
* Objects are passed in but never used directly (only used to get access to other objects)
* Law of Demeter violation: method call chain walks an object graph with more than one dot (.)
* Suspicious names: context, environment, principal, container, or manager

### Flaw #3: Brittle Global State & Singletons
#### Warning Signs
* Adding or using singletons
* Adding or using static fields or static methods
* Adding or using static initialization blocks
* Adding or using registries
* Adding or using service locators

### Flaw #4: Class Does Too Much
#### Warning Signs

* Summing up what the class does includes the word “and”
* Class would be challenging for new team members to read and quickly “get it”
* Class has fields that are only used in some methods
* Class has static methods that only operate on parameters

[Fonte](http://misko.hevery.com/code-reviewers-guide/)

[Fonte](http://misko.hevery.com/presentations/)

## Test-Driven Development with Inversion of Control.

Even if you aren't testing your code, you should write testable code. IoC enables testable code. Inject test-friendly dependencies or mocks at test time, to isolate the unit-under-test.

## Avoid mixing Object Creation with Application Logic

[Fonte](http://misko.hevery.com/2008/09/30/2008/07/08/how-to-think-about-the-new-operator/)

## Avoid creating technical debt.

"Although immature code may work fine and be completely acceptable to the customer, excess quantities will make a program unmasterable, leading to extreme specialization of programmers and finally an inflexible product. ... A little debt speeds development so long as it is paid back promptly with a rewrite ... *Every minute spent on not-quite-right code counts as interest on that [debt](http://en.wikipedia.org/wiki/Technical_debt
).* Entire engineering organizations can be brought to a stand-still under the debt load of an unconsolidated implementation ...”
(Emphasis mine)

[Fonte](http://c2.com/doc/oopsla92.html)


## Premature optimisation is the root of all evil

"Programmers waste enormous amounts of time thinking about, or worrying about, the speed of noncritical parts of their programs, and these attempts at efficiency actually have a strong negative impact when debugging and maintenance are considered. We should forget about small efficiencies, say about 97% of the time: premature optimization is the root of all evil. Yet we should not pass up our opportunities in that critical 3%."

[Fonte](http://c2.com/cgi/wiki?PrematureOptimization)

## Plan, Plan, Plan.

It is much cheaper to do it correctly the first time than to redo it later on.
The sooner a problem is identified and fixed, the cheaper it is to do so.

"The general who wins a battle makes many calculations in his temple before the battle is fought. The general who loses a battle makes but few calculations beforehand. Thus do many calculations lead to victory,
and few calculations to defeat: how much more no calculation at all! It is by attention to this point that I can foresee who is likely to win or lose."

#### "Plans are worthless, planning is invaluable."- Sir Winston Churchill

For this to work, everyone involved has to listen, everyone has to be open, everyone has to be responsive. Or we could keep flailing away with the fucked up attitude that “it has to be this way” because the sacred project plan says it’s this way. Because that really is a lot of fun, isn’t it?

## Programming is also Teaching your team
... a team of mediocre, inexperienced coders who work together and write for the benefit of the team has the capability to become a great team, and they can take that learning approach to create other great teams. *It all comes down to whether the team sees its work as simply writing code... or writing with the goal of both code and learning*"
(Emphasis mine)

– Reginald Braithwaite

[Fonte](http://www.theserverside.com/tt/articles/article.tss?l=ProgrammingisAlsoTeachingYourTeam)

### "The most important element of successful software development is learning."
When the entire team meets a certain standard for competence, there is a very large learning surface exposed and the team is able to absorb more information.

[Fonte](http://weblog.raganwald.com/2007/06/which-theory-first-evidence.html)

## "...there are lies, damned lies, and software development estimates."

Software can only partially be designed in advance. ... requirements suffer from observation, that the act of building software causes the requirements to change. ...technical factors cannot be perfectly understood, that only the act of trying to build something with specific components will reveal all of the gotchas and who-knews associated with a chosen technology strategy. ...software design is an iterative process, starting with a best guess that is continually refined with experience.
the normal case for software projects is that tasks are rarely completed exactly as estimated, but that as a project progresses, the aggregate variance from estimates falls.

[Fonte](http://weblog.raganwald.com/2007/06/which-theory-first-evidence.html)

Nobody likes to look stupid. If you’re a professional and someone puts you on the spot to answer “how long will this take?” it’s only human to want to provide an answer. Whether you call it professional pride or ego, it’s a powerful driver.
Good IT workers really don’t like saying “I don’t know.” If they say it, they probably mean it. So stop pushing for a definitive answer when one doesn’t exist.It’s perfectly reasonable to want some sort of plan up front. I’m actually one of those funny types who believe up front planning is a necessity. So long as everyone understands an estimate is just that: an estimate. You learn as you go along and discover more detail. So you revise the estimate accordingly.

[![The mess we're in](https://cloud.githubusercontent.com/assets/43438/4344401/0ddd5fc8-408f-11e4-8887-b0bfbce91dc7.png)](https://www.youtube.com/watch?v=lKXe3HUG2l4)

– Joe Armstrong, author Erlang

##Your architecture should resemble your domain

So what does the architecture of your application scream? When you look at the top level directory structure, and the source files in the highest level package; do they scream: health care system, or accounting system, or inventory management system? Or do they scream: rails, or spring/hibernate, or asp?

Architectures should not be supplied by frameworks. Frameworks are tools to be used, not architectures to be conformed to. If your architecture is based on frameworks, then it cannot be based on your use cases.

– Uncle Bob Martin, "Screaming Architecture"

[Fonte](http://blog.8thlight.com/uncle-bob/2011/09/30/Screaming-Architecture.html)

## Siga os princípios do X

* Do not add new functionality unless you know of some real application that will require it.
* It is as important to decide what a system is not as to decide what it is. Do not serve all the world's needs; rather, make the system extensible so that additional needs can be met in an upwardly compatible fashion.
* The only thing worse than generalizing from one example is generalizing from no examples at all.
* If a problem is not completely understood, it is probably best to provide no solution at all.
* If you can get 90 percent of the desired effect for 10 percent of the work, use the simpler solution. (See also Worse is better.)
* Isolate complexity as much as possible.
* Provide mechanism rather than policy. In particular, place user interface policy in the clients' hands.

[Fonte](http://en.wikipedia.org/wiki/X_Window_System_protocols_and_architecture#Design_principles)


## Siga os princípios UNIX

"This is the Unix philosophy: Write programs that do one thing and do it well. Write programs to work together. Write programs to handle text streams, because that is a universal interface" - Doug McIlroy, quoted in A Quarter Century of Unix [Salus]. Addison-Wesley. 1994. ISBN 0-201-54777-5.

* Rule of Modularity: Write simple parts connected by clean interfaces.
* Rule of Clarity: Clarity is better than cleverness.
* Rule of Composition: Design programs to be connected to other programs.
* Rule of Separation: Separate policy from mechanism; separate interfaces from engines.
* Rule of Simplicity: Design for simplicity; add complexity only where you must.
* Rule of Parsimony: Write a big program only when it is clear by demonstration that nothing else will do.
* Rule of Transparency: Design for visibility to make inspection and debugging easier.
* Rule of Robustness: Robustness is the child of transparency and simplicity.
* Rule of Representation: Fold knowledge into data so program logic can be stupid and robust.
* Rule of Least Surprise: In interface design, always do the least surprising thing.
* Rule of Silence: When a program has nothing surprising to say, it should say nothing.
* Rule of Repair: When you must fail, fail noisily and as soon as possible.
* Rule of Economy: Programmer time is expensive; conserve it in preference to machine time.
* Rule of Generation: Avoid hand-hacking; write programs to write programs when you can.
* Rule of Optimization: Prototype before polishing. Get it working before you optimize it.
* Rule of Diversity: Distrust all claims for “one true way”.
* Rule of Extensibility: Design for the future, because it will be here sooner than you think.

– Eric S. Raymond, "A Arte da programação UNIX"

[Fonte](http://www.catb.org/esr/writings/taoup/html/ch01s06.html)


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/timoxley/best-practices/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

