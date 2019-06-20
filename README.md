# Support-Vector-Machine


In this problem, you are to investigate the bias and variance of the optimal hyperplane in a simple setting. The input is (x1, x2) ∈ [−1, 1]2 and the target function is f(x) = sign(x2).
The hypothesis set H contains horizontal linear separators h(x) = sign(x2 −a), where −1 ≤ a ≤ 1. Consider two algorithms:
Random: Pick a random separator from H.
SVM: Pick the maximum margin separator from H.
(a) Generate 3 data point uniformly in the upper half of the input-space and 3 data points in the lower half, and obtain gRandom and gSVM.
(b) Create a plot of your data, and your two hypotheses.
(c) Repeat part (a) for a million data sets to obtain one million Random and SVM hypotheses.
(d) Give a histogram of the values of aRandom resulting from the random algorithm and another histogram of aSVM resulting from the optimal sep- arators. Compare the two histograms and explain the differences.
(e) Estimate the bias and var for the two algorithms. Explain your findings, in particular which algorithm is better for this toy problem.
