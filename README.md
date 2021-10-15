# COVID19 Severity of Illness Typology Definition and Evaluation


## Severity of Illness Typology

We have developed a four-level classification typology to categorize COVID-19 severity for acute episodes of care. The typology requires the creation of three flags and analysis of those flags within the context of a 14-day window. 

### Flag 1: Symptoms

This flag includes 13 symptom types. If any code in these symptom types is present, the flag is positive. The following symptoms for which codesets have been created:
- fever/chills
- anorexia/inability to eat
- nausea/vomiting/diarrhea
- abdominal pain
- cough
- nasal congestion/rhinorrhea
- sore throat
- malaise/fatigue
- headache
- myalgia
- loss of taste/smell
- lower respiratory symptoms
- COVID-19 Diagnosis
  - Only if present in a visit during the 13 days following the test positivity (D1-D13).

### Flag 2: GI/Respiratory Conditions
This flag includes 4 types of health conditions. If any code in each of these condition types is present, the flag is positive. The flag can also be positive if IV fluids are given in the ED or another outpatient setting.

- Bronchitis
- Bronchiolitis
- Gastroenteritis/Dehydration
- Pneumonia
- Guillain Barre 

This flag also includes:
- Administration of intravenous fluids in the ED or  ED to Inpatient (within 6 hours of admission), or outpatient setting.

### Flag 3: Unstable Conditions
This Flag is positive if there is a diagnosis code for any of the following condition or the patient has evidence of receiving care in the ICU:

- Health conditions
- Acute respiratory distress syndrome
- Encephalopathy, encephalitis, MIS, myocarditis, pericarditis, thrombosis, myocardial infarction, embolism, acute kidney injury, Kawasaki, acute hepatic failure, cardiac arrhythmia, acute viral transverse myelitis, macrophage activation syndrome
- Respiratory failure
- Sepsis
- Shock
- Evidence of a critical care service requirement:
- Admitted to ICU/NICU/PICU/CICU at any time during an included hospitalization
- Mechanically ventilated at any time during an included hospitalization
- Noninvasive mechanical ventilation
- Received pressor support
- Death
  - During the hospitalization

## Evaluation

#### Utilization Measures

- COVID 19 Medication Use
- COVID 19 Diagnosis
- Hospitalizations
- Outpatient Visits (Follow-up)

#### Logistic Regression
  - Health Condtions
    - Obesity 
    - Asthma (no prior admission in past 12 months)
    - Asthma (with prior admission in the past 12 months)
    - Diabetes mellitus (both types)
    - Cancer actively treated
    - Cancer non-activerly treated
    - Trisomy 21
    - Sickle cell disease
    - Prematurity
  - PMCA Categories
    - None
    - Non-Complex Chronic
    - Complex Chronic   
