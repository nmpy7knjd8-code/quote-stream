# Review of the research quote file (62 entries)

Reviewed `data/research-quotes.json` on `cursor/scholarly-passages-6bb8` as it stands now: the original 22 passages, each expansion lengthened from three paragraphs to five, plus 40 new entries. Six of the new entries are public-domain English (Steiner, Bergson, Eliot). Thirty-four are labeled paraphrases of copyrighted modern work.

Standard used: a recognized translation or a reliable secondary copy is enough, and a passage is **REJECT** only if it is fabricated or misattributed. A paraphrase has to represent the thinker's actual argument and name the work. Expansions are judged on whether the influence and lineage claims are accurate, whether the writing is deep enough to earn the space, and whether it says why the idea matters.

The first 22 quotations are unchanged and still match the named editions. The six new public-domain quotations match Gutenberg (Steiner 55761, Bergson 26163, Eliot 57795), apart from one joined line-break in Bergson. Of 109 source URLs, 108 returned a success code. The Internet Encyclopedia of Philosophy page for Bergson returned 500; that entry's Gutenberg and Stanford Encyclopedia links are live. The paraphrase entries mostly cite encyclopedia pages. Those pages are live and on the right person or book. They are not substitutes for the books, and the work lines are what carry the citation.

**Result: 51 PASS, 11 FIX, 0 REJECT.** Nothing was dropped. `corrected-quotes.json` is the full file of 62, with the eleven corrections below. The five corrections from the review of the 22-entry file were not taken up when those expansions were lengthened. They are restated here because they are still in the text.

## FIX

### 04 Keats — Negative Capability

**FIX.** Still the opening sentence. Colvin matches Gutenberg. The new paragraphs on Bion and on Eliot are right, and they are careful: Bion keeps the tolerance for half-knowledge and drops the letter's claim about Beauty, and Eliot's impersonality is set beside the letter as a rival art rather than as the same one.

Replace:

> a disquisition, a dispute.

with:

> not a dispute, but a disquisition.

### 05 Schopenhauer — music

**FIX.** The new paragraph on Wagner, Nietzsche, and Thomas Mann is the right story except at the joint. Wagner read Schopenhauer in 1854 and let the denial of the will press on the ending of the *Ring*. Nietzsche did not introduce them. He found Schopenhauer on his own in 1865 and met Wagner in 1868. *The Birth of Tragedy* (1872) and *Doctor Faustus* are fairly placed.

Replace:

> Nietzsche, who had been the go-between of that encounter and then the enemy of both men, publishes The Birth of Tragedy in 1872

with:

> Nietzsche was not the link between them. Wagner had lived with Schopenhauer since 1854; Nietzsche found Schopenhauer on his own in 1865 and met Wagner only in 1868, and he later became the enemy of both men. He publishes The Birth of Tragedy in 1872

### 07 Spengler — Faustian number

**FIX.** The new paragraphs are good. Cassirer refuses the organic soul, Heidegger moves calculation out of the culture-soul into the history of Being, and Gebser keeps the eye for form and drops the death sentence. Those three are accurately distinguished. The date in the first paragraph is still easy to misread next to Descartes.

Replace:

> Around 540 the Classical soul

with:

> Around 540 BCE the Classical soul

### 11 Eckhart — the nearness of the kingdom

**FIX.** Baader reading Eckhart to Hegel, and Hegel recognizing a speculative mysticism near his own, is the real anecdote, and the expansion is right to call the result a loss of a practice. The new closing paragraph conflates two Heidegger texts that were published together. The 1955 memorial address turns releasement toward things in a technological world. It does not name Eckhart. The country-path conversation published with it is where the word's older mystical use is the subject.

Replace:

> Heidegger's Gelassenheit, in the 1955 address, names Eckhart and turns the letting-go toward things in a technological world.

with:

> Heidegger's 1955 memorial address turns the letting-go toward things in a technological world. Eckhart is named in the country-path conversation published with that address, where the word's older mystical use is the subject.

### 12 Eckhart — giving up God

**FIX.** The extract is still Field's sermon IV, "True Hearing," on Ecclesiasticus 24:30. "The Angel's Greeting" is sermon III and ends before this page. The lengthened expansion now repeats the wrong title in the prose. The rest of that paragraph is right: the poverty sermon is the sharper statement, and "blood-relative" is Field's metaphor for the *vünkelîn*. Merton's use of the spark as a meeting with Zen is fairly marked as a twentieth-century crossing Eckhart did not arrange.

