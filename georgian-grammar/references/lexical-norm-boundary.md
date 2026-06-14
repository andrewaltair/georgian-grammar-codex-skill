# Lexical Norm Boundary

Use this file when a Georgian question cannot be decided by a productive grammar rule alone.

## Core Principle

Georgian grammar rules are finite, but concrete standard forms are not always derivable from the rules alone. Some decisions require knowing the lexical paradigm, fixed expression, or accepted normative form.

Do not guess those decisions from surface naturalness.

## Rule-Decidable Cases

Decide locally when the question is governed by a productive rule:

- `თქვენ` agreement
- numeral plus noun behavior
- case and postposition governance
- possessive pronoun form before dative or adverbial nouns
- coordinate compound hyphenation
- cause versus purpose conjunction choice
- punctuation tied to syntax

## Lexical-Norm Cases

Use a normative source when the question asks about a concrete form whose correctness depends on a specific paradigm or lexicalized norm:

- whether a particular verb uses one present stem or another
- whether an apparent `-ობ` verb is a standard paradigm form or an analogy
- whether a concrete verb form needs a specific stem, theme sign, perfect form, participle, or screeve-specific paradigm; use `verb-paradigm-boundary.md` before finalizing
- whether a frequent expression is lexicalized as one word or remains a phrase
- whether a transparent-looking compound is actually an accepted joined word rather than a hyphenated coordinate form
- whether a fixed adverbial expression is written joined, separately, or with a hyphen
- whether an `-ა`-final noun follows the expected productive declension pattern or keeps a lexicalized case form
- whether a borrowed adjective or adverb uses an apparently regular suffix or a stricter accepted literary form
- whether two near-synonymous forms differ by literary, colloquial, archaic, or dialectal status
- whether the meaning of a word is unclear and that meaning affects the grammatical or stylistic decision

## Working Behavior

For explicit correctness questions, verify lexical-norm cases before giving a final answer. For drafting and document editing, prefer a clearer construction when a concrete lexical form is uncertain.

External lookup is not the first step; it is the final step after rule analysis shows that a lexical norm is required.

## External Lexical Lookup

Use external dictionary lookup lazily. Do not query dictionaries during routine drafting, translation, punctuation, or grammar checks when the local rules and ordinary Georgian knowledge are enough.

Escalate to an external lexical source only when all are true:

1. The decision depends on a concrete word meaning, lexicalized expression, paradigm, register, or accepted dictionary form.
2. The local rule files do not settle it.
3. Guessing would change the answer, correction, or explanation.

For Georgian word meanings and definitions, prefer the National Parliamentary Library of Georgia dictionaries:

- Main dictionary portal: `http://www.nplg.gov.ge/gwdict/index.php`
- Exact term pages use `a=term`, `d=<dictionary-id>`, and `t=<term-id>`.
- The universal encyclopedic dictionary uses `d=14`; term pages expose the headword in `h1.term`, the definition in `div.defn`, and source metadata in `div.gwsrc`.

Lookup discipline:

- Query the exact lemma or likely dictionary form first, not a whole sentence.
- Limit to the smallest useful number of lookups, usually one or two terms.
- Treat NPLG definitions as semantic evidence, not automatic proof of grammatical correctness.
- Prefer grammar references for morphology, agreement, case, punctuation, and syntax.
- Cite the dictionary page when an external definition materially affects the answer.
- If the site is unavailable, say the lexical check could not be completed and answer from local rules with uncertainty.

## Strict Test Norms

For school-style multiple-choice questions, judge options by strict standard-literary/test norm, not by corpus frequency, legal usage, or a single source that lists a parallel-looking variant.

- Analyze all answer choices before selecting one.
- Treat apparent near-synonyms, participle variants, and professional/register variants as lexical-norm cases until their derivation and strict literary status are checked.
- For participles and result-state adjectives, identify the base verb, preverb, voice/version pattern, and expected participial suffix before accepting a surface-plausible form.
- If one option is a regular productive form and another is a usage-driven, register-bound, or analogical variant, prefer the strict standard-literary form for school-style tests.
- If a dictionary or corpus source conflicts with the school-test norm, explain the conflict briefly and answer according to the requested test norm.
- Do not add item-specific words, answer keys, or trap lists to this skill. Use rule categories and source-priority reasoning instead.

## Lexical Boundary Triggers

Escalate from productive rules to lexical-norm reasoning when any of these appear:

- joined/separate/hyphenated variants all look plausible from ordinary compound rules
- the form is a poetic, fixed, or school-norm compound rather than a live phrase
- the noun's case form cannot be derived safely from the visible ending alone
- two adverbs differ only by suffix shape and both sound derivable by analogy
- a stylistic item turns on the exact semantic scope of a near synonym
