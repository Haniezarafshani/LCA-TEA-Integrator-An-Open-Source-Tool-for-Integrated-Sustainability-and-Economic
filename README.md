# LCA-TEA-Integrator-An-Open-Source-Tool-for-Integrated-Sustainability-and-Economic
LCA-TEA Integrator: An Open-Source Tool for Integrated Sustainability and Economic Assessment of Biotechnological Innovations: Exploring Qualitative, Quantitative Combined Indicator-Based, and Preference-Based Integration Methods
Hanie Zarafshani 1 , Jo Van Caneghem1 , Giuseppe Granata 1 
1 Department of Materials Engineering, Campus Group T Leuven, KU Leuven, Andreas Vesaliusstraat 13, Leuven 3000, Belgium
ABSTRACT: Sustainability assessments of biotechnological innovations require holistic evaluation frameworks that integrate economic and environmental dimensions. Existing methodologies often lack transparency, accessibility, and adaptability, limiting their practical application across different sectors. This paper presents a novel open-source tool designed to facilitate structured sustainability assessments using three integration approaches: qualitative, quantitative combined indicator-based, and preference-based methods. The framework systematically analyzes trade-offs and synergies between economic viability and environmental impact, offering decision-makers a flexible and transparent decision-support mechanism. Through a case study on insect lipid production, the tool demonstrates its ability to provide structured sustainability insights while remaining adaptable to different biotechnological applications. The open-source nature of the tool ensures accessibility, encouraging widespread adoption in sustainable biotechnology development. The software is publicly available, allowing researchers, policymakers, and industry stakeholders to implement and further develop its capabilities.
Keywords: Integrated Sustainability Assessment, Open-Source Decision Support, Sustainability Evaluation Methods
1.	INTRODUCTION
The development of sustainable biotechnological innovations necessitates robust assessment tools that comprehensively evaluate both economic and environmental factors. (Finkbeiner et al., 2014). Traditional sustainability assessments often focus on individual dimensions—either environmental or economic—resulting in fragmented insights that hinder effective decision-making. (Scott et al., 2022; Zarafshani et al., 2024). To overcome these limitations, integrated sustainability assessment frameworks have emerged as essential tools for balancing economic feasibility with environmental impact in an evidence-based manner. (Prinsloo et al., 2021; Zeug et al., 2021).
Several methodologies exist for integrating sustainability and economic metrics, but many face challenges such as data inconsistencies, lack of transparency, and difficulty in balancing trade-offs. (Liu et al., 2023). To address these issues, this paper introduces a novel open-source framework that enables structured assessments using three complementary methodologies:
•	Qualitative Integration – A descriptive approach highlighting key trade-offs without numerical aggregation.
•	Quantitative Combined Indicator-Based Integration – A structured aggregation of economic and environmental metrics into a unified score.
•	Quantitative Preference-Based Integration – A stakeholder-driven evaluation using Multi-Criteria Decision Analysis (MCDA).
The novelty of this work lies in the development and implementation of an open-source tool that integrates these approaches into a user-friendly and transparent platform. Unlike proprietary or closed-access sustainability assessment models, this tool ensures broad accessibility and adaptability, allowing users to tailor the framework to different biotechnological applications.
To demonstrate the functionality and applicability of the tool, a case study on insect lipid production is conducted, comparing it with traditional lipid sources. This case study highlights the tool’s ability to systematically evaluate sustainability trade-offs and provide structured decision-support insights.
2.	Methods and Theoretical Background
2.1 General Framework
The proposed open-source tool is designed to integrate sustainability and economic assessments in a transparent, replicable, and structured manner. The tool enables users to systematically evaluate trade-offs and synergies between economic viability and environmental impact by implementing three complementary assessment methodologies. The framework follows a cradle-to-gate approach, ensuring that production-phase sustainability impacts are thoroughly analyzed.
A key feature of the tool is its flexibility, allowing users to input customized sustainability criteria based on their specific industry or technological context. To illustrate its functionality, a case study on lipid production is conducted, comparing insect-based lipid production with traditional lipid sources. The case study demonstrates the tool’s capability to address key sustainability questions in biotechnology and its potential for broader application in decision-making processes.
2.2 Theoretical Description of Integrated Models
2.2.1 Type A: Qualitative Integration
The qualitative integration method provides a descriptive assessment of trade-offs between economic and environmental indicators without numerical aggregation. This method is particularly useful in early-stage technology assessments, where data limitations may prevent detailed quantitative analysis (Cerchione et al., 2024).
The assessment begins by defining key sustainability indicators, such as:
•	Economic indicators: Net Present Value (NPV), Levelized Cost of Supply (LCOS), and Payback Period.
•	Environmental indicators: CO₂ emissions, land use, and water use.
By applying this method to insect lipid production, the analysis highlights the qualitative sustainability advantages (e.g., reduced land and water use) while acknowledging economic challenges related to production costs and market acceptance. This approach provides contextual insights for decision-makers before transitioning to more detailed quantitative analyses.

