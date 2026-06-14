# Maintenance Regression Prompts

Use this file only while maintaining or forward-testing the skill. Do not load it during ordinary Georgian writing or grammar answering.

The goal is to test routing and reasoning, not to create an answer database. When a prompt fails, improve the general rule or boundary file rather than adding the prompt as a memorized exception.

## Morphology Prompts

1. Choose the standard form and explain the grammatical layer: `სვამ` vs `სვავ`.
2. Judge whether the form is rule-decidable or paradigm-dependent: `დაუხატავს` vs `დაუხატია`.
3. Explain why `თქვენ შეგიძლია` is wrong in formal address.
4. Decide whether a candidate `-ობ` verb is productive or needs paradigm verification.
5. Check a form where `ვ-` may be subject marker versus part of the stem.
6. Convert a direct witnessed past sentence into a reported/inferred `თურმე` sentence.
7. Choose between a simple active form and a causative `-ინ-/-ევინ-` form.
8. Decide whether `მიაქვს` or `მიჰყავს` is required from the moved object.
9. Check a passive/active pair where the active object becomes passive subject.
10. Judge a participle-looking form and decide whether lexical verification is needed.

## Syntax Prompts

1. Rewrite an English-calque sentence into natural Georgian with the same meaning.
2. Identify the main clause and subordinate clause in a sentence with two finite predicates.
3. Choose between `რადგან` and `რათა`.
4. Choose between real and unreal conditional forms.
5. Decide whether `ოღონდ` is valid as a request/bargain condition.
6. Choose `რომელიც`, `რომელმაც`, or `რომელსაც` from the relative clause role.
7. Choose `ვინც` or `რაც`.
8. Convert direct speech to indirect speech while preserving person perspective.
9. Choose `-მეთქი`, `-თქო`, or `-ო`.
10. Repunctuate a sentence with an inserted phrase and a subordinate clause.

## Adverb Prompts

1. Classify `სადაც`, `სადღაც`, and `არსად` by function.
2. Decide whether an adverbial meaning should be expressed by an adverb, postpositional phrase, or subordinate clause.
3. Check a sentence with `არასდროს` and decide whether the finite negator should remain.
4. Distinguish cause adverbs such as `ამიტომ` from causal clauses with `რადგან`.
5. Decide whether an adverb-looking expression is lexicalized or still a transparent phrase.

## Orthography And Punctuation Prompts

1. Decide whether an expression is joined, separate, or hyphenated.
2. Choose between hyphen and dash.
3. Choose colon or dash around a generalizing word and an enumeration.
4. Check spacing around Georgian punctuation marks.
5. Decide whether a frequent expression is lexicalized or remains a transparent phrase.

## Pass Criteria

A maintenance pass is acceptable when the agent:

- routes to the correct reference layer
- distinguishes rule-decidable from paradigm-dependent cases
- avoids answer-list behavior
- gives short answers for short user prompts
- states uncertainty when a concrete paradigm is not locally settled
- keeps `SKILL.md` lean and does not move deep material into the hot path
