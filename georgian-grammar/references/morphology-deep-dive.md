# Morphology Deep Dive

Use this file only when the quick morphology route is not enough: difficult verb forms, voice/version choice, causatives, participles, verbal nouns, third-series inversion, or a form that may depend on a concrete lexical paradigm. For ordinary checks, use `verb-morphology.md`, `agreement-rules.md`, and `case-and-postposition-rules.md` first.

This file is a decision guide, not a conjugation database. If the final choice depends on one verb's accepted paradigm, route to `verb-paradigm-boundary.md`.

## Contents

1. Morphology Triage
2. Verb Form Algorithm
3. Series And Argument Frame
4. Person And Object Marking
5. Version, Voice, Benefactive
6. Causative And Assisted Action
7. Theme Signs And Stem Choice
8. Participles And Verbal Nouns
9. Nominal Morphology Checks
10. Final Standardness Decision

## Morphology Triage

Classify the question before choosing a form:

- noun, pronoun, adjective, numeral, or postposition form
- finite verb form
- participle, verbal noun, or result-state adjective
- agreement between a form and its sentence role
- lexical paradigm question that cannot be derived locally

If the issue is a concrete word's accepted stem, theme sign, or participial form, do not force an answer from analogy. Use the boundary file.

## Verb Form Algorithm

For a difficult verb, work in this order:

1. Identify the intended meaning and participants: actor, affected object, indirect object, beneficiary, possessor, instrument, and destination.
2. Decide whether the verb is active, passive, reflexive/self-benefactive, other-benefactive, causative, medial, or indirect-object-taking.
3. Identify the target series or function: present/future group, aorist/completed event, perfect/result/evidential, subjunctive/optative, imperative/prohibition.
4. Split the surface form where possible: preverb, person marker, object marker, version vowel, root, stem alternant, theme sign, causative marker, ending, plural marker.
5. Check which participant controls agreement in that series. Third-series transitive forms often invert the expected subject/object marking.
6. If the stem or theme sign is uncertain after the grammatical analysis, stop and route to `verb-paradigm-boundary.md`.

Never choose a form only because it sounds like another verb. Georgian verb classes are productive, but concrete verbs still keep lexical paradigms.

## Series And Argument Frame

The same verb can change case and agreement behavior across series. Before correcting a sentence, identify the series:

- Present/future-group forms often keep the ordinary subject/object frame visible.
- Aorist/completed-event forms can shift transitive subjects into ergative-style marking.
- Perfect and evidential/result forms can invert logical subject and grammatical marking.
- Optative/subjunctive and prohibitive forms must be checked as their own forms, not as automatic copies of aorist stems.

Do not decide from English tense labels. Ask what the Georgian form is doing in the sentence.

## Person And Object Marking

Check both subject and object markers:

- `ვ-` can mark first-person subject; `მ-` and `გვ-` often mark first-person object or affected participant.
- `გ-` often marks second-person object or affected participant.
- `-თ` can mark second-person plural/polite or plural agreement where the paradigm requires it.
- Objective markers can be inside the verb complex; do not move them before lexical prefixes by surface analogy.
- In formal address, keep `თქვენ` with plural verb morphology even for one person.

If two forms differ only by person marker placement, split the verb before judging.

## Version, Voice, Benefactive

Version vowels and voice markers must follow participant roles, not English wording:

- `ი-` can mark reflexive/self-benefactive or passive-like patterns, but it is not a universal passive marker.
- `ე-` can mark passive or object-oriented relations in some paradigms.
- `უ-` often marks action done for another participant or toward an indirect object.
- Zero or `ა-` forms can be neutral or active depending on the verb class.

For "for someone" constructions, identify whether the action is merely about someone, done for someone, or transferred to someone. Then choose the version pattern. If the concrete verb's version pattern is not locally known, route to the boundary file.

## Causative And Assisted Action

Use causative analysis when one participant causes, has, helps, or makes another participant do the action.

- Look for `-ინ-` or `-ევინ-` type causative patterns.
- Identify both the causer and the immediate doer.
- Do not replace causative forms with the simple active verb when the caused/assisted participant matters.
- If English has "make", "have", "let", or "help", do not translate mechanically; first decide the Georgian participant structure.

For correctness tasks, reject forms that lose the caused participant or place the object marker in the wrong relation.

## Theme Signs And Stem Choice

Theme signs are not interchangeable:

- `-ებ`, `-ობ`, `-ავ`, `-ამ`, `-ი`, `-ემ`, and rarer theme signs belong to verb classes.
- `-ობ` is not a universal way to form a present tense from a noun.
- `-ავ` and `-ამ` choices often require the concrete verb paradigm.
- Stem alternation across series can be regular within a class but cannot always be derived from the present form.

Use class rules when they clearly apply. Otherwise treat theme-sign choice as a lexical-paradigm issue.

## Participles And Verbal Nouns

For participles, result-state adjectives, and verbal nouns:

1. Identify the base verb and whether a preverb is part of the lexical form.
2. Identify the voice/version pattern before selecting the suffix.
3. Check whether the form describes an actor, an object/result, a possibility, or an action/event.
4. Do not accept a surface-plausible participle if it is only copied from a nearby adjective pattern.

If two participial forms are both possible-looking, route to lexical/paradigm verification unless the local rule clearly distinguishes their function.

## Nominal Morphology Checks

For nouns, pronouns, adjectives, and numerals:

- Decide the syntactic role before choosing case.
- Check postposition governance separately from the noun's base case.
- Recheck demonstrative stems: `ამ/მაგ/იმ` before case-marked nouns; `ამან/მაგან/იმან` when standalone.
- Recheck reflexive possession: `თავისი/თავიანთი` for the current subject's own possession; `მისი/მათი` for another third person.
- After numerals and `რამდენი`, prefer singular nouns in strict standard Georgian unless the context clearly requires plural interpretation.

Nominal morphology is often rule-decidable; concrete lexical stem alternation or fixed forms may still require the boundary file.

## Final Standardness Decision

Before answering:

1. State the grammatical layer internally: morphology, lexical paradigm, agreement, case, or syntax.
2. If rule-decidable, answer from the rule.
3. If paradigm-dependent, verify externally or state uncertainty.
4. In drafting mode, avoid risky uncertain forms by rewriting with a safer construction.

Do not add one-off problem words to this file. Add a rule only if it generalizes across a class.
