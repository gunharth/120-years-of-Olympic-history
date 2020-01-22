# tarql

Construct austrian athletes into turtle from the full olympics csv file.

Below commands are relative to the root of this repository - ammend the path to tarql depending on your setup.

command:  
To save to an output file use the following command:
./../tarql/bin/tarql tarql/transform_athletes.sparql > tarql/Athletes.ttl  

For testing limit the results in the sparql file with the LIMIT clause at the bottom. 

Validate the result with http://ttl.summerofcode.be/
