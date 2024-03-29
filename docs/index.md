---
title: "Vowel duration and consonant voicing: A production study"
author: "Stefano Coretta"
site: bookdown::bookdown_site
documentclass: book
classoption:
- oneside
- a4paper
bibliography: linguistics.bib
biblio-style: unified
link-citations: true
csl: unified-style-sheet-for-linguistics.csl
geometry:
- top=3cm
- bottom=3cm
- left=4cm
- right=2.5cm
indent: true
fontsize: 12pt
mainfont: Tinos
params:
  version: "7.3"
  version-date: "2021/01/01"
---



# Abstract {-}

This dissertation focusses on the so-called "voicing effect", by which vowels tend to be shorter when followed by voiceless stops and to be longer when followed by voiced stops, as exemplified by the English word pair *bat* vs *bad*.
While the presence of this effect is cross-linguistically widespread, less is known about the source(s) of this phenomenon and competing accounts have been proposed over the decades.
In this work, I draw from acoustic and articulatory data of Italian, Polish, and English and offer an overarching account of which aspects of the production of voiceless vs voiced stops, and vowel/consonant sequences in general, contribute to the emergence of the voicing effect.

The results indicate that the voicing effect is the product of a mechanism of compensation between the duration of the vowel and that of the following stop closure.
The acoustic temporal relations of consonants and vowels observed in disyllabic (CV́CV) words of Italian, Polish, and English suggest that the duration of the interval between the release of the two stops is not affected by the voicing of the second stop.
The release-to-release interval has similar duration in words with a voiceless C2 and those with a voiced C2.
Within this temporally stable interval, the timing of the closure onset (the VC boundary) determines the duration of both the vowel and the stop closure.

Ultrasound tongue imaging and electroglottographic data of Italian and Polish further show that the timing of the closure onset of voiced and voiced stops depends on articulatory factors related to the implementation of voicelessness and voicing.
In particular, I argue that a delayed closure onset allows for enough tongue root advancement (known to facilitate voicing during closure) to be implemented during the production of the vowel in anticipation of the stop closure.
Furthermore, glottal spreading typical of voiceless stops also can affect the timing of closure by anticipating the achievement of closure.
These two factors, among other known factors, contribute to the observed pattern of short voiced closures and long preceding vowel duration, and, vice versa, long voiceless closures and short preceding vowel duration.

# Declaration {-}

I declare that no portion of the work referred to in this thesis has been submitted in support of an application for another degree or qualification of this or any other university or other institute of learning.

# Copyright statement {-}

The author of this thesis (including any appendices and/or schedules to this thesis) owns certain copyright or related rights in it (the 'Copyright') and s/he has given The University of Manchester certain rights to use such Copyright, including for administrative purposes.

Copies of this thesis, either in full or in extracts and whether in hard or electronic copy, may be made only in accordance with the Copyright, Designs and Patents Act 1988 (as amended) and regulations issued under it or, where appropriate, in accordance with licensing agreements which the University has from time to time. This page must form part of any such copies made.

The ownership of certain Copyright, patents, designs, trademarks and other intellectual property (the 'Intellectual Property') and any reproductions of copyright works in the thesis, for example graphs and tables ('Reproductions'), which may be described in this thesis, may not be owned by the author and may be owned by third parties. Such Intellectual Property and Reproductions cannot and must not be made available for use without the prior written permission of the owner(s) of the relevant Intellectual Property and/or Reproductions.

