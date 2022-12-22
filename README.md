# Bra formler för SF1624 (linjär algebra)
Gjord och skapad av ++:are för ++:are. Va fri och skriv in valfria satser på A nivå som inte tas med på kursens föreläsningar.

## Compile?
För att kompilera PDF:n glöm inte template filerna och själva main tex filen:
- extra_theory.tex
- letterfonts.tex
- macros.tex
- preamble.tex

## Formatting?
Template filerna ger en möjlighet att använda boxes för att skriva in satserna så att dokumentet blir strukturerat. Kolla exemplet nedan:

```tex
\thm{INFO OM DIN SATS KORTFATTAT}
{
SKRIV IN SJÄLVA SATSEN HÄR
}

\dfn{INFO OM DIN DEFINITION KORTFATTAT}
{
SKRIV IN SJÄLVA DEFINITIONEN HÄR
}

\nt{EN LITEN NOTE HÄR}

\ex{INFO OM DITT EXEMPEL KORTFATTAT}
{
SKRIV IN SJÄLVA EXEMPLET HÄR
}
```

