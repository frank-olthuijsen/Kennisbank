> [!info] Regel van Bayes (Bayes' rule)
> Ook: stelling van Bayes
> De **regel van Bayes** berekent de voorwaardelijke kans op een gebeurtenis $A$, gegeven dat gebeurtenis $B$ is opgetreden.
>
> $P(A\mid B)=\frac{P(B\mid A)P(A)}{P(B)}$
>
> Hierbij is:
> - $P(A\mid B)$ de kans op $A$ gegeven $B$;
> - $P(B\mid A)$ de kans op $B$ gegeven $A$;
> - $P(A)$ de oorspronkelijke kans op $A$;
> - $P(B)$ de kans op $B$.
>
> De regel van Bayes maakt het mogelijk om een bestaande kans op $A$ aan te passen wanneer nieuwe informatie $B$ beschikbaar komt.

> [!example]+ Voorbeeld
> Stel dat $1\%$ van de patiënten een bepaalde ziekte heeft:
> - $P(Z)=0{,}01$
> - een test is bij $90\%$ van de zieke patiënten positief: $P(+\mid Z)=0{,}90$
> - in totaal is $5\%$ van alle tests positief: $P(+)=0{,}05$
>
> De kans dat een patiënt daadwerkelijk ziek is wanneer de test positief is:
>
> $P(Z\mid +)=\frac{P(+\mid Z)P(Z)}{P(+)}$
>
> $P(Z\mid +)=\frac{0{,}90\cdot0{,}01}{0{,}05}=0{,}18$
>
> Ondanks de positieve test is de kans dat de patiënt daadwerkelijk ziek is dus $18\%$.