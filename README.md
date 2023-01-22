# Game of Life on Penrose Tiling: Robinson Triangle

*Last Updated*: Jan. 21. 2023

*Author*: Seung Hyeon Mandy Hong

*Denison University, Department of Mathematics, year-long research project*

This is my year-long senior research working with Dr. May Mei in the department of Mathematics at Denison University. All codes in this repository is publicly available but please cite when using them.

# Description
John Horton Conway’s Game of Life gained much attention in different areas because of the concept that it generates complexity from simplicity. If we are given three simple rules: survival, death, and birth, and initial configuration, we can play Game of Life. Compared to the simple setting of this game, what we get is more complex. Generally, Game of Life is played on the regular square tiling, a periodic tiling. However, we implement Game of Life on an aperiodic tiling, specifically on the Robinson Triangle tiling, a variation of the Penrose tiling. We use an emerging programming language called Julia. We show patterns, still life and oscillator, discovered when playing Game of Life on Robinson Triangle tiling and classified four-cell still life in Robinson triangle tiling.

# Software
I used **Julia** to create algorithms that generate aperiodic tiling, simulate Game of Life on Penrose tiling, get graphics and animations, and classify all valid four-cell configurations that satisfy still life conditions.

## Research Prepartion (Jan. 2022 - May. 2022)
1. Wrote and developed research proposal.
2. Applied and received Anderson summer research scholarship.
3. Took *MATH 471 The Mathematics of Tiling* to learn about the research topic.

## Anderson Summer Research (May. 2022 - Jul. 2022)
1. *Game of Life on Robinson Triangle Tiling (section 4).ipynb*: Created an algorithm to play Game of Life on the Robinson triangle tiling using the progamming language *Julia*.
2. *Summer research paper.pdf*: Wrote a paper with description of the Game of Life algorithm.
3. *summer research poster_final.pdf*: Made a research poster and presented the work at the Denison summer research symposium.

## Senior Research (Aug. 2022 - Jan. 2023)
1. *Finding Four-Cell Still Life (scenario 1, section 7.1).ipynb*: Created the first algorithm to find all valid four-cell still life in distinct neighborhoods in the Robinson triangle tiling. This algorithm identifies four-cell still life where the center cell of the neighborhood is alive with three alive neighbors.
2. *Finding Four-Cell Still Life (scenario 2, section 7.2).ipynb*:  Created the second algorithm to find all valid four-cell still life in distinct neighborhoods in the Robinson triangle tiling. This algorithm identifies four-cell still life where the center cell of the neighborhood is dead with four alive neighbors.
3. Classified all four-cell still life into 31 categories using different labels.

## Research Presentation at Joint Mathematics Meetings 2023
Presented the research result at Pi Mu Epsilon contributed session on research by undergraduate session in Joint Mathematics Meeting 2023 at Boston.
