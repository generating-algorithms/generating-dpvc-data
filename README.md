Automated Generation of Faster Algorithms for d-Path Vertex Cover - Data
------------------------------------------------------------------------

The repository is about 800MB in size.
It contains several folders, each containing the proof, the proof_export, and the proof_visualization.

An example of one folder and its contents:

```
5_3.0742_20:
5_3.0742_20.proof_export  5_3.0742_20.proof.out.gz  5_3.0742_20.proof_visualization.tar.xz
```

The proof visualizations are compressed due to their large size. In order to uncompress them, you can use the following command:
`tar -xJf 5_3.0742_20.proof_visualization.tar.xz`

Please, be mindful, that the uncompressed version of the visualizations are quite large:

```
2.3M    2_1.3943_20.proof_visualization
1.6G    3_1.8107_20.proof_visualization
3.9G    4_2.3840_20.proof_visualization
3.6G    5_3.0742_20.proof_visualization
9.2G    6_3.9538_20.proof_visualization
5.8G    7_5.1916_20.proof_visualization
```

Description
-----------
For a comprehensive description of the format, see Section 7 of https://arxiv.org/pdf/2111.05896.pdf .

To see how these files were generated and to see how to verify them, see https://github.com/generating-algorithms/generating-dpvc .
