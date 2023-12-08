## On Braid Groups and Link Invariants

My thesis explores the connection between knots and braids. Knot theory and theory of braid groups are two representative topics of low-dimensional topology.

Knot theory is the study of mathematical knots which are closed, non-self-intersecting curves that are embedded in three dimensions. Loosely speaking, two knots are said to be isotopic (equivalent) if one can be continuously deformed into the other (cutting and rejoining are not allowed). A knot invariant is a function that gives the same output for any two isotopic knots and as such it can distinguish a knot from another. Classification of knots is one of the most important goals of knot theory. This means that knot invariants form an important study in knot theory.

\begin{figure}[h]
  \centering
  \includegraphics[scale=.2]{images/demo.png}
  \caption{A knot, a link, a braid, closure of the braid}
\end{figure}

Braid theory is the study of braids. An $n$-braid is an intertwining of $n$ strings attached to top and bottom bars such that each string never turns back up (just like hair braids). Loosely speaking, two $n$-braids are said to be isotopic (equivalent) if one can be continuously deformed into the other. Interestingly, $n$-braids form a group under the operation of concatenation. The Artin braid group $B_n$ is the group of all equivalent classes of $n$-braids under concatenation (equivalence provided by isotopy). The act of connecting two corresponding ends of a braid in a parallel fashion is called closing the braid. The closure of a braid always yields a knot or a link (disjoint union of knots).

Alexander's theorem was the first major result toward providing the connection between knot theory and braid theory. It states that any knot or link can be realised as the closure of a braid. This, however, does not say anything about the uniqueness of the braid. Markov's theorem, which came two decades later, gives moves relating any two closed braid representatives of a knot or link, while simultaneously preserving the closed braid structure. Thus, Alexander's theorem and Markov's theorem form the cornerstone of any study of knots via closed braids. A representation of a group is a homomorphism from the group to some other group, most often the general linear group. Using Markov's theorem, we can construct knot or link invariants from representations of braid groups. 

My thesis begins by giving Yamada-Vogel's algorithmic proof of Alexander's theorem. This proof is superior to Alexander's original proof in that it can easily be implemented in a computer program to turn knots to braids and also has a beautiful corollary. Then I provide a proof of Markov's theorem (the proof is due to P. Traczyk). Then I study construction of two invariants from representation of braid groups, viz., the Alexander-Conway polynomial from the Burau representation and the Jones polynomial from the Temperley-Lieb algebra.
