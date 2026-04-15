##Explica con tus palabras la diferencia entre git log y git reflog y qué tipo de información ofrece cada uno.
La diferencia entre git log y git reflog es que git log te muestra la historia "pública" y oficial de tus commits que está destinada a ser compartida, mientras que git reflog es un diario "privado" y local de cada movimiento que haces en tu ordenador, útil para recuperar trabajo perdido. 


##Describe una situación real en la que git reflog podría “salvarte la vida” (por ejemplo, tras un reset --hard o borrar una rama por error).
Después de usar por error un comando destructivo como git reset --har por ejemplo.


##¿Por qué, a pesar de existir git reflog, sigue siendo importante tener cuidado con comandos destructivos como reset --hard?
Porque tiene una retención temporal finita.
