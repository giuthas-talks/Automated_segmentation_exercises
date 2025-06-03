# Automated Segmentation Exercises with PATKIT

Talk at Queen Margaret University, Glasgow University and University of Lancaster in June 2025.

The slides are listed above as slides.pdf or you can follow one of these links:

- Slides at QMU on 2nd June [link [pdf]](slides_qmu.pdf)
- Current version [link [pdf]](slides.pdf)

[There will be instructions here for running the demo once it works.]

## Abstract

One of the major hurdles in phonetics is that we need to segment a lot of data.
This is true even with forced alignment and AI tools as they need good training
data in order to be reliable. With the limited time any of us can spend on
segmentation, it would be helpful to expand the pool of experts. Unfortunately,
it takes time to train a good segmenter and the teaching takes considerable
effort on the part of the teacher. This is a problem that I’m attempting to
address with some new tools.

The Phonetic Analysis ToolKIT (PATKIT, formerly SATKIT) is a set of free, open
source programs and tools for analysis of various kinds of phonetic data.
PATKIT is written in Python for ease of programming and access.  Python is a
very approachable programming language even for non-programmers and comes with
a truly huge selection of libraries.

Besides analysis automated analysis tools, PATKIT has an annotation interface.
By time of the talk, the annotation interface will copy the core functionality
of Praat’s TextGrid manipulation interface. There will also be a novel exercise
functionality in PATKIT. This will turn any set of TextGrids and accompanying
audio files into an automated, resettable segmentation exercise. When asked to,
PATKIT will scramble the boundaries in a given Tier of the TextGrids and then
let the user move the boundaries and check how well they did. And repeat the
process as many times as they like.

## Copyright

(c) Pertti Palo 2025 CC-by-nc-sa - see [License](LICENSE.md) for terms for
using my content and slides for references to images used under academic fair
use.
