# Bolig_Portal_Web-Scraping
Link: https://www.boligportal.dk/en/rental-properties/k%C3%B8benhavn/
- It is webscraping of Bolig Portal website which is one of the most famous website to find the rental residence in all over the Denmark.
- Webscarping is performed only for the Copenhagen residences.
- BeautifulSoup is used for the webscraping

# Dataframe
- Dataframe is consist of Apartments, Address, Rent, Rooms, Area(m2), URL(include all urls of the apartments)
- Longitude and Latitude is added by using geopy.geocoders with import ArcGIS
- Distance is measured in km from Copenhagen Central Station to Apartment address with the help of geopy great_circle
- Copenhagen map is printed with display of 6 rooms apartment by using folium library
