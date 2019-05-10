# ProgKnowledge

* Codificamos para outras pessoas, eventualmente para a máquina.
* Quanto tempo o fonte é usado por máquinas? Quanto tempo é usado por humanos?
* A manutenibilidade do código precede seu desempenho.
* Em vez de validar parâmetros Null em cada método, deve-se garantir que eles não são nulos antes de se passar para o método. Isso é tornar o código mais robusto.
* Validar parâmetros nulos é como colocar escoras no método. Será que justifica-se em um legado onde você não tem controle de onde vem o parâmetro ou não tem tempo de procurar? Ou numa biblioteca onde você não sabe como o programador vai usar? Isso compromete a filosofia de fail fast.
* Fazer essa validação e executar o negócio compromete a responsabilidade única do método segundo o SOLID.
* Um método com nome muito longo significaria que ele pode ser separado em outra classe? Um nome comprido geralmente envolve nomeações de escopos que seriam a(s) nova(s) classe(s)?

- [How to quickly and effectively read other people’s code](https://selftaughtcoders.com/how-to-quickly-and-effectively-read-other-peoples-code/)

## Blogs & sites sources
- [Geeks for Geeks](https://www.geeksforgeeks.org/)
- https://blog.cleancoder.com/
- http://tdd.caelum.com.br/
- http://www.growing-object-oriented-software.com/
- http://blog.ploeh.dk/archive/
- [Blog TDD: Geepaw Hill](http://geepawhill.org/blog/)
- [Guia de Desenvolvimento Técnico - ThoughtWorks Brasil](https://thoughtworksinc.github.io/guia-de-desenvolvimento-tecnico/)
- https://the-composition.com/the-origins-of-opera-and-the-future-of-programming-bcdaf8fbe960
- [Learn X in Y minutes](https://learnxinyminutes.com/)
- [A Smart Programmer Understands The Problems Worth Fixing](https://medium.com/@fagnerbrack/a-smart-programmer-understands-the-problems-worth-fixing-dcf15871f943)

## FreeBooks
- [Oreilly](https://www.oreilly.com/programming/free/)
- [Packt Pub](https://www.packtpub.com/packt/offers/free-learning)
- [Programming Notes for Professionals books](https://downloads.goalkicker.com/)

## Linguagens
- [Comparação entre C# e Java](https://imasters.com.br/dotnet/net-comparacao-dos-principais-recursos-entre-c-e-java)
- http://awesome-br.com
- https://usersnap.com/blog/programming-languages-2018/
- https://pt.slideshare.net/AndrJusti/presentations
- [Java versus C# .NET Core fastest programs](https://benchmarksgame-team.pages.debian.net/benchmarksgame/faster/java-csharpcore.html)

## Boas práticas
- [Special Cases Are a Code Smell](https://blog.conjur.org/special-cases-are-a-code-smell/)
- [Nine Steps of Learning by Refactoring](https://www.yegor256.com/2018/04/10/learning-by-refactoring.html)
- [Antipatterns - DevIQ](https://deviq.com/tag/antipattern/)
- [Navalha de Occam - Simplicidade](https://pt.wikipedia.org/wiki/Navalha_de_Occam)
- [A taxonomy of tech debt in LOL](https://engineering.riotgames.com/news/taxonomy-tech-debt)
- [Where Do I Put My Business Rules And Validation?](https://builtwithdot.net/blog/where-do-i-put-my-business-rules-and-validation)
- [ARTICLEHow To Code Like The Top Programmers At NASA — 10 Critical Rules](https://www.tastemovies.com/article/how-to-code-like-the-top-programmers-at-nasa-10-critical-rules/)
- [Clean Code Poster - free download](https://kingadesign.com/clean-code-poster-free-download)
- [Why I Never Null-Check Parameters](https://dzone.com/articles/why-i-never-null-check-parameters)
- [Designing Bulletproof Code](https://dzone.com/articles/designing-a-bulletproof-code)
- [Lessons learnt from “The Clean Code” — Robert C. Martin](https://medium.com/@huytrongnguyen1985/lessons-learnt-from-the-clean-code-robert-c-martin-cecbe2b09139)
- [Is “Defensive Programming” actually healthy?](https://dev.to/cubiclebuddha/is-defensive-programming-actually-healthy-5flj)
- [Algorithms as objects](https://gieseanw.wordpress.com/2019/05/10/algorithms-as-objects/)

## AntiPatterns & Code Smells
- [Anti Patterns Catalog](http://wiki.c2.com/?AntiPatternsCatalog)
- [Code Smell](http://wiki.c2.com/?CodeSmell)
- [10 Code Smells a Static Analyser Can Locate in a Codebase](https://www.fluentcpp.com/2019/03/26/10-code-smells-a-static-analyser-can-locate-in-a-codebase/)

## Conceitos e Algoritmos
- [Bitwise operators and tricks!](https://www.hyfr.life/bitwise-operators-tricks/)
- [Pathfinding for Tower Defense](https://www.redblobgames.com/pathfinding/tower-defense/)
- [Unmasking Bitmasked Dynamic Programming](https://medium.freecodecamp.org/unmasking-bitmasked-dynamic-programming-25669312b77b)
- [Methods for abstraction, programming paradigms, and techniques for managing the complexity of large programs](http://composingprograms.com/)
- [Reevaluating the Layered Architecture](https://javadevguy.wordpress.com/2019/01/06/reevaluating-the-layered-architecture/)
- [Cálculo lambda](https://github.com/Webschool-io/matematica-para-programadores/tree/master/calculo-lambda)
- [Introduction to the A* Algorithm](https://www.redblobgames.com/pathfinding/a-star/introduction.html)
- [Data Structure Visualizations](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html)
- [FLOATING POINT VISUALLY EXPLAINED](http://fabiensanglard.net/floating_point_visually_explained/index.php)
- [Asymptotic Analysis Explained with Pokémon: A Deep Dive into Complexity Analysis](https://medium.freecodecamp.org/asymptotic-analysis-explained-with-pok%C3%A9mon-a-deep-dive-into-complexity-analysis-8bf4396804e0)
- [Data Locality](http://www.gameprogrammingpatterns.com/data-locality.html)
- [Pathfinding Demystified (Part I): Generic Search Algorithm](http://www.gabrielgambetta.com/generic-search.html)
- [A Gentle Introduction to Divide and Conquer Algorithms](https://skerritt.blog/divide-and-conquer-algorithms/)

## TDD
- [FALANDO DE TDD](https://www.concrete.com.br/2011/10/17/falando-de-tdd/)
- [Yegor - The TDD That Works for Me](https://www.yegor256.com/2017/03/24/tdd-that-works.html)
- [Unit Testing Anti-Patterns, Full List](https://www.yegor256.com/2018/12/11/unit-testing-anti-patterns.html)
- [Using TDD to Break Through 'Paralysis by Analysis'](https://buildplease.com/pages/tdd-feedback-100215/)
- [The Evolution of TDD](https://www.thoughtworks.com/pt/insights/blog/evolution-of-tdd)
- [Introducing the Software Testing Cupcake (Anti-Pattern)](https://www.thoughtworks.com/pt/insights/blog/introducing-software-testing-cupcake-anti-pattern)
- [Uncle Bob: TDD Lesson - Terrain Generation](http://blog.cleancoder.com/uncle-bob/2017/01/09/DiamondSquare.html)
- [Uncle Bob: The Pragmatics of TDD](https://blog.cleancoder.com/uncle-bob/2013/03/06/ThePragmaticsOfTDD.html)
- [Uncle Bob: The Cycles of TDD](https://blog.cleancoder.com/uncle-bob/2014/12/17/TheCyclesOfTDD.html)
- [Uncle Bob: Giving Up on TDD](https://blog.cleancoder.com/uncle-bob/2016/03/19/GivingUpOnTDD.html)
- [Não faça testes, faça specs!](http://blog.caelum.com.br/nao-faca-testes-faca-specs/)
- [Effective Tests: Introduction](http://aspiringcraftsman.com/2011/03/07/effective-tests-introduction/)
- [4 Outside-in Signs That You Don’t Have Sufficient Unit Testing](https://blog.gurock.com/sufficient-unit-testing/)
- [The 7 Sins of Unit Testing](https://blog.gurock.com/the-7-sins-of-unit-testing/)
- [Testes Unitários 101: Mocks, Stubs, Spies e todas essas palavras difíceis](https://medium.com/trainingcenter/testes-unit%C3%A1rios-mocks-stubs-spies-e-todas-essas-palavras-dif%C3%ADceis-f2765ac87cc8)
- [Técnica mock em testes unitários](http://www.nessauepa.com.br/blog/2010/08/tecnica-mock-em-testes-unitarios/)
- [How writing tests can make you a faster and more productive developer](https://medium.freecodecamp.org/how-writing-tests-can-make-you-a-faster-and-more-productive-developer-f3ad978e3872)
- [Write tests. Not too many. Mostly integration.](https://blog.kentcdodds.com/write-tests-not-too-many-mostly-integration-5e8c7fff591c)
- [What to test and not to test](http://blog.ploeh.dk/2018/11/12/what-to-test-and-not-to-test/)
- [TDD — A New Transformation](https://cloudnative.ly/tdd-a-new-transformation-bb61bdee8422)
- [Testing In Production Isn’t a Sin Anymore](https://blog.gurock.com/testing-in-production/)
- [4 Properties of Highly Testable Code](https://blog.gurock.com/highly-testable-code/)
- [Underplayed Premises of TDD: Q&A with GeePaw Hill](https://www.infoq.com/news/2018/11/premises-tdd?utm_source=twitter&utm_medium=link&utm_campaign=calendar)
- [Premature Passes: Why You Might Be Getting Green on Red](http://agileinaflash.blogspot.com/2012/07/premature-passes-why-you-might-be.html)
- [Seven Steps to Great Unit Test Names](http://agileinaflash.blogspot.com/2012/05/seven-steps-to-great-unit-test-names.html)
- [The Myth Of 100% Code Coverage](https://itnext.io/the-myth-of-100-code-coverage-c7d4c789700d)
- [Don't Measure Unit Test Code Coverage](https://dzone.com/articles/dont-measure-unit-test-code-coverage)
- [Test-Driven Development is not about tests](https://lucasfcosta.com/2018/10/18/TDD-is-not-about-tests.html)

### TDD Humble Object
Uma view serve apenas para mostrar informações ao usuário e/ou receber instruções deste. Input/Output, nada de processamento. Todo processamento/lógica que interage com a view deve ficar em classes separadas, a interação entre estes deve ser através de parâmetros em funções tipo "CarregarUsuarios(AUsuarioView)", assim esse objeto poderá ser testado através de um mock da view "CarregarUsuario(AUsuarioViewMock)". Essa view desacoplada do processamento/lógica é chamada de "Humble dialog" no padrão humble objeto. 
* Este padrão é basicamente o uso do SRP do SOLID após ser devidamente esclarecida a responsabilidade da view (input/output com o usuário)?
* Um MVC implementado de acordo poderia fazer isso também?

- [A Simple Example of the "Humble Dialog Box"](http://codebetter.com/jeremymiller/2005/07/20/a-simple-example-of-the-humble-dialog-box/)
- [What is a Humble Object and how does it help make your code testable?](https://codeutopia.net/blog/2016/04/09/what-is-a-humble-object-and-how-does-it-help-make-your-code-testable/)
- [Build your own CAB Part #2 – The Humble Dialog Box](http://codebetter.com/jeremymiller/2007/05/23/build-your-own-cab-part-2-the-humble-dialog-box/)
- [TDD Patterns: Humble Object](https://ieftimov.com/tdd-humble-object)
- [Humble Object](http://xunitpatterns.com/Humble%20Object.html)
- [Patrón "Humble Object"](https://geeks.ms/jlao/2016/01/12/patron-humble-object/)

### TDD DB
- [Teste Unitário Camada de persistência](http://www.guj.com.br/t/teste-unitario-camada-de-persistencia/277246/7)
- [Técnicas para realizar testes unitários em CRUD](http://www.guj.com.br/t/tecnicas-para-realizar-testes-unitarios/220780/10)
- [Testes de Integração: Validando ainda mais sua aplicação](https://yuriadamsmaia.wordpress.com/2011/08/09/testes-de-integracao-validando-ainda-mais-sua-aplicacao-pa/)

- http://www.univale.com.br/unisite/mundo-j/artigos/23Testes.pdf

## DDD
- [Domain-Driven Design Demystified](https://dzone.com/articles/domain-driven-design-demystified)

## SOLID
- [Writing SOLID Code: Intro](https://www.anglesandtypes.io/archives/169)
- [Writing SOLID Code: SRP](https://www.anglesandtypes.io/archives/174)
- [Writing SOLID Code: OCP](https://www.anglesandtypes.io/archives/177)
- [Writing SOLID Code: LSP](https://www.anglesandtypes.io/archives/183)
- [Writing SOLID Code: ISP](https://www.anglesandtypes.io/archives/196)
- [Writing SOLID Code: DIP](https://www.anglesandtypes.io/archives/221)
- [Dependency Injection Is NOT The Same As The Dependency Inversion Principle](https://lostechies.com/derickbailey/2011/09/22/dependency-injection-is-not-the-same-as-the-dependency-inversion-principle/)
- [SOLID Principles every Developer Should Know](https://blog.bitsrc.io/solid-principles-every-developer-should-know-b3bfa96bb688)
- [The Single Responsibility Principle under the microscope](http://geekswithblogs.net/theArchitectsNapkin/archive/2015/04/25/the-single-responsibility-principle-under-the-microscope.aspx)

## IODA
- [The IODA Architecture](http://geekswithblogs.net/theArchitectsNapkin/archive/2015/04/29/the-ioda-architecture.aspx)

## Tell, dont ask
- [Martin Fowler](https://martinfowler.com/bliki/TellDontAsk.html)
- [wiki.c2](http://wiki.c2.com/?TellDontAsk)
- [Tell, don’t ask (ou… fique longe das minhas propriedades)](https://www.lambda3.com.br/2009/07/tell-dont-ask-ou-fique-longe-das-minhas-propriedades/)
- [ROBSON CASTILHO](https://robsoncastilho.com.br/2014/05/11/conceitos-tell-dont-ask/)

## FIRST
- [FIRST Concept](https://addyosmani.com/first/)

## YAGNI
 - [Yagni - Martin Fowler](https://martinfowler.com/bliki/Yagni.html)
 - [YAGNI - You ain't gonna need it](https://deviq.com/yagni/)
 
## KISS
 - [KISS for Reducing Tech Debt](https://dzone.com/articles/kiss-for-reducing-tech-debt)

## Dependecy Injection
- [Dependency injection containers vs object composition](https://www.driver733.com/2019/03/31/dependency-injection-containers-vs-object-composition.html)

## Patterns

### Architecture
- https://www.link-intersystems.com/blog/2011/10/01/anemic-vs-rich-domain-models/
- https://martinfowler.com/bliki/AnemicDomainModel.html
- https://www.quora.com/Is-it-true-that-a-good-programmer-uses-fewer-if-conditions-than-an-amateur
- [Yegor - Fail Fast](https://www.yegor256.com/2015/08/25/fail-fast.html)
- [Fail Fast](https://martinfowler.com/ieeeSoftware/failFast.pdf)
- [Crash early and crash often for more reliable software](https://medium.com/@mattklein123/crash-early-and-crash-often-for-more-reliable-software-597738dd21c5)
- [The Clean Architecture - Uncle Bob](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)
- [Clean Micro-service Architecture - Uncle Bob](https://blog.cleancoder.com/uncle-bob/2014/10/01/CleanMicroserviceArchitecture.html)
- [Immutable Data](http://kevinmahoney.co.uk/articles/immutable-data/)
- [How can you do anything useful without mutable state?](https://stackoverflow.com/questions/1020653/how-can-you-do-anything-useful-without-mutable-state)
- [10 Common Software Architectural Patterns in a nutshell](https://towardsdatascience.com/10-common-software-architectural-patterns-in-a-nutshell-a0b47a1e9013)
- [Software Architecture: the 5 Patterns You Need to Know](https://blog.ndepend.com/software-architecture-5-patterns-you-need-know/)

### GUI
- https://martinfowler.com/eaaDev/uiArchs.html
- https://pdfs.semanticscholar.org/1e22/dc6c0b5a5f2b64a91e28c68c6dd58f04d1bb.pdf
- http://ceur-ws.org/Vol-610/paper11.pdf
- https://medium.com/sketch-app-sources/design-cheatsheet-274384775da9
- https://www.programcreek.com/2009/01/the-steps-involved-in-building-a-swing-gui-application/
- https://www3.ntu.edu.sg/home/ehchua/programming/java/j4a_gui.html
- https://www3.ntu.edu.sg/home/ehchua/programming/howto/EclipseJava_HowTo.html#GUIBuider

### MVC
- [Seus controllers devem ser leves.](http://gabsferreira.com/seus-controllers-devem-ser-leves/)

### Design
- [From design patterns to category theory](http://blog.ploeh.dk/2017/10/04/from-design-patterns-to-category-theory/)
- https://sourcemaking.com/design_patterns
- https://stackoverflow.com/tags/design-patterns/info
- http://www.vincehuston.org/dp/
- https://www.yegor256.com/2016/02/03/design-patterns-and-anti-patterns.html
- https://www.lambda3.com.br/2009/04/o-que-sao-interfaces-fluentes/
- https://www.devmedia.com.br/interfaces-fluentes-revista-net-magazine-95/24065
- https://edermfl.wordpress.com/2016/01/05/interface-fluente-e-stepbuilders/
- https://dzone.com/refcardz/design-patterns?chapter=1

#### Singleton
- [Design Patterns — A quick guide to Singleton pattern.](https://medium.com/@andreaspoyias/design-patterns-a-quick-guide-to-singleton-pattern-60732ed43956)

#### Abstract Factory
- [Design Patterns — A quick guide to Abstract Factory.](https://medium.com/@andreaspoyias/design-patterns-a-quick-guide-to-abstract-factory-ab500dc12e6c)

#### Facade
- [Design Patterns — A quick guide to Facade pattern.](https://medium.com/@andreaspoyias/design-patterns-a-quick-guide-to-facade-pattern-16e3d2f1bfb6)

#### Observer
- [Design Patterns — A quick guide to Observer pattern.](https://medium.com/datadriveninvestor/design-patterns-a-quick-guide-to-observer-pattern-d0622145d6c2)

### Programação
- [The Only Coding Standard You’ll Ever Need](https://blog.gurock.com/only-coding-standard/)
- [Why shouldn't I use “Hungarian Notation”? - StackOverflow](https://stackoverflow.com/questions/111933/why-shouldnt-i-use-hungarian-notation)
- [The Mythical Man-Month](https://en.wikipedia.org/wiki/The_Mythical_Man-Month)
- [Monadic Error Handling](https://medium.com/@huund/monadic-error-handling-1e2ce66e3810)
- [What is imperative programming?](https://dev.to/mortoray/what-is-imperative-programming)
- [What is functional programming?](https://dev.to/mortoray/what-is-functional-programming)
- [What is event programming?](https://dev.to/mortoray/what-is-event-programming)
- [What is declarative programming?](https://dev.to/mortoray/what-is-declarative-programming)
- [What is reactive and stream programming?](https://dev.to/mortoray/what-is-reactive-and-stream-programming)
- [Dr. Alan Kay on the Meaning of “Object-Oriented Programming”](http://userpage.fu-berlin.de/~ram/pub/pub_jf47ht81Ht/doc_kay_oop_en)
- [REDDIT: Dr. Alan Kay on the Meaning of “Object-Oriented Programming”](https://en.reddit.com/r/programming/comments/b29qav/dr_alan_kay_on_the_meaning_of_objectoriented/)
- [What is Reactive Programming?](https://blog.redelastic.com/what-is-reactive-programming-bc9fa7f4a7fc)

## Programação funcional
- [So You Want to be a Functional Programmer (Part 1)](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-1-1f15e387e536)
- [Começando com Programação Funcional.](https://medium.com/trainingcenter/come%C3%A7ando-com-programa%C3%A7%C3%A3o-funcional-de389de2b8fe)
- [Programação funcional para iniciantes](https://medium.com/trainingcenter/programa%C3%A7%C3%A3o-funcional-para-iniciantes-9e2beddb5b43)
- [THE PILLARS OF FUNCTIONAL PROGRAMMING (PART 1)](https://sigma.software/about/media/pillars-functional-programming-part-1)
- [THE PILLARS OF FUNCTIONAL PROGRAMMING (PART 2)](https://sigma.software/about/media/pillars-functional-programming-part-2)
- [Functional programming is not a paradigm](https://dev.to/notriddle/functional-programming-is-not-a-paradigm-1p8o)
- [Can I do FP in my language?](https://dev.to/ericnormand/can-i-do-fp-in-my-language)
- [Lambda Calculus for Programmers](https://mathdevelopment.tumblr.com/post/182509661410/lambda-calculus-for-programmers)
- [Functional Programming in C#](https://blog.qfpl.io/posts/fp-in-csharp/)
- [A Gentle Introduction to Lambda Calculus - Part 1: Syntax](https://lucasfcosta.com/2018/07/29/An-Introduction-to-Lambda-Calculus-Part-1.html)
- [A Gentle Introduction to Lambda Calculus - Part 2: Execution](https://lucasfcosta.com/2018/08/05/An-Introduction-to-Lambda-Calculus-Part-2.html)
- [why-functional-programming-matters.pdf](https://github.com/papers-we-love/papers-we-love/blob/master/paradigms/functional_programming/why-functional-programming-matters.pdf)
- [An introduction to functional programming](https://codewords.recurse.com/issues/one/an-introduction-to-functional-programming)
- [Can Your Programming Language Do This?](https://www.joelonsoftware.com/2006/08/01/can-your-programming-language-do-this/)
- [Circuit Breaker in a Functional World](https://levelup.gitconnected.com/circuit-breaker-in-a-functional-world-9c555c8e9527)
- [Functional programming explained for the pragmatic programmer.](https://codurance.com/2018/08/09/the-functional-style-part-1/)

## Opiniões
- [THE FALLACY OF PREMATURE OPTIMIZATION](https://ubiquity.acm.org/article.cfm?id=1513451)
- [Enthusiasts vs. Pragmatists: two types of programmers and how they fail](https://codewithoutrules.com/2018/11/12/enthusiasts-vs-pragmatists/)
- [Why bad software architecture is easy to monetize](http://tojans.me/blog/2014/02/17/why-bad-software-architecture-is-easy-to-monetize/)
- [Goodbye, Object Oriented Programming](https://medium.com/@cscalfani/goodbye-object-oriented-programming-a59cda4c0e53)
- [10 tips and tricks for solving software problems](https://snede.net/10-tips-and-tricks-for-solving-software-problems/)
- [How to estimate programming time](https://flaviocopes.com/estimating/)
- [Do code comments suck?](https://medium.com/comparethemarket/do-code-comments-suck-abd99103c45a)
- [Famous Laws Of Software Development](https://www.timsommer.be/famous-laws-of-software-development/)
- [This Is What You Get When You Ask Programmers To Write Poetry](https://codesmithdev.com/this-is-what-you-get-when-you-ask-programmers-to-write-poetry/)
- [Technical Debt is like Tetris](https://medium.com/@erichiggins/technical-debt-is-like-tetris-168f64d8b700)
- [Programmer migration patterns (troca de linguagens)](https://apenwarr.ca/log/20190318)

## Livros
- [O Programador Pragmático. De Aprendiz a Mestre](https://www.amazon.com.br/Programador-Pragm%C3%A1tico-Aprendiz-Mestre/dp/8577807002/ref=tmm_pap_swatch_0?_encoding=UTF8&qid=&sr=)
- [Código Limpo. Habilidades Práticas Do Agile Software](https://www.amazon.com.br/C%C3%B3digo-Limpo-Habilidades-Pr%C3%A1ticas-Software/dp/8576082675/ref=pd_bxgy_14_img_2?_encoding=UTF8&pd_rd_i=8576082675&pd_rd_r=2513aadf-b815-11e8-940e-2fb2dccbe537&pd_rd_w=1yv3B&pd_rd_wg=SPJjG&pf_rd_i=desktop-dp-sims&pf_rd_m=A1ZZFT5FULY4LN&pf_rd_p=8f1717e5-6e62-42a9-8dff-5315a0fa89d7&pf_rd_r=MW8DN20FWB7JJ23R8ZHF&pf_rd_s=desktop-dp-sims&pf_rd_t=40701&psc=1&refRID=MW8DN20FWB7JJ23R8ZHF)
- [Padrões de Projetos](https://www.amazon.com.br/Padr%C3%B5es-Projetos-Erich-Gamma/dp/8573076100/ref=tmm_pap_swatch_0?_encoding=UTF8&qid=&sr=)
- [Use a Cabeça ! Padrões de Projetos](https://www.saraiva.com.br/use-a-cabeca-padroes-de-projetos-design-patterns-2-ed-revisada-1995765.html?pac_id=123134)

## OData
- http://www.odata.org/documentation/

## Parsers
- https://johnidm.gitbooks.io/compiladores-para-humanos/content/part1/lexical-analysis.html
- https://inf.ufes.br/~tavares/labcomp2000/introcomp.html
- http://www.dcc.ufrj.br/~fabiom/comp20112/
- https://pt.wikiversity.org/wiki/Introdu%C3%A7%C3%A3o_%C3%A0_Teoria_dos_Compiladores/An%C3%A1lise_L%C3%A9xica
- http://www.ic.unicamp.br/~sandro/cursos/mc910/slides/

## Extenso
- https://torry.net/quicksearchd.php?String=NumWords&Title=Yes
- http://www.migalhas.com.br/Gramatigalhas/10,MI30427,91041-Hum
- https://www.professornews.com.br/dicas-de-redacao/6895-como-escrever-valores-em-cheques-hum-mil-reais-ou-um-mil-reais.html
- http://www.languagesandnumbers.com/como-contar-em-portugues-brasil/pt/por-bra/
- http://www.languagesandnumbers.com/como-contar-em-espanhol/pt/spa/
- http://www.languagesandnumbers.com/como-contar-em-ingles/pt/eng/
- https://www.englishexperts.com.br/forum/numeros-em-ingles-de-0-a-1-000-000-000-t1078.html
- https://www.englishexperts.com.br/numeros-em-ingles-por-extenso/
- https://www.englishexperts.com.br/wp-content/themes/master/tools/numeros-extenso/numbers.js

## Autenticação
- [How We Solved Authentication and Authorization in Our Microservice Architecture](https://medium.com/technology-learning/how-we-solved-authentication-and-authorization-in-our-microservice-architecture-994539d1b6e6)

## IDE
- [Hoje irei apresentar o VS Code](https://medium.com/@programadriano/hoje-irei-apresentar-o-vs-code-visual-studio-code-para-quem-ainda-n%C3%A3o-teve-contato-com-ele-6a0d6bd3baec)

## Neural Nets
- [Neural Network Woes](https://en.reddit.com/r/ProgrammerHumor/comments/a8xe9w/neural_network_woes/?st=jq2d92md&sh=d76f4b13)
- [Computer Vision (AI): Object Detection and Segmentation with Mask R-CNN](https://www.youtube.com/watch?v=akK5ui-vel0&feature=youtu.be)
- [Neural Networks to Production, From an Engineer](https://austingwalters.com/neural-networks-to-production-from-an-engineer/)

## Problemas
- [Data structures and problems](https://www.techiedelight.com/list-of-problems/)
- [Top 50 Algorithms and Coding Interview Questions](https://hackernoon.com/50-data-structure-and-algorithms-interview-questions-for-programmers-b4b1ac61f5b0)

## Performance
- [Challenge your performance intuition with C++ operators](http://wordsandbuttons.online/challenge_your_performance_intuition_with_cpp_operators.html)

## Programação dinâmica
- [Geeks - Dynamic Programming](https://www.geeksforgeeks.org/dynamic-programming/)
- [The One On Dynamic Programming!](https://blogarithms.github.io/articles/2019-03/cracking-dp-part-one)
- [A graphical introduction to dynamic programming](https://medium.com/@avik.das/a-graphical-introduction-to-dynamic-programming-2e981fa7ca2?sk=37cd14642cf1a83eb0bb33d231442837)

## Expressões Regulares
- [Online Tester 101](https://regex101.com/)
- [Regex Cheat Sheet](https://dev.to/emmawedekind/regex-cheat-sheet-2j2a)
- [Regular expressions cheat sheet](http://www.cbs.dtu.dk/courses/27610/regular-expressions-cheat-sheet-v2.pdf)

## Lua
- [Binding Code To Lua](http://lua-users.org/wiki/BindingCodeToLua)


ΛΘΧΙΛΡΖ