In `work`:

> Sermons, 'True Hearing' (Ecclesiasticus 24:30), trans. Claud Field (1909)

Replace:

> Field's Angel's Greeting is the same family in a milder cadence

with:

> Field's 'True Hearing,' the sermon this extract comes from, is the same family in a milder cadence

### 15 *Cloud of Unknowing*, chapter 5

**FIX.** The new paragraphs are otherwise exact. Dionysius's leave-taking, the inclusion of the good, and the warning against confusing this work with a general contempt for creatures are the chapter. Ignatius is the right complementary practice and the wrong century. The *Cloud* is late fourteenth century. "Find God in all things" is sixteenth century.

Replace:

> Ignatius of Loyola's counsel to find God in all things is the complementary practice in the same century's neighborhood, and it is a different practice.

with:

> Ignatius of Loyola's counsel to find God in all things, two centuries later, is the complementary practice, and it is a different practice.

### 16 *Cloud of Unknowing*, chapter 6

**FIX.** The new paragraph is right about the reprint and wrong about the word. Underhill's 1922 text reads "listily." Sacred-texts reads "Mistily." That reprint wording is real, and it is a corruption, not a second authorial sense. *Listily*, set against *stalwartly* by a "but," means deftly or skillfully. The longing is the "stirring of love" and the dart. The earlier paragraph in the same expansion still glosses the adverb as longing, so the two paragraphs now disagree with each other and both miss the contrast.

Replace the earlier gloss:

> 'Listily' is the author's adverb, from list, longing. The step above holy thoughts is made with desire, with strength.

with:

> 'Listily,' set against 'stalwartly' by a 'but,' means deftly or skillfully. The step above holy thoughts is strong and also tactful. The longing is the devout stirring of love in the same sentence, and the sharp dart that follows.

Replace the new textual paragraph's opening:

> The adverb is a textual argument. Underhill's 1922 text, and the manuscripts she follows, read 'listily,' from list, longing. The step above holy thoughts is made with desire. A widespread reprint, sacred-texts among others, reads 'Mistily,' which turns a word for love's aim into a word for blurred sight. The quote follows the 1922 reading because the method of the chapter depends on it.

with:

> The adverb is a textual argument, and the meaning is the other half of it. Underhill's 1922 text reads 'listily.' Sacred-texts, a reprint in wide circulation, reads 'Mistily,' which turns the word into blurred sight. That is a corruption, and the quotation rightly follows Underhill. 'Listily' means deftly or skillfully, the contrast with 'stalwartly.' The longing is already named in the stirring of love and in the dart. The method of the chapter depends on the dart.

### 18 Plotinus — Nature's speech

**FIX.** Two claims. The older paragraph still puts the One at the top of a scale of seeing. In this tractate a pure unity has no room for vision and an object. The new paragraph on Schelling dates Creuzer too early. Ficino's Latin is the Renaissance path. *Ideas for a Philosophy of Nature* is 1797 and the *System of Transcendental Idealism* is 1800. Creuzer's edition of Plotinus is 1835. Goethe, Steiner, and Barfield, later in the same paragraph, are in the right order.

Replace:

> The hierarchy of Plotinus's cosmos is a hierarchy of the intensity of seeing: the One, intellect, soul, nature, and then the bodies that fall from nature's gaze.

with:

> The scale of seeing runs upward in clarity: nature, soul, intellect, where knower and known are one life. It does not culminate in the One. A pure unity, Plotinus says in this same tractate, has no room for vision and an object. The One is what the seeing is about. Bodies are what fall from nature's gaze.

Replace:

> The Renaissance Neoplatonists and, in his own time, the new editions and discussions around Creuzer made Plotinus available as a philosophy of production rather than only as a piety. In the Ideas for a Philosophy of Nature and in the System of Transcendental Idealism, productivity and the ideal are one act seen from two sides.

with:

> Ficino's Latin Plotinus had already made the Enneads a philosophy of production rather than only a piety. Schelling's early books do not depend on Creuzer. The Ideas for a Philosophy of Nature is 1797 and the System of Transcendental Idealism is 1800; Creuzer's edition of Plotinus is 1835. In those two books, productivity and the ideal are one act seen from two sides.

### 24 Bergson — duration

