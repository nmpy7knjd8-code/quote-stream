# Review of the research quote file

Reviewed `data/research-quotes.json` on `cursor/scholarly-passages-6bb8` (22 entries; schema `quote`, `author`, `work`, `expansion`, `sources`). Expansions are three paragraphs each.

Standard used, after Garrett's update: a recognized translation or a reliable secondary copy is enough. A passage is **REJECT** only if it is fabricated or misattributed. Most of the effort is on the expansions: are they accurate, are they deep enough to be worth the space, are they clear, and do they explain why the idea matters?

Checked the quotations against the named editions: Eastlake's *Theory of Colours* (Gutenberg 50572), Carlyle's *Wilhelm Meister* (36483), Colvin's Keats (35698), Haldane and Kemp's Schopenhauer (38427), Atkinson's *Decline of the West* (72344), MacDonald's *Rampolli* (8949), Field's Eckhart (CCEL), Underhill's *Cloud* (Wikisource, and Sacred Texts chapters 3–6), MacKenna's Plotinus (Wikisource), and Taylor's *Elements of Theology* (Gutenberg 78800). All 29 source URLs returned 200. Several entries cite one edition in two or three file formats. Those links are live and point at the right book.

**Result: 17 PASS, 5 FIX, 0 REJECT.** Nothing was dropped. `corrected-quotes.json` keeps every PASS entry as submitted and the FIX entries with the corrections below. The quotations themselves are the editions they name. Footnote numbers and italic markup in the Gutenberg files are not part of the quotation, and leaving them out is right.

## FIX

### 04 Keats — Negative Capability

**FIX.** Colvin's text of the letter of 21 December 1817 matches Gutenberg 35698, including the irregular *Penetralium*. The expansion is otherwise the one this letter needs: it keeps Negative Capability inside the letter, marks *penetralium* as Keats's own Latin, and separates the chameleon-poet letter and the 1819 soul-making letter from this one. The opening sentence reverses Keats's distinction.

Replace:

> a disquisition, a dispute.

with:

> not a dispute, but a disquisition.

### 07 Spengler — Faustian number

**FIX.** Atkinson's text matches Gutenberg 72344, and the expansion is the right use of the page: morphology learned from Goethe, Apollinian number as a prime symbol rather than a stage on the way to the calculus, and a real parting from Heidegger (a soul's vocation, against a forgetting of Being). One date is easy to misread. The quotation's "c. 540" sits beside Pythagoras and means the sixth century BCE. The expansion says "Around 540" in a paragraph that then names Descartes.

Replace:

> Around 540 the Classical soul

with:

> Around 540 BCE the Classical soul

### 12 Eckhart — giving up God

**FIX.** The extract is Field's, and the expansion earns its place. It treats "blood-relative" as Field's metaphor for the spark, names the *vünkelîn*, points to the poverty sermon ("free of God") as the sharper statement of the same paradox, and keeps the bull and the *Cloud* from collapsing into this paragraph. The sermon title is wrong. In Field's 1909 book this page is sermon IV, "True Hearing," on Ecclesiasticus 24:30. "The Angel's Greeting" is sermon III, and it ends before this extract. Field's own wording two paragraphs above the extract already has Paul say he would be "cut off from God for my friends' sake," so the expansion's account of the wish follows Field. It does not need a rewrite.

Correction, in `work` only:

> Sermons, 'True Hearing' (Ecclesiasticus 24:30), trans. Claud Field (1909)

### 16 *Cloud of Unknowing*, chapter 6

**FIX.** Underhill's chapter matches Wikisource, and the expansion is the operational center of the set: thought of God's goodness is honored and then, for this work, put under the cloud of forgetting; the dart of longing is the method; "gotten and holden" is kept as holding rather than concluding. The gloss of *listily* is wrong. In this book the noun *list* means desire. The adverb in "stalwartly, but listily" is the other word: deftly, skillfully. The "but" is the contrast. The longing is already named in "a devout and a pleasing stirring of love."

