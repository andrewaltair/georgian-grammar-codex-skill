# Normative Decision Protocol

Use this as the first rule-first thinking path for Georgian writing, editing, and short grammar questions. The goal is to derive the answer from grammar and orthography rules before falling back to memory, examples, or outside lookup.

## Fast Route

1. Classify the issue before answering:
   - verb form or verb agreement
   - compound, joined, separate, or hyphenated writing
   - particle, fixed expression, conjunction, or prohibition
   - adverb, adverbial meaning, question/relative/indefinite/negative adverb
   - case, postposition, possessive form, or direction form
   - subject-predicate, numeral, or polite `თქვენ` agreement
   - punctuation, spacing, register, or naturalness
2. Load only the matching rule file:
   - verbs: `verb-morphology.md`
   - complex morphology: `morphology-deep-dive.md`
   - concrete verb paradigms: `verb-paradigm-boundary.md`
   - compounds and spacing: `compound-writing-rules.md`
   - particles and fixed expressions: `particle-expression-rules.md`
   - adverbs and adverbial relation: `adverb-rules.md`
   - complex syntax: `syntax-deep-dive.md`
   - cases and postpositions: `case-and-postposition-rules.md`
   - agreement: `agreement-rules.md`
   - lexical standardness boundary: `lexical-norm-boundary.md`
   - stylistic and lexical choice: `style-and-lexical-choice.md`
   - punctuation and address: `polite-forms-and-punctuation.md`
3. Apply the rule and choose the standard contemporary literary form.
4. If the quick rule exposes a deeper morphology, syntax, or concrete-paradigm issue, load the matching deep reference instead of guessing.
5. Answer briefly unless the user asks for explanation.

## Writing Mode

For normal drafting or document editing, do not stop the prose with uncertainty notes. Choose the safest standard construction that follows the rules. If a risky form is avoidable, rewrite the sentence with a clearer rule-backed construction.

Examples are allowed only to illustrate a rule. Do not use examples as a word-answer database.

## Short QA Mode

For prompts like "which is correct?", "does this need a hyphen?", "is this grammatical?", or any other form-judgment task:

1. Identify the grammatical category.
2. Use the relevant rule file.
3. If two forms differ by register, prefer the strict standard literary form unless the user asks for colloquial Georgian.
4. If the decision depends on a concrete lexical paradigm or fixed lexicalized form, read `lexical-norm-boundary.md`; if the local rules do not determine the form, verify externally before finalizing.
5. If a verb form depends on a concrete stem, theme sign, participle, or screeve-specific paradigm, read `verb-paradigm-boundary.md`.
6. If local rules are insufficient, use an outside normative source only after the rule analysis fails or when the user explicitly asks for verification.

## Multiple-Choice Mode

For prompts like "which sentence has no error?", "which form is correct?", or "choose the wrong sentence", solve by elimination before answering:

1. Inspect every option, even if one option already sounds correct.
2. For each option, identify the layer: morphology, lexical norm, lexicalized form, syntax, agreement, punctuation, spelling, style, or register.
3. For every option judged wrong, state the exact error and the corrected form.
4. For every option judged correct, state why it survives the rule or normative check.
5. If the task asks for one answer but more than one option survives under current normative sources, report the conflict and the source-sensitive answer rather than guessing.
6. Only then give the final letter or form.

## Source Priority

1. Local rule references in this skill.
2. `source-map.md` for source orientation.
3. External normative sources only as a last verification layer, not as the default workflow.
