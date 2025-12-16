# Visualisation and Analysis of scRNA-seq of Human Cerebral Organoids and Fetal Brains

### Background

Brain organoids are 3D tissues that are cultured from stem cells _in vitro_, which act as ‘mini organs’, replicating brain functions in a dish. This new technology is incredibly useful in a variety of applications, as it allows greater isolation and manipulation of brain structures without causing harm to patients or animals. However, due to the vast differences in conditions where organoids and embryos are grown, they have some biological differences which are not fully characterized. Understanding the differences between fetal brains and brain organoids is important in improving the translational applications of organoid-based research. In Camp _et al._ 2015, the authors highlighted some of the developmental similarities and differences between fetal brains and cortical organoids using single cell RNA sequencing (scRNA-seq) of both sample types at different timing, showing the remarkable ability of cortical organoids to recapitulate key developmental stages in the fetal brain. 

### Project Aim
Here, the data from Camp _et al._ 2015 was re-analysed to focus on the developmental timing of organoids, and whether the transcriptome can discern the age of an organoid using modelling. Furthermore, the model was applied to fetal transcriptomes to see if there are parallels in developmental timing, and whether specific fetal ages have an organoid equivalent, helping to understand what organoid age is best for modelling specific fetal development stages. The code also includes visualisation via volcano plot and UMAP plot, and relevant visualisation of important features. This software is designed to aid in assessing developmental delays in organoid models of disease.

## Getting Started

### Dependencies

* Python ≥ 3.12.12
* Jupyter lab (V4.5.0)

Packages:
* NumPy (V2.3.5)
* Pandas (V2.3.3)
* SciPy (V1.16.3)
* scikit-learn (V1.7.2)
* Matplotlib (V3.10.7)
* Seaborn (V0.13.2)
* statsmodels(V0.14.6)
* UMAP (V0.5.9.post2)

This code should run independently of the operating system used. 

### Installing
Packages can be installed using the following:
```
pip install numpy pandas scipy scikit-learn matplotlib seaborn statsmodels umap
```
The zip file containing the code and necessary data files is located here on Github. 

### Executing program

Open code as a jupyter notebook and run all blocks in order. 

The code is designed to set the working directory to where the data is contained. Please make sure that the notebook and the data file are located in the same folder before running.

The input dataset is modified from Camp _et al._ 2015 to be compatible with Python. This has been provided as a compressed CSV (`.csv.gz`) to comply with GitHub file size limits. Pandas should handle decompression when loading the file.

## Help

If the programme is not running correctly, check that relevant dependencies have been installed in the same directory and that the specified versions have been adhered to. Else, see package documentation or contact the author (jonesa269@cardiff.ac.uk).

## Authors

Amy Jones
* email: jonesa269@cardiff.ac.uk

## Version History

* 0.1
    * Initial Release

## License

This project is licensed under the MIT License - see the LICENSE.txt file for details.

This project uses third-party Python packages released under permissive open-source licences. See individual package documentation for details.

## Acknowledgments

I would like to thank Raven Huilberts, Krishna Kerai, Amelia Francis, Chris Slack, Fiona Sobolewski-Bravo, and Lilia Smith for helpful discussions, guidance, and debugging advice on this project. 

## References

Camp, J. G. et al. Human cerebral organoids recapitulate gene expression programs of fetal neocortex development. Proc. Natl. Acad. Sci. 112, 15672–15677 (2015).
