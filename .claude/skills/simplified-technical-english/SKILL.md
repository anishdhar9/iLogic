---
name: simplified-technical-english
description: Reviews, rewrites, and drafts engineering and technical documentation (maintenance procedures, work instructions, assembly steps, descriptive specs, drawings notes, warnings/cautions) to comply with Simplified Technical English (STE / ASD-STE100), the controlled-language standard used across aerospace, defense, and industrial technical writing. Use this skill whenever the user asks to simplify, clarify, or plain-English a technical document, check a procedure or instruction for ambiguity, write or review a WARNING/CAUTION, shorten or restructure long technical sentences, or otherwise prepare engineering documentation for a broad or non-native-English audience — even if they never say "STE" or "ASD-STE100" by name (e.g. "make this maintenance manual easier to read," "simplify these assembly instructions," "is this warning label clear enough," "rewrite this procedure step").
---

# Simplified Technical English (STE) for engineering documentation

STE (ASD-STE100) is a controlled-English writing standard built for exactly one goal: a technical
document should have only one possible reading, for every reader, including people who learned
English as a second language. It does this with a small, fixed vocabulary and a short set of grammar
constraints — fewer ways to say something means fewer ways to misread it.

This skill is a condensed, original working guide to that standard, written for applying it to real
engineering text. It is **not** a reproduction of the official ASD-STE100 dictionary or rule text — ASD's
document is copyrighted, with free-reproduction rights limited to specific member organizations. For
the authoritative rule wording or a full word-by-word approval lookup, the official Issue 9 PDF is a free
download at https://www.asd-ste100.org.

## Workflow

1. **Identify the writing mode** — most rules depend on whether the text is a *procedure* (an
   instruction telling the reader to do something) or *descriptive writing* (information about how
   something is or works). Warnings/cautions are a third mode with their own shape. Mixed
   documents should be split cleanly: don't let instructions and background info share a sentence.
2. **Rewrite sentence by sentence.** Cut each sentence down to one idea. If a sentence contains
   "and," "which," multiple clauses, or more than one instruction, that's usually the signal to split it.
3. **Check vocabulary.** Flag words that are vague, formal/Latinate, jargon, regional slang, or
   idiomatic (phrasal verbs like "carry out," "set up," "look into"). Replace with a plain, single-meaning
   word — see the Word Choice section below. Keep company/industry technical nouns (part names,
   tool names) as-is; STE doesn't replace real terminology, it replaces the connective tissue around it.
4. **Check grammar constraints**: verb forms/tenses, active voice, article use, sentence length. See
   Core Rules below.
