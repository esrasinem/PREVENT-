# Instructions to Generate the Workflow 
Download the document titled "Yelp Term Categories". We have created a list of resources that we want to populate PREVENT with. The bolded, red terms in the document correspond to the how the resources will be encoded within PREVENT. The value in parenthesis is used when specifying a search category input. This corresponds to the categories parameter for a Search endpoint search. 


#Define my parameters of the search
#BUSINESS SEARCH PARAMETERS - EXAMPLE
PARAMETERS = {'term': 'grocery',
              'limit': 50,
              'offset': 50,
              'radius': 40000,
              'latitude': '38.637343', 'longitude': '-90.264325'}

#'grocery' can be substituted with 'food banks' , 'botanical gardnens', 'dietitians', 'CSA', etc. 
