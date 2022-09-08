# Previsione dello stipendio di un dipendente nell'ambito della data science sulla base delle condizioni di lavoro
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/LuciaCastellucci/ProgettoProgrammazioneApplicazioneDataIntensive/bcc1b48d4162604813b1df17bcd810bcee43eef0?urlpath=lab%2Ftree%2FProgetto.ipynb)

I dati utilizzati sono stati ottenuti da Kaggle. Il dataset è denominato "Data Science Job Salaries".

Il dataset è stato ricavato da un indagine effettuata su un campione di 606 lavoratori del campo della Data Science inserendo le informazioni ricavate in un file formato csv. La rilevazione è stata effettuata su salari percepiti tra gli anni 2020 e 2022.


Le feature presenti nel dataset sono:

- work_year: L'anno in cui è stato percepito il salario.
- experience_level: Il livello di esperienza del lavoratore, durante l'anno lavorativo campionato. I valori della colonna sono i seguenti:
    - EN: Entry-level
    - MI: Junior (Mid-level)
    - SE: Intermediate (Senior-level)
    - EX: Expert (Executive-level)
    - Director
- employment_type: Il contratto di lavoro in termini di orario. I valori della colonna sono i seguenti:
    - PT: Part-time
    - FT: Full-time
    - CT: Contract
    - FL: Freelance
- job_title: Il ruolo ricoperto durante l'anno lavorativo.
- salary: L'importo totale della retribuzione lorda pagata.
- salary_currency: La valuta dello stipendio rispettando lo standard del codice valuta ISO 4217.
- employee_residence: Il paese di residenza dei lavoratori durante l'anno lavorativo rispettando lo standard del codice paese ISO 3166.
- remote_ratio: La parte dell'impiego svolta da remoto. I valori della colonna sono i seguenti:
    - 0: Niente lavoro da remoto
    - 50: Parzialmente da remoto
    - 100: Totalmente da remoto (sopra una percentuale dell'80%)
- company_location: Il paese dove risiede la sede principale del datore di lavoro o la succursale appaltante rispettando lo standard del codice paese ISO 3166.
- company_size: Il numero medio di persone che hanno lavorato per l'azienda durante l'anno lavorativo. I valori della colonna sono i seguenti:
    - S: Per aziende con meno di 50 impeigati (Small).
    - M: Per aziende con un numero di impiegati compresi tra i 50 e i 250 (Medium).
    - L: Per aziende con più di 250 impeigati (Large).

La misura per la quale verrano svolte le analisi predittive è:

- salary_in_usd : Indica il salario percepito, espresso in nella valuta USD, ed è una variabile continua.
