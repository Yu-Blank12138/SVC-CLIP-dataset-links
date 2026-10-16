# SVC-CLIP dataset access links

This repository indexes the 14 target datasets named in the SVC-CLIP Image and Vision Computing manuscript (`04_experiments.tex`, checked on 2026-10-16). VisA and MVTec AD also serve as auxiliary training sources in the reciprocal evaluation protocol. The links point to dataset providers or original project pages; no images, annotations, or experimental results are hosted here.

Some providers require a form, account, or data-use agreement. Follow the terms on each provider's page before downloading or redistributing data. A link here does not grant redistribution rights. File downloads and the exact local dataset versions used in the experiments have not yet been independently verified.

## Industrial datasets

| Dataset | Provider or original project | Download or access | Access note |
| --- | --- | --- | --- |
| MVTec AD | [MVTec dataset page](https://www.mvtec.com/research-teaching/datasets/mvtec-ad) | Download through the form on the provider page | Also used as the auxiliary training source when VisA is the target. |
| VisA | [Amazon Science project](https://github.com/amazon-science/spot-diff) and [AWS Open Data record](https://registry.opendata.aws/visa/) | [Provider-hosted archive](https://amazon-visual-anomaly.s3.us-west-2.amazonaws.com/VisA_20220922.tar) | Used as the auxiliary training source for targets other than VisA. |
| MPDD | [Dataset authors' repository](https://github.com/stepanje/MPDD) | Download from the link in the authors' README | The download is hosted outside GitHub. |
| BTAD | [VT-ADL authors' repository](https://github.com/pankajmishra000/VT-ADL) | [Authors' dataset archive](https://avires.dimi.uniud.it/papers/btad/btad.zip) | The authors' README identifies this archive as the BTAD download. |
| DAGM 2007 | [Heidelberg HCI dataset record](https://zenodo.org/records/8086136) | Download from the Zenodo record | Record DOI: [10.5281/zenodo.8086136](https://doi.org/10.5281/zenodo.8086136). |
| DTD-Synthetic | [Original WACV paper record](https://mlanthology.org/wacv/2023/aota2023wacv-zeroshot/) | [Code and data folder linked by the paper](https://drive.google.com/drive/folders/10OyPzvI3H6llCZBxKxFlKWt1Pw1tkMK1) | DTD-Synthetic is the anomaly dataset, not the plain DTD texture archive. |

## Medical datasets

| Dataset | Provider or original project | Download or access | Access note |
| --- | --- | --- | --- |
| Br35H | [Dataset uploader's Kaggle page](https://www.kaggle.com/datasets/ahmedhamada0/brain-tumor-detection) | Download from Kaggle | Underlying image provenance and redistribution permission remain to be verified. |
| HeadCT | [Dataset uploader's Kaggle page](https://www.kaggle.com/datasets/felipekitamura/head-ct-hemorrhage) | Download from Kaggle | Underlying image provenance and redistribution permission remain to be verified. |
| BrainMRI | [Dataset uploader's Kaggle page](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection) | Download from Kaggle | Underlying image provenance and redistribution permission remain to be verified. |
| EndoTect2020 | [Challenge organizers' repository](https://github.com/simula/icpr-endotect-2020) | [Development dataset on OSF](https://osf.io/mh9sj/) | The organizers' repository links to the OSF dataset. |
| CVC-ClinicDB | [CVC provider's database index](https://pages.cvc.uab.es/CVC-Colon/index.php/databases/) | [Challenge download page listed by CVC](https://polyp.grand-challenge.org/CVCClinicDB/) | Check the [CVC data-use agreement](https://pages.cvc.uab.es/ai4polypnet/wp-content/uploads/2024/05/AgreementData_CVC-1.pdf) and current access route. Direct download was not independently confirmed. |
| CVC-ColonDB | [CVC provider's database index](https://pages.cvc.uab.es/CVC-Colon/index.php/databases/) | Use the provider index and its access instructions | The older download URL listed by CVC could not be independently reached; check the [CVC data-use agreement](https://pages.cvc.uab.es/ai4polypnet/wp-content/uploads/2024/05/AgreementData_CVC-1.pdf). |
| Kvasir-SEG | [Simula dataset page](https://datasets.simula.no/kvasir-seg/) | [Provider-hosted archive](https://datasets.simula.no/downloads/kvasir-seg.zip) | Use the Kvasir-SEG archive, not the broader Kvasir dataset. |
| Retina-OCT (Kermany OCT2017) | [Kermany et al. Mendeley Data record, version 3](https://data.mendeley.com/datasets/rscbjbr9sj/3) | Download the OCT files from the record | The manuscript cites Kermany et al.; the project labels its local dataset `Retina_OCT2017`. The exact downloaded version and local preprocessing still need confirmation. |

## Contextual benchmark mentioned in the manuscript

[BMAD](https://github.com/DorisBao/BMAD) is cited as medical-anomaly benchmarking context. It is not counted as a fifteenth target dataset in the manuscript. The BMAD repository links to its component datasets and preprocessing protocol.

## Scope and remaining verification

- This index covers only the datasets named in the current manuscript, not every dataset supported by the project's code.
- The manuscript's precise experimental splits, preprocessing, local file versions, and results should be documented separately after they have been checked against the actual experiment records.
- Third-party dataset files are intentionally absent from this repository.
