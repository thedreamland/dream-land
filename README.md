# Dream Land
Specification for interoperability of common functions across most programming languages

## Inspiration
The seed for the Dream Land specification was sown after learning about [Fantasy Land](https://github.com/fantasyland/fantasy-land). An initiative to consolidate functional programming libraries for JavaScript. This would put the pressure on the library authors rather than the developers utilizing the libraries. Further inspiration came from the late Joe Armstrong that repeatedly cited the increasing problem of fragmentation and entropy in the programming community. Among many things Joe wished for a universal reduce function that could take all the existing code and reduce it down to the bare minimum. The next epiphany came when I (Chris) started learning functional programming. There was a clear likeness between all mainstream imperative and object oriented languages, not that surprising considering their ALGOL legacy. However when applying functional principles and breaking down functions properly, the lines started blurring and previously unnoticeable similarities between Java, JavaScript and Haskell began to appear. This motivated me into the idea that there could be an untapped potential, a pivot that could move the industry forward significantly.

## Motivation
I (Chris) have spent the second half of my career, re-evaluating everything I had learned so far. I have been extremely open with alternative solutions and scrutinized mainstream approaches. The following points that I would like to highlight are merely personal observations and are by no means backed by any scientific data. The intention is to be thought provoking but by no means insult any of the involved communities. There is a necessity to initiate a discussion regarding these issues which should be constructive and methodical in nature. I would of course love to get everything backed by science if someone with a background in Computer Science or IT Industry research can help out.
* Several languages lack common fundamental functions. This has led some languages to become more popular due to the spectrum of the standard libraries rather than the properties and features of the language itself.
* The consistency of standard library functions varies a lot between languages. Functions and Types might differ only by name while otherwise behave in the exact same manner. This discrepancy only adds unnecessary confusion between language communities. Having a shared vocabulary and terminology would be a huge benefit considering the innate complexity of software in general.
* Further the misuse of terminology seems to be even greater when it comes to established functional programming and category theory concepts. Where concepts are deliberately renamed to "feel" less esoteric as some means of not discouraging the pragmatic nature of programmers. This is not only humiliating to the intelligence of software developers but also alienates the functional programming and mathematical communities. Which is sad considering the vast amounts of knowledge that never gets to surface.
* Most mainstream languages are slow at introducing established concepts from computer science. Languages promote "new" features, while in reality the concept might be several decades old or already featured in another less established language.
* Developer adoption of new features is very slow, this varies between communities of course.
* Many languages are intentionally or accidentally discriminating towards functional programming. This varies from cases where functional programming has been intentionally supported but incorrectly implmented or imperative and object oriented principles have only been prioritized. This is a missed opportunity since the required adjustments to make API:s work across more paradigms is usually minimal.
* Fundamental computer science, principled methods and formal verification is absent in the major part of the industry. This will likely be an increasing problem in the near future where Machine Learning, AI, Blockchain and Quantum Computing will be high in demand.
* Third party libraries are undergoing natural selection. This in itself is not a bad thing since competition tends to improve performance and quality. However there are several occurences where bloom and then suddenly die. While in the better cases library maintainers recognize how they can cooperate and decide to merge and kill off the remaining projects. There is no denying the enthusiasm and effort that is put into open source projects. So therefore it is sad when the effort could be more efficiently directed towards improving the big picture.
* Third party libraries are repeatedly penalized to compensate for the lack of common generic functions in the standard libraries and usually resort to writing their own internal functions or pulling in additional dependencies.
* The level of quality and reliability of third party functions is varied. The common notion is that open source is usually better because more people are or can be involved as well as the code is used in more projects and therefore tested more extensively. From a holistic point of view the level of testing and correctness can be like night and day. For example take the freedom of JavaScript and the available testing tools in that ecosystem and compare with the strictness of Haskell + property based testing + formal verification.

## Goals
* Learn a function once and apply in any language.
* Reduce focus on what standard libraries a language provides and instead highlight fundamental concepts and language features.
* Avoid common bugs and complexity by enforcing function purity and immutability by default.
* Provide mutable alternatives.
  * These should clearly document the potential side effect and motivate when it is a valid compromise, e.g. for extra performance.
* Functions should be optimized for currying to be able to include the broad spectrum of languages.
  * Functions should be curried by default, explicit/auto curried or due to other reasonable limitations provide an alternate module with curried versions of all functions.
* Reduce dependencies on third party libraries and speed up standard library implementation and adoption.
* Simplify porting code from one language to another so that programming languages can actually be treated as tools rather than business assets.
  * Utilize universal transpilers to simplify further.
* Reduce the learning curve from imperative and object oriented paradigms to adopt others like functional programming.
* Organically introduce principled methods and mental frameworks such as Category Theory.
* Bring programming language communities closer together.
* Provide the high quality test requirements and/or formal proofs that each function specification has to comply with.
* Provide a Dream Land Compliancy badge and be listed under Dream Land Compliant Languages.

## Initial Assumptions & Exceptions
* Some languages might be harder or impossible to conform to a universal standard.
  * APL which is designed after the tacit programming paradigm and relies heavily on operators.
  * Prolog and other languages that are design by the logical programming paradigm.

## Dream Land Compliant Badge
TBD

## Dream Land Compliant Languages
WIP

## Dream Land Standard Library Specification
WIP
