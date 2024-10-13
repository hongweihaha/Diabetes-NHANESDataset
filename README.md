The Diabetes-NHANES Dataset was extracted from the NHANES (National Health and Nutrition Examination Survey) data spanning from 1999 to 2020, comprising over 130,000 samples. Due to the vast size of the dataset, with the assistance of urologists, features related to diabetes were selected, including both direct and indirect indicators. The specific names of these features are as follows:

### Directly Related Diabetes Indicators
These indicators are typically used for diagnosing diabetes or monitoring blood glucose levels:

1. **Blood Glucose Indicators**:
   - `LBXGLU`: Fasting plasma glucose (mg/dL)
   - `LBXGLU1`, `LBXGLU2`, `LBXGLU3`, `LBXGLU4`: Repeated fasting plasma glucose measurements (mg/dL)
   - `LBXGLUSI`: Fasting plasma glucose (mmol/L)
   - `LBXGLUSI1`, `LBXGLUSI2`, `LBXGLUSI3`, `LBXGLUSI4`: Repeated fasting plasma glucose measurements (mmol/L)
   - `LBXSGL`: Serum glucose (mg/dL)
   - `LBXSGL1`, `LBXSGL2`: Repeated serum glucose measurements (mg/dL)

2. **Insulin Indicators**:
   - `PHPINSU1`, `PHPINSU2`: Use of insulin (unprocessed)
   - `LBDINSI`: Serum insulin (pmol/L)
   - `LBDINSI1`, `LBDINSI2`, `LBDINSI3`, `LBDINSI4`: Repeated serum insulin measurements (pmol/L)
   - `LBXIN`: Serum insulin (uU/mL)
   - `LBXIN1`, `LBXIN2`, `LBXIN3`, `LBXIN4`: Repeated serum insulin measurements (uU/mL)

3. **Oral Glucose Tolerance Test (OGTT) Related**:
   - `GTDCODE`: Incomplete OGTT comment code
   - `G1PCODE1`, `G1PCODE2`: Repeated incomplete glucose test (OGTT) codes

4. **C-Peptide**:
   - `LBXCP`: Serum C-peptide (pmol/mL)
   - `LBXCP1`, `LBXCP2`, `LBXCP3`, `LBXCP4`: Repeated serum C-peptide measurements (pmol/mL)
   - `LBXCPSI`: Serum C-peptide (nmol/L)
   - `LBXCPSI1`, `LBXCPSI2`, `LBXCPSI3`, `LBXCPSI4`: Repeated serum C-peptide measurements (nmol/L)

5. **Hemoglobin A1c (HbA1c)**:
   - `GHPMETH1`, `GHPMETH2`: Repeated HbA1c test method codes

### Indirectly Related Diabetes Indicators
These indicators may be associated with risk factors, complications, or other metabolic abnormalities related to diabetes:

1. **Lipid Indicators**:
   - `LBDHDD`, `LBDHDD1`, `LBDHDD2`: Serum high-density lipoprotein cholesterol (mg/dL)
   - `LBDHDDSI`, `LBDHDDSI1`, `LBDHDDSI2`: Serum high-density lipoprotein cholesterol (mmol/L)
   - `LBDLDL`, `LBDLDL1`, `LBDLDL2`: Serum low-density lipoprotein cholesterol (mg/dL)
   - `LBDLDLSI`, `LBDLDLSI1`, `LBDLDLSI2`: Serum low-density lipoprotein cholesterol (mmol/L)
   - `LBDSCHSI`, `LBDSCHSI1`, `LBDSCHSI2`: Serum total cholesterol (mmol/L)
   - `LBDSTRSI`, `LBDSTRSI1`, `LBDSTRSI2`: Serum triglycerides (mmol/L)
   - `LBXSCH`, `LBXSCH1`, `LBXSCH2`: Serum total cholesterol (mg/dL)
   - `LBXSTR`, `LBXSTR1`, `LBXSTR2`: Serum triglycerides (mg/dL)
   - `LBXTC`, `LBXTC1`, `LBXTC2`: Serum total cholesterol (mg/dL)
   - `LBXTR`, `LBXTR1`, `LBXTR2`: Serum triglycerides (mg/dL)

