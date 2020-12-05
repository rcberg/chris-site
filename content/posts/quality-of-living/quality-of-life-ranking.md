---
title: "Quality of Life in American Commuting Zones, Ranked"
date: '2020-12-03'
author:
  name: Chris B.
hero: /images/briefs/snowfall_plot.png
description: Study of quality of living values in US commuting zones
theme: Toha
menu:
  sidebar:
    name: Briefings
    identifier: amenities
    weight: 500
math: true
toc: true
---

Background
==========

How much value does amenities like warm and sunny late November days, or
being up the street from hot beaches on the Pacific Ocean, contribute to
the greater Los Angeles area? What are harsh winters and high crime
rates in Milwaukee really worth to the residents? These are uniquely
economic questions which shed light on the world of value beyond dollars
and cents. Urban economics offers us tools that we can use to map
information on the choices people make (such as the wages paid at
whichever job they accept, or the rents paid at the residence they pick)
to the value they place on the ineffable local qualities of their
surroundings.

The unit of analysis here will be *Commuting Zones (CZs).* For ease of
reference and interpretation, you will notice duplicate entries for CZs–
one for each MSA contained within it, because CZs may be multiple
Metropolitan (or Micropolitan) Statistical Areas (MSAs) where people frequently
commute between. For example, it’s not uncommon for folks to commute
between their home in Marion County, Oregon and the city of Portland.
Hence, while the city of Salem is in a different MSA than Portland, they
share a commuting zone. The CZ containing Portland has five duplicate
rows reflecting each of its MSAs (Portland, Salem, Albany, Corvallis,
and Eugene/Springfield).

As explained below in the “economic logic…” section, a positive
“fraction of income” expresses the value of the CZ amenities in terms of
the fraction of possible consumption given up by the average household
to live in the area, implying a high quality of living. “$ of avg.
income” multiplies this by average household income, expressing it as a
dollar value for the average household. If the figures are negative,
it’s interpretable as the amount that households are being *compensated*
(in percentage or dollar terms) to stay in the area at a given cost of
living, implying a worse quality of life.

