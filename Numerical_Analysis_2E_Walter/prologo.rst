P1 Overview

Numerical Analysis is the branch of mathematics that provides tools and methods
for solving mathematical problems in numerical form. The objective is to develop
detailed computational procedures, capable of being implemented on electronic
computers, and to study their performance characteristics. Related fields are Sci-
entific Computation, which explores the application of numerical techniques and
computer architectures to concrete problems arising in the sciences and engineering;
Complexity Theory, which analyzes the number of “operations” and the amount of
computer memory required to solve a problem; and Parallel Computation, which
is concerned with organizing computational procedures in a manner that allows
running various parts of the procedures simultaneously on different processors.

The problems dealt with in computational mathematics come from virtually
all branches of pure and applied mathematics. There are computational aspects
in number theory, combinatorics, abstract algebra, linear algebra, approximation
theory, geometry, statistics, optimization, complex analysis, nonlinear equations,
differential and other functional equations, and so on. It is clearly impossible
to deal with all these topics in a single text of reasonable size. Indeed, the
tendency today is to develop specialized texts dealing with one or the other
of these topics. In the present text we concentrate on subject matters that are
basic to problems in approximation theory, nonlinear equations, and differential
equations. Accordingly, we have chapters on machine arithmetic, approximation
and interpolation, numerical differentiation and integration, nonlinear equations,
one-step and multistep methods for ordinary differential equations, and boundary
value problems in ordinary differential equations. Important topics not covered
in this text are computational number theory, algebra, and geometry; constructive
methods in optimization and complex analysis; numerical linear algebra; and the
numerical solution of problems involving partial differential equations and integral
equations. Selected texts for these areas are enumerated in Sect. P3.

We now describe briefly the topics treated in this text. Chapter 1 deals with
the basic facts of life regarding machine computation. It recognizes that, although
present-day computers are extremely powerful in terms of computational speed,
reliability, and amount of memory available, they are less than ideal – unless
supplemented by appropriate software – when it comes to the precision available,
and accuracy attainable, in the execution of elementary arithmetic operations. This
raises serious questions as to how arithmetic errors, either present in the input
data of a problem or committed during the execution of a solution algorithm,
affect the accuracy of the desired results. Concepts and tools required to answer
such questions are put forward in this introductory chapter. In Chap. 2, the central
theme is the approximation of functions by simpler functions, typically polynomials
and piecewise polynomial functions. Approximation in the sense of least squares
provides an opportunity to introduce orthogonal polynomials, which are relevant
also in connection with problems of numerical integration treated in Chap. 3. A large
part of the chapter, however, deals with polynomial interpolation and associated
error estimates, which are basic to many numerical procedures for integrating
functions and differential equations. Also discussed briefly is inverse interpolation,
an idea useful in solving equations.

First applications of interpolation theory are given in Chap. 3, where the tasks
presented are the computation of derivatives and definite integrals. Although the
formulae developed for derivatives are subject to the detrimental effects of machine
arithmetic, they are useful, nevertheless, for purposes of discretizing differential
operators. The treatment of numerical integration includes routine procedures, such
as the trapezoidal and Simpson’s rules, appropriate for well-behaved integrands, as
well as the more sophisticated procedures based on Gaussian quadrature to deal
with singularities. It is here where orthogonal polynomials reappear. The method of
undetermined coefficients is another technique for developing integration formulae.
It is applied to approximate general linear functionals, the Peano representation
of linear functionals providing an important tool for estimating the error. The
chapter ends with a discussion of extrapolation techniques; although applicable to
more general problems, they are inserted here since the composite trapezoidal rule
together with the Euler–Maclaurin formula provides the best-known application –
Romberg integration.

