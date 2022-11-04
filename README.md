# Summary

A Universal Dependencies corpus for Zaar (aka Sayanci), a member of the Chadic branch of the Afro-Asiatic phylum. The language is mainly spoken by about 200,000 speakers in the Bogoro and Tafawa Balewa local governments of Bauchi State, Nigeria.

# Introduction

The treebank is an automatic conversion of the SUD_Zaar-Autogramm <b>[TODO: ajouter lien]</b> , which was extracted from Bernard Caron's corpus in Elan format (https://corpafroas.huma-num.fr/Archives/corpus.php).

Sentences are annotated with the following metadata :

    - sent_id (which indicates the source file and the segmentation identifier in the source file)
    - speaker_id (which identifies the audio file on the server playing the audio recording)
    - sound_url (which enables playback of the audio recording)
    - seṅt_timecode (which enables playback of the sentence)
    - text (lexical tokenization)
    - text_ortho (original transcription of the audio recording)
    - text_en (English interpretation)
  

# Structure

This version of the treebank is a dependency parsing of the original corpus first three files. 

The original data are spoken data, which were originally segmented in interpausal units, and interlinearized, translated and glossed in Elan. For the syntactic treebank, a re-alignment was done using the illocutionary unit as a sentence. Tokens comprize words and affixes (preceded by a "=" sign) when those bear a syntactic function. Punctuation tokens (e.g. <, >, //, etc.) organise the illocutionary unit into: pre-nucleus < nucleus > post-nucleus //.

The UD Zaar treebank counts 8441 tokens for 817 sentences.


# Reference

Bernard Caron. Zaar Grammatical Sketch. 2015. ⟨halshs-00647526v3⟩

# Acknowledgments

This treebank was produced as part of the Autogramm CNRS project. With special thanks to Bruno Guillaume for the conversion from SUD to UD, Sylvain Kahane and Christian Chanard. A special tribute must be paid to Marvellous S. Davan, who transcribed and translated the Zaar Corpus, and met an untimely death in Bauchi at the age of 40. 

# Changelog

* 2022-11-15 v2.11
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.11
License: CC BY-SA 4.0
Includes text: yes
Genre: grammar-examples
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Kahane, Sylvain; Guillaume, Bruno; Caron, Bernard; Jiang, Katharine
Contributing: here
Contact: bruno.guillaume@inria.fr
===============================================================================
</pre>
