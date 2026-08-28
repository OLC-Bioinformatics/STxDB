# Database Notes

## Notes

### Novel Alleles

FASTA headers were renamed to indicate novel allele identification by **StxTyper**. Subtypes are marked as `Novel` or, if closely related to a known type, appended with `_like` (e.g., `stx2f_like`).

### Partial Alleles

FASTA headers were renamed to indicate partial allele identification by **StxTyper**. These alleles show **>99% identity** to known subtypes but differ at the C-terminus. They are appended with `_part` according to their closest match (e.g., `stx1a_part`).

### Removed Entry

`StxOp4769_Stx2_1353` was removed because raw-read analysis indicates that it is an assembly artifact.

## FASTA Headers and Stx Profiles

| FASTA Header                | Operon Sequence ID | Toxin Type | Stx Profile       |
| --------------------------- | -----------------: | ---------- | ----------------- |
| `StxOp58_Stx1a_like_76`     |                 58 | Stx1       | `Stx1a_like_76`   |
| `StxOp401_Stx1c_part_23`    |                401 | Stx1       | `Stx1c_part_23`   |
| `StxOp598_Stx2_novel_621`   |                598 | Stx2       | `Stx2_novel_621`  |
| `StxOp650_Stx2acd_304`      |                650 | Stx2       | `Stx2acd_304`     |
| `StxOp823_Stx2c_part_714`   |                823 | Stx2       | `Stx2c_part_714`  |
| `StxOp862_Stx2d_part_275`   |                862 | Stx2       | `Stx2d_part_275`  |
| `StxOp949_Stx2m_like_547`   |                949 | Stx2       | `Stx2m_like_547`  |
| `StxOp1460_Stx2c_part_286`  |               1460 | Stx2       | `Stx2c_part_286`  |
| `StxOp3259_Stx2acd_1025`    |               3259 | Stx2       | `Stx2acd_1025`    |
| `StxOp4114_Stx2c_part_286`  |               4114 | Stx2       | `Stx2c_part_286`  |
| `StxOp4754_Stx1c_part_708`  |               4754 | Stx1       | `Stx1c_part_708`  |
| `StxOp4757_Stx1a_part_705`  |               4757 | Stx1       | `Stx1a_part_705`  |
| `StxOp4759_Stx2f_like_1343` |               4759 | Stx2       | `Stx2f_like_1343` |
| `StxOp4761_Stx2l_like_1345` |               4761 | Stx2       | `Stx2l_like_1345` |
| `StxOp4764_Stx2f_like_1348` |               4764 | Stx2       | `Stx2f_like_1348` |
| `StxOp4765_Stx2f_1349`      |               4765 | Stx2       | `Stx2f_like_1349` |
| `StxOp4768_Stx2o_like_1352` |               4768 | Stx2       | `Stx2o_like_1352` |
