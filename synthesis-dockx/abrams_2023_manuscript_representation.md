# Towards More Effective Spatio-Temporal Schemes for Remediation of Agricultural Soils in Response to Large-Scale Contamination with Radionuclides

## Citation Information
**Full citation**: Abrams, F. (2023). Towards More Effective Spatio-Temporal Schemes for Remediation of Agricultural Soils in Response to Large-Scale Contamination with Radionuclides [Doctoral dissertation, KU Leuven]. Doctoraatsproefschrift nr. 1909.

**Inline citation**: (Abrams, 2023)

**Note**: This is a PhD thesis, not a single research paper. This representation focuses on the overall work while highlighting key methodologies and findings across chapters.

## Abstract/Summary

Although nuclear energy can be categorized as a safe and low-carbon energy source, two major accidents (Chornobyl, 1986, and Fukushima, 2011) demonstrated the large-scale impact it may have. While immediate response plans to nuclear accidents are well established, the complex and resource-intensive recovery phase lacks adequate (inter)national guidance and tools. The recovery is especially important for agricultural areas, where food production needs to be returned to normalcy. This research contributes to the development of tools within a spatial decision support system (sDSS) to improve the post-accident decision-making process about where, how, and when to remediate agricultural land.

This research illustrates the tools in two agricultural watersheds: the Maarkebeek, located in Flanders (Belgium), and the Niida watershed, located in the Fukushima prefecture (Japan). At the basis of the sDSS was a multi-criteria decision-aiding methodology (MCDA), which was found to be a good framework for supporting soil remediation on a local scale through optimal remedial technology selection for a specific site and on a regional scale through optimal site selection. However, we identified four major gaps in the reviewed case studies: (i) A lack of inclusion of social criteria, (ii) A lack of early stakeholder engagement, (iii) A mismatch between weighting and aggregation methodologies, and (iv) A lack of sensitivity analysis.

To overcome (i) and (iv), a methodology to include linguistic scoring within ordinal qualitative scales as fuzzy numbers, for the evaluation of criteria or weight setting was proposed. The impact of an increasing amount of uncertainty within the triangular fuzzy numbers (TFN) was studied, and it became clear that the impact of uncertainty on decision-making power cannot be ignored. Proposing remedial plans using two compromise programming methodologies for site selection and action selection results in a very complex spatial pattern for remediation. The clustering of individual entities into larger, homogeneous, actionable units can improve feasibility and reduce the cost of remediation, especially when interventions are costly and technically challenging to perform. A spatio-temporal clustering approach under a budget constraint was presented to determine homogenous clusters of polygons and interventions to reduce the cost of intervention while still attaining near-optimal effectiveness.

When remedial actions are converted into remediation trajectories, a sequence of multiple remedial actions in time is explicitly considered within the decision-making. A column generation model was proposed that reconciles the economic and productive aspects of remediation for agricultural areas. The model's main novelty is its ability to find optimal multi-period sequences or trajectories of remedial actions from a set of predefined remedial actions, where column generation is used to extend the candidate set of the remedial trajectories while keeping the computational complexity limited. It was found that the introduction of new trajectories with the column generation approach, after 4700 iterations, reduced the loss in productive years by 237 years and the accumulated productivity score by 20%.

An iterative framework called the CAMF approach (Cellular Automata-Based Heuristic for Minimizing Flow) was used to model and reduce the off-site impacts of soil remediation in the Niida watershed. Spatially targeted afforestation of the 1000 best cells reduces the sediment quantity resulting from the decontamination work by 15.4%, compared to 0.8% when the cells are selected randomly. Prioritizing topsoil removal interventions within the Maarkebeek watershed while accounting exclusively for off-site criteria results in a 267% increase in Cs-137 flux reduction efficiency in the first year when compared to remedial schemes based only on on-site criteria.

## Study Areas

- **Maarkebeek watershed**: Located in Flanders, Belgium - used for demonstrating spatio-temporal clustering, column generation approaches, and off-site criteria integration
- **Niida watershed**: Located in Fukushima prefecture, Japan - used for demonstrating CAMF approach for minimizing sediment flux from decontaminated areas

## Chapter 2: Multi-criteria Decision Analysis Review - Key Takeaways

