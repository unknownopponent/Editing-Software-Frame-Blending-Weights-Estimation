# Premiere Pro Estimation

Estimations made on version 2019. The option used to blend frames is interpolation in export tab. Note that Premiere does not blend frames after 1000fps. Note that interpolation does not only blend frames, it adds a transparency effect on moving pixels.

Input framerate | Number of frames blended | Weights
--- | --- | ---
120 | 2 | 1 1
180 | 4 | 13 18 13 5
240 | 5 | 9 13 13 9 5
300 | 6 | 7 10 11 10 7 4
360 | 7 | 6 8 9 9 8 6 4
420 | 8 | 5 6 8 8 8 6 5 3
480 | 9 | 3 4 5 6 7 7 6 5 4
540 | 10 | 3 4 5 6 6 6 6 6 5 4
600 | 10 | 4 4 5 6 6 6 6 5 4 4
660 | 10 | 4 5 5 6 6 6 5 5 4 3
720 | 10 | 4 5 5 5 6 6 5 5 5 4
780 | 10 | 4 5 5 6 6 6 5 5 4 4
840 | 10 | 4 5 5 5 6 6 5 5 5 4
900 | 10 | 4 5 5 5 5 5 5 5 5 5
960 | 10 | 4 5 5 5 5 5 5 5 5 4
1020 | 1 | 1