Quality of Living Rankings
--------------------------
|Rank|CZ Code|MSA Name in CZ|Score|Amenity value (fraction of income)|Amenity value ($ of avg. income)|
|--- |--- |--- |--- |--- |--- |
|1|34701|Honolulu, HI Metropolitan Statistical Area|0.68|0.18|23783.31|
|2|1203|Asheville, NC Metropolitan Statistical Area|0.58|0.13|11514.95|
|2|1203|Brevard, NC Micropolitan Statistical Area|0.58|0.13|11514.95|
|3|38000|San Diego-Carlsbad-San Marcos, CA Metropolitan Statistical Area|0.52|0.15|19610.05|
|4|35901|Cedar City, UT Micropolitan Statistical Area|0.50|0.12|11418.35|
|4|35901|St. George, UT Metropolitan Statistical Area|0.50|0.12|11418.35|
|5|39203|Bend, OR Metropolitan Statistical Area|0.49|0.13|13761.47|
|5|39203|Prineville, OR Micropolitan Statistical Area|0.49|0.13|13761.47|
|6|34802|Espanola, NM Micropolitan Statistical Area|0.48|0.11|10982.03|
|6|34802|Los Alamos, NM Micropolitan Statistical Area|0.48|0.11|10982.03|
|6|34802|Santa Fe, NM Metropolitan Statistical Area|0.48|0.11|10982.03|
|6|34802|Taos, NM Micropolitan Statistical Area|0.48|0.11|10982.03|
|7|38200|San Luis Obispo-Paso Robles, CA Metropolitan Statistical Area|0.47|0.13|16206.73|
|7|38200|Santa Barbara-Santa Maria-Goleta, CA Metropolitan Statistical Area|0.47|0.13|16206.73|
|8|38300|Los Angeles-Long Beach-Glendale, CA Metropolitan Division|0.46|0.13|16182.97|
|8|38300|Oxnard-Thousand Oaks-Ventura, CA Metropolitan Statistical Area|0.46|0.13|16182.97|
|8|38300|Riverside-San Bernardino-Ontario, CA Metropolitan Statistical Area|0.46|0.13|16182.97|
|8|38300|Santa Ana-Anaheim-Irvine, CA Metropolitan Division|0.46|0.13|16182.97|
|9|7000|Fort Lauderdale-Pompano Beach-Deerfield Beach, FL Metropolitan Division|0.40|0.11|11661.43|
|9|7000|Key West-Marathon, FL Micropolitan Statistical Area|0.40|0.11|11661.43|
|9|7000|Miami-Miami Beach-Kendall, FL Metropolitan Division|0.40|0.11|11661.43|
|10|37700|Clearlake, CA Micropolitan Statistical Area|0.38|0.10|13625.91|
|10|37700|Santa Rosa-Petaluma, CA Metropolitan Statistical Area|0.38|0.10|13625.91|
|10|37700|Ukiah, CA Micropolitan Statistical Area|0.38|0.10|13625.91|
|11|28800|Fort Collins-Loveland, CO Metropolitan Statistical Area|0.38|0.10|11000.02|
|11|28800|Fort Morgan, CO Micropolitan Statistical Area|0.38|0.10|11000.02|
|11|28800|Greeley, CO Metropolitan Statistical Area|0.38|0.10|11000.02|
|12|9900|Tallahassee, FL Metropolitan Statistical Area|0.38|0.10|8904.20|
|13|9301|Athens-Clarke County, GA Metropolitan Statistical Area|0.38|0.10|7762.20|
|13|9301|Atlanta-Sandy Springs-Marietta, GA Metropolitan Statistical Area|0.38|0.10|7762.20|
|14|16100|DuBois, PA Micropolitan Statistical Area|0.36|0.09|8517.78|
|14|16100|Huntingdon, PA Micropolitan Statistical Area|0.36|0.09|8517.78|
|14|16100|State College, PA Metropolitan Statistical Area|0.36|0.09|8517.78|
|15|6900|Arcadia, FL Micropolitan Statistical Area|0.34|0.08|8241.76|
|15|6900|Punta Gorda, FL Metropolitan Statistical Area|0.34|0.08|8241.76|
|15|6900|Sarasota-Bradenton-Venice, FL Metropolitan Statistical Area|0.34|0.08|8241.76|
|16|7400|Orlando, FL Metropolitan Statistical Area|0.33|0.09|8602.38|
|16|7400|The Villages, FL Micropolitan Statistical Area|0.33|0.09|8602.38|
|17|7200|Cape Coral-Fort Myers, FL Metropolitan Statistical Area|0.33|0.08|8359.34|
|17|7200|Naples-Marco Island, FL Metropolitan Statistical Area|0.33|0.08|8359.34|
|18|36700|Eureka-Arcata-Fortuna, CA Micropolitan Statistical Area|0.33|0.09|8079.33|
|19|36800|Grants Pass, OR Micropolitan Statistical Area|0.32|0.07|6905.94|
|19|36800|Medford, OR Metropolitan Statistical Area|0.32|0.07|6905.94|
|20|7100|Clewiston, FL Micropolitan Statistical Area|0.32|0.08|9024.26|
|20|7100|Okeechobee, FL Micropolitan Statistical Area|0.32|0.08|9024.26|
|20|7100|Port St. Lucie-Fort Pierce, FL Metropolitan Statistical Area|0.32|0.08|9024.26|
|20|7100|West Palm Beach-Boca Raton-Boynton Beach, FL Metropolitan Division|0.32|0.08|9024.26|
|21|38901|Albany-Lebanon, OR Micropolitan Statistical Area|0.32|0.08|7145.79|
|21|38901|Corvallis, OR Metropolitan Statistical Area|0.32|0.08|7145.79|
|21|38901|Eugene-Springfield, OR Metropolitan Statistical Area|0.32|0.08|7145.79|
|21|38901|Portland-Vancouver-Beaverton, OR-WA Metropolitan Statistical Area|0.32|0.08|7145.79|
|21|38901|Salem, OR Metropolitan Statistical Area|0.32|0.08|7145.79|
|22|7900|Gainesville, FL Metropolitan Statistical Area|0.30|0.08|6966.96|
|23|35600|Hilo, HI Micropolitan Statistical Area|0.30|0.07|6989.58|
|24|37500|Salinas, CA Metropolitan Statistical Area|0.26|0.06|12933.97|
|24|37500|San Jose-Sunnyvale-Santa Clara, CA Metropolitan Statistical Area|0.26|0.06|12933.97|
|24|37500|Santa Cruz-Watsonville, CA Metropolitan Statistical Area|0.26|0.06|12933.97|
|25|2000|Elizabeth City, NC Micropolitan Statistical Area|0.25|0.06|6758.59|
|25|2000|Virginia Beach-Norfolk-Newport News, VA-NC Metropolitan Statistical Area|0.25|0.06|6758.59|
|26|7300|Palm Bay-Melbourne-Titusville, FL Metropolitan Statistical Area|0.24|0.05|4963.41|
|26|7300|Vero Beach, FL Metropolitan Statistical Area|0.24|0.05|4963.41|
|27|37800|Napa, CA Metropolitan Statistical Area|0.23|0.06|10491.94|
|27|37800|Oakland-Fremont-Hayward, CA Metropolitan Division|0.23|0.06|10491.94|
|27|37800|San Francisco-San Mateo-Redwood City, CA Metropolitan Division|0.23|0.06|10491.94|
|27|37800|Vallejo-Fairfield, CA Metropolitan Statistical Area|0.23|0.06|10491.94|
|28|20500|Barnstable Town, MA Metropolitan Statistical Area|0.23|0.06|8621.53|
|28|20500|Boston-Quincy, MA Metropolitan Division|0.23|0.06|8621.53|
|28|20500|Cambridge-Newton-Framingham, MA Metropolitan Division|0.23|0.06|8621.53|
|28|20500|Essex County, MA Metropolitan Division|0.23|0.06|8621.53|
|28|20500|Worcester, MA Metropolitan Statistical Area|0.23|0.06|8621.53|
|29|1302|Dillon, SC Micropolitan Statistical Area|0.23|0.05|4330.00|
|29|1302|Florence, SC Metropolitan Statistical Area|0.23|0.05|4330.00|
|29|1302|Georgetown, SC Micropolitan Statistical Area|0.23|0.05|4330.00|
|29|1302|Myrtle Beach-Conway-North Myrtle Beach, SC Metropolitan Statistical Area|0.23|0.05|4330.00|
|30|37300|Chico, CA Metropolitan Statistical Area|0.22|0.05|5935.19|
|30|37300|Yuba City-Marysville, CA Metropolitan Statistical Area|0.22|0.05|5935.19|
|31|39302|Bellingham, WA Metropolitan Statistical Area|0.22|0.05|5219.61|
|32|19400|New York-Wayne-White Plains, NY-NJ Metropolitan Division|0.21|0.06|7639.69|
|32|19400|Suffolk County-Nassau County, NY Metropolitan Division|0.21|0.06|7639.69|
|33|38801|Portland-Vancouver-Beaverton, OR-WA Metropolitan Statistical Area|0.20|0.05|5841.02|
|34|6700|Tampa-St. Petersburg-Clearwater, FL Metropolitan Statistical Area|0.18|0.04|4104.93|
|35|5401|Bowling Green, KY Metropolitan Statistical Area|0.17|0.03|2681.21|
|36|37604|Carson City, NV Metropolitan Statistical Area|0.15|0.04|3908.24|
|36|37604|Fallon, NV Micropolitan Statistical Area|0.15|0.04|3908.24|
|36|37604|Reno-Sparks, NV Metropolitan Statistical Area|0.15|0.04|3908.24|
|37|5600|Nashville-Davidson–Murfreesboro, TN Metropolitan Statistical Area|0.13|0.03|3210.37|
|38|29204|Lawrence, KS Metropolitan Statistical Area|0.12|0.03|2546.72|
|38|29204|Topeka, KS Metropolitan Statistical Area|0.12|0.03|2546.72|
|39|12901|Frankfort, KY Micropolitan Statistical Area|0.12|0.03|2749.76|
|39|12901|Lexington-Fayette, KY Metropolitan Statistical Area|0.12|0.03|2749.76|
|40|35100|Nogales, AZ Micropolitan Statistical Area|0.12|0.03|2406.60|
|40|35100|Sierra Vista-Douglas, AZ Micropolitan Statistical Area|0.12|0.03|2406.60|
|40|35100|Tucson, AZ Metropolitan Statistical Area|0.12|0.03|2406.60|
|41|10900|Fort Walton Beach-Crestview-Destin, FL Metropolitan Statistical Area|0.12|0.03|2574.27|
|41|10900|Pensacola-Ferry Pass-Brent, FL Metropolitan Statistical Area|0.12|0.03|2574.27|
|42|35001|Payson, AZ Micropolitan Statistical Area|0.12|0.03|2841.48|
|42|35001|Phoenix-Mesa-Scottsdale, AZ Metropolitan Statistical Area|0.12|0.03|2841.48|
|43|37400|Gardnerville Ranchos, NV Micropolitan Statistical Area|0.12|0.03|3537.21|
|43|37400|Sacramento–Arden-Arcade–Roseville, CA Metropolitan Statistical Area|0.12|0.03|3537.21|
|43|37400|Stockton, CA Metropolitan Statistical Area|0.12|0.03|3537.21|
|43|37400|Truckee-Grass Valley, CA Micropolitan Statistical Area|0.12|0.03|3537.21|
|44|34901|Albuquerque, NM Metropolitan Statistical Area|0.12|0.02|2334.66|
|44|34901|Grants, NM Micropolitan Statistical Area|0.12|0.02|2334.66|
|45|38100|El Centro, CA Metropolitan Statistical Area|0.11|0.03|1849.33|
|45|38100|Yuma, AZ Metropolitan Statistical Area|0.11|0.03|1849.33|
|46|36100|Ogden-Clearfield, UT Metropolitan Statistical Area|0.10|0.02|2442.83|
|46|36100|Salt Lake City, UT Metropolitan Statistical Area|0.10|0.02|2442.83|
|47|36600|Red Bluff, CA Micropolitan Statistical Area|0.10|0.02|2338.40|
|47|36600|Redding, CA Metropolitan Statistical Area|0.10|0.02|2338.40|
|48|14600|Bedford, IN Micropolitan Statistical Area|0.10|0.02|2075.80|
|48|14600|Bloomington, IN Metropolitan Statistical Area|0.10|0.02|2075.80|
|48|14600|Washington, IN Micropolitan Statistical Area|0.10|0.02|2075.80|
|49|34102|Anchorage, AK Metropolitan Statistical Area|0.09|0.02|2622.15|
|50|1400|Fayetteville, NC Metropolitan Statistical Area|0.09|0.02|1697.22|
|50|1400|Laurinburg, NC Micropolitan Statistical Area|0.09|0.02|1697.22|
|50|1400|Lumberton, NC Micropolitan Statistical Area|0.09|0.02|1697.22|
|50|1400|Rockingham, NC Micropolitan Statistical Area|0.09|0.02|1697.22|
|50|1400|Southern Pines, NC Micropolitan Statistical Area|0.09|0.02|1697.22|
|51|20401|Providence-New Bedford-Fall River, RI-MA Metropolitan Statistical Area|0.09|0.02|2179.67|
|52|31201|Austin-Round Rock, TX Metropolitan Statistical Area|0.09|0.02|2551.18|
|53|9400|Cornelia, GA Micropolitan Statistical Area|0.09|0.02|2013.64|
|53|9400|Gainesville, GA Metropolitan Statistical Area|0.09|0.02|2013.64|
|54|39400|Bremerton-Silverdale, WA Metropolitan Statistical Area|0.08|0.02|2817.58|
|54|39400|Centralia, WA Micropolitan Statistical Area|0.08|0.02|2817.58|
|54|39400|Mount Vernon-Anacortes, WA Metropolitan Statistical Area|0.08|0.02|2817.58|
|54|39400|Oak Harbor, WA Micropolitan Statistical Area|0.08|0.02|2817.58|
|54|39400|Olympia, WA Metropolitan Statistical Area|0.08|0.02|2817.58|
|54|39400|Seattle-Bellevue-Everett, WA Metropolitan Division|0.08|0.02|2817.58|
|54|39400|Shelton, WA Micropolitan Statistical Area|0.08|0.02|2817.58|
|54|39400|Tacoma, WA Metropolitan Division|0.08|0.02|2817.58|
|55|6800|Lakeland-Winter Haven, FL Metropolitan Statistical Area|0.08|0.02|1571.89|
|55|6800|Sebring, FL Micropolitan Statistical Area|0.08|0.02|1571.89|
|55|6800|Wauchula, FL Micropolitan Statistical Area|0.08|0.02|1571.89|
|56|23100|Baraboo, WI Micropolitan Statistical Area|0.08|0.02|2040.49|
|56|23100|Madison, WI Metropolitan Statistical Area|0.08|0.02|2040.49|
|57|22100|Iowa City, IA Metropolitan Statistical Area|0.08|0.02|2209.68|
|57|22100|Muscatine, IA Micropolitan Statistical Area|0.08|0.02|2209.68|
|58|30802|Levelland, TX Micropolitan Statistical Area|0.08|0.02|1529.46|
|58|30802|Lubbock, TX Metropolitan Statistical Area|0.08|0.02|1529.46|
|59|28101|Beatrice, NE Micropolitan Statistical Area|0.07|0.02|1386.91|
|59|28101|Lincoln, NE Metropolitan Statistical Area|0.07|0.02|1386.91|
|60|38601|Coeur d’Alene, ID Metropolitan Statistical Area|0.07|0.01|1422.24|
|60|38601|Spokane, WA Metropolitan Statistical Area|0.07|0.01|1422.24|
|61|19901|Dover, DE Metropolitan Statistical Area|0.06|0.01|1392.28|
|61|19901|Ocean Pines, MD Micropolitan Statistical Area|0.06|0.01|1392.28|
|61|19901|Salisbury, MD Metropolitan Statistical Area|0.06|0.01|1392.28|
|61|19901|Seaford, DE Micropolitan Statistical Area|0.06|0.01|1392.28|
|62|32900|Killeen-Temple-Fort Hood, TX Metropolitan Statistical Area|0.06|0.02|1294.78|
|63|30601|El Paso, TX Metropolitan Statistical Area|0.06|0.01|982.83|
|63|30601|Las Cruces, NM Metropolitan Statistical Area|0.06|0.01|982.83|
|64|20902|Bennington, VT Micropolitan Statistical Area|0.06|0.01|1281.95|
|64|20902|Pittsfield, MA Metropolitan Statistical Area|0.06|0.01|1281.95|
|65|6401|Chattanooga, TN-GA Metropolitan Statistical Area|0.05|0.01|1096.19|
|66|20100|Augusta-Waterville, ME Micropolitan Statistical Area|0.05|0.01|1009.97|
|66|20100|Lewiston-Auburn, ME Metropolitan Statistical Area|0.05|0.01|1009.97|
|66|20100|Portland-South Portland, ME Metropolitan Statistical Area|0.05|0.01|1009.97|
|67|36000|Provo-Orem, UT Metropolitan Statistical Area|0.05|0.01|1337.52|
|68|31301|San Antonio, TX Metropolitan Statistical Area|0.05|0.01|1172.44|
|69|302|Harriman, TN Micropolitan Statistical Area|0.05|0.01|867.41|
|69|302|Knoxville, TN Metropolitan Statistical Area|0.05|0.01|867.41|
|69|302|La Follette, TN Micropolitan Statistical Area|0.05|0.01|867.41|
|70|7600|Jacksonville, FL Metropolitan Statistical Area|0.05|0.01|1088.41|
|70|7600|St. Marys, GA Micropolitan Statistical Area|0.05|0.01|1088.41|
|71|17400|Chambersburg, PA Micropolitan Statistical Area|0.05|0.01|1017.77|
|71|17400|Hagerstown-Martinsburg, MD-WV Metropolitan Statistical Area|0.05|0.01|1017.77|
|71|17400|Washington-Arlington-Alexandria, DC-VA-MD-WV Metropolitan Division|0.05|0.01|1017.77|
|72|19600|Allentown-Bethlehem-Easton, PA-NJ Metropolitan Statistical Area|0.04|0.01|1605.35|
|72|19600|Edison, NJ Metropolitan Division|0.04|0.01|1605.35|
|72|19600|New York-Wayne-White Plains, NY-NJ Metropolitan Division|0.04|0.01|1605.35|
|72|19600|Newark-Union, NJ-PA Metropolitan Division|0.04|0.01|1605.35|
|72|19600|Trenton-Ewing, NJ Metropolitan Statistical Area|0.04|0.01|1605.35|
|73|1100|Hickory-Morganton-Lenoir, NC Metropolitan Statistical Area|0.04|0.01|640.30|
|73|1100|Statesville-Mooresville, NC Micropolitan Statistical Area|0.04|0.01|640.30|
|74|36301|Blackfoot, ID Micropolitan Statistical Area|0.03|0.01|671.92|
|74|36301|Idaho Falls, ID Metropolitan Statistical Area|0.03|0.01|671.92|
|74|36301|Pocatello, ID Metropolitan Statistical Area|0.03|0.01|671.92|
|74|36301|Rexburg, ID Micropolitan Statistical Area|0.03|0.01|671.92|
|75|22900|La Crosse, WI-MN Metropolitan Statistical Area|0.03|0.01|634.64|
|76|3300|Bogalusa, LA Micropolitan Statistical Area|0.02|0.00|472.80|
|76|3300|New Orleans-Metairie-Kenner, LA Metropolitan Statistical Area|0.02|0.00|472.80|
|77|2700|Gulfport-Biloxi, MS Metropolitan Statistical Area|0.02|0.00|297.78|
|77|2700|Pascagoula, MS Metropolitan Statistical Area|0.02|0.00|297.78|
|77|2700|Picayune, MS Micropolitan Statistical Area|0.02|0.00|297.78|
|78|31503|Laredo, TX Metropolitan Statistical Area|0.02|0.00|296.21|
|79|37901|Lake Havasu City-Kingman, AZ Micropolitan Statistical Area|0.01|0.00|128.40|
|79|37901|Las Vegas-Paradise, NV Metropolitan Statistical Area|0.01|0.00|128.40|
|79|37901|Pahrump, NV Micropolitan Statistical Area|0.01|0.00|128.40|
|80|2400|Richmond, VA Metropolitan Statistical Area|-0.01|0.00|-171.04|
|81|1701|Dunn, NC Micropolitan Statistical Area|-0.01|0.00|-275.52|
|81|1701|Durham, NC Metropolitan Statistical Area|-0.01|0.00|-275.52|
|81|1701|Raleigh-Cary, NC Metropolitan Statistical Area|-0.01|0.00|-275.52|
|81|1701|Sanford, NC Micropolitan Statistical Area|-0.01|0.00|-275.52|
|82|500|Burlington, NC Metropolitan Statistical Area|-0.02|0.00|-291.50|
|82|500|Danville, VA Metropolitan Statistical Area|-0.02|0.00|-291.50|
|82|500|Greensboro-High Point, NC Metropolitan Statistical Area|-0.02|0.00|-291.50|
|82|500|Lexington-Thomasville, NC Micropolitan Statistical Area|-0.02|0.00|-291.50|
|83|11304|Bethesda-Frederick-Gaithersburg, MD Metropolitan Division|-0.02|0.00|-736.98|
|83|11304|Lexington Park, MD Micropolitan Statistical Area|-0.02|0.00|-736.98|
|83|11304|Washington-Arlington-Alexandria, DC-VA-MD-WV Metropolitan Division|-0.02|0.00|-736.98|
|84|37200|Fresno, CA Metropolitan Statistical Area|-0.02|-0.01|-485.69|
|84|37200|Hanford-Corcoran, CA Metropolitan Statistical Area|-0.02|-0.01|-485.69|
|84|37200|Madera, CA Metropolitan Statistical Area|-0.02|-0.01|-485.69|
|84|37200|Visalia-Porterville, CA Metropolitan Statistical Area|-0.02|-0.01|-485.69|
|85|100|Bristol, VA Metropolitan Statistical Area|-0.02|-0.01|-482.94|
|85|100|Greeneville, TN Micropolitan Statistical Area|-0.02|-0.01|-482.94|
|85|100|Johnson City, TN Metropolitan Statistical Area|-0.02|-0.01|-482.94|
|85|100|Kingsport-Bristol, TN-VA Metropolitan Statistical Area|-0.02|-0.01|-482.94|
|86|19500|Edison, NJ Metropolitan Division|-0.03|-0.01|-1073.50|
|87|14500|Danville, IL Metropolitan Statistical Area|-0.03|-0.01|-579.43|
|87|14500|Frankfort, IN Micropolitan Statistical Area|-0.03|-0.01|-579.43|
|87|14500|Lafayette, IN Metropolitan Statistical Area|-0.03|-0.01|-579.43|
|88|15000|Canton-Massillon, OH Metropolitan Statistical Area|-0.03|-0.01|-491.70|
|88|15000|Coshocton, OH Micropolitan Statistical Area|-0.03|-0.01|-491.70|
|88|15000|New Philadelphia-Dover, OH Micropolitan Statistical Area|-0.03|-0.01|-491.70|
|88|15000|Wooster, OH Micropolitan Statistical Area|-0.03|-0.01|-491.70|
|89|3400|Houma-Bayou Cane-Thibodaux, LA Metropolitan Statistical Area|-0.03|-0.01|-589.14|
|89|3400|Morgan City, LA Micropolitan Statistical Area|-0.03|-0.01|-589.14|
|89|3400|Pierre Part, LA Micropolitan Statistical Area|-0.03|-0.01|-589.14|
|90|33100|Dallas-Plano-Irving, TX Metropolitan Division|-0.03|-0.01|-980.90|
|90|33100|Gainesville, TX Micropolitan Statistical Area|-0.03|-0.01|-980.90|
|91|33000|Fort Worth-Arlington, TX Metropolitan Division|-0.04|-0.01|-886.76|
|91|33000|Granbury, TX Micropolitan Statistical Area|-0.04|-0.01|-886.76|
|91|33000|Mineral Wells, TX Micropolitan Statistical Area|-0.04|-0.01|-886.76|
|92|6100|Albertville, AL Micropolitan Statistical Area|-0.04|-0.01|-515.49|
|92|6100|Gadsden, AL Metropolitan Statistical Area|-0.04|-0.01|-515.49|
|92|6100|Scottsboro, AL Micropolitan Statistical Area|-0.04|-0.01|-515.49|
|93|20001|Bangor, ME Metropolitan Statistical Area|-0.04|-0.01|-624.09|
|93|20001|Rockland, ME Micropolitan Statistical Area|-0.04|-0.01|-624.09|
|94|8300|Anderson, SC Metropolitan Statistical Area|-0.05|-0.01|-851.40|
|94|8300|Greenville, SC Metropolitan Statistical Area|-0.05|-0.01|-851.40|
|94|8300|Greenwood, SC Micropolitan Statistical Area|-0.05|-0.01|-851.40|
|94|8300|Seneca, SC Micropolitan Statistical Area|-0.05|-0.01|-851.40|
|95|401|Mount Airy, NC Micropolitan Statistical Area|-0.05|-0.01|-1096.26|
|95|401|Winston-Salem, NC Metropolitan Statistical Area|-0.05|-0.01|-1096.26|
|96|13101|Louisville, KY-IN Metropolitan Statistical Area|-0.06|-0.01|-1132.45|
|97|900|Albemarle, NC Micropolitan Statistical Area|-0.06|-0.01|-1357.66|
|97|900|Charlotte-Gastonia-Concord, NC-SC Metropolitan Statistical Area|-0.06|-0.01|-1357.66|
|97|900|Chester, SC Micropolitan Statistical Area|-0.06|-0.01|-1357.66|
|97|900|Lancaster, SC Micropolitan Statistical Area|-0.06|-0.01|-1357.66|
|97|900|Salisbury, NC Micropolitan Statistical Area|-0.06|-0.01|-1357.66|
|98|31700|Alice, TX Micropolitan Statistical Area|-0.06|-0.01|-1309.61|
|98|31700|Corpus Christi, TX Metropolitan Statistical Area|-0.06|-0.01|-1309.61|
|98|31700|Kingsville, TX Micropolitan Statistical Area|-0.06|-0.01|-1309.61|
|99|1900|Greenville, NC Metropolitan Statistical Area|-0.08|-0.02|-1425.44|
|99|1900|Jacksonville, NC Metropolitan Statistical Area|-0.08|-0.02|-1425.44|
|99|1900|Kinston, NC Micropolitan Statistical Area|-0.08|-0.02|-1425.44|
|99|1900|Morehead City, NC Micropolitan Statistical Area|-0.08|-0.02|-1425.44|
|99|1900|New Bern, NC Micropolitan Statistical Area|-0.08|-0.02|-1425.44|
|100|12200|Allegan, MI Micropolitan Statistical Area|-0.08|-0.02|-1529.58|
|100|12200|Grand Rapids-Wyoming, MI Metropolitan Statistical Area|-0.08|-0.02|-1529.58|
|100|12200|Holland-Grand Haven, MI Metropolitan Statistical Area|-0.08|-0.02|-1529.58|
|100|12200|Muskegon-Norton Shores, MI Metropolitan Statistical Area|-0.08|-0.02|-1529.58|
|101|2500|Virginia Beach-Norfolk-Newport News, VA-NC Metropolitan Statistical Area|-0.08|-0.02|-1663.49|
|102|24300|Chicago-Naperville-Joliet, IL Metropolitan Division|-0.08|-0.02|-2519.52|
|102|24300|Lake County-Kenosha County, IL-WI Metropolitan Division|-0.08|-0.02|-2519.52|
|103|8401|Augusta-Richmond County, GA-SC Metropolitan Statistical Area|-0.09|-0.02|-1876.20|
|104|16500|Erie, PA Metropolitan Statistical Area|-0.09|-0.02|-1608.09|
|104|16500|Jamestown-Dunkirk-Fredonia, NY Micropolitan Statistical Area|-0.09|-0.02|-1608.09|
|104|16500|Meadville, PA Micropolitan Statistical Area|-0.09|-0.02|-1608.09|
|104|16500|Oil City, PA Micropolitan Statistical Area|-0.09|-0.02|-1608.09|
|104|16500|Warren, PA Micropolitan Statistical Area|-0.09|-0.02|-1608.09|
|105|8900|Fort Valley, GA Micropolitan Statistical Area|-0.09|-0.02|-1810.54|
|105|8900|Macon, GA Metropolitan Statistical Area|-0.09|-0.02|-1810.54|
|105|8900|Warner Robins, GA Metropolitan Statistical Area|-0.09|-0.02|-1810.54|
|106|37000|Merced, CA Metropolitan Statistical Area|-0.09|-0.02|-2246.95|
|106|37000|Modesto, CA Metropolitan Statistical Area|-0.09|-0.02|-2246.95|
|106|37000|Phoenix Lake-Cedar Ridge, CA Micropolitan Statistical Area|-0.09|-0.02|-2246.95|
|107|9100|Atlanta-Sandy Springs-Marietta, GA Metropolitan Statistical Area|-0.09|-0.02|-2356.80|
|108|23400|Bloomington-Normal, IL Metropolitan Statistical Area|-0.10|-0.02|-2045.48|
|108|23400|Pontiac, IL Micropolitan Statistical Area|-0.10|-0.02|-2045.48|
|109|8503|Moultrie, GA Micropolitan Statistical Area|-0.10|-0.02|-1700.92|
|109|8503|Tifton, GA Micropolitan Statistical Area|-0.10|-0.02|-1700.92|
|109|8503|Valdosta, GA Metropolitan Statistical Area|-0.10|-0.02|-1700.92|
|110|11302|Baltimore-Towson, MD Metropolitan Statistical Area|-0.10|-0.02|-2870.19|
|111|19700|Atlantic City, NJ Metropolitan Statistical Area|-0.10|-0.02|-2881.93|
|111|19700|Camden, NJ Metropolitan Division|-0.10|-0.02|-2881.93|
|111|19700|Ocean City, NJ Metropolitan Statistical Area|-0.10|-0.02|-2881.93|
|111|19700|Philadelphia, PA Metropolitan Division|-0.10|-0.02|-2881.93|
|111|19700|Vineland-Millville-Bridgeton, NJ Metropolitan Statistical Area|-0.10|-0.02|-2881.93|
|111|19700|Wilmington, DE-MD-NJ Metropolitan Division|-0.10|-0.02|-2881.93|
|112|11001|Daphne-Fairhope, AL Micropolitan Statistical Area|-0.10|-0.02|-1807.09|
|112|11001|Mobile, AL Metropolitan Statistical Area|-0.10|-0.02|-1807.09|
|113|30903|Amarillo, TX Metropolitan Statistical Area|-0.10|-0.02|-2088.52|
|113|30903|Hereford, TX Micropolitan Statistical Area|-0.10|-0.02|-2088.52|
|114|700|Gaffney, SC Micropolitan Statistical Area|-0.11|-0.02|-1718.17|
|114|700|Spartanburg, SC Metropolitan Statistical Area|-0.11|-0.02|-1718.17|
|114|700|Union, SC Micropolitan Statistical Area|-0.11|-0.02|-1718.17|
|115|26801|Fargo, ND-MN Metropolitan Statistical Area|-0.11|-0.02|-2176.17|
|115|26801|Wahpeton, ND-MN Micropolitan Statistical Area|-0.11|-0.02|-2176.17|
|116|3800|Abbeville, LA Micropolitan Statistical Area|-0.11|-0.02|-2192.51|
|116|3800|Crowley, LA Micropolitan Statistical Area|-0.11|-0.02|-2192.51|
|116|3800|Lafayette, LA Metropolitan Statistical Area|-0.11|-0.02|-2192.51|
|116|3800|New Iberia, LA Micropolitan Statistical Area|-0.11|-0.02|-2192.51|
|116|3800|Opelousas-Eunice, LA Micropolitan Statistical Area|-0.11|-0.02|-2192.51|
|117|15900|Columbus, OH Metropolitan Statistical Area|-0.11|-0.02|-2583.01|
|117|15900|Mount Vernon, OH Micropolitan Statistical Area|-0.11|-0.02|-2583.01|
|118|20901|Bridgeport-Stamford-Norwalk, CT Metropolitan Statistical Area|-0.11|-0.03|-3740.66|
|118|20901|Hartford-West Hartford-East Hartford, CT Metropolitan Statistical Area|-0.11|-0.03|-3740.66|
|118|20901|New Haven-Milford, CT Metropolitan Statistical Area|-0.11|-0.03|-3740.66|
|118|20901|Norwich-New London, CT Metropolitan Statistical Area|-0.11|-0.03|-3740.66|
|118|20901|Torrington, CT Micropolitan Statistical Area|-0.11|-0.03|-3740.66|
|118|20901|Willimantic, CT Micropolitan Statistical Area|-0.11|-0.03|-3740.66|
|119|19800|Wilmington, DE-MD-NJ Metropolitan Division|-0.12|-0.02|-2884.66|
|120|10700|Birmingham-Hoover, AL Metropolitan Statistical Area|-0.12|-0.03|-2546.74|
|120|10700|Cullman, AL Micropolitan Statistical Area|-0.12|-0.03|-2546.74|
|121|24100|Beaver Dam, WI Micropolitan Statistical Area|-0.12|-0.03|-2632.77|
|121|24100|Milwaukee-Waukesha-West Allis, WI Metropolitan Statistical Area|-0.12|-0.03|-2632.77|
|121|24100|Watertown-Fort Atkinson, WI Micropolitan Statistical Area|-0.12|-0.03|-2632.77|
|122|33803|Oklahoma City, OK Metropolitan Statistical Area|-0.12|-0.03|-2624.40|
|122|33803|Shawnee, OK Micropolitan Statistical Area|-0.12|-0.03|-2624.40|
|123|21501|Minneapolis-St. Paul-Bloomington, MN-WI Metropolitan Statistical Area|-0.12|-0.03|-3261.15|
|124|39000|Ellensburg, WA Micropolitan Statistical Area|-0.14|-0.03|-2548.77|
|124|39000|Yakima, WA Metropolitan Statistical Area|-0.14|-0.03|-2548.77|
|125|24000|Janesville, WI Metropolitan Statistical Area|-0.14|-0.03|-2982.16|
|125|24000|Lake County-Kenosha County, IL-WI Metropolitan Division|-0.14|-0.03|-2982.16|
|125|24000|Racine, WI Metropolitan Statistical Area|-0.14|-0.03|-2982.16|
|125|24000|Whitewater, WI Micropolitan Statistical Area|-0.14|-0.03|-2982.16|
|126|31600|Brownsville-Harlingen, TX Metropolitan Statistical Area|-0.15|-0.03|-2206.98|
|126|31600|McAllen-Edinburg-Pharr, TX Metropolitan Statistical Area|-0.15|-0.03|-2206.98|
|126|31600|Raymondville, TX Micropolitan Statistical Area|-0.15|-0.03|-2206.98|
|126|31600|Rio Grande City, TX Micropolitan Statistical Area|-0.15|-0.03|-2206.98|
|127|32000|Brenham, TX Micropolitan Statistical Area|-0.15|-0.03|-3916.44|
|127|32000|Houston-Baytown-Sugar Land, TX Metropolitan Statistical Area|-0.15|-0.03|-3916.44|
|128|4200|Little Rock-North Little Rock, AR Metropolitan Statistical Area|-0.15|-0.03|-2899.20|
|129|37100|Bakersfield, CA Metropolitan Statistical Area|-0.15|-0.04|-3353.90|
|130|22601|Green Bay, WI Metropolitan Statistical Area|-0.15|-0.03|-2720.98|
|131|18800|Bloomsburg-Berwick, PA Micropolitan Statistical Area|-0.15|-0.04|-3504.94|
|131|18800|East Stroudsburg, PA Micropolitan Statistical Area|-0.15|-0.04|-3504.94|
|131|18800|Newark-Union, NJ-PA Metropolitan Division|-0.15|-0.04|-3504.94|
|131|18800|Scranton–Wilkes-Barre, PA Metropolitan Statistical Area|-0.15|-0.04|-3504.94|
|132|19300|Kingston, NY Metropolitan Statistical Area|-0.16|-0.04|-5008.77|
|132|19300|Poughkeepsie-Newburgh-Middletown, NY Metropolitan Statistical Area|-0.16|-0.04|-5008.77|
|133|28202|Fremont, NE Micropolitan Statistical Area|-0.16|-0.03|-3612.71|
|133|28202|Omaha-Council Bluffs, NE-IA Metropolitan Statistical Area|-0.16|-0.03|-3612.71|
|134|18600|Albany-Schenectady-Troy, NY Metropolitan Statistical Area|-0.16|-0.03|-3765.57|
|134|18600|Glens Falls, NY Metropolitan Statistical Area|-0.16|-0.03|-3765.57|
|134|18600|Hudson, NY Micropolitan Statistical Area|-0.16|-0.03|-3765.57|
|135|19100|Lancaster, PA Metropolitan Statistical Area|-0.16|-0.03|-3175.99|
|135|19100|Lebanon, PA Metropolitan Statistical Area|-0.16|-0.03|-3175.99|
|135|19100|Pottsville, PA Micropolitan Statistical Area|-0.16|-0.03|-3175.99|
|135|19100|Reading, PA Metropolitan Statistical Area|-0.16|-0.03|-3175.99|
|136|19200|Gettysburg, PA Micropolitan Statistical Area|-0.17|-0.04|-3563.49|
|136|19200|Harrisburg-Carlisle, PA Metropolitan Statistical Area|-0.17|-0.04|-3563.49|
|136|19200|Lewistown, PA Micropolitan Statistical Area|-0.17|-0.04|-3563.49|
|136|19200|York-Hanover, PA Metropolitan Statistical Area|-0.17|-0.04|-3563.49|
|137|24701|St. Louis, MO-IL Metropolitan Statistical Area|-0.17|-0.03|-3732.60|
|138|13600|Michigan City-La Porte, IN Metropolitan Statistical Area|-0.17|-0.04|-3049.38|
|138|13600|Niles-Benton Harbor, MI Metropolitan Statistical Area|-0.17|-0.04|-3049.38|
|138|13600|Plymouth, IN Micropolitan Statistical Area|-0.17|-0.04|-3049.38|
|138|13600|South Bend-Mishawaka, IN-MI Metropolitan Statistical Area|-0.17|-0.04|-3049.38|
|139|22500|Appleton, WI Metropolitan Statistical Area|-0.18|-0.04|-3193.63|
|139|22500|Fond du Lac, WI Metropolitan Statistical Area|-0.18|-0.04|-3193.63|
|139|22500|Oshkosh-Neenah, WI Metropolitan Statistical Area|-0.18|-0.04|-3193.63|
|140|31401|Andrews, TX Micropolitan Statistical Area|-0.18|-0.04|-5274.60|
|140|31401|Midland, TX Metropolitan Statistical Area|-0.18|-0.04|-5274.60|
|140|31401|Odessa, TX Metropolitan Statistical Area|-0.18|-0.04|-5274.60|
|141|4002|Minden, LA Micropolitan Statistical Area|-0.18|-0.04|-3344.52|
|141|4002|Natchitoches, LA Micropolitan Statistical Area|-0.18|-0.04|-3344.52|
|141|4002|Shreveport-Bossier City, LA Metropolitan Statistical Area|-0.18|-0.04|-3344.52|
|142|11600|Ann Arbor, MI Metropolitan Statistical Area|-0.18|-0.04|-4182.40|
|142|11600|Detroit-Livonia-Dearborn, MI Metropolitan Division|-0.18|-0.04|-4182.40|
|142|11600|Flint, MI Metropolitan Statistical Area|-0.18|-0.04|-4182.40|
|142|11600|Owosso, MI Micropolitan Statistical Area|-0.18|-0.04|-4182.40|
|142|11600|Warren-Farmington Hills-Troy, MI Metropolitan Division|-0.18|-0.04|-4182.40|
|143|14700|Evansville, IN-KY Metropolitan Statistical Area|-0.19|-0.04|-3497.59|
|143|14700|Jasper, IN Micropolitan Statistical Area|-0.19|-0.04|-3497.59|
|144|14200|Indianapolis, IN Metropolitan Statistical Area|-0.19|-0.04|-3839.66|
|145|29502|Kansas City, MO-KS Metropolitan Statistical Area|-0.19|-0.04|-4309.71|
|145|29502|Warrensburg, MO Micropolitan Statistical Area|-0.19|-0.04|-4309.71|
|146|30300|Fayetteville-Springdale-Rogers, AR-MO Metropolitan Statistical Area|-0.21|-0.04|-4227.34|
|147|22700|Merrill, WI Micropolitan Statistical Area|-0.21|-0.04|-3679.84|
|147|22700|Stevens Point, WI Micropolitan Statistical Area|-0.21|-0.04|-3679.84|
|147|22700|Wausau, WI Metropolitan Statistical Area|-0.21|-0.04|-3679.84|
|147|22700|Wisconsin Rapids-Marshfield, WI Micropolitan Statistical Area|-0.21|-0.04|-3679.84|
|148|14100|Angola, IN Micropolitan Statistical Area|-0.22|-0.04|-3789.17|
|148|14100|Auburn, IN Micropolitan Statistical Area|-0.22|-0.04|-3789.17|
|148|14100|Decatur, IN Micropolitan Statistical Area|-0.22|-0.04|-3789.17|
|148|14100|Fort Wayne, IN Metropolitan Statistical Area|-0.22|-0.04|-3789.17|
|148|14100|Huntington, IN Micropolitan Statistical Area|-0.22|-0.04|-3789.17|
|149|5202|Memphis, TN-MS-AR Metropolitan Statistical Area|-0.23|-0.05|-5185.26|
|150|3901|Bastrop, LA Micropolitan Statistical Area|-0.25|-0.06|-4656.62|
|150|3901|Monroe, LA Metropolitan Statistical Area|-0.25|-0.06|-4656.62|
|151|22001|Waterloo-Cedar Falls, IA Metropolitan Statistical Area|-0.25|-0.05|-5679.28|
|152|24802|Lincoln, IL Micropolitan Statistical Area|-0.26|-0.05|-4855.41|
|152|24802|Springfield, IL Metropolitan Statistical Area|-0.26|-0.05|-4855.41|
|152|24802|Taylorville, IL Micropolitan Statistical Area|-0.26|-0.05|-4855.41|
|153|16300|Indiana, PA Micropolitan Statistical Area|-0.26|-0.05|-5363.59|
|153|16300|Pittsburgh, PA Metropolitan Statistical Area|-0.26|-0.05|-5363.59|
|154|22200|Cedar Rapids, IA Metropolitan Statistical Area|-0.26|-0.06|-5269.67|
|155|23500|Champaign-Urbana, IL Metropolitan Statistical Area|-0.28|-0.06|-5148.18|
|155|23500|Decatur, IL Metropolitan Statistical Area|-0.28|-0.06|-5148.18|
|156|15200|Akron, OH Metropolitan Statistical Area|-0.28|-0.06|-5736.08|
|156|15200|Ashtabula, OH Micropolitan Statistical Area|-0.28|-0.06|-5736.08|
|156|15200|Cleveland-Elyria-Mentor, OH Metropolitan Statistical Area|-0.28|-0.06|-5736.08|
|157|18000|Batavia, NY Micropolitan Statistical Area|-0.29|-0.06|-5944.74|
|157|18000|Buffalo-Cheektowaga-Tonawanda, NY Metropolitan Statistical Area|-0.29|-0.06|-5944.74|
|157|18000|Rochester, NY Metropolitan Statistical Area|-0.29|-0.06|-5944.74|
|157|18000|Seneca Falls, NY Micropolitan Statistical Area|-0.29|-0.06|-5944.74|
|158|11500|Adrian, MI Micropolitan Statistical Area|-0.29|-0.06|-4870.49|
|158|11500|Jackson, MI Metropolitan Statistical Area|-0.29|-0.06|-4870.49|
|159|14000|Anderson, IN Metropolitan Statistical Area|-0.29|-0.06|-4396.79|
|159|14000|Marion, IN Micropolitan Statistical Area|-0.29|-0.06|-4396.79|
|159|14000|Muncie, IN Metropolitan Statistical Area|-0.29|-0.06|-4396.79|
|159|14000|New Castle, IN Micropolitan Statistical Area|-0.29|-0.06|-4396.79|
|160|12701|Cincinnati-Middletown, OH-KY-IN Metropolitan Statistical Area|-0.30|-0.06|-6640.49|
|161|12501|Bellefontaine, OH Micropolitan Statistical Area|-0.30|-0.06|-5393.36|
|161|12501|Dayton, OH Metropolitan Statistical Area|-0.30|-0.06|-5393.36|
|161|12501|Greenville, OH Micropolitan Statistical Area|-0.30|-0.06|-5393.36|
|161|12501|Sidney, OH Micropolitan Statistical Area|-0.30|-0.06|-5393.36|
|161|12501|Springfield, OH Metropolitan Statistical Area|-0.30|-0.06|-5393.36|
|161|12501|Urbana, OH Micropolitan Statistical Area|-0.30|-0.06|-5393.36|
|162|3500|Baton Rouge, LA Metropolitan Statistical Area|-0.32|-0.07|-6945.30|
|162|3500|Hammond, LA Micropolitan Statistical Area|-0.32|-0.07|-6945.30|
|163|15100|Cleveland-Elyria-Mentor, OH Metropolitan Statistical Area|-0.34|-0.07|-6548.46|
|163|15100|Norwalk, OH Micropolitan Statistical Area|-0.34|-0.07|-6548.46|
|163|15100|Sandusky, OH Metropolitan Statistical Area|-0.34|-0.07|-6548.46|
|164|14900|Gary, IN Metropolitan Division|-0.35|-0.07|-6918.81|
|165|23801|Davenport-Moline-Rock Island, IA-IL Metropolitan Statistical Area|-0.38|-0.08|-7293.04|
|165|23801|Peoria, IL Metropolitan Statistical Area|-0.38|-0.08|-7293.04|
|166|13501|Monroe, MI Metropolitan Statistical Area|-0.40|-0.07|-7403.07|
|166|13501|Toledo, OH Metropolitan Statistical Area|-0.40|-0.07|-7403.07|
|167|23900|Ottawa-Streator, IL Micropolitan Statistical Area|-0.44|-0.09|-8246.60|
|167|23900|Peoria, IL Metropolitan Statistical Area|-0.44|-0.09|-8246.60|
|168|11900|Bay City, MI Metropolitan Statistical Area|-0.45|-0.08|-6969.44|
|168|11900|Midland, MI Micropolitan Statistical Area|-0.45|-0.08|-6969.44|
|168|11900|Saginaw-Saginaw Township North, MI Metropolitan Statistical Area|-0.45|-0.08|-6969.44|
|169|24900|St. Louis, MO-IL Metropolitan Statistical Area|-0.46|-0.09|-9285.30|
|170|16200|Altoona, PA Metropolitan Statistical Area|-0.58|-0.10|-8165.66|
|170|16200|Johnstown, PA Metropolitan Statistical Area|-0.58|-0.10|-8165.66|
|170|16200|Somerset, PA Micropolitan Statistical Area|-0.58|-0.10|-8165.66|
|171|32100|Beaumont-Port Arthur, TX Metropolitan Statistical Area|-0.62|-0.13|-11784.40|


