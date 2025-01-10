# TestingTournament
FEL HITTADE:

1 POST api/orders : Du får lov att sätta ett strängvärde på ID, price och quantity. 1P

2 GET api/orders/:id : orders/:id loggar inte fel. 1P 

3 PATCH orders/:id : Du får lov att sätta tomma strängar på alla parametrar vilket tillåter att man ändrar i customerId, status, osv. 1P

4 Order processing console loggar ingenting, och alla ordrar uppdateras endast till status "processing". X

5 POST order calculate : last-test failar efter två iterationer. X 

6 Verkar fungera som den ska. X 

7 Inga fel kastas oavsett vilka fält du uppdaterar till vad som helst. 1P 

8 Kan ej processera flera ordrar samtidigt, overload. Vid för många post requests på kort tid så går ungefär hälften igenom. 1P

9 Får ej lov att länka ordrar, får felet "Converting circular structure to JSON, relationship closes the circle". 1P

7/10