- **Systematic review of MCDA applications**: Comprehensive review of 41 case studies examining how multi-criteria decision analysis supports remediation of polluted soils
- **Framework appropriateness**: MCDA found to be suitable framework for both local-scale (optimal technology selection) and regional-scale (optimal site selection) soil remediation decisions
- **Four critical gaps identified**: (i) lack of social criteria inclusion, (ii) insufficient early stakeholder engagement, (iii) mismatches between weighting and aggregation methods, (iv) inadequate sensitivity analysis
- **Criteria patterns**: Analysis revealed most frequently used criteria across economic, social, technical, environmental, and human health dimensions **(detailed in Tables 2-2 through 2-6)**
- **Technology frequency analysis**: Documented relative frequency of different remedial technologies in case studies **(Table 2-7)**

## Chapter 3: Fuzzy MCDM Methodology - Key Takeaways

- **Triangular Fuzzy Numbers (TFN) approach**: Methodology developed to incorporate linguistic scoring and uncertainty into MCDA for agricultural land remediation after radioactive contamination
- **Uncertainty quantification**: Study examined impact of increasing uncertainty in TFNs combined with Monte Carlo simulation, demonstrating that uncertainty significantly affects decision-making power and cannot be ignored
- **Case study application**: Applied to selection of optimal remediation technology for Cs-137 contaminated cereal field near Tihange nuclear facility
- **Linguistic variable framework**: Five remedial countermeasures evaluated using linguistic scales (Low, Medium, Medium-High, High, Very High) converted to fuzzy numbers **(Tables 3-1, 3-2)**
- **Criteria evaluation**: Technologies assessed on multiple criteria including effectiveness, cost, and implementation factors **(Tables 3-3, 3-4, 3-5)**
- **Sensitivity to disagreement**: Analyzed impact of disagreement between decision makers on final rankings **(Tables 3-7, 3-8)**

## Chapter 4: Spatial Optimization Under Budget Constraints - Key Takeaways

- **Spatio-temporal clustering algorithm**: Developed approach to group dispersed contaminated parcels into homogeneous, actionable clusters under annual budget constraints
- **Cost reduction mechanism**: Clustering reduces intervention costs while maintaining near-optimal effectiveness, particularly important for expensive and technically challenging operations
- **Action Priority Score (APS)**: Created composite scoring system using six weighted criteria to evaluate remedial interventions **(Tables 4-3, 4-4)**
- **Parcel Priority Score (PPS)**: Developed weighted scoring system for contaminated parcels **(Table 4-5)**
- **Similarity threshold impact**: Demonstrated how threshold values (0.3 vs 0.15) affect cluster formation and resulting remedial technology selection **(Tables 4-1, 4-2)**
- **Compromise programming integration**: Used two compromise programming methodologies for site and action selection, resulting in complex spatial patterns that benefit from clustering

## Chapter 5: Column Generation for Temporal Trajectories - Key Takeaways

- **Novel trajectory optimization**: Column generation model reconciles economic and productive aspects by finding optimal multi-period sequences of remedial actions from predefined action set
- **Computational efficiency**: Approach extends candidate remedial trajectory set while limiting computational complexity through iterative column generation
- **Significant improvements**: After 4700 iterations, new trajectories reduced loss in productive years by 237 years and accumulated productivity score by 20%
- **Budget scenario analysis**: Evaluated performance with successive annual budgets of 400k€, 400k€, 300k€, 200k€, 100k€ across different objective functions **(Tables 5-4 through 5-7)**
- **Compensation cost sensitivity**: Analyzed impact of four different farmer compensation scenarios on remediation costs and trajectory selection **(Tables 5-6, 5-7, 5-8, 5-9)**
- **Countermeasure set**: Twelve remedial actions defined from combination of agricultural countermeasures (topsoil removal, deep ploughing, shallow ploughing, skim & burial, potassium fertilizers, clean feeding) **(Tables 5-1, 5-2)**
- **Large-scale application**: Applied to Maarkebeek catchment with n=1380 parcels, 800k€ annual budget over 5 years **(Tables 5-10, 5-11)**
- **Extended trajectory set**: Column generation methodology created new, more efficient trajectories beyond initial predefined set **(Tables 5-13, 5-14, 5-15, 5-16)**

## Chapter 6: CAMF Approach for Sediment Flux Reduction - Key Takeaways