The economic logic behind amenity value
---------------------------------------

A thought experiment to start off. Imagine three cities within a county:
Acropolis, Upfrum Down, and Spira. In Acropolis and Upfrum Down, the
wage is \\$200 per week. In Spira, on the other hand, the wage is \\$300 per
week. Continue to imagine that anyone can rent a residence (or purchase
at an equal ownership cost) for \\$300 per month. In fact, go ahead and
assume that all other prices except for the wage are the same. The
obvious question that arises is why does anyone still live in Acropolis
or Upfrum Down? Couldn’t people just move to Spira and have the same
residence, with an extra \\$400 a month to spend enjoying other goods and
services? Using examples from before, one wonders if maybe Spira is
similar to Milwaukee or Minneapolis, with Acropolis and Upfrum Down
similar to somplace like Los Angeles and San Francisco. The extra \\$400 a
month might even seem like a joke to some accustomed to year-round
sunshine and beach access. Hence, we would say that Acropolis and Upfrum Down a high
( &gt; 0) quality of living, measured at 50% of foregone consumption (by giving up the extra \\$400 in wages, compared to their current income of \\$800). We
could alternatively say that the quality of life in Spira is lower ( &lt; 0), since firms in these cities *need to pay* an
extra 50% wage each month to keep workers from emigrating to higher
quality-of-life Spira.

