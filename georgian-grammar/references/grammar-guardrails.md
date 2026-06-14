# Grammar Guardrails

This note distills the core source books into the highest-value rules for Georgian content generation and proofreading.

Use this file as the compact global checklist. For a precise decision, route to the focused rule files:

- verbs: `verb-morphology.md`
- joined, separate, and hyphenated writing: `compound-writing-rules.md`
- particles, fixed expressions, conjunctions, prohibitions: `particle-expression-rules.md`
- adverbs and adverbial relation: `adverb-rules.md`
- cases and postpositions: `case-and-postposition-rules.md`
- agreement: `agreement-rules.md`
- normative answering route: `normative-decision-protocol.md`

## 1. Register and Script

- Default to Mkhedruli.
- Prefer contemporary standard literary Georgian.
- Use archaic or elevated forms only when the user explicitly wants them.
- Avoid word-for-word calques from English or Russian if Georgian has a more natural construction.

## 2. Agreement

- Keep `ჩვენ` and `თქვენ` aligned with plural verbal morphology.
  - `ჩვენ ვიცით`
  - `თქვენ ხართ`
  - `თქვენ შეგიძლიათ`
- When a subject is introduced by a cardinal numeral above one, keep the noun singular. If that quantified phrase is the subject, the predicate is usually singular too.
  - `ორი კაცი გამოვიდა`
  - `ხუთი წიგნი დაიკარგა`
- Keep the noun singular after `რამდენი`.
  - `რამდენი ბავშვი მოვიდა?`
  - `რამდენი წიგნი გჭირდება?`
- Collective subjects usually take singular predicate forms.
  - `ხალხი მოგროვდა`
- If a possessive pronoun modifies a noun in dative or adverbial function, use the correct possessive form.
  - `ჩემს მეგობარს`
  - `შენს მეგობრად`
  - `ჩვენს ქალაქს`
  - `თქვენს მეუღლეს`
  - `მათს მეგობარს`
- Keep attributive agreement clean. Adjectives and other modifiers must match their head noun where the construction requires it.
- For third-person ownership, distinguish the current subject's own possession from another person's possession:
  - subject's own: `თავისი`, plural-owner `თავიანთი`
  - other third person: `მისი`, plural-owner `მათი`
- For relative pronouns, choose both number and case:
  - one referent: `რომელიც`
  - multiple referents: `რომლებიც`
  - role inside the relative clause controls forms such as `რომელმაც` or `რომელსაც`

## 3. Cases and Postpositions

- Do not choose a postposition by intuition alone; first identify the governing case.
- High-value pairings:
  - dative-based: `-თან`, `-ზე`, `-ში`
  - dative/interval-based: `შორის`
  - genitive-based: `-თვის`, `-გან`, `-კენ`, `-თანავე`, `-ებრ`, `მიმართ`, `მიერ`, `გარდა`, `შესახებ`, `განმავლობაში`
  - instrumental-based: `-ურთ`
  - nominative or expanded dative: `-ვით`
- Remember the common surface consequences:
  - with `-ზე` and `-ში`, the dative `ს` disappears on the surface
    - `სახლზე`
    - `სახლში`
  - with `-თან`, the dative `ს` may also disappear before heavy consonant clusters
    - `კართან`
    - `სახლთან`
- Distinguish source-person from source-place forms when `-გან` is involved.
  - `ვისგან?` `რისგან?`
  - `საიდან?` `რა დროიდან?`
- Use demonstrative case stems correctly:
  - before nouns: `ამ სახლმა`, `მაგ სახლს`, `იმ სახლის`
  - standalone pronouns: `ამან`, `მაგას`, `იმით`

## 4. Verbs

- Recheck person and number agreement before sending Georgian output.
- Derive a verb form from its paradigm, not from a noun or verbal noun by surface analogy.
- Do not use `-ობ` as a universal present-tense maker. First check whether the verb belongs to an `-ობ` class.
- For noun-derived verbs from `-ო`-final bases, choose `-ო-` or `-ოვ-` by concrete screeve and function, not by surface sound or broad series label. The aorist completed-action stem can take `-ოვ-`; do not carry that `-ვ-` automatically into present/future or second subjunctive/optative forms. Separate the first-person subject marker `ვ-` from any stem `-ვ-`.
- For compound verbs with lexical prefixes such as `თანა-`, keep the lexical prefix before the personal marker complex.
- Recheck version, passive, benefactive, and causative patterns:
  - self-benefactive/reflexive often uses `ი-`
  - action for another participant often uses `უ-`
  - causative/helping patterns often use `-ინ-` or `-ევინ-`
- For "take/bring", distinguish a carried thing from a led/driven person, animal, or vehicle:
  - thing: `მიაქვს`
  - person/animal/vehicle: `მიჰყავს`
- With `თურმე`, use an evidential/perfect-style verb form when the past action is reported or inferred, not directly witnessed.
- Treat third-series transitive forms as a danger zone. Inversion frequently breaks AI output.
  - compare `ვწერ`
  - with third-series `დამიწერია`
