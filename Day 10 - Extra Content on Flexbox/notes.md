## IMA 5 PROPERTISA

- flex-grow: ;
- flex-shrink: ;
- flex-basis: ;
- flex: (shorthand for grow/shrink/basis)
- order: ;
- align-self: ; (DEFAULT = stretch)

## FLEX GROW
Zauzima dostupno mjesto, čak i ako je veće od FLEX BASIS-a
Koliko brzo se povećava ako je veće od flex basisa

## FLEX SHRINK
Koliko brzo se smanjuje flex item ako je manji od flex basisa

## FLEX BASIS / IDEALNA ŠIRINA
How much room does this want to be taking up
If it has the available space, how much should it take up

`.one {
flex-grow: 1;
flex-shrink: 1;
flex-basis: 250px;
}`

Ovaj primjer kaže: želim biti 250px, ali ako ima slobodnog mjesta, item može narasti da popuni ostatak

## SHORTHAND
`flex: 0 1 250pxx`

- Ako stavim samo flex: 250px, automatski će pretpostavit grow i shrink na 1

## ORDER (DEFAULT = 0) 
ako stavimo 1 - ide na kraj
ako stavimo 0 - ide na mjesto gdje je trenutno
ako stavimo -1 - ide na start

- TIP: imamo i flex-direction: row-reverse