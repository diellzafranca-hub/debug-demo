Jeg satte et breakpoint i calculateEndPoint for at se, hvordan spillet valgte skibets retning.
Med Step Into så jeg, at nextInt fik værdien 1 og derfor kun kunne give 0.
Jeg ændrede værdien til 2, så skibet kan placeres både vandret og lodret.
Et betinget breakpoint viste, at isSunk gav false ved tre træffere. Jeg ændrede > til >=.
Jeg fulgte fejlbeskeden til addBattleship og brugte et betinget breakpoint til at se, at x blev 10.
Jeg tilføjede et tjek, så spillet vælger en ny placering, hvis skibets slutpunkt er uden for brættet.