**FIX.** Mitchell's chapter 1 matches Gutenberg, and the expansion is right that the next sentences give the brain the job of holding the past back so that action can go forward. *Time and Free Will* (1889), the *élan*, and the refusal of a drawer of states are accurate. William James cannot be among the readers of the 1911 English. He died in 1910. He had read the French of 1907, and *A Pluralistic Universe* (1909) is the sympathetic book.

Replace:

> Mitchell's 1911 English is the translation in which this reached American and British readers, William James among the sympathetic.

with:

> Mitchell's 1911 English is the translation in which the book reached many American and British readers. William James, who died in 1910, had been the sympathetic reader of the French Creative Evolution of 1907, not of this translation.

### 25 Bergson — the cinematograph

**FIX.** The passage is Mitchell's, and the expansion's use of it is right: Zeno to the idea to modern science, action needing stops, speculation that uses only stops missing the movement. Proust by marriage, and Deleuze turning the figure of illusion into an art that can think time, are fair and in the right order. One word in the quotation is a broken line-join.

Replace:

> per sonal attitudes

with:

> personal attitudes

### 61 Vervaeke — the meaning crisis

**FIX.** The paraphrase is a fair map of the public series: propositional, procedural, perspectival, and participatory knowing; relevance realization; the 2019 lectures. The ecology of practices and the zombie as a myth of motion without meaning are his. *Zombies in Western Culture* (2017) has a third author.

Replace:

> written with Christopher Mastropietro

with:

> written with Christopher Mastropietro and Filip Miscevic

## PASS

The lengthened paragraphs on the original 22 are, apart from the corrections above, the part of this update that most earns the space. They follow a real transmission and they say what mutates.

**00–03 Goethe.** Steiner's Kürschner edition in the 1880s, Barfield's original and final participation, and McGilchrist as a later description from another method are the right chain for the sunlike eye. Coleridge's primary and secondary imagination are distinguished from Goethe's laboratory irony. Heisenberg is fairly allowed to grant the methodological point and withhold the physics. The preface's blind man is used to refuse Schopenhauer's ranking of music as the one metaphysical sense, which is a real difference and not a forced harmony. Schiller's letters and the *Apprenticeship* are the same years; Carlyle's 1824 English and the question in *Past and Present* are fair; Weil, Crawford, and Berry are marked as answers to the sentence rather than as readings of the novel.

**06, 08–10, 13, 14, 17, 19–21.** Murdoch's unselfing is kept off Schopenhauer's denial of the will. Spengler's portrait, tragedy, and music are tied to a secular sublime, and Taylor's buffered self is described from the inside of a life rather than as another prophecy of death. Novalis's hymn is kept in its sequence, with the Christological turn reserved for the later hymns, and Rilke is not handed back to a church. The Hyacinth tale is dated against Schiller, and Corbin's 1964 essay is used as a title for a room Novalis already wrote, with the warning that a psychological reading loses the world Corbin insisted on. The *Cloud* chapters keep Gallus, Aquinas, and Underhill's 1912/1922 editions in the right relation. The shooter and the prick do follow the chapter 5 extract. Plotinus on symmetry, Aristotle's last book of the *Ethics* against Pieper and then Crawford, Koch and Stiglmayr in 1895, Dodds in 1933, and the refusal to flatten emanation into creation are accurate. Taylor's Proclus is no longer asked to be a page Blake certainly had open.

**22–23 Steiner.** Hoernlé's English matches Gutenberg 55761, including the appendix *Truth and Science* in the Putnam edition whose editor's note is March 1921 and whose imprint is the enlarged edition. Moral imagination as the concrete idea, the refusal of a voice from beyond, and the later mutation into anthroposophical exercises and Barfield's final participation are the right three stages. Goethe's irony is named as the safeguard the appendix does not yet emphasize.

**26–27 Eliot, *The Sacred Wood*.** Both essays match Gutenberg 57795. Tradition as labor, the simultaneous order, and the new work altering that order are the 1919 essay, rightly placed before the 1927 conversion. The Blake essay's home-made furniture, put together from the odds and ends about the house, is in the essay even though it sits outside the extract, and the expansion uses it faithfully. Raine is the real reply, and she is not allowed to make Eliot's demand for a framework trivial.