Chapter 4 deals with iterative methods for solving nonlinear equations and
systems thereof, the pi`ece de r´esistance being Newton’s method. The emphasis here
lies in the study of, and the tools necessary to analyze, convergence. The special
case of algebraic equations is also briefly given attention.

Chapter 5 is the first of three chapters devoted to the numerical solution of
ordinary differential equations. It concerns itself with one-step methods for solving
initial value problems, such as the Runge–Kutta method, and gives a detailed
analysis of local and global errors. Also included is a brief introduction to stiff
equations and special methods to deal with them. Multistep methods and, in
particular, Dahlquist’s theory of stability and its applications, is the subject of
Chap. 6. The final chapter (Chap. 7) is devoted to boundary value problems and their
solution by shooting methods, finite difference techniques, and variational methods.

P2 Numerical Analysis Software

There are many software packages available, both in the public domain and dis-
tributed commercially, that deal with numerical analysis algorithms. A widely used
source of numerical software is Netlib, accessible at http://www.netlib.org.

Large collections of general-purpose numerical algorithms are contained in
sources such as Slatec (http://www.netlib.org/slatec) and TOMS
(ACM Transactions on Mathematical Software). Specialized packages relevant
to the topics in the chapters ahead are identified in the “Notes” to each chapter.
Likewise, specific files needed to do some of the machine assignments in the
Exercises are identified as part of the exercise.

Among the commercial software packages we mention the Visual Numerics
(formerly IMSL) and NAG libraries. Interactive systems include HiQ, Macsyma,
Maple, Mathcad, Mathematica, and Matlab. Many of these packages, in addition
to numerical computation, have symbolic computation and graphics capabilities.
Further information is available in the Netlib file commercial. For more libraries,
and for interactive systems, also see Lozier and Olver [1994, Sect. 3].

In this text we consistently use Matlab as a vehicle for describing algorithms
and as the software tool for carrying out some of the exercises and all machine
assignments.

P3 Textbooks and Monographs

We provide here an annotated list (ordered alphabetically with respect to authors)
of other textbooks on numerical analysis, written at about the same, or higher, level
as the present one. Following this, we also mention books and monographs dealing
with topics in computational mathematics not covered in our (and many other) books
on numerical analysis. Additional books dealing with specialized subject areas, as
well as other literature, are referenced in the “Notes” to the individual chapters. We
generally restrict ourselves to books written in English and, with a few exceptions,
published within the last 25 years or so. Even so, we have had to be selective. (No
value judgment is to be implied by our selections or omissions.) A reader with access
to the AMS (American Mathematical Society) MathSci Net homepage will have no
difficulty in retrieving a more complete list of relevant items, including older texts.

P3.1 Selected Textbooks on Numerical Analysis

Atkinson [1989] A comprehensive in-depth treatment of standard topics short of
partial differential equations; includes an appendix describing some of the better-
known software packages.

Atkinson and Han [2009] An advanced text on theoretical (as opposed to com-
putational) aspects of numerical analysis, making extensive use of functional
analysis.

Bruce, Giblin, and Rippon [1990] A collection of interesting mathematical prob-
lems, ranging from number theory and computer-aided design to differential
equations, that require the use of computers for their solution.

Cheney and Kincaid [1994] Although an undergraduate text, it covers a broad
area, has many examples from science and engineering as well as computer
programs; there are many exercises, including machine assignments.

Conte and de Boor [1980] A widely used text for upper-division undergraduate
students; written for a broad audience, with algorithmic concerns in the fore-
ground; has Fortran subroutines for many algorithms discussed in the text.

Dahlquist and Bj¨orck [2003, 2008] The first (2003) text – a reprint of the 1974
classic – provides a comprehensive introduction to all major fields of numerical
analysis, striking a good balance between theoretical issues and more practical
ones. The second text expands substantially on the more elementary topics
treated in the first and represents the first volume of more to come.

Deuflhard and Hohmann [2003] An introductory text with emphasis on machine
computation and algorithms; includes discussions of three-term recurrence
relations and stochastic eigenvalue problems (not usually found in textbooks),
but no differential equations.

Fr¨oberg [1985] A thorough and exceptionally lucid exposition of all major topics
of numerical analysis exclusive of algorithms and computer programs.

H¨ammerlin and Hoffmann [1991] Similar to Stoer and Bulirsch [2002] in its
emphasis on mathematical theory; has more on approximation theory and
multivariate interpolation and integration, but nothing on differential equations.

Householder [2006] A reissue of one of the early mathematical texts on the
subject, with coverage limited to systems of linear and nonlinear equations and
topics in approximation.

Isaacson and Keller [1994] One of the older but still eminently readable texts,
stressing the mathematical analysis of numerical methods.

Kincaid and Cheney [1996] Related to Cheney and Kincaid [1994] but more
mathematically oriented and unusually rich in exercises and bibliographic items.

Kress [1998] A rather comprehensive text with a strong functional analysis
component.

Neumaier [2001] A text emphasizing robust computation, including interval
arithmetic.

Rutishauser [1990] An annotated translation from the German of an older text
based on posthumous notes by one of the pioneers of numerical analysis;
although the subject matter reflects the state of the art in the early 1970s, the
treatment is highly original and is supplemented by translator’s notes to each
chapter pointing to more recent developments.

Schwarz [1989] A mathematically oriented treatment of all major areas of numer-
ical analysis, including ordinary and partial differential equations.

Stoer and Bulirsch [2002] Fairly comprehensive in coverage; written in a style
appealing more to mathematicians than engineers and computer scientists; has
many exercises and bibliographic references; serves not only as a textbook but
also as a reference work.

Todd [1979, 1977] Rather unique books, emphasizing problem-solving in areas
often not covered in other books on numerical analysis.

P3.2 Monographs and Books on Specialized Topics

A collection of outstanding survey papers on specialized topics in numerical
analysis is being assembled by Ciarlet and Lions [1990–2003] in handbooks of
numerical analysis; nine volumes have appeared so far. Another source of surveys
on a variety of topics is Acta numerica, an annual series of books edited by Iserles
[1992–2010], of which 19 volumes have been published so far. For an authoritative
account of the history of numerical analysis from the 16th through the 19th century,
the reader is referred to the book by Goldstine [1977]. For more recent history, see
Bultheel and Cools, eds. [2010].

The related areas of Scientific Computing and Parallel Computing are rather
more recent fields of study. Basic introductory texts are Scott et al. [2005]
and Tveito and Winter [2009]. Texts relevant to linear algebra and differential
equations are Schendel [1984], Ortega and Voigt [1985], Ortega [1989], Golub
and Ortega [1992], [1993], Van de Velde [1994], Burrage [1995], Heath [1997],
Deuflhard and Bornemann [2002], O’Leary [2009], and Quarteroni et al. [2010].
Other texts address topics in optimization, Pardalos et al. [1992] and Gonnet
and Scholl [2009]; computational geometry, Akl and Lyons [1993]; and other
miscellaneous areas, Crandall [1994], [1996], K¨ockler [1994], Bellomo and Preziosi
[1995], Danaila et al. [2007], and Farin and Hansford [2008]. Interesting historical
essays are contained in Nash, ed. [1990]. Matters regarding the Complexity of
numerical algorithms are discussed in an abstract framework in books by Traub and
Wo´zniakowski [1980] and Traub, Wasilkowski, and Wo´zniakowski [1983], [1988],
with applications to the numerical integration of functions and nonlinear equations,
and similarly, applied to elliptic partial differential equations and integral equations,
in the book by Werschulz [1991]. Other treatments are those by Kronsj¨o [1987], Ko
[1991], Bini and Pan [1994], Wang et al. [1994], Traub and Werschulz [1998], Ritter
[2000], and Novak et al. [2009]. For an in-depth complexity analysis of Newton’s
method, the reader is encouraged to study Smale’s [1987] lecture.

Material on Computational Number Theory can be found, at the undergraduate
level, in the book by Rosen [2000], which also contains applications to cryptography
and computer science, and in Allenby and Redfern [1989], and at a more advanced
level in the books by Niven et al. [1991], Cohen [1993], and Bach and Shallit
[1996]. Computational methods of factorization are dealt with in the book by
Riesel [1994]. Other useful sources are the set of lecture notes by Pohst [1993]
on algebraic number theory algorithms, and the proceedings volumes edited by
Pomerance [1990] and Gautschi [1994a, Part II]. For algorithms in Combinatorics,
see the books by Nijenhuis and Wilf [1978], Hu and Shing [2002], and Cormen et
al. [2009]. Various aspects of Computer Algebra are treated in the books by Geddes
et al. [1992], Mignotte [1992], Davenport et al. [1993], Mishra [1993], Heck [2003],
and Cox et al. [2007].

Other relatively new disciplines are Computational Geometry and Geometric
Modeling, Computer-Aided Design, and Computational Topology, for which rel-
evant texts are, respectively, Preparata and Shamos [1985], Edelsbrunner [1987],
M¨antyl¨a [1988], Taylor [1992], McLeod and Baart [1998], Gallier [2000], Cohen et
al. [2001], and Salomon [2006]; Hoschek and Lasser [1993], Farin [1997], [1999],
and Prautsch et al. [2002]; Edelsbrunner [2006], and Edelsbrunner and Harer [2010].
Statistical Computing is covered in general textbooks such as Kennedy and Gentle
[1980], Anscombe [1981], Maindonald [1984], Thisted [1988], Monahan [2001],
Gentle [2009], and Lange [2010]. More specialized texts are Devroye [1986] and
H¨ormann et al. [2004] on the generation of nonuniform random variables, Sp¨ath
[1992] on regression analysis, Heiberger [1989] on the design of experiments,
Stewart [1994] on Markov chains, Xiu [2010] on stochastic computing and uncer-
tainty quantification, and Fang and Wang [1994], Manno [1999], Gentle [2003],
Liu [2008], Shonkwiler and Mendivil [2009], and Lemieux [2009] on Monte Carlo
and number-theoretic methods. Numerical techniques in Optimization (including
optimal control problems) are discussed in Evtushenko [1985]. An introductory
book on unconstrained optimization is Wolfe [1978]; among more advanced and
broader texts on optimization techniques we mention Gill et al. [1981], Ciarlet
[1989], and Fletcher [2001]. Linear programming is treated in Nazareth [1987] and
Panik [1996], linear and quadratic problems in Sima [1996], and the application of
conjugate direction methods to problems in optimization in Hestenes [1980]. The
most comprehensive text on (numerical and applied) Complex Analysis is the three-
volume treatise by Henrici [1988, 1991, 1986]. Numerical methods for conformal
mapping are also treated in Kythe [1998], Schinzinger and Laura [2003], and
Papamichael and Stylianopoulos [2010]. For approximation in the complex domain,
the standard text is Gaier [1987]; Stenger [1993] deals with approximation by
sinc functions, Stenger [2011] providing some 450 Matlab programs. The book by
Iserles and Nørsett [1991] contains interesting discussions on the interface between
complex rational approximation and the stability theory of discretized differential
equations. The impact of high-precision computation on problems and conjectures
involving complex approximation is beautifully illustrated in the set of lectures by
Varga [1990].
For an in-depth treatment of many of the preceding topics, also see the four-
volume work of Knuth [1975, 1981, 1973, 2005–2006].
Perhaps the most significant topic omitted in our book is numerical linear algebra
and its application to solving partial differential equations by finite difference or
finite element methods. Fortunately, there are many treatises available that address
these areas. For Numerical Linear Algebra, we refer to the classic work of Wilkinson
[1988] and the book by Golub and Van Loan [1996]. Links and applications
of matrix computation to orthogonal polynomials and quadrature are the subject
P3 Textbooks and Monographs xxv
of Golub and Meurant [2010]. Other general texts are Jennings and McKeown
[1992], Watkins [2002], [2007], Demmel [1997], Trefethen and Bau [1997], Stewart
[1973], [1998], Meurant [1999], White [2007], Allaire and Kaber [2008], and
Datta [2010]; Higham [2002], [2008] has a comprehensive treatment of error and
stability analyses and the first, equally extensive, treatment of the numerics of matrix
functions. Solving linear systems on vector and shared memory parallel computers
and the use of linear algebra packages on high-performance computers are discussed
in Dongarra et al. [1991], [1998]. The solution of sparse linear systems and the
special data structures and pivoting strategies required in direct methods are treated
in Østerby and Zlatev [1983], Duff et al. [1989], Zlatev [1991], and Davis [2006],
whereas iterative techniques are discussed in the classic texts by Young [2003]
and Varga [2000], and in Il’in [1992], Hackbusch [1994], Weiss [1996], Fischer
[1996], Brezinski [1997], Greenbaum [1997], Saad [2003], Broyden and Vespucci
[2004], Hageman and Young [2004], Meurant [2006], Chan and Jin [2007], Byrne
[2008], and Wo´znicki [2009]. The books by Branham [1990] and Bj¨orck [1996]
are devoted especially to least squares problems. For eigenvalues, see Chatelin
[1983], [1993], and for a good introduction to the numerical analysis of symmetric
eigenvalue problems, see Parlett [1998]. The currently very active investigation of
large sparse symmetric and nonsymmetric eigenvalue problems and their solution
by Lanczos-type methods has given rise to many books, for example, Cullum and
Willoughby [1985], [2002], Meyer [1987], Sehmi [1989], and Saad [1992]. For
structured and symplectic eigenvalue problems, see Fassbender [2000] and Kressner
[2005], and for inverse eigenvalue problems, Xu [1998] and Chu and Golub [2005].
For readers wishing to test their algorithms on specific matrices, the collection of
test matrices in Gregory and Karney [1978] and the “matrix market” on the Web
(http://math.nist.gov./MatrixMarket) are useful sources.
Even more extensive is the textbook literature on the numerical solution of Par-
tial Differential Equations. The field has grown so much that there are currently only
a few books that attempt to cover the subject more or less as a whole. Among these
are Birkhoff and Lynch [1984] (for elliptic problems), Hall and Porsching [1990],
Ames [1992], Celia and Gray [1992], Larsson and Thom´ee [2003], Quarteroni and
Valli [1994], Morton and Mayers [2005], Sewell [2005], Quarteroni [2009], and
Tveito and Winter [2009]. Variational and finite element methods seem to have
attracted the most attention. An early and still frequently cited reference is the
book by Ciarlet [2002] (a reprint of the 1978 original); among more recent texts
we mention Beltzer [1990] (using symbolic computation), K˘r´ı˘zek and Neittaanm¨aki
[1990], Brezzi and Fortin [1991], Schwab [1998], Kwon and Bang [2000] (using
Matlab), Zienkiewicz and Taylor [2000], Axelsson and Barker [2001], Babuˇska
and Strouboulis [2001], H¨ollig [2003], Monk [2003] (for Maxwell’s equation),
Ern and Guermonde [2004], Kythe and Wei [2004], Reddy [2004], Chen [2005],
Elman et al. [2005], Thom´ee [2006] (for parabolic equations), Braess [2007],
Demkowicz [2007], Brenner and Scott [2008], Bochev and Gunzburger [2009],
Efendiev and Hou [2009], and Johnson [2009]. Finite difference methods are treated
in Ashyralyev and Sobolevski˘ı [1994], Gustafsson et al. [1995], Thomas [1995],
[1999], Samarskii [2001], Strikwerda [2004], LeVeque [2007], and Gustafsson
xxvi Prologue
[2008]; the method of lines in Schiesser [1991]; and the more refined techniques
of multigrids and domain decomposition in McCormick [1989], [1992], Bramble
[1993], Sha˘ıdurov [1995], Smith et al. [1996], Quarteroni and Valli [1999], Briggs
et al. [2000], Toselli and Widlund [2005], and Mathew [2008]. Problems in potential
theory and elasticity are often approached via boundary element methods, for which
representative texts are Brebbia and Dominguez [1992], Chen and Zhou [1992],
Hall [1994], and Steinbach [2008]. A discussion of conservation laws is given in the
classic monograph by Lax [1973] and more recently in LeVeque [1992], Godlewski
and Raviart [1996], Kr¨oner [1997], and LeVeque [2002]. Spectral methods, i.e.,
expansions in (typically) orthogonal polynomials, applied to a variety of problems,
were pioneered in the monograph by Gottlieb and Orszag [1977] and have received
extensive treatments in more recent texts by Canuto et al. [1988], [2006], [2007],
Fornberg [1996], Guo [1998], Trefethen [2000] (in Matlab), Boyd [2001], Peyret
[2002], Hesthaven et al. [2007], and Kopriva [2009].
Early, but still relevant, texts on the numerical solution of Integral Equations are
Atkinson [1976] and Baker [1977]. More recent treatises are Atkinson [1997] and
Kythe and Puri [2002]. Volterra integral equations are dealt with by Brunner and van
der Houwen [1986] and Brunner [2004], whereas singular integral equations are the
subject of Pr¨ossdorf and Silbermann [1991].
P4 Journals
Here we list the major journals (in alphabetical order) covering the areas of
numerical analysis and mathematical software.
ACM Transactions on Mathematical Software
Applied Numerical Mathematics
BIT Numerical Mathematics
Calcolo
Chinese Journal of Numerical Mathematics and Applications
Computational Mathematics and Mathematical Physics
Computing
IMA Journal on Numerical Analysis
Journal of Computational and Applied Mathematics
Mathematical Modelling and Numerical Analysis
Mathematics of Computation
Numerical Algorithms
Numerische Mathematik
SIAM Journal on Numerical Analysis
SIAM Journal on Scientific Computing
Chapter 1
Machine Arithm