2.2.2 Type B: Quantitative Combined Indicator-Based Integration
The quantitative combined indicator-based method aggregates economic and environmental metrics into a unified sustainability score. This method enables structured numerical comparisons between alternatives, facilitating a more objective assessment of sustainability trade-offs (Berjawi et al., 2021),
The process involves:
1.	Normalization of indicators to a common scale.
2.	Weighted aggregation based on predefined criteria (e.g., cost per unit of CO₂ abated).
Applying this method to insect lipid production reveals whether environmental benefits outweigh economic trade-offs. While this structured comparison enhances decision-making, its reliability depends on the selection and weighting of indicators, which introduces subjectivity into the analysis.
2.2.3 Type C: Quantitative Preference-Based Integration
The preference-based integration method incorporates stakeholder priorities using Multi-Criteria Decision Analysis (MCDA). This method allows for a flexible decision-support mechanism by customizing sustainability assessments based on different stakeholder preferences (Romero-Perdomo and González-Curbelo, 2023).
The assessment process includes:
1.	Defining stakeholder priorities and assigning relative weights to indicators.
2.	Ranking alternatives based on their overall performance across weighted criteria.
3.	Performing sensitivity analysis to evaluate the impact of different preference settings.
When applied to insect lipid production, this method demonstrates that sustainability rankings vary significantly depending on whether economic feasibility or environmental benefits are prioritized. This insight underscores the importance of transparent weighting methodologies in sustainability assessments.
3.	Results and Discussion
3.1 Comparison of Methodologies
Each approach provides distinct insights into sustainability assessment:
•	Qualitative integration identifies key trade-offs but lacks numerical comparability.
•	Quantitative combined indicator-based integration allows for structured trade-off quantification but is influenced by weighting assumptions.
•	Preference-based integration aligns assessments with stakeholder priorities, making it useful for decision-making in industry and policy contexts.

3.2 Role of the Open-Source Tool
The novelty of this work lies in the development of an open-source tool that integrates these methodologies into a single, accessible platform. Unlike traditional closed-access models, this tool:
•	Provides a transparent and replicable assessment process.
•	Enables users to customize sustainability criteria for their specific applications.
•	Facilitates the broader adoption of sustainability assessments in biotechnology.
The tool’s open-access nature ensures that it can be continuously updated and expanded by the research community, fostering collaborative improvements in sustainability assessment methodologies.
4.	Conclusion and Recommendations
This paper introduces a novel open-source tool for integrated sustainability and economic assessments in biotechnology. The tool enhances decision-making by providing a structured, transparent, and adaptable assessment framework. Key insights include:
•	The flexibility of qualitative and quantitative approaches in sustainability assessment.
•	The importance of stakeholder preferences in shaping sustainability rankings.
•	The role of open-source accessibility in fostering broader adoption and transparency.
Future research should explore real-time data integration to improve the tool’s applicability in industry and policy-making contexts.
5.	Supplementary Information
The open-source tool is publicly accessible, with detailed documentation available at [https://gitlab.com/py_lca_bio/lca_tea-integrator/-/blob/main/LCA_TEA_integrator.ipynb]. Users can apply, modify, and expand the tool for sustainability assessments in diverse biotechnological applications.
REFERENCES  
Berjawi, A. E. H., Walker, S. L., Patsios, C., & Hosseini, S. H. R. (2021). An evaluation framework for future integrated energy systems: A whole energy systems approach. Renewable and Sustainable Energy Reviews, 145, 111163. https://doi.org/10.1016/J.RSER.2021.111163
Cerchione, R., Morelli, M., Passaro, R., & Quinto, I. (2024). A critical analysis of the integration of life cycle methods and quantitative methods for sustainability assessment. Corporate Social Responsibility and Environmental Management. https://doi.org/10.1002/CSR.3010
Finkbeiner, M., Ackermann, R., Bach, V., Berger, M., Brankatschk, G., Chang, Y.-J., Grinberg, M., Lehmann, A., Martínez-Blanco, J., Minkov, N., Neugebauer, S., Scheumann, R., Schneider, L., & Wolf, K. (2014). Challenges in Life Cycle Assessment: An overview of current gaps and research needs. In M. Finkbeiner et al. (Eds.), Life Cycle Assessment: Challenges and perspectives (pp. 207–258). Springer. https://doi.org/10.1007/978-94-017-8697-3_7
Liu, Y., Osterrieder, J., Hadji Misheva, B., Koenigstein, N., & Baals, L. (2023). Navigating the Environmental, Social, and Governance (ESG) landscape: Constructing a robust and reliable scoring engine – Insights into data source selection, indicator determination, weighting and aggregation techniques, and validation processes for comprehensive ESG scoring systems. Open Research Europe, 3, 119. https://doi.org/10.12688/OPENRESEUROPE.16278.1
Prinsloo, F. C., Schmitz, P., & Lombard, A. (2021). Sustainability assessment framework and methodology with trans-disciplinary numerical simulation model for analytical floatovoltaic energy system planning assessments. Sustainable Energy Technologies and Assessments, 47, 101515. https://doi.org/10.1016/J.SETA.2021.101515
Romero-Perdomo, F., & González-Curbelo, M. Á. (2023). Integrating multi-criteria techniques in life-cycle tools for the circular bioeconomy transition of agri-food waste biomass: A systematic review. Sustainability (Switzerland), 15, 5026. https://doi.org/10.3390/SU15065026/S1
Scott, A., Holtby, R., East, H., & Lannin, A. (2022). Mainstreaming the environment: Exploring pathways and narratives to improve policy and decision-making. People and Nature, 4, 201–217. https://doi.org/10.1002/PAN3.10276
Zarafshani, H., Watjanatepin, P., Navare, K., Sauve, G., & Van Acker, K. (2024). SAB: An open-access Python-based integrated platform for fully automated emergent sustainability assessment of biorefineries. International Journal of Life Cycle Assessment, 29, 632–651. https://doi.org/10.1007/S11367-023-02271-W/FIGURES/7
Zeug, W., Bezama, A., & Thrän, D. (2021). A framework for implementing holistic and integrated life cycle sustainability assessment of regional bioeconomy. International Journal of Life Cycle Assessment, 26, 1998–2023. https://doi.org/10.1007/S11367-021-01983-1/TABLES/3