Replace:

> 'Listily' is the author's adverb, from list, longing. The step above holy thoughts is made with desire, with strength.

with:

> 'Listily' is not the book's word for longing. The noun 'list' means desire, but this adverb, set against 'stalwartly' by a 'but,' means deftly or skillfully. The step above holy thoughts is strong and also tactful, and the longing is named in the next phrase, the devout stirring of love.

### 18 Plotinus — Nature's speech

**FIX.** MacKenna's speech of Nature matches the Wikisource text of III.8, and the expansion's reading of production as a silent seeing is the tractate's thesis. Schelling and Goethe are offered as a family, with the Goethe link left unforced. One sentence puts the One at the top of a scale of seeing. In this same tractate a pure unity has no room for vision and an object. Intellect is the seeing in which knower and known are one life. The One is what that seeing is finally about.

Replace:

> The hierarchy of Plotinus's cosmos is a hierarchy of the intensity of seeing: the One, intellect, soul, nature, and then the bodies that fall from nature's gaze.

with:

> The scale of seeing runs upward in clarity: nature, soul, intellect, where knower and known are one life. It does not culminate in the One. A pure unity, Plotinus says in this same tractate, has no room for vision and an object. The One is what the seeing is about. Bodies are what fall from nature's gaze.

## PASS

**00 Goethe, the sunlike eye.** Eastlake matches Gutenberg. The couplet is Goethe's own distich, adapting Plotinus I.6, which is what the expansion says; Eastlake's "old mystic writer" is the pose of the preface. Empedocles through *De Anima*, the move into the *Farbenlehre*, and the dormant light as evidence rather than ornament are the right frame. Delicate empiricism is named as the later maxim this kinship leads to, which is fair.

**01 Goethe, irony.** The chain from seeing to combination, and the demand to theorize while knowing that one is theorizing, are the preface's method. Newton as the target, the cousinship with Schlegel's irony, and the theory-laden look are kept in proportion. The expansion says what the irony is for: so the phenomenon can still correct the grid.

**02 Goethe, color and hearing.** "Acts of light" and the turn to the ear are in the preface. Calling this a sensory restitution of *musica mundana* is marked as a reading, and it is a good one. The blind man who still meets an infinite vitality is used as an argument for more than one kind of attention, which is what the paragraph is doing.

**03 Goethe, burgher and nobleman.** Carlyle matches Gutenberg. The passage is Wilhelm's answer to Werner in Book V, as the expansion says. Schiller's *Aesthetic Education* (1795) and the *Apprenticeship* (1795–96) are the same years. The Tower Society does not endorse the theater as the cure, and the expansion lets Wilhelm be partly wrong. The class costume is acknowledged, and the question "what art thou?" is what survives it.

**05 Schopenhauer, music.** Haldane and Kemp match Gutenberg, including their *exercitum* for Leibniz's *exercitium*. The expansion glosses the sense, an unconscious exercise in arithmetic, which is the right meaning of the formula. The isolation of music from the series of Ideas, Kant's lower rank for music as sensation, and the *Birth of Tragedy* taking the elevation and refusing the resignation are accurate. The expansion explains why the aesthetic effect is being used as a criterion.

**06 Schopenhauer, the ethical sublime.** The extension from storm and abyss to character matches §39. Kant's mathematical and dynamical sublime, Burke's terror at a distance, and the path into Book IV are the right revisions, and Nietzsche's refusal is named as a refusal of this posture. The expansion brings the sublime into a room with one's enemies without losing the definition.

**08 Spengler, destiny and causality.** Atkinson matches Gutenberg. Causality as the badge of waking life, destiny as what portrait, tragedy, and music can show, and the late man of the megalopolis are the book's method. "On his reading" of Kant is properly hedged. The expansion says what the intense hour is for: the apology for it is the late habit.

