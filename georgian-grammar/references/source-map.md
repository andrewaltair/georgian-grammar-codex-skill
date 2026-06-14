# Source Map

This skill is distilled from Georgian-learning and Georgian-grammar sources. It does not try to reproduce them in full; it pulls forward the rules that matter most for AI-generated Georgian.

## Core Sources

- `შემსწავლელის გრამატიკა`
  - learner-oriented explanations
  - practical treatment of cases, pronouns, numerals, postpositions, and basic verb patterns

- `შემსწავლელის გრამატიკა (ნაწილი II)`
  - learner-oriented expansion of place/time relations, demonstratives, reflexive possession, relative clauses, conditionals, reported speech, negation, and discourse helper words
  - useful controls for `მიაქვს/მიჰყავს`, active/passive, benefactive, causative, `-ავ/-ამ`, and evidential `თურმე` forms

- `Beginner's Georgian` by Dodona Kiziria
  - learner-oriented Georgian grammar source used as a background cross-check for progressive coverage
  - keep as a maintenance source; the provided PDF is image-based in text extraction, so do not make it a runtime dependency

- `Qartuli_Enis_Sintaqsi_1996.pdf`
  - syntax-oriented source used for clause structure, sentence members, dependent relations, and punctuation-by-syntax orientation

- `მოკლე პრაქტიკული კურსი`
  - morphology and syntax in compact form
  - orthography and punctuation coverage
  - polite forms and verb tables

- `ქართული ენის გრამატიკის ზოგადი კურსი`
  - normative backbone for morphology and syntax
  - agreement, case governance, postpositions, verb series, inversion, and clause structure

- `1634974351_Book-Learn Georgian-WEB(4).pdf`
  - exercise-based confirmation of learner pain points
  - especially useful for identifying repeated failure zones: cases, postpositions, verbs, polite forms, conjunctions

## Why These Topics Were Prioritized

Across the sources, the same high-risk areas recur:

1. noun case and case functions
2. postposition governance
3. quantified noun phrases
4. subject-predicate agreement
5. polite `თქვენ` forms
6. verb person marking and third-series inversion
7. version, passive, benefactive, and causative verb patterns
8. conjunction meaning and conditional clauses
9. reflexive possession and relative-pronoun agreement
10. punctuation tied to syntax

The skill therefore focuses on those areas first and keeps the workflow rule-based rather than list-based.

## Rule File Mapping

- Normative morphology and syntax feed `verb-morphology.md`, `agreement-rules.md`, and `case-and-postposition-rules.md`.
- Orthography and punctuation coverage feed `compound-writing-rules.md`, `particle-expression-rules.md`, `normative-orthography.md`, and `polite-forms-and-punctuation.md`.
- Conditional clauses, reported speech, negation, relative linkers, and discourse helper words feed `particle-expression-rules.md`.
- Adverb classification, relative/indefinite/negative adverbs, and adverbial formation feed `adverb-rules.md`.
- Deep morphology routing feeds `morphology-deep-dive.md`; concrete verb paradigm boundaries feed `verb-paradigm-boundary.md`.
- Deep syntax routing feeds `syntax-deep-dive.md`.
- `maintenance-regression-prompts.md` is for maintenance and forward-testing only; do not use it as a normal answer source.
- The boundary between productive rules and concrete lexical norms is handled in `lexical-norm-boundary.md`.
- Learner pain points inform the rule examples, but they should not become a runtime answer database.

The rule files should stay compact and procedural. Add examples only when they clarify a rule.
