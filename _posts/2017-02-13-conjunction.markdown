---
layout: post
title: "Conjunction"
categories: logic truth-functional-logic
---
Two statements combined by the use of the logical connective "_and_" is another
statement known as a _conjunction_. The constituent elements of a conjunction
are its _conjuncts_.

A conjunction is true when both of its conjuncts are true, and false otherwise.

We will symbolize statements by lowercase latin letters. Also, we will use
\\(\land\\) to symbolize the logical connective "_and_". So, if we let \\(p\\)
denote statement "You have mail" and \\(q\\) denote the statement "I have
to get back to work", then the statement "You have mail and I have to get back
to work" can be symbolized as \\(p \land q\\).

**Theorem**: The logical connective \\(\land\\) is commutative.  
**Proof**: Let \\(p\\) and \\(q\\) be statements. The statement \\(p \land q\\) is true
if and only if \\(p\\) and \\(q\\) are both true. Now, the statement
\\(q \land p\\) is also true if and only if \\(p\\) and \\(q\\) are both true.
Hence, \\(p \land q\\) and \\(q \land p\\) are equivalent statements. \\(\blacksquare\\)

**Theorem**: The logical connective \\(\land\\) is associative.  
**Proof**: Let \\(p\\), \\(q\\), and \\(r\\) be statements. The statement
\\((p \land q) \land r\\) is true if and only if \\(p \land q\\) and \\(r\\) are both
true. Now, \\(p \land q\\) is true if and only if \\(p\\) and \\(q\\) are both true. Hence,
\\((p \land q) \land r\\) is true if and only if \\(p\\), \\(q\\), and \\(r\\) are all
true. On the other hand, \\(p \land (q \land r)\\) is true if and only if \\(p\\) and
\\(q \land r\\) are both true. Also, \\(q \land r\\) is true if and only if \\(q\\) and
\\(r\\) are both true. Hence, \\(p \land (q \land r)\\) is true if and only if
\\(p\\), \\(q\\), and \\(r\\) are all true. Therefore \\((p \land q) \land r\\) and
\\(p \land (q \land r)\\) are equivalent statements. \\(\blacksquare\\)

When analyzing an english statement as a conjunction care must be taken with pronouns. We
must understand to whom the pronoun is referring. For example, the english statement
"Han Solo flies with Chewbacca and carries his food" can be analyzed as a conjunction in
two different ways:

- Han Solo flies with Chewbacca \\(\land\\) Han Solo carries his food.
- Han Solo flies with Chewbacca \\(\land\\) Han Solo carries Chewbacca's food.

Another issue when analyzing english sentences as conjunctions is that the word "and" don't
expresses conjunction in all cases.

The word "and" in english can be used to express succession in time,
as in the sentence "I entered the room and shouted". If we analyse this sentence as
"I entered the room \\(\land\\) I shouted", then we must also accept as a valid analysis
the statement "I shouted \\(\land\\) I entered the room" since the logical connective
\\(\land\\) is commutative. But this last sentence doesn't have the same meaning as the
original.

Another use of the word "and" in english is to express a collective subject. When the
statement "Mary and Joe went to the movies" is analyzed as
"Mary went to the movies \\(\land\\) Joe went to the movies" part of the meaning of the
original statement is lost since it intended to convey that they went to the movies
together, not just that each of them went to the movies.

The following are the inference rules for conjunction.

Simplification, in two forms:

\\[
  \frac{
    \begin{array}{@{}c@{}}
      \phi \land \psi
    \end{array}
   }{
    \phi
   }
\\]

\\[
  \frac{
    \begin{array}{@{}c@{}}
      \phi \land \psi
    \end{array}
   }{
    \psi
   }
\\]

The rule of simplification says that whenever we know that a conjunction is
true we can infer either of its conjuncts.

Adjunction:

\\[
  \frac{
    \begin{array}{@{}c@{}}
      \phi \newline
      \psi
    \end{array}
   }{
    \phi \land \psi
   }
\\]

The rule of adjunction says that whenever we know that two statements are
true we can infer their conjunction.