**09 Novalis, *Hymns to the Night* II.** MacDonald's second hymn matches Gutenberg 8949, opening "Must the morning always return?" Sophie von Kühn's death in 1797 and the *Athenaeum* text of 1800 are right. The *Ungrund* is left "in the background." The later hymns' turn toward Christ is fairly reserved for what follows this one. The expansion treats unholy activity as a name for busyness that consumes the visit it is busy for, which is the hymn's point.

**10 Novalis, Hyacinth and Rosebud.** The veil passage matches *Rampolli*, and MacDonald does name him Hyacinth and her Rosebud earlier in the same tale. Schiller's "Veiled Image at Sais," where the youth who lifts the veil is destroyed, is the right poem to set against this marriage. Corbin's *mundus imaginalis* and Jung's anima are marked as later vocabularies. The expansion's claim is the one the ending supports: what was sought at the end of the world was the nearest face.

**11 Eckhart, the nearness of the kingdom.** Field's sermon II matches CCEL, and the expansion already says that the 1909 English is free and compressing. Time and place, the creature as nothing beside God, and the recovery of all things inside that knowing are the sermon's arc. *In agro dominico* (1329) is rightly limited to "sentences of this family." The contrast with Aquinas on analogy is fair, and *Gelassenheit* is a real debt Heidegger names.

**13 *Cloud*, chapter 3.** Underhill matches Wikisource, and Sacred Texts `cou08` is this chapter. "Mean Himself, and none of His goods," the late fourteenth century, Thomas Gallus, and the affective reading of Dionysius are the right lineage. The expansion's best point is the one that is easy to miss: a private work is described as helping the living and the dead, so contemplation is being claimed as an invisible public act.

**14 *Cloud*, chapter 4.** Sacred Texts `cou09` is this chapter. Knowledgeable power and loving power, and the claim that a loving soul comprehends the one who exceeds every vessel, are the chapter. The Aquinas contrast is careful: in this life love can reach where knowledge does not, and beatitude remains, for him, an intellectual vision. The expansion answers the worry that unknowing is a blank.

**15 *Cloud*, chapter 5.** Sacred Texts `cou10` is this chapter. The cloud of forgetting, and the inclusion of good creatures and good thoughts, match Underhill. The shooter with his eye on the prick does follow immediately after this extract, in the same chapter. The expansion's use of it is right: what you behold, you stand under.

**17 Plotinus, symmetry.** MacKenna's I.6 matches Wikisource. The demolition of beauty-as-proportion, the simples (light, gold, a single tone), and the face whose symmetry does not change, are the argument. Stoic proportion, Aquinas's *claritas*, and Goethe's sunlike eye are the right descendants. The expansion shows why a ratio goes silent in front of those cases.

**19 Plotinus, action as a trace of vision.** MacKenna matches Wikisource. Aristotle's ranking of the contemplative life in the last book of the *Ethics* is right, and the expansion is harsher than Aristotle on purpose, then saves the complement clause: a deed can be justified when it gives the soul something nobler to look at than the work. Pieper is a kinship, not a citation. The expansion asks the question the passage leaves: whether the doing is ordered toward that nobler object.

**20 Proclus, proposition IV.** Taylor's 1816 text matches Gutenberg 78800, proposition and proof. The expansion states the trap accurately: the united is both one and not one, and identifying it with the One would make the One an infinite multitude. Dodds (1933) as the better critical text, Dionysius's dependence on the distinction, and Eckhart's "one, and above this and that" are fair. Taylor's Plato in Blake's world, and Taylor's Proclus as the same labor, does not claim that Blake read this proposition.

**21 Proclus, proposition V.** The extract is the reductio inside Taylor's proof of proposition V, and the expansion follows it: multitude cannot be prior, because a multitude that in no respect participates the One cannot be. The scholastic restatement is given with the difference Proclus would not accept, a creator in the biblical sense. The expansion uses the driest page as the floor under the others, which is the right use.
