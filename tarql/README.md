# tarql

Construct austrian athletes into turtle from the full olympics csv file.

Commands are relative to the root of this repository - the tarql command path depends on where you got it installed on your system.

First tests:  
olympics csv file: olympics.csv  
tarql file: transform_athletes.sparql  
result: athletes_aut.ttl  

command: ./../tarql/bin/tarql tarql/transform_athletes.sparql  
To save to an output file use the following command:
./../tarql/bin/tarql tarql/transform_athletes.sparql > tarql/athletes_aut.ttl  

For testing limit the results in the sparql file with LIMIT  

Validate the result with http://ttl.summerofcode.be/