- Prefer modern standard prefixes by default. Do not invent archaic-looking variants.
  - old: `აღ-`, `გან-`, `შთა-`, `წარ-`
  - modern default: `ა-`, `გა-`, `გადა-`, `ჩა-`, `წა-`
- For negative or prohibitive commands:
  - use `არ` with second-subjunctive style forms
    - `არ უთხრა`
    - `არ გააკეთო`
  - use `ნუ` with present or future-style prohibitions
    - `ნუ ხსნი`
    - `ნუ გახსნი`

## 5. Clauses and Conjunctions

- Classify adverbial meaning before choosing a word or construction:
  - place: `სად?`, `საიდან?`, `საითკენ?`
  - time: `როდის?`, `როდიდან?`, `როდემდე?`
  - manner: `როგორ?`, `რანაირად?`
  - cause: `რატომ?`
  - purpose: `რისთვის?`
  - frequency: `რამდენჯერ?`
- Recheck question, relative, indefinite, and negative adverbs:
  - question: `სად?`, `როდის?`, `რატომ?`
  - relative: `სადაც`, `როდესაც`
  - indefinite: `სადღაც`, `სადმე`, `ოდესღაც`
  - negative: `არსად`, `ვერსად`, `არასდროს`
- For negative adverbs, preserve Georgian clause-level negation; do not delete the finite negator by English analogy.
- Use causal conjunctions for cause:
  - `რადგან`
  - `ვინაიდან`
  - `იმიტომ, რომ`
- Use purposive conjunctions for aim or purpose:
  - `რათა`
  - `იმისთვის, რომ`
- Do not swap causal and purposive conjunctions just because the English source uses "that" or "so that".
- Recheck `რომ` and `თუ` clauses when translating from English. English often compresses distinctions that Georgian expresses more explicitly.
- For conditionals, distinguish:
  - real condition/result: `თუ`, `რომ`, `როცა/როდესაც`, `როგორც კი`
  - unreal or wished-for condition: `რომ` plus counterfactual/desired-state forms and a conditional result
  - request/bargain nuance: `ოღონდ`
- Use `ვინც` for a person/actor and `რაც` for a thing, event, content, or action-object relation.
- For reported speech, preserve perspective:
  - `-მეთქი` for the speaker's own repeated words
  - `-თქო` for words the speaker wants passed on
  - `-ო` for someone else's words
- Do not erase Georgian double negation by English analogy: `არავინ არ`, `არაფერი არ`, `არსად არ`, `არასდროს არ`.

## 6. Punctuation

- Let syntax control punctuation.
- Before choosing a punctuation mark, identify the construction:
  - separate clause or subordinate clause
  - homogeneous members or list
  - generalizing word plus list
  - direct address
  - inserted or detached phrase
  - direct speech
  - explanation, consequence, or summary
- Distinguish hyphen from dash:
  - hyphen joins parts of a word
  - dash separates clauses, signals dialogue, or marks insertion
- Use a hyphen in measurement-plus-half compounds where `ნახევარი` joins the already formed measurement expression:
  - `ორკილო-ნახევარი`
  - Avoid `ორკილონახევარი`, `ორ კილონახევარი`, and `ორ-კილონახევარი`.
- For enumerations, check the direction of the generalizing element:
  - generalizing word or clause before the list -> colon
    - `ყველაფერი წარსულში დარჩა: სილამაზე, სილაღე და ახალგაზრდობა.`
  - list before the summarizing/generalizing clause -> dash
    - `სილამაზე, სილაღე და ახალგაზრდობა — ყველაფერი წარსულში დარჩა.`
- For homogeneous members, use commas between listed elements unless they are joined by a single non-repeated `და`.
  - `ვიყიდე პური, ყველი და ხილი.`
- For direct address, separate the addressed person or phrase with commas.
  - `ნინო, გთხოვ, დამირეკე.`
- Check comma placement around:
  - detached modifiers
  - inserted phrases
  - multi-clause sentences
  - direct address
- Keep spacing clean:
  - no space before `, ; : ? !`
  - normally one space after those marks

## 7. Normative Orthography

- Treat spelling, joined/separate writing, hyphenation, and fixed lexical forms as a separate review pass from grammar.
- Use `compound-writing-rules.md` and `particle-expression-rules.md` before relying on memory.
- Use `normative-orthography.md` for compact spelling and hyphenation reminders.
- Do not rely only on analogy for fixed forms; prefer the rule route first.

## 8. Manual Final Pass

Before finalizing Georgian output, reread the text once only for:

1. verb paradigm and person marking
2. quantified noun phrases
3. case plus postposition pairing
4. `თქვენ` agreement
5. possessive pronouns before dative or adverbial forms
6. `თავისი` vs `მისი`
7. relative pronoun number and case
8. version, passive, benefactive, and causative verb patterns
9. third-series and `თურმე` evidential forms
10. cause, purpose, and condition conjunctions
11. adverbial relation and negative adverb behavior
12. punctuation spacing
13. fixed spelling, joined/separate writing, and hyphenation rules
