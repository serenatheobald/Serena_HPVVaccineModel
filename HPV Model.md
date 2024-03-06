This model initiates a population of girls (starting at age 7) born with perinatally acuired HIV infection. The model follows the girls over the lifecourse to estimate cervical cancer incidence rates after employing a variety of HPV vaccination stratigies.

The vaccination strategies are:

0 - No vaccinations given (natural history) 1 - Vaccinated according to current CDC guidelines (before sexual debut, i.e. around 11 or 12 years of age). Second HPV vaccine dose given 2 months after the first, the third dose given 6 months after the second. 2 - All girls vaccinated at a specified age, with dose interval the same as scenario 1 3 - All vaccinated when CD4 is at or above 500, regardless of age, with dose interval the same as scenario 1 4 - Same guidelines as scenario 1, with an additional dose given 12 months after the 3rd dose

Girls at the age of 7 years old are populated with a range of CD4/RNA VL levels and ART histories. Every cycle, they age one month, update CD4/VL based on ART and age distributions, update ART status based on CD4/VL and age, get an HPV vaccine, based on prior dosage history, age and CD4/VL. Each month each girl also has some probability of getting an HPV infection (from any of the following; HPV06, HPV11, HPV16, HPV18, HPV31, HPV33, HPV35, HPV45, HPV52 and HPV58, other HR or LR) dependent on age, vaccine history, ART history and CD4/VL. If a girl has an HPV infection, at each time step she has some probability of regression/clearance and progression to a cancerous stage. If the girl is in a cancer stage, she has a probability of regression/progression. All girls are subject to background mortality, cancer mortality and HIV mortality. We will monitor HPV infection incidence, stage-specific cancer incidence, and cancer mortality.