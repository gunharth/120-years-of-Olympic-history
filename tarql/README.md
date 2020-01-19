# tarql

Convert Austrian athletes csv file to turtle rdf

Commands are relative to the root of this repository. tarql command path depends on where you got it installed on your system.

First tests:  
csv file of all Austrian athletes: Athletes_AUT.csv
tarql file: transform_athletes.sparql
result: athletes_aut.ttl

TODO: all in all details to the query
Helpful example: https://github.com/tarql/tarql/wiki/Examples

command: ./../tarql/bin/tarql --delimiter "," tarql/transform_athletes.sparql > tarql/athletes_aut.ttl  
To save to the output file:
./../tarql/bin/tarql --delimiter "," tarql/transform_athletes.sparql > tarql/athletes_aut.ttl  


for quick testing LIMIT the results

Validate the result with http://ttl.summerofcode.be/
