# What?
Create a Kindle dictionary from an Anki deck. This is just and example notebook where I build a kindle dictionary for Heisig keywords and Kanji Koohi mnemonics so you can easily look them up on the Kindle. The example is specific to the RTK dataset, but this code can easily be modified to create your own dictionary from an Anki Deck or other source.

# How
I followed Jake McCrary's guide. [Creating a custom Kindle dictionary](https://jakemccrary.com/blog/2020/11/11/creating-a-custom-kindle-dictionary/)
His summary is as follows:
1) Construct your list of words and definitions. (I used ankipandas to import the anki deck's data)
2) Convert the list into the format specified by Amazon.
3) Create a cover page.
4) Create a copyright page.
5) Create a usage page (definitely optional).
6) Make an .opf file.
7) Combine the files together.
8) Put it onto your device.

References:
- Kanji Koohi: All kanji mnemonics provided in this repository are licensed under CC BY-NC-SA 3.0 (Attribution-NonCommercial-ShareAlike 3.0 Unported)
- How to Create a Kindle Dictionary: Jake McCrary https://jakemccrary.com/blog/2020/11/11/creating-a-custom-kindle-dictionary/
- Anki "Heisig's RTK 6th Edition- Stories, Stroke diagrams, Readings" Deck used to mine data
- Anki Pandas used to mine anki deck
