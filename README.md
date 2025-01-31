# treesegmented
The effect of stem and root-plate defects on the tree response during static loading – Numerical analysis 
Macros in MECHANICAL APDL (ANSYS PARAMETRIC DESIGN LANGUAGE), Ansys Academic Research Mechanical, v. 18.0, ANSYS, Inc.

Link to publication (please cite): 
> ## Vojáčková, B., Tippner, J., Horáček, P., Sebera, V., Praus, L., Mařík, R., Brabec, M., 2021. The effect of stem and root-plate defects on the tree response during static loading—Numerical analysis. Urban For. Urban Green. 59, 1–13. https://doi.org/10.1016/j.ufug.2021.127002

Work was supported by the Ministry of Education Youth nad Sports in the Czech Republic grant No. LL1909, ERC CZ.

### Main file
* `strom.mac` creation of segmented tree stem and composite root-plate

### Input files: 
* `mat_korsys.mac` material properties of root-plate
* `mat_kmen.mac` material properties of stem
* `koef_mat.mac` matrix for reduction of material properties in segments
* `DIC_0.mac` position of markers along the stem

 <br>

* `post_inklino.mac` postprocessing of results - stem base inclination
* `post_extenzo.mac` postprocessing of results - stem strains
* `post_dic.mac` postprocessing of results - displacements

<br>

* `resul.mac` write results into tables

# Sensitivity analysis: 
* `strom_pds.mac` run sensitivity analysis by Probabilistic Design System with generation of random input values by Monte Carlo method.

