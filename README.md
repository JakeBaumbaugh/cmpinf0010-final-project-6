# cmpinf0010-final-project-6

mask =  (fireIncidents["type_description"].str.lower().str.find("trash") > -1) | (fireIncidents["type_description"].str.lower().str.find("rubbish") > -1)
fireIncidents = fireIncidents[mask]
