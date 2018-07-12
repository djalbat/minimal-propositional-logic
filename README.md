# Minimal Propositional Logic

Minimal propositional logic for the [Occam](http://djalbat.com/occam) proof assistant.

\[
\frac{[P]\;...\;Q}{P\Rightarrow{Q}}\quad\small\text{[ImplicationIntroduction,ConditionalProof]}
\]
\[
\frac{P\Rightarrow{Q}\;\;P}{Q}\quad\small\text{[ModusPonens,ImplicationElimination,RuleOfDetachment]}
\]
&nbsp;
\[
\frac{P\Rightarrow{Q}\;\;P\Rightarrow\neg{Q}}{\neg{P}}\quad\small\text{[NegationIntroduction,ProofByNegation]}
\]
&nbsp;
\[
\frac{P\;\;Q}{P\land{Q}}\quad\small\text{[ConjunctionIntroduction]}
\]
\[
\frac{P\land{Q}}{P}\quad\small\text{[ConjunctionLeftElimination]}
\]
\[
\frac{P\land{Q}}{Q}\quad\small\text{[ConjunctionRightElimination]}
\]
&nbsp;
\[
\frac{P}{P\lor{Q}}\quad\small\text{[DisjunctionLeftIntroduction,LeftAddition]}
\]
\[
\frac{Q}{P\lor{Q}}\quad\small\text{[DisjunctionRightIntroduction,RightAddition]}
\]
\[
\frac{P\Rightarrow{R}\;\;Q\Rightarrow{R}\;\;P\lor{Q}}{R}\quad\small\text{[DisjunctionElimination,ProofByCases]}
\]
&nbsp;
\[
\frac{P\Rightarrow{Q}\;\;Q\Rightarrow{P}}{P\iff{Q}}\quad\small\text{[BiconditionalIntroduction]}
\]
\[
\frac{P\iff{Q}}{P\Rightarrow{Q}}\quad\small\text{[BiconditionalLeftElimination]}
\]
\[
\frac{P\iff{Q}}{Q\Rightarrow{P}}\quad\small\text{[BiconditionalRightElimination]}
\]

## Resources

* [Natural Deduction (The Internet Encyclopedia of Philosphy)](http://www.iep.utm.edu/nat-ded/#H4)

## Contact

* jecs@imperial.ac.uk
* http://djalbat.com
