# RegTechChallenge
RegTechChallenge.ipynb is Jupyter notebook that demonstrates my coding abilities.

The task is to get a rough understanding of the objectives of the Investment Firm Regulation and implement
a calculator in Python. There are two aspects, one regulatory and one technical.

For the purpose of this exercise, we will limit the implementation to the Trading Counterparty Default Risk
(K-TCD) for a Reverse Repo transaction.

It is not necessary any resource other than the definitions in Chapter 4 Section 1 "Trading Counterparty default" in the
Investment Firm Regulation (Articles 26 to 32). <a href="https://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32019R2033">IFR link.</a>

The code should accept as an input the two legs of the SFT as a JSON file (.json) that conforms to the
securities.json schema of the FIRE Data Format and return the K-TCD for that transaction.

data.json contains the two legs of the SFT as a json file.

Regulation.pdf saves as pdf the Regulation from the URL.

RegTechSubmission.pdf contains my submission to the regulatory aspect of the exercise.
