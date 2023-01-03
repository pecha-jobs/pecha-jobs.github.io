
# Vulgate e-text creation

Many Tibetan works are available in numerous versions. This is because in the past, woodblock versions were made in various places and times, and with modern printing, many monasteries and organizations have inputed the same works into computers and printed them for their communities. Along the way, woodblock cutters and data enterers have both fixed mistakes in previous editions and made new ones of their own. As a result, it's difficult to assess which version is best. 

Our solution is to create a **vulgate edition** of a work. Based on the idea used to create the [Vulgate Bible](https://en.wikipedia.org/wiki/Vulgate), a vulgate edition is a commonly recognized text or edition compiled from other editions. It our case, we automatically create vulgate editions of a work by comparing multiple versions of the same work.

To create a vulgate text, we use a tool created by OpenPecha that compares multiple digital editions of the same work on a character-by-character basis. The algorithm calculates the most probable version of each syllable and strings them together to create a new, cleaner version of the work. The process removes spelling mistakes and deletes noise such as page headers, footnotes, and running titles, allowing us to create a high-quality e-text from several imperfect sources.

To preserve the tradition from which the text you give us originated from, we also add an annotation layer to the newly created vulgate text. This layer contains the original file provided to us and a list of differences between the vulgate version and the original version so that nothing is lost, only gained.
