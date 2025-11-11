---
title: "STFT-GradTTS: A Robust, Diffusion-based Speech Synthesis System with iSTFT decoder for Bangla"
collection: publications
category: manuscripts
# permalink: /publication/bntts
excerpt: 'This project involved building a large Text to Speech dataset and model for Bangla, which was funded by the University Grants Commission. The paper is current under review'
# date: 2009-10-01
# venue: 'International Journal of Speech Technology'
venue: 'Under Review'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'http://academicpages.github.io/files/btts_speech_technology anonymized-2.pdf'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Text-to-speech (TTS) synthesis is a critical area in speech and language processing, with extensive applications in assistive technologies, virtual assistants, and automated content generation. Despite Bangla being the seventh most spoken language globally, high-quality TTS datasets remain scarce, limiting advancements in Bangla speech synthesis. To bridge this gap, we introduce a meticulously curated single-speaker Bangla audio dataset comprising over 20 hours of clean speech. Our dataset ensures diverse linguistic coverage, incorporating compound letters, long vowels, Sanskrit words, and varied sentence structures while maintaining phonetic balance.

In addition to the dataset, we propose STFT-GradTTS, a novel diffusion-based TTS model featuring a Multi-Stream iSTFT decoder and a Stochastic Duration Predictor (SDP). The iSTFT-based decoder synthesizes high-fidelity waveforms by decomposing signals into sub-bands using learnable synthesis filters, enhancing spectral clarity. The SDP models phoneme duration distributions, capturing the natural variability in speech pacing. Together, these innovations address key limitations of GradTTS, particularly in duration accuracy and audio naturalness.

We validate our approach through blind subjective & objective evaluations and demostrate STFT-GradTTS significantly outperforms the baseline models in speech quality, naturalness, and duration modeling. Our work not only establishes a new benchmark for Bangla Text-to-Speech (TTS) systems but also provides a solid foundation for future research in low-resource language speech synthesis. The code is publicly available in https://github.com/mushahid-intesum/STFT-GradTTS.
