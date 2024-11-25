# Application of machine learning methods to forecast petrophysical properties in basalts of the Serra Geral Group: Implications for carbon storage

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13821458.svg)](https://doi.org/10.5281/zenodo.13821458)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

**Authors:**
<a href="https://orcid.org/0000-0002-1787-2206"> <img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /></a> João Paulo G. R. Alves <sup>a</sup>, <a href="https://orcid.org/0000-0002-7249-5706"> <img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /></a> Claudio Riccomini <sup>a,b</sup>

<sup>a</sup> *Institute of Energy and Environment, University of São Paulo (IEE-USP), São Paulo, 05508-010, Brazil*

<sup>b</sup> *Institute of Geosciences, University of São Paulo (IGc-USP), São Paulo, 05508-080, Brazil*

## About

*This paper has been submitted to the journal *Applied Computing and Geosciences* for peer review. Included in this directory are the Jupyter notebooks and associated data required to replicate the results.

**Title:** Application of machine learning methods to forecast petrophysical properties in basalts of the Serra Geral Group: Implications for carbon storage

**Preprint:** https://doi.org/10.31223/X5ZM6K

**Final paper:** http://doi.org/---


## Abstract

This study applies machine learning techniques to forecast petrophysical properties (density, porosity, and permeability) in the basalts of the Serra Geral Group, located in the Paraná Basin, Brazil. These properties are crucial for the successful implementation of carbon capture and storage (CCS), an important technology to combat climate change. Employing machine learning models—XGBoost, Gradient Boosting, and Random Forest—the research aims to overcome the limitations of traditional empirical methods that often fail to capture the complex variabilities in basalt formations. The models were applied to 28 wells within the study area. The interpolation of the well data indicated that the northern region of the Serra Geral Group in the State of Santa Catarina exhibits optimal conditions for geological storage. From 600 to 900 m, the basalts present suitable intervals ranging from 7 to 22 m thick, with density lows of almost 2.1 g/cm³, high peaks of 17.8% apparent porosity, and permeability of 55 $$\mu D$$. The results demonstrated significant improvements in accuracy of property predictions compared to empirical methods from the literature, highlighting the potential of machine learning to enhance the feasibility and reliability of CCS in basaltic formations. This study contributes to the ongoing efforts to optimize CCS technology by providing a more accurate geological assessment of suitable storage sites.


## Content

* [DensityModel](DensityModel) - Contains the data and the Jupyter notebook for density model (XGBoost) - (python 3 kernel, dated 2024-09)

* [PorosityModel](PorosityModel) - Contains the data and the Jupyter notebook for porosity model (Gradient Boosting) - (python 3 kernel, dated 2024-09)

* [PermeabilityModel](PermeabilityModel) - Contains the data and the Jupyter notebook for permeability model (Random Forest) - (python 3 kernel, dated 2024-09)

* [WellLogs_Data](WellLogs_Data) - Contains the data necessary to generate the interepolated maps and the Jupyter notebook to generate the section plot - (python 3 kernel, dated 2024-09)

* [Maps](Maps) - Contains the data (.tif, .cpt, .gpkg) and the Jupyter notebook necessary to generate the loaction and interpolated maps - python 3 kernel, dated 2024-09)

* [TestData](TestData) - Contains the test datasets to compare with empirical equations (dated 2024-09)


## Results
The key outputs of running the notebooks include:

- Interpolated maps identifying suitable regions for carbon storage in the State of Santa Catarina, Brazil.
- Well log profiles from 600 to 900 m, highlighting suitable sections for use as reservoir and cap rock.
- Prediction models for density, porosity, and permeability in basaltic rocks, including evaluation metrics such as RMSE, MAE, and R<sup>2</sup>.
- A comparison of the performance of machine learning prediction models against traditional empirical equations.


## Original references used to generate the datasets

- Famelli, N. (2020). *Associação de litofácies, interação lava-sedimento e caracterização sísmica do magmatismo Serra Geral na região de Uberlândia e Araguari (MG)*. [Doctoral Thesis, Universidade Federal do Rio Grande do Sul]. Available at: http://hdl.handle.net/10183/223773

- Goulart, D. (2019). *Análise e correlação de propriedades físicas e mecânicas de rochas da Formação Botucatu e Grupo Serra Geral*. [Undergraduate Thesis, Universidade Federal de Santa Catarina]. Available at: https://repositorio.ufsc.br/handle/123456789/204071

- Rossetti, L. M., Healy, D., Hole, M. J., Millett, J. M., de Lima, E. F., Jerram, D. A., & Rossetti, M. M. M. (2019). *Evaluating petrophysical properties of volcano-sedimentary sequences: A case study in the Paraná-Etendeka Large Igneous Province*. Marine and Petroleum Geology, 102, 638–656. https://doi.org/10.1016/j.marpetgeo.2019.01.028

- ANP-SGB. (2023, October 22). *Programa de Revitalização da Atividade de Exploração e Produção de Petróleo e Gás Natural em Áreas Terrestres*. Available at: https://reate.cprm.gov.br/anp/TERRESTRE



## Getting the code

You can download a copy of all the files in this repository by cloning the
[git](https://git-scm.com/) repository:

    git clone https://github.com/jp-alves/ml_basalts_ccs.git

or [download a zip archive](https://github.com/jp-alves/ml_basalts_ccs/archive/master.zip).

After downloading, you can install the required dependencies with:

    pip install -r requirements.txt


## License

All source code is made available under a MIT license. You can freely use 
and modify the code, without warranty, so long as you provide attribution
to the authors. See 'LICENSE.md' for the full license text.

The manuscript is avaliable under CC-BY-4.0 license. The authors reserve the rights to the 
article content, which is currently submitted to the journal *Applied Computing and Geosciences* 
for peer review.


## Contact

For any questions or inquiries, please contact:
João Paulo G. R. Alves - [email](mailto:joao.guilherme.alves@usp.br)

