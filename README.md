# indexed-Zips
A 4.1 MB CSV containing GeoName's US zip code data, but indexed to the zip codes themselves. Allows accessing the latitide and longitude of a zip in O(1) time.

Many zip codes have leading zeros. Strip leading zeroes for the index (e.g. 00501 becomes 501).
