# Estats dels Processos
Els processos, en el seu cicle de vida, passen per diversos estats que reflecteixen la seva activitat i disponibilitat. Comprendre aquests estats és fonamental per gestionar eficaçment els recursos del sistema. A continuació, es detallen els principals estats dels processos:

1. **Ready (Preparat):** En aquest estat, el procés està preparat per ser executat, però encara no ha rebut el temps de CPU. Es troba a la cua d'espera del planificador per obtenir l'oportunitat d'executar-se.

2. **Running (En Execució):** Quan un procés obté el temps de CPU, entra a l'estat "Running". En aquest moment, les instruccions del programa s'estan executant activament.

3. **Blocked (Bloquejat):** El procés pot passar a aquest estat quan espera alguna condició per continuar, com ara l'entrada de dades de l'usuari o la finalització d'una operació d'entrada/sortida. Mentre està bloquejat, no utilitza temps de CPU.

4. **Terminated (Finalitzat):** Un cop el procés ha completat la seva tasca, entra a l'estat "Terminated". En aquest punt, es poden alliberar els recursos que ocupava i es pot informar del seu estat final.