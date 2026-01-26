User Funnel & Product Analysis (Python)

AARRR Summary

Caso di product analytics basato su dati event-level.
	•	Acquisition: Alto volume di visualizzazioni, ma assenza di attribution delle sorgenti di traffico.
	•	Activation: Principale bottleneck tra View → Cart (11.15%), mentre Cart → Purchase ≈ 60%.
	•	Retention: Retention per coorti non disponibile; picco di attività tra 14:00–17:00, soprattutto Tue/Wed.
	•	Revenue: Samsung e Apple guidano il fatturato. LG mostra bassa activation ma alta intenzione di acquisto.
	•	Referral: Non tracciato.

Azioni di Prodotto Prioritarie
	•	Priorità all’activation (product discovery è il collo di bottiglia principale).
	•	Miglioramento UX delle product pages e chiarezza delle CTA.
	•	Riduzione del time-to-value.
	•	Maggiore visibilità ai brand ad alta intenzione (es. LG).
	•	Allineamento delle campagne ai peak hours.
	•	Investigazione delle anomalie di tracking.
	•	Target CLV:CAC ≥ 3:1.

⸻

Overview

Analisi end-to-end del funnel utenti utilizzando dati event-level per individuare bottleneck comportamentali e tradurre gli insight in raccomandazioni di prodotto.

⸻

Dataset

Dataset ecommerce event-level da Kaggle.

⸻

Analysis Highlights
	•	Costruzione funnel View → Cart → Purchase
	•	Identificazione del bottleneck di activation
	•	Analisi comportamentale per ora e giorno della settimana
	•	Funnel per brand
	•	Mappatura degli insight sul framework AARRR

⸻

Metrics Framework

Activation
	•	View → Cart conversion
	•	Time to first cart
	•	% utenti che aggiungono al carrello nella prima sessione

Retention (future)
	•	D1 / D7 retention
	•	Cohort retention
	•	Churn

Revenue
	•	Cart → Purchase
	•	AOV
	•	CLV:CAC

Acquisition / Referral (future)
	•	Source attribution
	•	Referral rate

⸻

Tools

Python, pandas, matplotlib, seaborn

⸻

Notes

Progetto focalizzato sulla traduzione degli insight quantitativi in decisioni di prodotto concrete.