**28–32 Barfield, Tolkien, Williams, Merton, Rowan Williams.** Original and final participation, idolatry as appearances taken for things, and the independent cousinship with Gebser are accurate, including the warning not to invent a line from Gebser to Barfield. Lewis's Great War and Tolkien's debt on language are fair. The Lang lecture of 1939, the 1947 volume for Williams, recovery, escape, consolation, and sub-creation are the lecture. Coinherence, the Companions, Beatrice against the *Cloud*, and Eliot at Faber are Williams. Merton's false self, *New Seeds* against the early flight from the world, and the Zen reading of Eckhart are kept distinct. *The Wound of Knowledge* (1979) is fairly read as apophasis bound to Christ and to a life, against a mysticism that has detached itself from both.

**33–36 Weil, Murdoch, Bachelard.** Attention, affliction, decreation, the *Iliad* essay, and the split among heirs (Murdoch dropping the void, political readers sometimes dropping the severity) are Weil. Murdoch's three essays, the kestrel, Weil named as the source, and fantasy as the opposite of attention are *The Sovereignty of Good*. Bachelard's reversal, from the image as epistemological obstacle in *The Psychoanalysis of Fire* to reverie in the late poetics, and the house as a topography of intimacy, are the books. Corbin is allowed to answer that a phenomenology of reverie is still a description of a subject.

**37–43 Neumann, von Franz, Giegerich, Moore, Bly, Corbin.** The heroic sequence is stated and then charged with the gendering later criticism has pressed. Von Franz is the corrective inside the same school, tale before theory. Giegerich's logical life, against a soul pictured as a gallery of figures, is his actual argument with Hillman, and the risk of a new contempt for the image is named. Moore is Ficino's care and Hillman's campaign, with the cost of popularity said plainly. *Iron John* is summarized as the Grimm sequence, and the weekend-rite movement is not defended past the tale. *Alam al-mithal*, the 1964 essay, *ta'wil* against allegory, and the chain Corbin–Hillman–Giegerich are accurate. The standard the Corbin paraphrase offers, that a commentary which replaces the image has become the allegory he refused, is the right use of him.

**44–53 Gebser, Girard, Jonas, Hart, Scruton, Berry, Dillard, Raine, Kingsley, Cassirer.** Structures and deficient modes, Spengler used and refused, diaphany as transparency rather than a return to myth. Mimetic desire, the romantic lie, the scapegoat, and Nietzsche as the philosopher who saw the mechanism and took the other side. Jonas's anti-cosmic syndrome against a careless reading of the spark, with specialists' revisions noted, and *The Imperative of Responsibility* as the reversal of his teacher. Hart's God as not a being among beings, and beauty as peaceful difference, with Gregory, Dionysius, and Maximus as the sources. Scruton's beauty as a summons, warmed out of Kant's disinterest and free of Schopenhauer's denial. Berry's membership against the industrial mind, with Weil, Ellul, and Kingsnorth in the right roles. Dillard's two ways of looking, and the refusal of a tidy consolation, as the mutation of Thoreau. Raine's learned Blake against Eliot's homemade philosophy. Kingsley's Parmenides, with the mainstream rejection left visible and the claim tied to Velia and Apollo Oulios rather than to a wish that the Presocratics be mystics. Cassirer's symbolic forms against Spengler's organism, the Davos meeting of 1929, and *The Myth of the State* as myth returning inside political technique.

**54–60 Rilke, *Four Quartets*, Florensky, Bulgakov, Kingsnorth, Taylor, Crawford.** The Ninth Elegy's saying of perishable things, the *Letters* of 1929 as letters written decades earlier, and Heidegger's 1946 "What Are Poets For?" marked as Heidegger's use of Rilke. The *Quartets* as the essay on tradition lived, after 1927, in a garden, on a coast, and at Ferrar's Little Gidding, with the timeless absolute and the mere historical process both refused. Florensky's antinomy, the Trinity against a simple One, the execution in 1937, and Bulgakov as the cosmological mutation. Sophia as *ousia* rather than a fourth hypostasis, the 1930s controversy, and the strain against Palamas. Kingsnorth's Machine as a way of seeing, *Against the Machine* (2025), Weil, Ellul, and Berry named as the tradition he claims, and the saw distinguished from the worldview. Taylor's porous and buffered selves, the immanent frame, and the rejection of the subtraction story, set beside Barfield and Gebser without making them disciples. Crawford's material that pushes back, Polanyi and Arendt, and attention as a resource being enclosed.
