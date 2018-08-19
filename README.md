Double Negation Translations.
=============================

## What is this ?

In proof theory, a double-negation translation is a way of embedding
a formula known from classical logic into intuitionistic logic
(first order logic without the double-negation-elimination rule,
and all rules that follow from it (including proof-by-contradiction)).

It was proposed by the soviet mathematician Kolmogorov, that any proof of a
formula ϕ in Peano's arithmetic system (classical logic), could be embedded
as a proof of the double negated formula ¬(¬ϕ) in Heyting's arithmetic system
(intuitionistic logic).

In this project we formalize the two arithmetic systems, the translation,
and prove that it is sound and complete in Twelf.