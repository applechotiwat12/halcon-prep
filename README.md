# halcon-prep
Blob inspection pipeline in Python, mapped to HALCON operators
# Machine Vision Prep — Blob Inspection

Python implementation of a classic HALCON blob analysis pipeline,
built to understand region-based machine vision concepts.

**Pipeline:** read_image → threshold → connection → select_shape → measure

- Each step is commented with its HALCON operator equivalent
- Found and fixed a merged-blob problem (uneven background) using
  border clearing + area filtering; local/adaptive threshold as root-cause fix
<img width="1500" height="500" alt="blob_result" src="https://github.com/user-attachments/assets/d519a8f4-f3a2-40ed-af45-1389e001b718" />
*Stack: NumPy, scikit-image, Matplotlib*