Further information on the conditions under which disclosure, publication and commercialisation of this thesis, the Copyright and any Intellectual Property and/or Reproductions described in it may take place is available in the University IP Policy (see <http://documents.manchester.ac.uk/DocuInfo.aspx?DocID=24420>), in any relevant Thesis restriction declarations deposited in the University Library, The University Library’s regulations (see <http://www.library.manchester.ac.uk/about/regulations/>) and in The University's policy on Presentation of Theses.

# Acknowledgements {-}


<img src="img/tengwar.svg" alt="elen sila lumeann-omentielvo" width=300>

Elen síla lúmenn' omentielvo.\
*A star shines on the hour of our meeting.*

---J.R.R. Tolkien, The Fellowship of the Ring

--------

I am for ever indebted to very many people, without whom I would not have seen the light at the end of this journey.
A long journey that has witnessed bliss and sorrow, friends coming and parting, and lines of written words, over words, over words.
But a joyful journey nonetheless, thanks to the cheer and comfort I was given by those who, in full or in good measure, walked next to me along such perilous path.
Among these heroic figures, I wish to thank first and foremost my supervisors and mentors, Ricardo (Dr Bermúdez-Otero) and Patrycja (Dr Strycharczuk).
With perpetual patience and kindness, they offered to me in countless occasions guidance and inspiration.

I also wish to thank my colleagues, as well as friends, from the Division and the Phonetics Lab, to which I owe so much in terms of time, thoughts, and laughter.
Thanks to Simone, for the numerous chats about academia and life, for his moral support, and for the unicorn-shaped mug he had his coffee from, which gave to our time spent together a note of candour and light-heartedness.
Thanks to Andrea (Dr Nini), who taught me about matters of study and of day-to-day living.
Thanks must also go to Juliette, a companion of lunches and brunches, drinks and dinners, work sessions and pleasure trips, who brought constant light in cloudy Manchester and in my heart.
Thanks to Jessica, for the lovely *chiacchierate* about all things and for her sparkling energy.

Thanks to the fellows I started this journey with: Stephen, to whom I am grateful for his continuous help and for our creative exchanges; and Donald, to whom I am grateful for the cheerful wit and the appreciation for the good things in life.
I have also received immense personal and academic support from George, whose exchanges of ideas were a continuous inspiration, and from Hannah, whose calmness and poise helped me cherish the good and the bad times.
Last, but not least, a great thanks to all the other graduate students, some of whom were there before me, some of whom came later (Deepthi, Fernanda, Henri, Jane, Chris, Max, Lorenzo, Kai, Sarah, Mary, and many others whom I wished I had the chance to know better), and to all the other members of staff at LEL who contributed each with their own field to my broader understanding of linguistics.
I am also indebted to Prof. Steven Lulich from Indiana University in Bloomington for hosting me in his Lab during October 2018 and letting me play with the 3D ultrasound machine (what a toy!), and to Prof. Małgorzata Ćavar for sharing her ideas on the tongue root.
Thanks also to Sherman, Romario, Rebecca, Luma, and all the beautiful people in Bloomington that accompanied me for too short a time along the PhD path.

I would have not made it through without all of my friends in Manchester, especially (in order of appearance, because they are all dearest to me) David, Juan, Richard and Jaqui, Mark and Kat, and Crystal, who offered me unconditional friendship and help when I most needed them. Also thanks to Mariana, Maxime, Gül, Valentina, Ximena, Lucia, Edo, and to the friends I met in York but whom I found again in Manchester, thank you all for the great time.

Thanks to my teachers and friends from *Il Loto Blu*, whose love has sustained me for all these years.
Thanks to Valentina A., with whom I share an irrepressible thrust to "acquire for ourselves a knowledge of higher worlds."
Special thanks go to my friends in Verbania, who supported me and stood me (*supportato e sopportato*) since the dawn of time, and to Mattia, *sorella mia*, whose friendship, *in præsentia et in absentia*, has gracefully marked my University years from day one.
Thanks to Sig.ra Racchelli, whose help and care provided me with the resources to survive difficult times.
Thanks to my loving family on Earth and beyond, and a special thanks to my mother, whose continuous sacrifice encouraged me to keep on moving forward.

The tutelage and support of these and many more people came as those of *Kṛṣṇa* upon *Arjuna* in the *Bhagavadgitā*, during the battle at *Kurukṣetra*.
Without their direction and kindness, I would have lost my way and strayed, never to find again the will to persist along the road.
For all of you, a thousand thoughts, then a hundred, then another thousand, then a second hundred, then yet another thousand, then a hundred more.

--------

असंशयं महाबाहो मनो दुर्निग्रहं चलम् ।\
अभ्यासेन तु कौन्तेय वैराग्येण च गृह्यते ॥ ६-३५॥

asaṃśayaṃ mahābāho mano durnigrahaṃ calam |\
abhyāsena tu kaunteya vairāgyeṇa ca gṛhyate || 6-35 ||

*O mighty-armed one, it is undoubtedly very difficult to curb the flickering mind, but it can be controlled, O son of Kunti, by constant practice and by detachment.* [BG 6.35]
