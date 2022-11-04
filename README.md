# AIS-data for kartlegging av grunnstøting
#### Introduksjon
Et lite prosjekt som demonstrerer nytte av posisjonsdata (AIS-data). I prosjektet hentes, "cleanes" og analyseres offentlig AIS-data fra Sjøfartsdirektoratets ulykkes-database i et forsøk på  finne nyttig innsikt.

I ulykkesdatabasen er det registrert diverse ulykker sammen med posisjonsdata (AIS).
Fra denne databasen valgte jeg å ta for meg grunnstøting som ulykkestype. Tanken er å se om posisjonsdataen kan brukes til å vurdere farlige områder hvor fartøy må være ekstra varsomme for grunnstøting.

#### AIS plottet som varmekart
Under ser vi plott av posisjonsdataen til tilfeller av grunnstøting som er registrert av SDIR. Dette er presentert som et varmekart som jeg har plottet i Google Maps. Dataen som er brukt går helt fra året 1981 og seneste ulykke som er registrert er fra mars 2021. Plottene er klippet til å vise interessante kystområder som Rogaland og Oslofjorden.

#### Metoder 
For å gjøre dette brukte jeg relativt enkle og vanlige data science-teknikker som inkluderer litt data cleaning, bibliotekene numpy og pandas i tillegg til en Google Maps-utvidelse.

Det finnes nok mer praktisk og avansert teknologi som fartøy kan bruke til å unngå grunnstøting, men dette er et eksempel på nytte som kan skapes fra AIS-data.

### Rogaland:
<img width="600" alt="Rogaland_plot" src="https://user-images.githubusercontent.com/35327581/200029913-fbcaca87-40c1-49d9-bb99-399e06be7c20.png">

### Haugesund:
<img width="600" alt="Haugesund_plot" src="https://user-images.githubusercontent.com/35327581/200029966-6912c2f1-1890-47fb-915a-d741998d2afb.png">

### Oslo:
<img width="600" alt="Oslo" src="https://user-images.githubusercontent.com/35327581/200029991-33efd021-4c59-4264-a6e2-353540931517.png">
