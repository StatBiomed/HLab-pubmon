# HLab-pubmon
Publication monitoring at Huang Lab


## Simplified Archive with markdown (version 2)

> Just making life simple: add the reference, in anyformat you like; you may use `>` for blockquote.

* [Y2024.md](Y2024.md)
* [Y2025.md](Y2025.md)
* [Y2026.md](Y2026.md)




## Below is for version 1 (outdated)

### How to use
1. Pick [a few journals](https://hlab-pubmon.readthedocs.io/en/latest/#journal-list), 
   e.g., 3 that you are interested in and found papers that may be interesting 
   to some of us in the lab.
2. Keep them in [bib format](https://en.wikipedia.org/wiki/BibTeX), which you 
   can get easily from the journal or Google scholar -> cite -> BibTex
3. Modify the .bib file for our meeting, e.g., [bibs/m2020-09-07.bib](https://github.com/StatBiomed/HLab-pubmon/tree/master/bibs/m2020-09-07.bib) for next
   meeting.
4. Possibly add the meeting .bib file to the [docs/Pub2021-22.rst](https://github.com/StatBiomed/HLab-pubmon/tree/master/docs/Pub2021-22.rst) if no one has done 
   (only need to be done once, not everyone).

Done! Hopefully readthedocs will build automatically, and you can find it at https://hlab-pubmon.readthedocs.io

### Troubleshooting
If you are not sure the readthedocs will build auotmatically, you can check it in your local environment first with the following two steps
* Activate a conda environment with the required packages listed in 
  [docs/requirements.txt](https://github.com/StatBiomed/HLab-pubmon/blob/master/docs/requirements.txt):
* Go to the ``docs`` folder in terminal and type ``make html`` and see if any error exists


**Note:** Please pull before your commit, as other people may edit it in the same
time. You may consider edit the bib file on web directly.
