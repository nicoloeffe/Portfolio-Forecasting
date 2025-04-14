# Portfolio Forecasting

Questo progetto utilizza R per l'analisi e la modellizzazione delle serie temporali finanziarie, con particolare attenzione agli aspetti relativi alla previsione dei rendimenti e alla stima del rischio di portafoglio.

## Tecnologie e Modelli

- **R:**  
  Il linguaggio R è usato per l'elaborazione dei dati, l'analisi esplorativa, e la stima dei modelli.

- **Modelli ARMA/ARIMA:**  
  Questi modelli vengono utilizzati per catturare la dinamica lineare della serie dei prezzi o, in alternativa, dei rendimenti (differenze logaritmiche).

- **Modelli ARCH/GARCH:**  
  Vengono impiegati per modellare la volatilità condizionale, ovvero per catturare il clustering di volatilità tipico dei dati finanziari. Questi modelli aiutano a stimare la varianza dei residui e a valutare il rischio.

- **Modello DCC (Dynamic Conditional Correlation):**  
  Il modello DCC viene usato per stimare dinamicamente le correlazioni tra più asset, consentendo di costruire matrici di covarianza aggiornate per la previsione del rischio di portafoglio.
