# Comunicació
En entorns informàtics, és comú que els processos necessitin comunicar-se entre ells per compartir informació o coordinar activitats. Hi ha diverses maneres de facilitar aquesta comunicació, i aquí destaquem alguns dels mecanismes més rellevants:

1. **Pipes (Tubs):** Les pipes proporcionen un canal de comunicació unidireccional entre dos processos. Un procés pot escriure a la pipe, i l'altre pot llegir de la mateixa. Aquesta és una manera eficaç d'enviar dades entre dos processos que s'executen de manera concurrent.

2. **Sockets (Punts d'entrada):** Els sockets permeten la comunicació entre processos que s'executen en la mateixa màquina o en màquines diferents a través d'una xarxa. Aquesta és una opció potent per a la comunicació distribuïda i permet la interacció entre processos en diferents entorns.

3. **Memòria compartida:** A través de l'ús d'àrees de memòria compartida, diversos processos poden accedir i modificar dades en un espai de memòria comú. Aquesta tècnica és eficient per a la comunicació ràpida entre processos, ja que elimina la necessitat de transferir explícitament les dades.

4. **Signaling (Senyalització):** Els processos poden comunicar-se enviant senyals entre ells. Aquests senyals poden ser utilitzats per notificar esdeveniments o gestionar interrupcions. Exemples comuns són els senyals de UNIX, com SIGTERM o SIGKILL.

[Readme](readme.md)