2. **Blood Pressure Indicators**:
   - `BPXSAR`: Systolic blood pressure mean
   - `BPXDAR`: Diastolic blood pressure mean
   - `VNLBAVEBPXDI`: Mean diastolic blood pressure (mm Hg)
   - `VNAVEBPXSY`: Mean systolic blood pressure (mm Hg)
   - `VNAVEBPXSY1`, `VNAVEBPXSY2`: Repeated mean systolic blood pressure measurements (mm Hg)
   - `BPXCHR`: 60-second heart rate
   - `BPXDB`: Number of heartbeats missed in 30 seconds
   - `BPXDI1`, `BPXDI11`, `BPXDI12`: First diastolic blood pressure measurement (mm Hg)
   - `BPXDI2`, `BPXDI21`, `BPXDI22`: Second diastolic blood pressure measurement (mm Hg)
   - `BPXDI3`, `BPXDI31`, `BPXDI32`: Third diastolic blood pressure measurement (mm Hg)
   - `BPXDI4`: Fourth diastolic blood pressure measurement (if needed)
   - `BPXSY1`, `BPXSY11`, `BPXSY12`: First systolic blood pressure measurement (mm Hg)
   - `BPXSY2`, `BPXSY21`, `BPXSY22`: Second systolic blood pressure measurement (mm Hg)
   - `BPXSY3`, `BPXSY31`, `BPXSY32`: Third systolic blood pressure measurement (mm Hg)
   - `BPXSY4`: Fourth systolic blood pressure measurement (if needed)

3. **Anthropometric Indicators**:
   - `BMXWAIST`, `BMXWAIST1`, `BMXWAIST2`: Waist circumference (cm)
   - `BMXSAD1`, `BMXSAD2`, `BMXSAD3`, `BMXSAD4`: Sagittal abdominal diameter (cm)
   - `BMXSUB`, `BMXSUB1`, `BMXSUB2`: Subscapular skinfold thickness (mm)
   - `BMXBMI`, `BMXBMI1`, `BMXBMI2`: Body mass index (kg/m²)
   - `BMPWHR`, `BMPWHR1`, `BMPWHR2`: Waist-to-hip ratio

4. **Other Biochemical Indicators**:
   - `LBDSBUSI`, `LBDSBUSI1`, `LBDSBUSI2`: Serum urea nitrogen (mmol/L)
   - `LBXSBU`, `LBXSBU1`, `LBXSBU2`: Serum urea nitrogen (mg/dL)
   - `LBXSC3SI`, `LBXSC3SI1`, `LBXSC3SI2`: Serum bicarbonate (mmol/L)
   - `LBDSTBLC`: Total bilirubin comment code
   - `LBDSTBSI`, `LBDSTBSI1`, `LBDSTBSI2`: Serum total bilirubin (umol/L)
   - `LBXSTB`, `LBXSTB1`, `LBXSTB2`: Serum total bilirubin (mg/dL)
   - `LBDSATLC`: Alanine aminotransferase (ALT) comment code
   - `LBXSATSI`, `LBXSATSI1`, `LBXSATSI2`: Alanine aminotransferase (ALT) (U/L)
   - `LBDSALSI`, `LBDSALSI1`, `LBDSALSI2`: Serum albumin (g/L)
   - `LBXSAL`, `LBXSAL1`, `LBXSAL2`: Serum albumin (g/dL)
   - `URXUMA`, `URXUMA1`, `URXUMA2`: Urinary albumin (ug/mL)
   - `URXUMS`: Urinary albumin (mg/L)
   - `LBXSAPSI`: Serum alkaline phosphatase (U/L)
   - `AAP`, `AAP1`, `AAP2`: Serum apolipoprotein AI (mg/dL)
   - `AAPSI`, `AAPSI1`, `AAPSI2`: Serum apolipoprotein AI (g/L)
   - `LBDAPBSI`, `LBDAPBSI1`, `LBDAPBSI2`: Serum apolipoprotein B (g/L)
   - `LBXAPB`, `LBXAPB1`, `LBXAPB2`: Serum apolipoprotein B (mg/dL)

For repeated measurements, the average values were calculated. For example, for `LBXAPB`, `LBXAPB1`, `LBXAPB2` (serum apolipoprotein B, mg/dL), the average of the three measurements was taken, and the resulting data were stored in the `LBXAPB` column.

In the target variable, a value of 1 indicates a diabetic sample, while 0 indicates a healthy individual. This conclusion was derived from an analysis of over 130,000 questionnaire responses.
