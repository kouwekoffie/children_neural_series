# children_neural_series

here comes documentation:

Datasets
Datasets zijn aangemaakt met een x-aantal karakters berekend naar hoeveel het model nodig heeft
om getrained hebben. In het algemeen minimum 120kb in een .txt bestand. De volgende berekeningen
gebeuren per emotie percentages.

Avatar -> (% * 1000) + (50.000 / %)
Phineas & Ferb -> ((50.000 * %) * 2)
My Little Pony -> ((55.000 * %) * 2) + (13.000 * %)

in praktijk ->
Avatar is 16.66% woede -> (0.1666 * 1000) + (50.000 * 0.1666) -> 8.496 karakters
