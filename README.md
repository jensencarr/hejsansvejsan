Förklara vad whitebox- respektive blackbox-testning innebä
1. Whitebox testing är när man har insyn i koden och kan den, blackbox är tvärt emot.

Ge exempel på ett testcase där whitebox-testning är att föredra, samt ett testcase där blackboxtestning är att föredra. Motivera varför i respektive fall.
2. Om man ska göra enhetstester måste man ha tillgång till källkoden (Whitebox-testing). Annars om man ska göra yttre tester som vi gjort på SJ Och Snälltåget så kan de vara bra att inte ha tillgång till källkoden (Blackbox-testing).

Förklara vad TDD – Test Driven Development – innebär.
3. (TDD) När man börjar göra test före man skriver koden. För att testen ska fallera.

Vad finns det för för- och nackdelar med TDD?
4. (TDD) Att det tar mycket längre tid att koda på detta sätt, försäkrar kodkvaliten och är säkrare sätt att arbeta på.

Förklara vad BDD – Behavior Driven Development – innebär.
5. (BDD) koden är skriven på ett lättare sätt så att alla förstår. även de 'dumma'.

Vad finns det för för- och nackdelar med BDD?
6. (BDD) Alla kan vara med och uppfatta vad koden gör, negativt tar det längre tid.

Förklara vad utforskande testning innebär.
7. Utforskande testing liknande BETA release inom gaming, festar sig runt utan att ha större inblick i hur det egentligen fungerar bakom

Är påståendet "utforskande testning är alltid det första ledet i all testning" sant eller falskt?
Motivera!
8.  Falskt, motivera

Vad är regressionstestning?
9. Regressionstesting är när man försöker hitta buggar som uppstått när man gjort förändringar i koden, man säkerställer att koden fortfarande fungerar korrekt efter ändringar gjorts.

Är manuell regressionstestning effektivt och ekonomiskt försvarbart? Eller bör regressionstestning
alltid genomföras automatiserat? Motivera
10. Manuellt är inte effektivt och ekonomiskt, det är bättre att automatisera då de är ett lättare sätt att arbeta och minimera felen som kan uppstå när man gör ändringar i koden. 

Vad innebär automatiserad testning? Beskriv tre exempel på olika former av automatiserad testning.
11. Automatiserad testing är när man skriver kod som gör test som utförs per automatik istället för att göra det manuellt. 
expempel: Unit test / enhetstest, Gränssnittstestning, API-testning/endpointtestning.

Ge exempel på två testcase där automatiserad testning är att föredra, samt två där manuell testning
är att föredra. Motivera!
12. Endpoint-testing är bättre automatisera. Enhetstester är bättre att automatisera. Utforskande testning är bättre att göra manuellt. Gränsnitttesting kan vara manuellt, behöver inte vara.

Vad är ett smoke test? Förklara.
13. Smoke testing innebär att man testar de viktigaste arbetsflödena i systemet så att huvudfunktionerna fungerar.

När i testprocessen är det relevant att göra smoke tests?
Förklara med fokus på olika (yrkes)roller och deras samverkan när och varför dessa tester är särskilt
viktiga.
14. Överlämningar mellan olika team, (överlämning från utvecklare till testare).

Vilka yrkesroller är involverade i testning av mjukvara? Nämn minst 3 stycken, samt förklara varför
personer med denna yrkesroll bör vara involverade i testning av mjukvara.
15. Utvecklare, Testare, DevOps. Utvecklare skriver enhetestester ofta i arbetet när de skriver kod. Testare arbetare regelbundet med olika typer av tester för att säkra mjukvaran. DevOps också för att allt ska intregrera på ett bra sätt.

Vad är CI – Continuous Integration? Förklara.
17. Utvecklare skickar kodändringar flera gånger varje dag till sitt repo via commits. Vid denna integrering så körs automatiserade tester för att säkerställa att den nya koden fungerar korrekt tillsammans med befintlig kod. 

Varför är CI centralt inom testning? Förklara med fokus på CI:s betydelse för olika yrkesroller.
18. Det är ju bara mycket simplare att arbeta på detta sätt, mer effektivt och säkrare.
Eftersom vi kan köra tester automatiserat varje gång vi gör commits, och de gör att kod inte buggar och slutar fungera. Detta är också bra för att om någon ny skulle göras en commit så slutar inte hela koden fungera. De automatiserade testerna hjälper till med detta.

Vad innebär ACL (Access Control List) inom REST (Representational State Transfer)? Hur testar man
att ACL fungerar som det ska? Förklara.
19. ACL inom REST innebär att olika användare har olika åtkomst och behörigheter för olika data. en ACL definierar vilka användare som har till stånd till att ex läsa, skriva och ta bort info.
Man har en lista på vilka som har vilken tillgång till vilket, därav får man göra manuella tester för att se så att de fungerar som det ska och behörigheterna stämmer.

Bör man föredra white listing-principen eller black listing-principen inom ACL från ett säkerhets- och
testningsperspektiv? Kan de samverka/samexistera? Motivera!
20.  White listing innebär att endast godkända åtkomstmetoder, resurser eller användare tillåts, medan allt annat automatiskt nekas.
Black listing innebär att allt är tillåtet förutom det som explicit har förbjudits eller svartlistats.
