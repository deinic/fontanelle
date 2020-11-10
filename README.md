# fontanelle
JSON source data for Acquamat project

Website: https://maps.nicoladeinnocentis.it/acquamat/

AcquaMAT is a project powered by CleaNAP, based in Naples. It is creating a crowdsourced map of drinking water points 
scattered in all the cities of Europe, with the aim of promoting the use of public water, thus reducing the purchase 
of plastic bottles for water.
The map allows you to geolocate to see if there are points in the immediate vicinity of streets or squares of the city. 
Help the project by mapping water points that work and those that do not work, through a reporting form on the site.

In the repository https://raw.githubusercontent.com/deinic/fontanelle/main/fontanelle.json
you can find the whole public json where the project takes its source data.

Attributes

'indirizzo' = address <br>
'img' = path to picture of drinking water point<br>
'status' = Drinking Water point status (0:to be checked, 1:working, 2:not working)<br>
'city' = Drinking Water point city<br>
'country' = Drinking Water spot country (eg. ITA, AUT, ESP, FRA, etc..)<br>




*Part of data are taken by OSM, in detail only record data which have properties set as status = 0 AND city = 'Naples'