Jennifer Roback laid-out a simple, formal version of this reasoning in
one equation:

$$p_z = H \frac{dr}{dz} - \frac{dw}{dz}$$

Here, $p_z$ is the implied price of amenity $z$; $r$ is the
residential rent for the housing unit $H$ (this could be defined
variously, like square feet or rooms, as long as it’s consistent), and
$w$ is the wage that the worker accepts.

For those who prefer English to mathematics, it’s just the intuition
laid-out above; the value $p_z$ of an additional amount of
the local amenity $dz$ is revealed by the difference between its
contribution to rent spending and its contribution to workers earnings.
Above, we formulated $z$ as the amount of some particular amenity, like
average termperature in January, or distance to national forests. We
could also consider $z$ instead to be the value of *every combined
place-based amenity* in a local area. David Albouy writing in 2012
summarises the best intuition for this interpretation of $z$:

>"[It] represents the [fraction] of total consumption households are
willing to forego to live in [a city with these rents and wages]
instead of an average city."

If local amenities are associated with more spending on rent relative to
earnings, and people aren’t moving away from an area, they must value
the amenities at least this much, Otherwise their wellbeing would go
down and they would leave the area, right? Maybe that seems *too*
simple, and while it is simplistic, it seems to do a good job describing
what’s going on with people’s choices.

Hence, we can interpret $z$ as a *cardinal measure of quality of life*
separate from earnings or living expenses required to stay in the area.
Even though we use those to measure this quality of life, it’s
independent because it’s the value that’s *revealed* by people’s choices
rather than being a *function of* them.