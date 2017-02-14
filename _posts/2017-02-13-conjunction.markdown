---
layout: post
title: "Conjunction"
categories: logic truth-functional-logic
---
Two statements combined by the use of the logical conective "_and_" is another
statement known as a _conjunction_. The constituent elements of a cojunction
are its _conjuncts_.

A conjunction is true when both of its conjuncts are true, and false otherwise.

We will symbolice statements by lowercase latin letters. Also, we will use
\\(\land\\) to symbolice the logical conective "_and_". So, if we let \\(p\\)
denote statement "You have mail" and \\(q\\) denote the statement "I have
to get back to work", then the statement "You have mail and I have to get back
to work" can be symobliced as \\(p \land q\\).

**Theorem**: The logical conective "_and_" is comutative.  
**Proof**: Let \\(p\\) and \\(q\\) be statements. The statement \\(p \land q\\) is true
if and only if \\(p\\) and \\(q\\) are both true. Now, the statement
\\(q \land p\\) is also true if and only if \\(p\\) and \\(q\\) are both true.
Hence, \\(p \land q\\) and \\(q \land p\\) are equivalent statements. \\(\blacksquare\\)

**Theorem**: The logical conective "_and_" is asociative.  
**Proof**: Let \\(p\\), \\(q\\), and \\(r\\) be statements. The statement
\\((p \land q) \land r\\) is true if and only if \\(p \land q\\) and \\(r\\) are both
true. Now, \\(p \land q\\) is true if and only if \\(p\\) and \\(q\\) are both true. Hence,
\\((p \land q) \land r\\) is true if and only if \\(p\\), \\(q\\), and \\(r\\) are all
true. On the other hand, \\(p \land (q \land r)\\) is true if and only if \\(p\\) and
\\(q \land r\\) are both true. Also, \\(q \land r\\) is true if and only if \\(q\\) and
\\(r\\) are both true. Hence, \\(p \land (q \land r)\\) is true if and only if
\\(p\\), \\(q\\), and \\(r\\) are all true. Therefore \\((p \land q) \land r\\) and
\\(p \land (q \land r)\\) are equivalent statements. \\(\blacksquare\\)