- **CAMF framework**: Cellular Automata-based heuristic for Minimizing Flow - iterative approach to identify optimal spatial configuration of remedial actions minimizing radioactive sediment export from agricultural catchments
- **Off-site impact reduction**: Framework specifically designed to model and reduce off-site impacts of soil remediation in Niida watershed following Fukushima accident
- **Spatial targeting effectiveness**: Targeted afforestation of 1000 best-ranked cells reduced sediment quantity from decontamination by 15.4%, compared to only 0.8% for random cell selection
- **Model calibration**: Calibrated using measured data from Haramachi monitoring station for annual discharge, suspended sediment load, and Cs-137 flux 2013-2018 **(Table 6-1)**
- **Temporal trends**: Incorporated temporal variation in solid entrainment coefficient using parameters from previous studies **(Table 6-2)**
- **Erosivity factors**: Used measured rainfall erosivity factors specific to Haramachi site **(Table 6-3)**
- **Land cover differentiation**: Applied C-factor values differentiated by land cover type for accurate erosion modeling **(Table 6-4)**
- **Model validation**: Strong agreement between simulated and observed yearly sediment yields (Gg yr⁻¹) and Cs-137 flux after calibration with KTC parameters **(Tables 6-5, 6-6)**
- **Intervention ranking analysis**: Quantified sediment yield reduction (ton yr⁻¹) and Cs-137 flux reduction (MBq yr⁻¹) for afforestation of 1, 10, 100, 500, and 1000 highest-ranked cells **(Tables 6-7, 6-8)**

## Chapter 7: Integrated On-Site and Off-Site Criteria - Key Takeaways

- **Dual criteria framework**: Developed approach accounting for both on-site (parcel-level) and off-site (catchment-level) criteria for remediation priority setting
- **Dramatic efficiency gains**: Prioritizing topsoil removal based exclusively on off-site criteria resulted in 267% increase in Cs-137 flux reduction efficiency in first year compared to on-site only schemes
- **RUSLE integration**: Applied Revised Universal Soil Loss Equation to predict sediment transport and contamination flux at catchment scale
- **Land use and texture factors**: Incorporated specific C-values by land use class and K-values by texture class for Maarkebeek catchment **(Tables 7-1, 7-2)**
- **On-site priority components**: Parcel Priority Score (PPS) based on Cs-137 deposition, parcel area, and soil-to-plant transfer factors **(Table 7-3)**
- **Five-year remediation planning**: Evaluated annual Cs-137 flux reduction (kBq) and sediment reduction (ton) for topsoil removal plans under different prioritization schemes **(Tables 7-4, 7-5, 7-6)**
- **Baseline conditions**: Maarkebeek catchment baseline sediment yield = 16,857 tons year⁻¹; Cs-137 flux after contamination = 9,876 kBq
- **Trade-off demonstration**: Comparison between on-site only, off-site only, and combined criteria approaches shows significant differences in flux reduction efficiency

## Key Methodologies and Technical Contributions

### Decision Support Framework
- **Spatial DSS (sDSS)** combining spatial and non-spatial data for evaluating remediation alternatives
- **Multi-criteria decision analysis (MCDA)** as foundation for local and regional scale decision support
- **Fuzzy set theory** to handle linguistic variables and uncertainty in criteria evaluation
- **Monte Carlo simulation** for sensitivity analysis of fuzzy MCDA rankings

### Optimization Approaches
- **Compromise programming** for multi-objective site and action selection
- **Spatio-temporal clustering** under budget constraints for grouping interventions
- **Column generation** for discovering optimal remedial action trajectories
- **CAMF (Cellular Automata)** iterative heuristic for minimizing contaminant flow

### Spatial Modeling
- **RUSLE (Revised Universal Soil Loss Equation)** for sediment loss prediction
- **Sediment routing algorithms** for catchment-scale contaminant transport
- **GIS integration** for spatial analysis and visualization
- **Cellular automata** for distributed flow modeling

## Radiation and Contamination Context

- **Focus radionuclide**: Primarily Cs-137 (Cesium-137) contamination from nuclear accidents
- **Exposure pathways**: Soil-to-plant transfer, ingestion through contaminated food, external radiation
- **Dose concepts**: Use of Sievert (Sv) for health risk assessment; typical background dose ~2.4 mSv/year
- **LNT model**: Linear No-Threshold model used for radiation protection, assuming 5.5% fatal cancer probability per Sv
- **Decay characteristics**: Exponential decay described by A(t) = A(0) * e^(-λt) where λ is decay constant

## Agricultural Remediation Technologies Evaluated

