# Doughnut potential: the films

Four runs of RFdiffusion3 guided by the Doughnut potential, filmed step by step. They are the films behind the QR code on the poster *The Doughnut Potential: Guiding RFdiffusion Towards Open-Pore Protein Ring Design*.

Open <https://jmacnar.github.io/doughnut_movies/>, or play the files here.

| file | chain length | r0 |
|---|---|---|
| `c2_200_r15.mp4` | 200 residues, C2 | 15 Å |
| `c2_200_r20.mp4` | 200 residues, C2 | 20 Å |
| `c2_500_r25.mp4` | 500 residues, C2 | 25 Å |
| `c2_500_r35.mp4` | 500 residues, C2 | 35 Å |

What is in a film:

- RFdiffusion3 builds the backbone over 200 steps, out of noise.
- The potential pushes every atom towards a circle of radius r0 on the symmetry axis, so whatever is inside gets pushed out.
- It is on from step 0 to step 158 and off after that. RFdiffusion3 finishes the ring on its own.
- Four panels per film, differing only in the weight of the potential: 20, 30, 40, 50.
- Top row looks down the symmetry axis, middle row from the side, trace below for when the push is on, dashed circle at r0.
- Each panel animates the most typical backbone that passed the shape filter, and says how many passed.
- 1440 x 850, 108 frames, 13.5 s per film.

Joanna M. Macnar, Kevin O'Brien, Alena Khmelinskaia
Department of Chemistry, Ludwig-Maximilians-Universität München
joanna.macnar@lmu.de
