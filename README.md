# supply-chain-vba-automation
Excel VBA automation for supply chain RFP analysis. Converts order volumes from boxes to pallets and pieces, and runs 22 workforce (FTE) scenarios with a single macro.
Excel VBA toolkit that automates repetitive logistics calculations for supply chain solution design and RFP responses.

Volumes conversion: volumes_conversion loops through sales/picking order rows and converts quantities from boxes to pallets and pieces using a parameters sheet.
Scenario modeling: run_scenarios cycles through scenario IDs 1 to 22, recalculates the model, and logs the FTE requirement for each scenario so they can be compared.
Performance helpers: fast_on and fast_off turn off screen updating and automatic calculation while macros run.