5. **For instructions**, convert to direct commands ("Remove the panel," not "The panel should be
   removed" or "You will need to remove the panel").
6. **For warnings/cautions**, make sure risk level, command/condition, and consequence are all
   present — see Section 7.
7. When you change wording, **re-read for meaning drift**. STE optimizes for clarity, not brevity for
   its own sake — never let a simplification change what the instruction actually tells the reader to do.
8. When presenting a rewrite, it's often useful to show the original next to the STE version so the
   user can verify no technical meaning was lost — this document uses "Before / After" for that.

## Core rules (condensed from ASD-STE100 Issue 9, Part 1)

### 1. Word choice
- Use a word only if it's (a) part of the plain, controlled vocabulary, or (b) a genuine technical noun
  or technical verb for the subject field (part names, tool names, process names from drawings,
  catalogs, or the company glossary).
- Use each word in only one sense and one part of speech — don't stretch "test" (a noun) into a verb,
  or use "dim" (an adjective) as if it meant "to dim."
- Technical nouns/verbs are fine even if they're not everyday words, but: keep them short, never
  slang or jargon, never invent a second name for something that already has one, and don't blur
  parts of speech — a technical noun stays a noun (don't verb it), a technical verb stays a verb.
- Use American spelling unless the target publication's house style says otherwise.

### 2. Multi-word nouns — cap at 3 words
- A noun string longer than three words is hard to parse ("main gear door retraction winch handle"
  — is "retraction" modifying "door" or "winch"?).
- Fix long official/catalog terms one of two ways: spell the term out in full the first time, then use a
  short form or approved abbreviation afterward; or hyphenate the words that act as a single unit
  (hyphenated words count as one word). Don't hyphenate everything just to force the count down —
  only hyphenate genuine single units.

### 3. Verbs
- Use only the verb forms the dictionary lists for that specific verb — not every English tense is
  assumed available for every verb.
- Six forms only: infinitive, imperative/command, simple present, simple past, simple future, and
  past participle used as an adjective. No progressive ("is removing"), no perfect tenses ("has been
  removed" as an action), no conditionals ("would remove").
- Past participles work as adjectives ("the removed panel"), not as a passive-tense construction
  beyond what's listed.
- Don't stack auxiliary verbs into compound constructions ("will have been checked") — state it
  plainly in one of the six forms.
- "-ing" words are nouns or modifiers only ("the operating lever," "the mounting bracket") — never a
  verb form ("while operating the lever...").
- Default to active voice. Passive is allowed only in descriptive writing, and only when the agent
  performing the action genuinely isn't known or doesn't matter.
- Describe actions with verbs, not nouns: "inspect the seal," not "do an inspection of the seal."

### 4. Sentences (general)
- Short, single-clause sentences beat long compound ones.
- Don't drop words to save space, and don't use contractions — "do not," never "don't."
- Break up complex information into a vertical (numbered or lettered) list rather than one dense
  run-on sentence.
- Make relationships between sentences explicit with connecting words ("if," "when," "because,"
  "and," "but") instead of leaving the reader to infer them.
- Use articles ("a," "the") and demonstratives ("this," "these") wherever normal English grammar
  calls for them — omitting them to save words creates ambiguity, not clarity.

### 5. Procedural writing (instructions / work steps)
- Maximum 20 words per instruction sentence.
- One instruction per sentence, unless two actions genuinely happen simultaneously (in which case
  say so explicitly).
- Instructions are imperative/command form: "Remove the cover," not "The cover should be removed"
  or "You should remove the cover."
- If the reader needs context before acting, give the condition first, then a comma, then the
  command: "If the light comes on, stop the test."
- Notes carry information only — never an instruction — and get slightly more room: 25 words.

### 6. Descriptive writing (specs, background, system descriptions)
- Build information up gradually. One subject/idea per sentence; don't front-load everything.
- Reuse the same key word or phrase for the same concept throughout a passage so the reader can
  follow the thread — don't vary vocabulary for style.
- Maximum 25 words per sentence.
- Group related sentences into paragraphs; give each paragraph exactly one topic.
- Cap paragraphs at 6 sentences — split into a new paragraph rather than let one run longer.

### 7. Safety instructions (warnings / cautions)
Every warning or caution needs all three of:
1. **A risk-level word up front** — conventionally WARNING for risk of injury or death, CAUTION for
   risk of damage to equipment or property (follow the target publication's existing house style/graphic
   convention if one exists; STE governs the content, not the formatting).
2. **A clear, direct command or condition** stating what to do or what situation applies.
3. **An explanation of the risk or consequence** — never leave a warning as a bare command with no
   stated reason; the reader needs to know *why* it matters to take it seriously.

Before: "CAUTION: EXTREME CLEANLINESS OF OXYGEN TUBES IS IMPERATIVE."
(Vague, no command, and actually understates the risk — oxygen contamination is an explosion/
injury risk, not just a cleanliness issue.)
After: "WARNING: MAKE SURE THAT THE OXYGEN TUBES ARE FULLY CLEAN. OXYGEN AND
GREASE CAN CAUSE AN EXPLOSION. AN EXPLOSION CAN CAUSE INJURY OR DEATH."

### 8. Punctuation and word count
- Any standard punctuation is fine except the semicolon.
- Hyphens join words that function as a single unit.
- Reserve parentheses for specific jobs: illustration references, item/step numbers, abbreviations,
  giving singular and plural together, a short in-line explanation, or an alternative term — not
  general aside commentary.
- For the 20/25-word sentence caps: a colon in a vertical list ends a sentence, same as a period;
  anything inside parentheses counts as one word regardless of length; numbers, a number+unit pair,
  abbreviations, alphanumeric IDs, quoted text, titles/headings/labels, and proper nouns each count
  as one word no matter how many words they contain; hyphenated terms count as one word.

### 9. Writing practices and common pitfalls
- When swapping in a plainer word doesn't preserve the meaning or changes the part of speech,
  restructure the sentence instead of forcing an awkward substitution.
- Use each approved word strictly in its intended sense — don't stretch it to a nearby meaning.
- Don't chain words into an informal phrasal verb ("set up," "carry out," "look into") — use a single
  direct verb instead ("install," "do," "check").
- Pick one term per concept and keep it for the whole document — varying vocabulary for style
  reintroduces the ambiguity STE exists to remove.

**General recommendations (grammar details worth double-checking):**
- Keep "that" after verbs like "make sure," "show," "recommend" — "Make sure that the valve is open,"
  not "Make sure the valve is open." It marks the clause boundary and helps non-native readers and
  translators.
- Watch the preposition "with" — it can mean association, accompaniment, or means/instrument, and
  a sentence can genuinely support more than one reading. If ambiguous, reword, or make the tool the
  sentence's actual object: "Seal the opening with tool TS9867," not "Use tool TS9867 to seal the
  opening."
- Only use pronouns with a single, unmistakable referent (it, they, that, these, those — not he/she).
  If a pronoun could point to more than one noun in context, repeat the noun instead.
- Same for "this" — if more than one thing in the preceding text could be "this," restate what's meant.
- Watch for "false friends" — words that resemble a term in another language but carry a different
  meaning in English (e.g. "disposition" does not mean "instruction," despite resembling words that
  do in some other languages).
- Spell out Latin abbreviations in plain English — "for example" not "e.g.," "that is" not "i.e.," and
  replace "etc." with an explicit list or drop it if it's not adding information.
- Use gender-neutral language throughout. Avoid "he/she" and "man/woman" except where the
  context genuinely requires sex-specific language (e.g. a medical procedure).
- The possessive "'s" is fine when unambiguous ("the manufacturer's instructions"); when in doubt,
  rephrase with "of" instead.

## Word choice quick reference

The official dictionary (~875 approved words, ~1,274 non-approved words with approved
alternatives) isn't reproduced here — it's proprietary and this skill doesn't have a reliable full copy of
it. What follows is a compact table of the kind of plain-word substitution STE (and controlled English
generally) trains writers to make. Treat it as illustrative of the *pattern*, not an authoritative or
exhaustive list — when a word's approval status genuinely matters, check the official dictionary.

| Instead of | Use | Instead of | Use |
|---|---|---|---|
| utilize | use | prior to | before |
| subsequent to | after | in order to | to |
| in the event that | if | commence | start / begin |
| terminate | stop / end | sufficient | enough |
| insufficient | not enough | approximately | about |
| acceptable | permitted / allowed | unacceptable | not permitted |
| assist | help | obtain | get |
| purchase | buy | fabricate / manufacture | make |
| accomplish / perform | do | initiate | start |
| facilitate | help / make easier | ensure / assure | make sure |
| verify | check | demonstrate / indicate | show |
| possess | have | require | need |
| additional | more / extra | numerous | many |
| majority of | most of | in close proximity to / in the vicinity of | near |
| due to the fact that | because | at this point in time | now |
| optimum / optimal | best | adequate | enough |
| endeavor | try | modify | change |
| retain | keep | remove (as "get rid of an abstract thing") | remove is fine as a physical action; for abstract removal, reword (e.g. "no longer applies") |

**General pattern to teach, not just this table**: prefer short, common, everyday words over long or
formal/Latinate synonyms; prefer a plain verb over "verb + abstract noun" (e.g. avoid turning a verb
into a noun phrase); and if a word could be read more than one way in context, replace it even if it's
technically "approved."

## Attribution and authoritative source

Rule numbers cited above (e.g. "Rule 3.6") refer to ASD-STE100 Issue 9 (2025), published by the
Aerospace, Security and Defence Industries Association of Europe (ASD), for locating the original
clause — they are not quotations of ASD's text. For the complete official rule text, worked examples,
and the full approved/non-approved dictionary, use the free official download at
https://www.asd-ste100.org. Consult the official document directly for any compliance-critical or
publication-bound use (e.g. documentation delivered under a contract that mandates ASD-STE100
conformance), since this skill is a practical working aid, not a substitute for the standard itself.
