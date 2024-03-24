# Interactive-Kellogg-diagrams
Interactive Kellogg diagrams applied to mineral treatment. A simple alternative in Excel

Gheophysical Reshearch Letters
Supporting Information for
Interactive Kellogg diagrams applied to mineral treatment. A simple alternative in 
Excel
D. Calla-Choque1*, A. M. Valerio-Gómez1, F. Nava-Alonso2
1Faculty of Engineering, National Autonomous University of Mexico (UNAM), 04510 Mexico City, Mexico
2CINVESTAV Unidad Saltillo, Avenida Industria Metalúrgica 1062, Parque Industrial Saltillo-Ramos Arizpe, 
Ramos Arizpe, Coahuila 25900, Mexico
Corresponding author: D. Calla-Choque (dcalla@unam.mx)

Contents of this file 

Table S1 to S7
Table SA to SE

Additional Supporting Information (Files uploaded separately)

Table S1. Determination of logK.
Table S2. The thermodynamic constants.
Table S3. Intersection.
Table S4.  Intercept.
Table S5. Label.
Table S6. Axis.
Table S7. Select the values of each equation (intercept).
Table SA. Constants.
Table SB. Thermodynamic constants, HSC®
Table SC. Thermodynamic constants at working temperature
Table SD. Selection of constants and calculation of H° and Delta S° at working 
temperature
Table SE. Determination Delta G at working temperature

Introduction 
Excel files
The development of equilibria for each system is attached in an independent Excel 
workbook, Predominance area diagrams for Cu-S-O, Predominance area diagrams for 
Mo-S-O, and Predominance area diagrams for Fe-S-O.

Each file consists of two parts. 
The first sheet (Sheet1, Me) presents the Me-S-O diagram, the calculation of Delta Grxn and 
logK (Table 1), a summary of the thermodynamic constants at the evaluation 
temperature (Table 2), equilibria between the phases (Table 3), intersection points (Table 
4), labels (Table 5), axes (Table 6), and the values section for the graph of each equation 
(Table 7).
The second sheet (Sheet2, Me calculations), constants (Table A), thermodynamic 
constants, HSC® (Table B), thermodynamic calculation at T2 (Table C), selection of 
constants and calculation of Delta H° and Delta S° at working temperature (Table D), Delta G° 
determinations at operating temperature (Table E).

*	Table 1. Determination of logK, this table presents the balanced reactions 
present and the coefficients of each equilibrium, Allows the calculation of the Delta G 
by the coefficient of each species using the IF function, and finally, the 
determination of the Delta G of each reaction Eq 7 and the log K (Eq 9)
*	Table 2. The thermodynamic constants, heat capacity, enthalpy, entropy, and 
Gibbs free energy for the species in the system are presented in the system. The 
Cp is calculated with Eq 3, and the values of Delta H°(Eq 4), Delta S°(Eq 5), and Delta G°(Eq 6) for each species the value calculated in the “Calculations” Sheet is searched with the VLOOKUP function.
*	Table 3. Intersection, the equilibria, and the intercept are presented as a function 
of logK. The VLOOKUP function will look up the logK values for equilibrium from 
Table 1.
*	Table 4.  Intercept, with the MMULT and MINVERSA functions, we will obtain the 
intercepts for the balances present in the M-S-O system. 
*	Table 5. Label. The labels are essential to represent the area of predominance of 
each species. The AVERAGE function allows the average of two points to obtain 
the location point of the label.
*	Table 6. Axis. Define the limits of the graph according to the maximum and 
minimum pressures of SO2 and PO2.
*	Table 7. Select the values of each equation (intercept). According to PO2 or 
PSO2', the maximums and minimums are plotted with each equilibrium's 
start and endpoints.
The second sheet, "M calculations," contains the thermodynamic calculations used in the 
first sheet, which consists of five tables (Table A to E).
*	Table A. Constants. These constants are used in the calculations of Cp, Delta H°, Delta S° 
and finally Delta G°.
*	Table B. Thermodynamic constants, HSC®: This table shows the values of each 
species; these were obtained from the HSC® software.
*	Table C. Thermodynamic constants at working temperature, the data in this table 
are calculated Delta H°, and Delta S°, in each temperature range.
*	Table D. Selection of constants and calculation of Delta H° and Delta S° at working 
temperature allows the calculation of Delta H°, and Delta S°. The LOOKUP function allows 
you to locate the evaluation temperature range.
*	Table E. Determination Delta G at working temperature, with Tables A, B, C, and D, 
the Cp, Delta H°, Delta S° and Delta G°, are calculated for each species used in Table 2. The IFS 
function is used to determine the constants of Cp, Delta H°, Delta S°, and Delta G° from the 
ambient temperature to the evaluation range.

