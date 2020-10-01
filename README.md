# Tabular Data to Knowledge Graph Matching
### For the Cell Entity annotation
Read the target file for CEA task <br/>
Link the targets value to tables with help of Get_entity function and function_for_row <br/>
save the result <br/>
next step call the Entity function<br/>
Call the look up function to get the query<br/>
### For CTA (Cell Type Annotation) 
First read the CEA result file <br/>
call the  WikidataEndpoint funtion to get the type<br/>

### Reference -
https://github.com/ernestojimenezruiz/tabular-data-semantics-py/tree/master/TabularSemantics/src/kg 


### Supported Packages in python to run the code
import json <br/>
from pprint import pprint <br/>
from urllib import parse, request <br/>
from SPARQLWrapper import SPARQLWrapper <br/>
