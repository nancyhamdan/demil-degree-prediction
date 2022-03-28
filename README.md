This project presents findings from exploring the Military Equipment for Local Law Enforcement
dataset that is provided from The Defense Logistics Agency (DLA) in the United States. Excess
military equipment and devices from the Department of Defense in the US are handled by the
DLA which transfers this excess equipment to federal, state, and local law enforcement agencies
in the US as part of the LESO program (Law Enforcement Support Office program). The dataset
contains 130958 records representing the transfers that happened between 01/01/1980 and
30/09/2021.

All military items that are transferred must be demilitarized to some degree; the degree of
demilitarization required is represented by the DEMIL Code attribute in the dataset. Each DEMIL
Code has a corresponding DEMIL IC representing the integrity of the DEMIL Code registered for
the transfer. This report details the process that was followed in building a high performing deep
learning predictor of the DEMIL Code and in deriving key insights about the data.

You can read the full report in [this document](./report.pdf) and you can find the code [here](./DLA_multiclass_classification.ipynb)

You can find the dataset that was used [here](./AllStatesAndTerritoriesQTR4FY21.xlsx) along with its dictionary [here](./MeaningOfFieldsInTheDataset.pdf)