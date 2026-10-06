xvi
1 Machine Arithmetic and Related Matters . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 1
1.1 Real Numbers, Machine Numbers, and Rounding .. . . . . . . . . . . . . . . . . 2
1.1.1 Real Numbers.. . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 2
1.1.2 Machine Numbers .. . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 3
1.1.3 Rounding . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 5
1.2 Machine Arithmetic . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 7
1.2.1 A Model of Machine Arithmetic . . . . . . . . .. . . . . . . . . . . . . . . . . . . 7
1.2.2 Error Propagation in Arithmetic Operations:
Cancellation Error .. . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 8
1.3 The Condition of a Problem .. . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 11
1.3.1 Condition Numbers . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 13
1.3.2 Examples.. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 16
1.4 The Condition of an Algorithm . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 24
1.5 Computer Solution of a Problem; Overall Error .. . . . . . . . . . . . . . . . . . . 27
1.6 Notes to Chapter 1 .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 28
Exercises and Machine Assignments to Chapter 1 . . . . . .. . . . . . . . . . . . . . . . . . . 31
Exercises .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 31
Machine Assignments .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 39
Selected Solutions to Exercises .. . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 44
Selected Solutions to Machine Assignments. . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 48
2 Approximation and Interpolation .. . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 55
2.1 Least Squares Approximation .. . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 59
2.1.1 Inner Products . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 59
2.1.2 The Normal Equations . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 61
xiii
xiv Contents
2.1.3 Least Squares Error; Convergence.. . . . . . .. . . . . . . . . . . . . . . . . . . 64
2.1.4 Examples of Orthogonal Systems . . . . . . . .. . . . . . . . . . . . . . . . . . . 67
2.2 Polynomial Interpolation .. . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 73
2.2.1 Lagrange Interpolation Formula: Interpolation Operator .. . 74
2.2.2 Interpolation Error.. . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 77
2.2.3 Convergence . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 81
2.2.4 Chebyshev Polynomials and Nodes . . . . . .. . . . . . . . . . . . . . . . . . . 86
2.2.5 Barycentric Formula . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 91
2.2.6 Newton’s Formula .. . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 93
2.2.7 Hermite Interpolation . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 97
2.2.8 Inverse Interpolation . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 100
2.3 Approximation and Interpolation by Spline Functions . . . . . . . . . . . . . 101
2.3.1 Interpolation by Piecewise Linear Functions . . . . . . . . . . . . . . . 102
2.3.2 A Basis for S0
1.ĩ/ . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 104
2.3.3 Least Squares Approximation . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 106
2.3.4 Interpolation by Cubic Splines . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 107
2.3.5 Minimality Properties of Cubic Spline Interpolants . . . . . . . . 110
2.4 Notes to Chapter 2 .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 112
Exercises and Machine Assignments to Chapter 2 . . . . . .. . . . . . . . . . . . . . . . . . . 118
Exercises .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 118
Machine Assignments .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 134
Selected Solutions to Exercises .. . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 138
Selected Solutions to Machine Assignments. . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 150
3 Numerical Differentiation and Integration . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 159
3.1 Numerical Differentiation .. . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 159
3.1.1 A General Differentiation Formula for Unequally
Spaced Points . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 159
3.1.2 Examples.. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 161
3.1.3 Numerical Differentiation with Perturbed Data .. . . . . . . . . . . . 163
3.2 Numerical Integration . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 165
3.2.1 The Composite Trapezoidal and Simpson’s Rules . . . . . . . . . . 165
3.2.2 (Weighted) Newton–Cotes and Gauss Formulae.. . . . . . . . . . . 169
3.2.3 Properties of Gaussian Quadrature Rules . . . . . . . . . . . . . . . . . . . 175
3.2.4 Some Applications of the Gauss Quadrature Rule .. . . . . . . . . 178
3.2.5 Approximation of Linear Functionals: Method
of Interpolation vs. Method of Undetermined
Coefficients . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 182
3.2.6 Peano Representation of Linear Functionals .. . . . . . . . . . . . . . . 187
3.2.7 Extrapolation Methods . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 190
3.3 Notes to Chapter 3 .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 195
Exercises and Machine Assignments to Chapter 3 . . . . . .. . . . . . . . . . . . . . . . . . . 200
Exercises .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 200
Machine Assignments .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 214
Selected Solutions to Exercises .. . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 219
Selected Solutions to Machine Assignments. . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 232
Contents xv
4 Nonlinear Equations . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 253
4.1 Examples .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 254
4.1.1 A Transcendental Equation . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 254
4.1.2 A Two-Point Boundary Value Problem . .. . . . . . . . . . . . . . . . . . . 254
4.1.3 A Nonlinear Integral Equation .. . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 256
4.1.4 s-Orthogonal Polynomials . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 257
4.2 Iteration, Convergence, and Efficiency . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 258
4.3 The Methods of Bisection and Sturm Sequences . . . . . . . . . . . . . . . . . . . 261
4.3.1 Bisection Method .. . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 261
4.3.2 Method of Sturm Sequences . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 264
4.4 Method of False Position . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 266
4.5 Secant Method . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 269
4.6 Newton’s Method .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 274
4.7 Fixed Point Iteration .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 278
4.8 Algebraic Equations . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 280
4.8.1 Newton’s Method Applied to an Algebraic Equation . . . . . . 280
4.8.2 An Accelerated Newton Method for Equations
with Real Roots. . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 282
4.9 Systems of Nonlinear Equations . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 284
4.9.1 Contraction Mapping Principle . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 284
4.9.2 Newton’s Method for Systems of Equations .. . . . . . . . . . . . . . . 285
4.10 Notes to Chapter 4 .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 287
Exercises and Machine Assignments to Chapter 4 . . . . . .. . . . . . . . . . . . . . . . . . . 292
Exercises .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 292
Machine Assignments .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 302
Selected Solutions to Exercises .. . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 306
Selected Solutions to Machine Assignments. . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 318
5 Initial Value Problems for ODEs: One-Step Methods . . . . . . . . . . . . . . . . . . 325
5.1 Examples .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 326
5.2 Types of Differential Equations .. . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 328
5.3 Existence and Uniqueness .. . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 331
5.4 Numerical Methods .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 332
5.5 Local Description of One-Step Methods . . . . . . . . .. . . . . . . . . . . . . . . . . . . 333
5.6 Examples of One-Step Methods . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 335
5.6.1 Euler’s Method . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 335
5.6.2 Method of Taylor Expansion.. . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 336
5.6.3 Improved Euler Methods .. . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 337
5.6.4 Second-Order Two-Stage Methods .. . . . . .. . . . . . . . . . . . . . . . . . . 339
5.6.5 Runge–Kutta Methods . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 341
5.7 Global Description of One-Step Methods . . . . . . . .. . . . . . . . . . . . . . . . . . . 343
5.7.1 Stability . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 344
5.7.2 Convergence . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 347
5.7.3 Asymptotics of Global Error .. . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 348
xvi Contents
5.8 Error Monitoring and Step Control . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 352
5.8.1 Estimation of Global Error .. . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 352
5.8.2 Truncation Error Estimates . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 354
5.8.3 Step Control . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 357
5.9 Stiff Problems .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 360
5.9.1 A-Stability . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 361
5.9.2 Pad´e Approximation . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 362
5.9.3 Examples of A-Stable One-Step Methods . . . . . . . . . . . . . . . . . . 367
5.9.4 Regions of Absolute Stability . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 370
5.10 Notes to Chapter 5 .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 371
Exercises and Machine Assignments to Chapter 5 . . . . . .. . . . . . . . . . . . . . . . . . . 378
Exercises .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 378
Machine Assignments .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 383
Selected Solutions to Exercises .. . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 387
Selected Solutions to Machine Assignments. . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 392
6 Initial Value Problems for ODEs: Multistep Methods .. . . . . . . . . . . . . . . . . 399
6.1 Local Description of Multistep Methods . . . . . . . . .. . . . . . . . . . . . . . . . . . . 399
6.1.1 Explicit and Implicit Methods . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 399
6.1.2 Local Accuracy .. . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 401
6.1.3 Polynomial Degree vs. Order . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 405
6.2 Examples of Multistep Methods . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 408
6.2.1 Adams–Bashforth Method . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 409
6.2.2 Adams–Moulton Method . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 412
6.2.3 Predictor–Corrector Methods .. . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 413
6.3 Global Description of Multistep Methods .. . . . . . .. . . . . . . . . . . . . . . . . . . 416
6.3.1 Linear Difference Equations . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 416
6.3.2 Stability and Root Condition . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 420
6.3.3 Convergence . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 424
6.3.4 Asymptotics of Global Error .. . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 426
6.3.5 Estimation of Global Error .. . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 430
6.4 Analytic Theory of Order and Stability. . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 433
6.4.1 Analytic Characterization of Order .. . . . . .. . . . . . . . . . . . . . . . . . . 433
6.4.2 Stable Methods of Maximum Order .. . . . .. . . . . . . . . . . . . . . . . . . 441
6.4.3 Applications . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 446
6.5 Stiff Problems .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 450
6.5.1 A-Stability . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 450
6.5.2 A.˛/-Stability . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 452
6.6 Notes to Chapter 6 .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 453
Exercises and Machine Assignments to Chapter 6 . . . . . .. . . . . . . . . . . . . . . . . . . 456
Exercises .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 456
Machine Assignments .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 459
Selected Solutions to Exercises .. . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 461
Selected Solutions to Machine Assignments. . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 466
Contents xvii
7 Two-Point Boundary Value Problems for ODEs . . . . .. . . . . . . . . . . . . . . . . . . 471
7.1 Existence and Uniqueness .. . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 474
7.1.1 Examples.. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 474
7.1.2 A Scalar Boundary Value Problem . . . . . . .. . . . . . . . . . . . . . . . . . . 476
7.1.3 General Linear and Nonlinear Systems . .. . . . . . . . . . . . . . . . . . . 481
7.2 Initial Value Techniques .. . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 482
7.2.1 Shooting Method for a Scalar Boundary Value Problem . . . 483
7.2.2 Linear and Nonlinear Systems . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 485
7.2.3 Parallel Shooting . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 490
7.3 Finite Difference Methods . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 494
7.3.1 Linear Second-Order Equations . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 494
7.3.2 Nonlinear Second-Order Equations . . . . . .. . . . . . . . . . . . . . . . . . . 500
7.4 Variational Methods . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 503
7.4.1 Variational Formulation .. . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 503
7.4.2 The Extremal Problem . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 506
7.4.3 Approximate Solution of the Extremal Problem .. . . . . . . . . . . 507
7.5 Notes to Chapter 7 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 509
Exercises and Machine Assignments to Chapter 7 . . . . . .. . . . . . . . . . . . . . . . . . . 512
Exercises .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 512
Machine Assignments .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 518
Selected Solutions to Exercises .. . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 521
Selected Solutions to Machine Assignments. . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 532
References .. .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 543
Index . . . . . . . . .. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .. . . . . . . . . . . . . . . . . . . 57


