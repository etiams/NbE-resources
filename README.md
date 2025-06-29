# 📚 `NbE-resources`

Normalization-by-evaluation ("NbE" for short) is an elegant technique for computing normal forms of object language terms. It consists of only two parts: _evaluation_ (_reflection_, _denotation_), which maps syntactic terms to the semantic domain, and _quotation_ (_read-back_, _reification_), which maps values from the semantic domain back to terms. The composition of evaluation followed by quotation is called _normalization_. One classical example of normalization-by-evaluation is computing β-normal forms of lambda calculus terms, optionally enriched with additional constructions. Alongside with bidirectional type checking, normalization-by-evaluation is considered traditional in the implementation of dependently typed programming languages & proof assistants based on type theory.

This is a collection of resources for studying normalization-by-evaluation & its applications, ranging from introductory materials to advanced papers. Any questions regarding NbE will be welcomed in the issues.

## Projects

 - [`AndrasKovacs/elaboration-zoo`](https://github.com/AndrasKovacs/elaboration-zoo) -- Minimal implementations for dependent type checking and elaboration.
 - [`nguermond/normalization-by-evaluation`](https://github.com/nguermond/normalization-by-evaluation) -- Various implementations of normalization by evaluation.
 - [`jozefg/nbe-for-mltt`](https://github.com/jozefg/nbe-for-mltt) -- Normalization by Evaluation for Martin-Löf Type Theory.
 - [`AndrasKovacs/sysF-NbE`](https://github.com/AndrasKovacs/sysF-NbE) -- Normalization by evaluation for intrinsic System F.
 - [`nachivpn/nbe-edsl`](https://github.com/nachivpn/nbe-edsl) -- Normalization by Evaluation for Embedded Domain-specific Languages.
 - [`src/Core/Normalise/Eval.idr`](https://github.com/idris-lang/Idris2/blob/main/src/Core/Normalise/Eval.idr), [`Quote.idr`](https://github.com/idris-lang/Idris2/blob/main/src/Core/Normalise/Quote.idr) -- Normalization-by-evaluation in Idris2.
 - [`src/full/Agda/TypeChecking/Reducer.hs`](https://github.com/agda/agda/blob/master/src/full/Agda/TypeChecking/Reduce.hs), [`Quote.hs`](https://github.com/agda/agda/blob/master/src/full/Agda/TypeChecking/Quote.hs) - Normalization-by-evaluation in Agda.
 - [`webyrd/normalization-by-evaluation`](https://github.com/webyrd/normalization-by-evaluation) -- Normalization-by-evaluation in miniKanren.

## Blog posts

 - [_"A Brief Introduction to Normalization-By-Evaluation"_](https://gist.github.com/etiams/7fbb66a46b2a43be908ccd4015d00fb9) by Louis F. Ashfield.
 - [_"Checking Dependent Types with Normalization by Evaluation: A Tutorial"_](https://davidchristiansen.dk/tutorials/nbe/) by David Thrane Christiansen.
 - [_"Normalization by Evaluation Four Ways: Reconstructing NbE Designs from First Principles"_](https://williamjbowman.com/tmp/nbe-four-ways/) by William J. Bowman.
 - [_"Elementary Tutorial on Normalization-by-Evaluation"_](https://okmij.org/ftp/tagless-final/NBE.html) by Oleg Kiselyov.
 - [_"Evaluators, Normalizers, Reducers: from denotational to operational semantics"_](https://okmij.org/ftp/tagless-final/semantics.html) by Oleg Kiselyov.

## Papers

### 1991

 - Berger, Ulrich, and Helmut Schwichtenberg. "An inverse of the evaluation functional for typed lambda-calculus." (1991): 203-211.
   <br>[URL](https://epub.ub.uni-muenchen.de/4261/1/4261.pdf), [webarchive](http://web.archive.org/web/20250628221736/https://epub.ub.uni-muenchen.de/4261/1/4261.pdf)

### 1996

 - Danvy, Olivier. "Type-directed partial evaluation." Proceedings of the 23rd ACM SIGPLAN-SIGACT symposium on Principles of programming languages. 1996.
   <br>[URL](https://dl.acm.org/doi/pdf/10.1145/237721.237784)

### 1997

 - Coquand, Thierry, and Peter Dybjer. "Intuitionistic model constructions and normalization proofs." Mathematical Structures in Computer Science 7.1 (1997): 75-94.
   <br>[URL](http://www.cs.ru.nl/~herman/PUBS/NijmegenTypes.pdf#page=95), [webarchive](http://web.archive.org/web/20240420151416/http://www.cs.ru.nl/~herman/PUBS/NijmegenTypes.pdf#page=95)

### 1999

 - Filinski, Andrzej. "A semantic account of type-directed partial evaluation." International Conference on Principles and Practice of Declarative Programming. Berlin, Heidelberg: Springer Berlin Heidelberg, 1999.
   <br>[URL](https://www.brics.dk/RS/99/17/BRICS-RS-99-17.pdf), [webarchive](http://web.archive.org/web/20240416214621/https://www.brics.dk/RS/99/17/BRICS-RS-99-17.pdf)

### 2001

 - Altenkirch, Thorsten, et al. "Normalization by evaluation for typed lambda calculus with coproducts." Proceedings 16th Annual IEEE Symposium on Logic in Computer Science. IEEE, 2001.
   <br>[URL](https://people.cs.nott.ac.uk/psztxa/publ/lics01.pdf), [webarchive](http://web.archive.org/web/20250628220136/https://people.cs.nott.ac.uk/psztxa/publ/lics01.pdf)
 - Danvy, Olivier, Morten Rhiger, and Kristoffer H. Rose. "Normalization by evaluation with typed abstract syntax." Journal of Functional Programming 11.6 (2001): 673-680.
   <br>[URL](https://www.brics.dk/RS/01/16/BRICS-RS-01-16.pdf), [webarhive](http://web.archive.org/web/20250310141725/https://www.brics.dk/RS/01/16/BRICS-RS-01-16.pdf)

### 2005

 - Filinski, Andrzej, and Henning Korsholm Rohde. "Denotational aspects of untyped normalization by evaluation." RAIRO-Theoretical Informatics and Applications 39.3 (2005): 423-453.
   <br>[URL](https://www.numdam.org/item/10.1051/ita:2005026.pdf), [webarchive](http://web.archive.org/web/20240415161150/http://www.numdam.org/item/10.1051/ita:2005026.pdf)

### 2007

 - Abel, Andreas, Klaus Aehlig, and Peter Dybjer. "Normalization by evaluation for Martin-Löf type theory with one universe." Electronic Notes in Theoretical Computer Science 173 (2007): 17-39.
   <br>[URL](https://www.cse.chalmers.se/~peterd/papers/NbeMLTT.pdf), [webarchive](http://web.archive.org/web/20240420045941/https://www.cse.chalmers.se/~peterd/papers/NbeMLTT.pdf)
 - Abel, Andreas, Thierry Coquand, and Peter Dybjer. "Normalization by evaluation for Martin-Löf Type Theory with typed equality judgements." 22nd Annual IEEE Symposium on Logic in Computer Science (LICS 2007). IEEE, 2007.
   <br>[URL](https://www.cse.chalmers.se/~peterd/papers/NbeMLTTEqualityJudgements.pdf), [webarchive](http://web.archive.org/save/https://www.cse.chalmers.se/~peterd/papers/NbeMLTTEqualityJudgements.pdf)

### 2009

 - Boespflug, Mathieu. "Efficient normalization by evaluation." 2009 Workshop on Normalization by Evaluation. 2009.
   <br>[URL](https://inria.hal.science/inria-00434283/document), [webarchive](http://web.archive.org/web/20250628215519/https://inria.hal.science/inria-00434283/document)
 - Coquand, Thierry, et al. “A Simple Type-Theoretic Language: Mini-TT.” From Semantics to Computer Science: Essays in Honour of Gilles Kahn. Ed. Yves Bertot, et al. Cambridge: Cambridge University Press, 2009. 139–164. Print.
    <br>[URL](https://scispace.com/pdf/a-simple-type-theoretic-language-mini-tt-wfbf2kd6qm.pdf)

### 2010

 - Mendel-Gleason, Gavin E., and Geoff W. Hamilton. "Supercompilation and normalisation by evaluation." (2010).
   <br>[URL](http://meta2010.pereslavl.ru/accepted-papers/meta2010-Gavin-Mendel-Gleason-Geoff-Hamilton.pdf), [webarchive](http://web.archive.org/web/20250512144830/http://meta2010.pereslavl.ru/accepted-papers/meta2010-Gavin-Mendel-Gleason-Geoff-Hamilton.pdf)

### 2013

 - Abel, Andreas. "Normalization by evaluation: Dependent types and impredicativity." Habilitation. Ludwig-Maximilians-Universität München (2013).
   <br>[URL](https://www.cse.chalmers.se/~abela/habil.pdf), [webarchive](http://web.archive.org/web/20250616055205/https://www.cse.chalmers.se/~abela/habil.pdf)
 - Ahman, Danel, and Sam Staton. "Normalization by evaluation and algebraic effects." Electronic Notes in Theoretical Computer Science 298 (2013): 51-69.
   <br>[URL](https://danel.ahman.ee/papers/mfps13.pdf), [webarchive](http://web.archive.org/web/20240524043112/https://danel.ahman.ee/papers/mfps13.pdf)

### 2014

 - Danvy, Olivier, Chantal Keller, and Matthias Puech. "Typeful normalization by evaluation." 20th International Conference on Types for Proofs and Programs, TYPES 2014. 2014.
   <br>[URL](https://inria.hal.science/hal-01397929/file/types14.pdf), [webarchive](http://web.archive.org/web/20250628220318/https://inria.hal.science/hal-01397929/file/types14.pdf)

### 2017

 - Abel, Andreas, Andrea Vezzosi, and Theo Winterhalter. "Normalization by evaluation for sized dependent types." Proceedings of the ACM on Programming Languages 1.ICFP (2017): 1-30.
   <br>[URL](https://dl.acm.org/doi/pdf/10.1145/3110277), [webarchive](http://web.archive.org/web/20250628215415/https://dl.acm.org/doi/pdf/10.1145/3110277)

### 2019

 - Gratzer, Daniel, Jonathan Sterling, and Lars Birkedal. "Implementing a modal dependent type theory." Proceedings of the ACM on Programming Languages 3.ICFP (2019): 1-29.
   <br>[URL](http://www.danielgratzer.com/papers/2019-implementing-modal-dependent-type-theory.pdf), [webarchive](http://web.archive.org/web/20241214000208/https://www.danielgratzer.com/papers/2019-implementing-modal-dependent-type-theory.pdf)

### 2021

 - Valliappan, Nachiappan, Alejandro Russo, and Sam Lindley. "Practical normalization by evaluation for EDSLs." Proceedings of the 14th ACM SIGPLAN International Symposium on Haskell. 2021.
   <br>[URL](https://www.cse.chalmers.se/~russo/publications_files/haskell21.pdf), [webarchive](http://web.archive.org/web/20241119110900/https://www.cse.chalmers.se/~russo/publications_files/haskell21.pdf)

### 2022

 - Biernacka, Małgorzata, Witold Charatonik, and Tomasz Drab. "A simple and efficient implementation of strong call by need by an abstract machine." Proceedings of the ACM on Programming Languages 6.ICFP (2022): 109-136.
   <br>[URL](https://dl.acm.org/doi/pdf/10.1145/3549822)