1. **Topsoil Removal (TR)**: Removal of contaminated top soil layer
2. **Deep Ploughing (DP)**: Dilution of contamination by mixing with deeper soil layers  
3. **Shallow Ploughing (SP)**: Shallower mixing approach
4. **Skim & Burial (S&B)**: Removing contaminated layer and burying beneath clean soil
5. **Potassium Fertilizers (PF)**: Reducing Cs uptake through K competition
6. **Clean Feeding (CF)**: Providing uncontaminated feed to livestock
7. **Afforestation**: Converting agricultural land to forest to reduce erosion

## Key Performance Indicators and Criteria

### Economic Criteria
- Direct cost of remediation action (DCA)
- Farmer compensation costs for production loss
- Annual budget constraints

### Technical Criteria  
- Reduction efficiency (RE) for contamination
- Time to reach acceptable contamination levels
- Waste production and management requirements
- Feasibility and implementation complexity

### Environmental Criteria
- Sediment yield (SY) at catchment outlet [ton year⁻¹]
- Sediment flux reduction (SFR)
- Cs-137 flux reduction [Bq or kBq year⁻¹]
- Ecological impact and soil quality preservation

### Agricultural/Production Criteria
- Production years lost due to restrictions
- Time to return to full marketable production
- Crop-specific transfer factors affecting food safety

### Social/Health Criteria
- Annual effective dose to population [mSv/year]
- Excess lifetime cancer risk (ELCR)
- Stakeholder acceptance and engagement
- Equity considerations for vulnerable groups

## Major Findings and Contributions

1. **MCDA framework gaps**: Identified critical limitations in existing approaches - lack of social criteria, limited stakeholder engagement, methodological mismatches, insufficient sensitivity analysis

2. **Uncertainty management**: Demonstrated that uncertainty in fuzzy MCDA significantly impacts decision-making and must be explicitly addressed

3. **Spatial complexity reduction**: Clustering approaches can reduce implementation costs while maintaining effectiveness, converting complex spatial patterns into actionable units

4. **Temporal optimization**: Column generation significantly improves multi-period remediation planning, finding better trajectory sequences than predefined sets

5. **Off-site prioritization**: Accounting for sediment and contaminant transport provides dramatically better flux reduction (267% improvement) than parcel-level criteria alone

6. **Integrated framework**: Successfully combined multiple optimization approaches (fuzzy MCDA, clustering, column generation, cellular automata) into comprehensive sDSS for nuclear remediation planning

## Symbols and Key Parameters

- **A**: Mean annual soil loss [ton ha⁻¹ year⁻¹]
- **Acs-137**: Deposition of Cs-137 [Bq m⁻²]
- **R**: Rainfall erosivity factor [MJ mm ha⁻¹ h⁻¹ year⁻¹]
- **K**: Soil erodibility factor [ton h MJ⁻¹ mm⁻¹]
- **LS**: Slope length and steepness factor [-]
- **C**: Cover management factor [-]
- **P**: Support practice factor [-]
- **KTC**: Transport capacity coefficient [m]
- **Sc**: Solid entrainment coefficient [m² kg⁻¹]
- **PPS**: Parcel Priority Score
- **APS**: Action Priority Score
- **KD**: Solid-liquid distribution coefficient [l kg⁻¹]
- **TF**: Transfer Factor (soil-to-plant)
- **λ**: Radioactive decay constant [yr⁻¹]

## Data Sources and Model Parameters

### Fukushima/Niida Watershed
- Measured discharge, sediment load, and Cs-137 flux from Haramachi monitoring station (2013-2018)
- Contamination data from decontamination operations (year 2014)
- Site-specific rainfall erosivity and temporal trends in entrainment coefficient

### Maarkebeek Watershed  
- GIS-based topography (DEM), land use, and soil texture data
- Parcel-level contamination scenarios based on Tihange nuclear facility
- Crop types, agricultural practices, and transfer factor databases **(Tables in Appendix A)**
- Economic data for remediation costs and farmer compensation

### Transfer Factors and Dose Calculations
- Soil-to-plant transfer factors for Cs-137 by crop type **(Table A-1)**
- Soil parameters by texture (bulk density, Kd, infiltration, water content) **(Table A-2)**
- Crop dry weight content **(Table A-3)**
- Animal transfer parameters **(Table A-4)**
- Ingestion dose factors for different age groups **(Table A-5)**
- Population food intake data **(Table A-6)**

