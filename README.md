# Tabular Data to Knowledge Graph Matching
For the Cell Entity annotation, Read the target file for CEA task
next step call the Entity function

then after call the WikidataEndpoint funtion to get the query
### For CTA (Cell Type Annotation) 
First read the CEA result file and call the  WikidataEndpoint funtion to get the type

### Reference -
https://github.com/ernestojimenezruiz/tabular-data-semantics-py/tree/master/TabularSemantics/src/kg 


### Supported Packages in python to run the code
import json
from pprint import pprint
import time
from urllib import parse, request
from SPARQLWrapper import SPARQLWrapper
