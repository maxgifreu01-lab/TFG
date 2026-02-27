## Introducció

Aquest repositori conté el desenvolupament del Treball de Fi de Grau (TFG), centrat en la creació i l’anàlisi d’estratègies de trading algorítmic.
Tot el codi de backtesting ha estat dissenyat i desenvolupat específicament per treballar dins l’entorn de QuantConnect, aprofitant la seva infraestructura per a la simulació i l’avaluació d’estratègies sobre dades històriques de mercat.
L’objectiu principal del projecte és implementar, provar i analitzar diferents estratègies basades en anàlisi tècnica i mètodes quantitatius, valorant-ne el comportament mitjançant simulacions històriques.
El càlcul de l’índex de Hurst es pot desenvolupar utilitzant Python, fet que permet analitzar el comportament temporal de les sèries financeres i complementar l’estudi quantitatiu de les estratègies.

## Estructura del projecte
El projecte s’organitza en diferents mòduls que corresponen a les estratègies i metodologies analitzades. El mòdul  index_hurst inclou el càlcul de l’índex de Hurst i el desenvolupament d’estratègies basades en l’anàlisi de la dependència temporal de les sèries financeres. El mòdul rsi_indicator està orientat a la implementació i avaluació d’estratègies de trading basades en l’indicador RSI (Relative Strength Index). D’altra banda, nivells_fibonacci recull l’anàlisi i l’aplicació dels nivells de Fibonacci com a eina de suport per a la presa de decisions en trading. Finalment, el mòdul mitjanes_mobils se centra en el desenvolupament d’estratègies basades en les Bandes de Bollinger, utilitzant mitjanes mòbils i mesures de volatilitat per identificar possibles senyals d’entrada i sortida al mercat.
