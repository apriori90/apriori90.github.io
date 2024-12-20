---
title: Computational Scientific Interpretation of Wittgenstein's Tractatus Logico-Philosophicus and his 'Ladder'
---

Ludwig Josef Johann Wittgenstein (1889~1951) was an Austrian Philosopher, often known for his huge contribution to the philosophy of logic, language and mathematics. His magnum opus, Tractatus Logico-Philosophicus penetrates one of the well-known, tricky philosophical questions. How should we handle the highest, the most abstract axioms of our linguistic system? Is it achievable to find a true meaning of any substance in our language?
Linguistic determinism

Regardless of how human consciousness is created, it is clear that our language almost dominates our way of thinking. When we think of anything, we easily fall into the trap of assumption, thinking that our mind generates a vague object (often imagined as a graphical object), and it is verbalized later. However, is that really so?

The idea of linguistic determinism is well pictured in the Sapir–Whorf hypothesis, asserting that one's culture and environment can influence the linguistic system and vocabulary. While this hypothesis is not actively accepted in academia, it's not because of the existence of empirical knowledge disproving the theory. It's merely because we have no formal method to completely prove this theory. Wittgenstein made a decent contribution to this field with his private language argument and language-game concept. Note that some of his work on this field (his later philosophy) is partially negating his work on TLP (his early philosophy).
Limit of our Language

There should be only two types of statements: primary statements and compound statements. The primary statement is considered as /atom/, and this concept projects its shadow on programming languages such as Scheme. Atom is something the Scheme interpreter should not evaluate anymore, because it is merely a value, proving its valid existence by itself. (logic and philosophy is required if you want to learn how to program instead of learning a domain-specific language.)

This metaphor describes the identity of the primary/compound statement in Wittgenstein's Tractatus very well. While a primary statement is a non-evaluative argument, a compound statement can be considered as a function which takes one or more primary statement (s), and returns the boolean result of it. The result tells us if the statement is in the facts or not.

This shows us an intriguing paradox. According to the definition of compound statements and atomic statements, we can divide everything in this world into those two categories. This implies that to properly construct to structure of definitive statements, we have to define which statement is compound and which is atomic, non-evaluatable. However, we need the structure of definitive statements to define what is atomic. This is a paradox.

In LISP, simply putting an apostrophe (') preceding will give the sign of epoché to the interpreter program. This is plausible only because the interpreter itself is also built with another programming language. (Here is a good question to think about: What if we try to build the interpreter with that of its language? How can projects like PyPy, building Python interpreter with Python, can exist?)

This was a significant problem found in Gottlob Frege's project, Begriffsschrift ("concept-language"). Nonetheless, its endeavour and experience turned into an important tool to investigate the limit of our language and make clear of what we can actually know. Long way around, this gave birth to the idea of abstract computational machine, by Alan Turing who also attended to Wittgenstein’s lectures on the foundations of mathematics, but couldn’t fully agree with it.
Logical Space of Programming

> §1. The world is everything that is the case.
>
> §2. What is the case, a fact, is the obtaining of states-of-things.
>
> §3. A logical picture of facts is a thought.

This can correspond to the primitive concept of an executable program and its source code. People often say that "everything is possible in the world of software." We cannot launch a rocket to the moon ONLY with software. However, we can imagine and define one's customized state-of-affair in our source code. Therefore, source code is a set of compound statements, waiting to get evaluated and tell us if the result is in our set of facts or not. This corresponds to §2: "What is the case, a fact, is the obtaining of states-of-things." This is a primitive concept for every evaluatable computer programming languages.
Wittgenstein's Ladder

The §6.54 has been a controversial statement since the publication of TLP.

> §6.54 My propositions elucidate when someone who understands me finally recognizes them as nonsensical by using them to climb up, over, and out of them. (They must throw away the ladder, so to speak, having used it to climb up.)
> They must get over these propositions, and then they see the world correctly.

This gives us the impression that everything he's been talking about was merely a nonsensical idea. There are various interpretations about §6.54, and this paradoxical phrase, namely "Wittgenstein's Ladder", suggests reader to throw away the ladder of logic he used to guide us to the destination, §7.
Programming by Demonstration and the Purity of Computational Action

In the Theoretical Computer Science, this Ladder may correspond to the action of the program. We picture facts with a programming language, full of statements. However, the action itself is not a source code, nor a compiled binary. The action is just an action, and its existence can only proved by demonstrating itself. Here, we can bring in the concept of Programming by Example (PbE, also known as Programming by Demonstration). In PbE, unlike traditional programming, the computer simply "records" the user's action demonstration and repeats it.

While this term is known as the so-called "end user development technique", we often overlook the fact that every programming is, in fact, PbE. It's only a matter of who performs the pattern finding; the programmer, or the program. Even if the computer itself records the user action, it will be recorded as the user's cursor coordinate and keyboard input deviation. That data is not the action itself, but it might create a similar action in the future.

If then, we can assume that, what Wittgenstein tried to do was to show us the logical action in the form of PbE. TLP created a whole new approach to the traditional logic and philosophy, but that is just a result it created. The importance of TLP is that it provides us the way to make a whole new logical work like Wittgenstein himself as well while producing the conclusion which helps us realize the limit of such a method.

Henceforth, Source code (which is our language): Logic. Demonstration of PbE: The action of Logical Reasoning (which is the fact, also the ladder). Compiled Result (which is the case): The limit of our language.

*Written by: HS Choi*
