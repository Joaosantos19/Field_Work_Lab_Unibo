# Field_Work_Lab_Unibo

This was a Churn project of the Field Work Lab class in my master of Data Science &amp; Business Analytics at BBS-Unibo

Data give a full picture of the company's entire customer base as of 2015.
This is to say that we can observe all clients with an active contract in 2015 end their complete contracts history until 2020.

**CLIENT**

<i>Dataset containing anagraphical information on the clients as of december 2020</i>

- COD_TIPO_PERSONA: Client Type
- ANZIANITA_ATTIVA: active seniority of the client
- NUMERO_SINISTRI: overall number of accidents
- PROV_RES: province of residence
- RATING: risk rating
- COD_GEND_PF: gender
- FIGLI: Flag for children in the household
- FLG_APP: Flag for use of the mobile application
- SUM_IMP_PREMIO_CTTO: sum of premia paid by the client to the insurance company
- ID_CLIENTE: identification number of the client
- ANNO_NASC_PF: year of birth of the client

**CONTRACT**

<i>Dataset containing information on the contracts with the perimeter as of december 2020</i>

- ID_CLIENTE: identification number of the client
- CANALE_PROV: channel of purchase
- RISCHIO: risk type
- PRODOTTO: product type
- STATO: status of the contract
- SIT ASSUN: underwriting condition
- NUM_RATE: number of installments
- MODALITA_PAGAMENTO_STIPULA: payment modality at underwriting
- MODALITA_PAGAMENTO_RATE: payment modality at installments
- RAGG_BUSINESS: business grouping
- AMT_PREMIO_RCA: premium amount of the RCA component (RCA: Responsabilità Civile Autoveicoli)
- SCONTO_TOT_RCA: overall discount on the RCA component
- AMT_PREMIO_CTTO: premium amount of the contract
- AMT_SCONTO_CTTO: discount amount of the contract
- GAR_[...]: set of warranty indicators
- CONTRACT_CODE: key identifier of the contract

**CONTRACT_DATES**

<i>Dataset containing information on relevant dates of the contracts</i>

- DAT_DECORRENZA: effective date (date since when the contract is effective)
- DAT_CHIUSURA: closing date (when the contract has been closed by the client)
- DAT_SCADENZA: expiration date (natural end of the contract)

**INFOMOTOR**

<i>Dataset containing information on relevant characteristics of the insured good (vehicle)</i>

- COD_TIPO_VEICOLO: vehicle type
- DATA_PRIMA_IMMATRICOLAZIONE: first matriculation date
- IMPORTO_VALORE_COMMERCIALE: commercial value
- COD_TIPOLOGIA_GUIDATORI: drive type
- KM_ANNUI_PREVISTI: yearly expected km
- POTENZA_KW: kw power
- COD_TIPO_ALIMENTAZIONE: power supply
- DESC_MARCA: vehicle brand
- DESC_TIPO_VEICOLO: vehicle type
- TIPO_CARROZZERIA: car body
- DESC_TIPO_CARROZZERIA: car body description
- PRESENZA_ABS: presence of ABS
- PRESENZA_AIRBAG: presence of Airbag
- PRESENZA_ANTIF: presence of theft protection system
- CONTRACT_CODE: code of the contract

