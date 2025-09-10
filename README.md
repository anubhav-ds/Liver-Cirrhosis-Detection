# Liver Cirrhosis Stage Detection

Goal of this project is to create a model for Liver Cirrhosis stage detection. The data provided to us has sourced from a Mayo Clinic study on primary biliary cirrhosis (PBC) of the liver carried out from 1974 to 1984.

Data contains 19 columns containing information about patients as follows:
1. N_Days: Number of days between registration and the earlier of death, transplantation,
or study analysis time in 1986
2. Status: status of the patient C (censored), CL (censored due to liver tx), or D (death)
3. Drug: type of drug D-penicillamine or placebo
4. Age: age in days
5. Sex: M (male) or F (female)
6. Ascites: presence of ascites N (No) or Y (Yes)
7. Hepatomegaly: presence of hepatomegaly N (No) or Y (Yes)
8. Spiders: presence of spiders N (No) or Y (Yes)
9. Edema: presence of edema N (no edema and no diuretic therapy for edema), S (edema present without diuretics, or edema resolved by diuretics), or Y (edema despite diuretic therapy)
10. Bilirubin: serum bilirubin in [mg/dl]
11. Cholesterol: serum cholesterol in [mg/dl]
12. Albumin: albumin in [gm/dl]
13. Copper: urine copper in [ug/day]
14. Alk_Phos: alkaline phosphatase in [U/liter]
15. SGOT: SGOT in [U/ml] (a liver enzyme)
16. Tryglicerides: triglicerides in [mg/dl]
17. Platelets: platelets per cubic [ml/1000]
18. Prothrombin: prothrombin time in seconds [s]
19. Stage: histologic stage of disease ( 1, 2, or 3 )

We will perform initial EDA and data cleaning, and then fit Random Forest, XGBoost, and DNN models for the dataset and compare the results in conclusion section.
