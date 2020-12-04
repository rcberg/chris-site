---
title: "Test Post"
date: 2020-12-03
hero: /images/posts/writing-posts/analytics.svg
description: Testing a brief post
menu:
  sidebar:
    name: Testing
    identifier: test
    weight: 500
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

<table>
<colgroup>
<col style="width: 3%" />
<col style="width: 5%" />
<col style="width: 44%" />
<col style="width: 4%" />
<col style="width: 21%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th style="text-align: center;">Rank</th>
<th style="text-align: center;">CZ Code</th>
<th style="text-align: center;">MSA Name in CZ</th>
<th style="text-align: center;">Score</th>
<th style="text-align: center;">Amenity value (fraction of income)</th>
<th style="text-align: center;">Amenity value ($ of avg. income)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: center;">1</td>
<td style="text-align: center;">34701</td>
<td style="text-align: center;">Honolulu, HI Metropolitan Statistical Area</td>
<td style="text-align: center;">0.68</td>
<td style="text-align: center;">0.18</td>
<td style="text-align: center;">23783.31</td>
</tr>
<tr class="even">
<td style="text-align: center;">2</td>
<td style="text-align: center;">1203</td>
<td style="text-align: center;">Asheville, NC Metropolitan Statistical Area</td>
<td style="text-align: center;">0.58</td>
<td style="text-align: center;">0.13</td>
<td style="text-align: center;">11514.95</td>
</tr>
<tr class="odd">
<td style="text-align: center;">2</td>
<td style="text-align: center;">1203</td>
<td style="text-align: center;">Brevard, NC Micropolitan Statistical Area</td>
<td style="text-align: center;">0.58</td>
<td style="text-align: center;">0.13</td>
<td style="text-align: center;">11514.95</td>
</tr>
<tr class="even">
<td style="text-align: center;">3</td>
<td style="text-align: center;">38000</td>
<td style="text-align: center;">San Diego-Carlsbad-San Marcos, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.52</td>
<td style="text-align: center;">0.15</td>
<td style="text-align: center;">19610.05</td>
</tr>
<tr class="odd">
<td style="text-align: center;">4</td>
<td style="text-align: center;">35901</td>
<td style="text-align: center;">Cedar City, UT Micropolitan Statistical Area</td>
<td style="text-align: center;">0.50</td>
<td style="text-align: center;">0.12</td>
<td style="text-align: center;">11418.35</td>
</tr>
<tr class="even">
<td style="text-align: center;">4</td>
<td style="text-align: center;">35901</td>
<td style="text-align: center;">St. George, UT Metropolitan Statistical Area</td>
<td style="text-align: center;">0.50</td>
<td style="text-align: center;">0.12</td>
<td style="text-align: center;">11418.35</td>
</tr>
<tr class="odd">
<td style="text-align: center;">5</td>
<td style="text-align: center;">39203</td>
<td style="text-align: center;">Bend, OR Metropolitan Statistical Area</td>
<td style="text-align: center;">0.49</td>
<td style="text-align: center;">0.13</td>
<td style="text-align: center;">13761.47</td>
</tr>
<tr class="even">
<td style="text-align: center;">5</td>
<td style="text-align: center;">39203</td>
<td style="text-align: center;">Prineville, OR Micropolitan Statistical Area</td>
<td style="text-align: center;">0.49</td>
<td style="text-align: center;">0.13</td>
<td style="text-align: center;">13761.47</td>
</tr>
<tr class="odd">
<td style="text-align: center;">6</td>
<td style="text-align: center;">34802</td>
<td style="text-align: center;">Espanola, NM Micropolitan Statistical Area</td>
<td style="text-align: center;">0.48</td>
<td style="text-align: center;">0.11</td>
<td style="text-align: center;">10982.03</td>
</tr>
<tr class="even">
<td style="text-align: center;">6</td>
<td style="text-align: center;">34802</td>
<td style="text-align: center;">Los Alamos, NM Micropolitan Statistical Area</td>
<td style="text-align: center;">0.48</td>
<td style="text-align: center;">0.11</td>
<td style="text-align: center;">10982.03</td>
</tr>
<tr class="odd">
<td style="text-align: center;">6</td>
<td style="text-align: center;">34802</td>
<td style="text-align: center;">Santa Fe, NM Metropolitan Statistical Area</td>
<td style="text-align: center;">0.48</td>
<td style="text-align: center;">0.11</td>
<td style="text-align: center;">10982.03</td>
</tr>
<tr class="even">
<td style="text-align: center;">6</td>
<td style="text-align: center;">34802</td>
<td style="text-align: center;">Taos, NM Micropolitan Statistical Area</td>
<td style="text-align: center;">0.48</td>
<td style="text-align: center;">0.11</td>
<td style="text-align: center;">10982.03</td>
</tr>
<tr class="odd">
<td style="text-align: center;">7</td>
<td style="text-align: center;">38200</td>
<td style="text-align: center;">San Luis Obispo-Paso Robles, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.47</td>
<td style="text-align: center;">0.13</td>
<td style="text-align: center;">16206.73</td>
</tr>
<tr class="even">
<td style="text-align: center;">7</td>
<td style="text-align: center;">38200</td>
<td style="text-align: center;">Santa Barbara-Santa Maria-Goleta, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.47</td>
<td style="text-align: center;">0.13</td>
<td style="text-align: center;">16206.73</td>
</tr>
<tr class="odd">
<td style="text-align: center;">8</td>
<td style="text-align: center;">38300</td>
<td style="text-align: center;">Los Angeles-Long Beach-Glendale, CA Metropolitan Division</td>
<td style="text-align: center;">0.46</td>
<td style="text-align: center;">0.13</td>
<td style="text-align: center;">16182.97</td>
</tr>
<tr class="even">
<td style="text-align: center;">8</td>
<td style="text-align: center;">38300</td>
<td style="text-align: center;">Oxnard-Thousand Oaks-Ventura, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.46</td>
<td style="text-align: center;">0.13</td>
<td style="text-align: center;">16182.97</td>
</tr>
<tr class="odd">
<td style="text-align: center;">8</td>
<td style="text-align: center;">38300</td>
<td style="text-align: center;">Riverside-San Bernardino-Ontario, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.46</td>
<td style="text-align: center;">0.13</td>
<td style="text-align: center;">16182.97</td>
</tr>
<tr class="even">
<td style="text-align: center;">8</td>
<td style="text-align: center;">38300</td>
<td style="text-align: center;">Santa Ana-Anaheim-Irvine, CA Metropolitan Division</td>
<td style="text-align: center;">0.46</td>
<td style="text-align: center;">0.13</td>
<td style="text-align: center;">16182.97</td>
</tr>
<tr class="odd">
<td style="text-align: center;">9</td>
<td style="text-align: center;">7000</td>
<td style="text-align: center;">Fort Lauderdale-Pompano Beach-Deerfield Beach, FL Metropolitan Division</td>
<td style="text-align: center;">0.40</td>
<td style="text-align: center;">0.11</td>
<td style="text-align: center;">11661.43</td>
</tr>
<tr class="even">
<td style="text-align: center;">9</td>
<td style="text-align: center;">7000</td>
<td style="text-align: center;">Key West-Marathon, FL Micropolitan Statistical Area</td>
<td style="text-align: center;">0.40</td>
<td style="text-align: center;">0.11</td>
<td style="text-align: center;">11661.43</td>
</tr>
<tr class="odd">
<td style="text-align: center;">9</td>
<td style="text-align: center;">7000</td>
<td style="text-align: center;">Miami-Miami Beach-Kendall, FL Metropolitan Division</td>
<td style="text-align: center;">0.40</td>
<td style="text-align: center;">0.11</td>
<td style="text-align: center;">11661.43</td>
</tr>
<tr class="even">
<td style="text-align: center;">10</td>
<td style="text-align: center;">37700</td>
<td style="text-align: center;">Clearlake, CA Micropolitan Statistical Area</td>
<td style="text-align: center;">0.38</td>
<td style="text-align: center;">0.10</td>
<td style="text-align: center;">13625.91</td>
</tr>
<tr class="odd">
<td style="text-align: center;">10</td>
<td style="text-align: center;">37700</td>
<td style="text-align: center;">Santa Rosa-Petaluma, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.38</td>
<td style="text-align: center;">0.10</td>
<td style="text-align: center;">13625.91</td>
</tr>
<tr class="even">
<td style="text-align: center;">10</td>
<td style="text-align: center;">37700</td>
<td style="text-align: center;">Ukiah, CA Micropolitan Statistical Area</td>
<td style="text-align: center;">0.38</td>
<td style="text-align: center;">0.10</td>
<td style="text-align: center;">13625.91</td>
</tr>
<tr class="odd">
<td style="text-align: center;">11</td>
<td style="text-align: center;">28800</td>
<td style="text-align: center;">Fort Collins-Loveland, CO Metropolitan Statistical Area</td>
<td style="text-align: center;">0.38</td>
<td style="text-align: center;">0.10</td>
<td style="text-align: center;">11000.02</td>
</tr>
<tr class="even">
<td style="text-align: center;">11</td>
<td style="text-align: center;">28800</td>
<td style="text-align: center;">Fort Morgan, CO Micropolitan Statistical Area</td>
<td style="text-align: center;">0.38</td>
<td style="text-align: center;">0.10</td>
<td style="text-align: center;">11000.02</td>
</tr>
<tr class="odd">
<td style="text-align: center;">11</td>
<td style="text-align: center;">28800</td>
<td style="text-align: center;">Greeley, CO Metropolitan Statistical Area</td>
<td style="text-align: center;">0.38</td>
<td style="text-align: center;">0.10</td>
<td style="text-align: center;">11000.02</td>
</tr>
<tr class="even">
<td style="text-align: center;">12</td>
<td style="text-align: center;">9900</td>
<td style="text-align: center;">Tallahassee, FL Metropolitan Statistical Area</td>
<td style="text-align: center;">0.38</td>
<td style="text-align: center;">0.10</td>
<td style="text-align: center;">8904.20</td>
</tr>
<tr class="odd">
<td style="text-align: center;">13</td>
<td style="text-align: center;">9301</td>
<td style="text-align: center;">Athens-Clarke County, GA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.38</td>
<td style="text-align: center;">0.10</td>
<td style="text-align: center;">7762.20</td>
</tr>
<tr class="even">
<td style="text-align: center;">13</td>
<td style="text-align: center;">9301</td>
<td style="text-align: center;">Atlanta-Sandy Springs-Marietta, GA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.38</td>
<td style="text-align: center;">0.10</td>
<td style="text-align: center;">7762.20</td>
</tr>
<tr class="odd">
<td style="text-align: center;">14</td>
<td style="text-align: center;">16100</td>
<td style="text-align: center;">DuBois, PA Micropolitan Statistical Area</td>
<td style="text-align: center;">0.36</td>
<td style="text-align: center;">0.09</td>
<td style="text-align: center;">8517.78</td>
</tr>
<tr class="even">
<td style="text-align: center;">14</td>
<td style="text-align: center;">16100</td>
<td style="text-align: center;">Huntingdon, PA Micropolitan Statistical Area</td>
<td style="text-align: center;">0.36</td>
<td style="text-align: center;">0.09</td>
<td style="text-align: center;">8517.78</td>
</tr>
<tr class="odd">
<td style="text-align: center;">14</td>
<td style="text-align: center;">16100</td>
<td style="text-align: center;">State College, PA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.36</td>
<td style="text-align: center;">0.09</td>
<td style="text-align: center;">8517.78</td>
</tr>
<tr class="even">
<td style="text-align: center;">15</td>
<td style="text-align: center;">6900</td>
<td style="text-align: center;">Arcadia, FL Micropolitan Statistical Area</td>
<td style="text-align: center;">0.34</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">8241.76</td>
</tr>
<tr class="odd">
<td style="text-align: center;">15</td>
<td style="text-align: center;">6900</td>
<td style="text-align: center;">Punta Gorda, FL Metropolitan Statistical Area</td>
<td style="text-align: center;">0.34</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">8241.76</td>
</tr>
<tr class="even">
<td style="text-align: center;">15</td>
<td style="text-align: center;">6900</td>
<td style="text-align: center;">Sarasota-Bradenton-Venice, FL Metropolitan Statistical Area</td>
<td style="text-align: center;">0.34</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">8241.76</td>
</tr>
<tr class="odd">
<td style="text-align: center;">16</td>
<td style="text-align: center;">7400</td>
<td style="text-align: center;">Orlando, FL Metropolitan Statistical Area</td>
<td style="text-align: center;">0.33</td>
<td style="text-align: center;">0.09</td>
<td style="text-align: center;">8602.38</td>
</tr>
<tr class="even">
<td style="text-align: center;">16</td>
<td style="text-align: center;">7400</td>
<td style="text-align: center;">The Villages, FL Micropolitan Statistical Area</td>
<td style="text-align: center;">0.33</td>
<td style="text-align: center;">0.09</td>
<td style="text-align: center;">8602.38</td>
</tr>
<tr class="odd">
<td style="text-align: center;">17</td>
<td style="text-align: center;">7200</td>
<td style="text-align: center;">Cape Coral-Fort Myers, FL Metropolitan Statistical Area</td>
<td style="text-align: center;">0.33</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">8359.34</td>
</tr>
<tr class="even">
<td style="text-align: center;">17</td>
<td style="text-align: center;">7200</td>
<td style="text-align: center;">Naples-Marco Island, FL Metropolitan Statistical Area</td>
<td style="text-align: center;">0.33</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">8359.34</td>
</tr>
<tr class="odd">
<td style="text-align: center;">18</td>
<td style="text-align: center;">36700</td>
<td style="text-align: center;">Eureka-Arcata-Fortuna, CA Micropolitan Statistical Area</td>
<td style="text-align: center;">0.33</td>
<td style="text-align: center;">0.09</td>
<td style="text-align: center;">8079.33</td>
</tr>
<tr class="even">
<td style="text-align: center;">19</td>
<td style="text-align: center;">36800</td>
<td style="text-align: center;">Grants Pass, OR Micropolitan Statistical Area</td>
<td style="text-align: center;">0.32</td>
<td style="text-align: center;">0.07</td>
<td style="text-align: center;">6905.94</td>
</tr>
<tr class="odd">
<td style="text-align: center;">19</td>
<td style="text-align: center;">36800</td>
<td style="text-align: center;">Medford, OR Metropolitan Statistical Area</td>
<td style="text-align: center;">0.32</td>
<td style="text-align: center;">0.07</td>
<td style="text-align: center;">6905.94</td>
</tr>
<tr class="even">
<td style="text-align: center;">20</td>
<td style="text-align: center;">7100</td>
<td style="text-align: center;">Clewiston, FL Micropolitan Statistical Area</td>
<td style="text-align: center;">0.32</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">9024.26</td>
</tr>
<tr class="odd">
<td style="text-align: center;">20</td>
<td style="text-align: center;">7100</td>
<td style="text-align: center;">Okeechobee, FL Micropolitan Statistical Area</td>
<td style="text-align: center;">0.32</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">9024.26</td>
</tr>
<tr class="even">
<td style="text-align: center;">20</td>
<td style="text-align: center;">7100</td>
<td style="text-align: center;">Port St. Lucie-Fort Pierce, FL Metropolitan Statistical Area</td>
<td style="text-align: center;">0.32</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">9024.26</td>
</tr>
<tr class="odd">
<td style="text-align: center;">20</td>
<td style="text-align: center;">7100</td>
<td style="text-align: center;">West Palm Beach-Boca Raton-Boynton Beach, FL Metropolitan Division</td>
<td style="text-align: center;">0.32</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">9024.26</td>
</tr>
<tr class="even">
<td style="text-align: center;">21</td>
<td style="text-align: center;">38901</td>
<td style="text-align: center;">Albany-Lebanon, OR Micropolitan Statistical Area</td>
<td style="text-align: center;">0.32</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">7145.79</td>
</tr>
<tr class="odd">
<td style="text-align: center;">21</td>
<td style="text-align: center;">38901</td>
<td style="text-align: center;">Corvallis, OR Metropolitan Statistical Area</td>
<td style="text-align: center;">0.32</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">7145.79</td>
</tr>
<tr class="even">
<td style="text-align: center;">21</td>
<td style="text-align: center;">38901</td>
<td style="text-align: center;">Eugene-Springfield, OR Metropolitan Statistical Area</td>
<td style="text-align: center;">0.32</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">7145.79</td>
</tr>
<tr class="odd">
<td style="text-align: center;">21</td>
<td style="text-align: center;">38901</td>
<td style="text-align: center;">Portland-Vancouver-Beaverton, OR-WA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.32</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">7145.79</td>
</tr>
<tr class="even">
<td style="text-align: center;">21</td>
<td style="text-align: center;">38901</td>
<td style="text-align: center;">Salem, OR Metropolitan Statistical Area</td>
<td style="text-align: center;">0.32</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">7145.79</td>
</tr>
<tr class="odd">
<td style="text-align: center;">22</td>
<td style="text-align: center;">7900</td>
<td style="text-align: center;">Gainesville, FL Metropolitan Statistical Area</td>
<td style="text-align: center;">0.30</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">6966.96</td>
</tr>
<tr class="even">
<td style="text-align: center;">23</td>
<td style="text-align: center;">35600</td>
<td style="text-align: center;">Hilo, HI Micropolitan Statistical Area</td>
<td style="text-align: center;">0.30</td>
<td style="text-align: center;">0.07</td>
<td style="text-align: center;">6989.58</td>
</tr>
<tr class="odd">
<td style="text-align: center;">24</td>
<td style="text-align: center;">37500</td>
<td style="text-align: center;">Salinas, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.26</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">12933.97</td>
</tr>
<tr class="even">
<td style="text-align: center;">24</td>
<td style="text-align: center;">37500</td>
<td style="text-align: center;">San Jose-Sunnyvale-Santa Clara, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.26</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">12933.97</td>
</tr>
<tr class="odd">
<td style="text-align: center;">24</td>
<td style="text-align: center;">37500</td>
<td style="text-align: center;">Santa Cruz-Watsonville, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.26</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">12933.97</td>
</tr>
<tr class="even">
<td style="text-align: center;">25</td>
<td style="text-align: center;">2000</td>
<td style="text-align: center;">Elizabeth City, NC Micropolitan Statistical Area</td>
<td style="text-align: center;">0.25</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">6758.59</td>
</tr>
<tr class="odd">
<td style="text-align: center;">25</td>
<td style="text-align: center;">2000</td>
<td style="text-align: center;">Virginia Beach-Norfolk-Newport News, VA-NC Metropolitan Statistical Area</td>
<td style="text-align: center;">0.25</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">6758.59</td>
</tr>
<tr class="even">
<td style="text-align: center;">26</td>
<td style="text-align: center;">7300</td>
<td style="text-align: center;">Palm Bay-Melbourne-Titusville, FL Metropolitan Statistical Area</td>
<td style="text-align: center;">0.24</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">4963.41</td>
</tr>
<tr class="odd">
<td style="text-align: center;">26</td>
<td style="text-align: center;">7300</td>
<td style="text-align: center;">Vero Beach, FL Metropolitan Statistical Area</td>
<td style="text-align: center;">0.24</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">4963.41</td>
</tr>
<tr class="even">
<td style="text-align: center;">27</td>
<td style="text-align: center;">37800</td>
<td style="text-align: center;">Napa, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.23</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">10491.94</td>
</tr>
<tr class="odd">
<td style="text-align: center;">27</td>
<td style="text-align: center;">37800</td>
<td style="text-align: center;">Oakland-Fremont-Hayward, CA Metropolitan Division</td>
<td style="text-align: center;">0.23</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">10491.94</td>
</tr>
<tr class="even">
<td style="text-align: center;">27</td>
<td style="text-align: center;">37800</td>
<td style="text-align: center;">San Francisco-San Mateo-Redwood City, CA Metropolitan Division</td>
<td style="text-align: center;">0.23</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">10491.94</td>
</tr>
<tr class="odd">
<td style="text-align: center;">27</td>
<td style="text-align: center;">37800</td>
<td style="text-align: center;">Vallejo-Fairfield, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.23</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">10491.94</td>
</tr>
<tr class="even">
<td style="text-align: center;">28</td>
<td style="text-align: center;">20500</td>
<td style="text-align: center;">Barnstable Town, MA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.23</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">8621.53</td>
</tr>
<tr class="odd">
<td style="text-align: center;">28</td>
<td style="text-align: center;">20500</td>
<td style="text-align: center;">Boston-Quincy, MA Metropolitan Division</td>
<td style="text-align: center;">0.23</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">8621.53</td>
</tr>
<tr class="even">
<td style="text-align: center;">28</td>
<td style="text-align: center;">20500</td>
<td style="text-align: center;">Cambridge-Newton-Framingham, MA Metropolitan Division</td>
<td style="text-align: center;">0.23</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">8621.53</td>
</tr>
<tr class="odd">
<td style="text-align: center;">28</td>
<td style="text-align: center;">20500</td>
<td style="text-align: center;">Essex County, MA Metropolitan Division</td>
<td style="text-align: center;">0.23</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">8621.53</td>
</tr>
<tr class="even">
<td style="text-align: center;">28</td>
<td style="text-align: center;">20500</td>
<td style="text-align: center;">Worcester, MA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.23</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">8621.53</td>
</tr>
<tr class="odd">
<td style="text-align: center;">29</td>
<td style="text-align: center;">1302</td>
<td style="text-align: center;">Dillon, SC Micropolitan Statistical Area</td>
<td style="text-align: center;">0.23</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">4330.00</td>
</tr>
<tr class="even">
<td style="text-align: center;">29</td>
<td style="text-align: center;">1302</td>
<td style="text-align: center;">Florence, SC Metropolitan Statistical Area</td>
<td style="text-align: center;">0.23</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">4330.00</td>
</tr>
<tr class="odd">
<td style="text-align: center;">29</td>
<td style="text-align: center;">1302</td>
<td style="text-align: center;">Georgetown, SC Micropolitan Statistical Area</td>
<td style="text-align: center;">0.23</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">4330.00</td>
</tr>
<tr class="even">
<td style="text-align: center;">29</td>
<td style="text-align: center;">1302</td>
<td style="text-align: center;">Myrtle Beach-Conway-North Myrtle Beach, SC Metropolitan Statistical Area</td>
<td style="text-align: center;">0.23</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">4330.00</td>
</tr>
<tr class="odd">
<td style="text-align: center;">30</td>
<td style="text-align: center;">37300</td>
<td style="text-align: center;">Chico, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.22</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">5935.19</td>
</tr>
<tr class="even">
<td style="text-align: center;">30</td>
<td style="text-align: center;">37300</td>
<td style="text-align: center;">Yuba City-Marysville, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.22</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">5935.19</td>
</tr>
<tr class="odd">
<td style="text-align: center;">31</td>
<td style="text-align: center;">39302</td>
<td style="text-align: center;">Bellingham, WA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.22</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">5219.61</td>
</tr>
<tr class="even">
<td style="text-align: center;">32</td>
<td style="text-align: center;">19400</td>
<td style="text-align: center;">New York-Wayne-White Plains, NY-NJ Metropolitan Division</td>
<td style="text-align: center;">0.21</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">7639.69</td>
</tr>
<tr class="odd">
<td style="text-align: center;">32</td>
<td style="text-align: center;">19400</td>
<td style="text-align: center;">Suffolk County-Nassau County, NY Metropolitan Division</td>
<td style="text-align: center;">0.21</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">7639.69</td>
</tr>
<tr class="even">
<td style="text-align: center;">33</td>
<td style="text-align: center;">38801</td>
<td style="text-align: center;">Portland-Vancouver-Beaverton, OR-WA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.20</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">5841.02</td>
</tr>
<tr class="odd">
<td style="text-align: center;">34</td>
<td style="text-align: center;">6700</td>
<td style="text-align: center;">Tampa-St. Petersburg-Clearwater, FL Metropolitan Statistical Area</td>
<td style="text-align: center;">0.18</td>
<td style="text-align: center;">0.04</td>
<td style="text-align: center;">4104.93</td>
</tr>
<tr class="even">
<td style="text-align: center;">35</td>
<td style="text-align: center;">5401</td>
<td style="text-align: center;">Bowling Green, KY Metropolitan Statistical Area</td>
<td style="text-align: center;">0.17</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">2681.21</td>
</tr>
<tr class="odd">
<td style="text-align: center;">36</td>
<td style="text-align: center;">37604</td>
<td style="text-align: center;">Carson City, NV Metropolitan Statistical Area</td>
<td style="text-align: center;">0.15</td>
<td style="text-align: center;">0.04</td>
<td style="text-align: center;">3908.24</td>
</tr>
<tr class="even">
<td style="text-align: center;">36</td>
<td style="text-align: center;">37604</td>
<td style="text-align: center;">Fallon, NV Micropolitan Statistical Area</td>
<td style="text-align: center;">0.15</td>
<td style="text-align: center;">0.04</td>
<td style="text-align: center;">3908.24</td>
</tr>
<tr class="odd">
<td style="text-align: center;">36</td>
<td style="text-align: center;">37604</td>
<td style="text-align: center;">Reno-Sparks, NV Metropolitan Statistical Area</td>
<td style="text-align: center;">0.15</td>
<td style="text-align: center;">0.04</td>
<td style="text-align: center;">3908.24</td>
</tr>
<tr class="even">
<td style="text-align: center;">37</td>
<td style="text-align: center;">5600</td>
<td style="text-align: center;">Nashville-Davidson–Murfreesboro, TN Metropolitan Statistical Area</td>
<td style="text-align: center;">0.13</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">3210.37</td>
</tr>
<tr class="odd">
<td style="text-align: center;">38</td>
<td style="text-align: center;">29204</td>
<td style="text-align: center;">Lawrence, KS Metropolitan Statistical Area</td>
<td style="text-align: center;">0.12</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">2546.72</td>
</tr>
<tr class="even">
<td style="text-align: center;">38</td>
<td style="text-align: center;">29204</td>
<td style="text-align: center;">Topeka, KS Metropolitan Statistical Area</td>
<td style="text-align: center;">0.12</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">2546.72</td>
</tr>
<tr class="odd">
<td style="text-align: center;">39</td>
<td style="text-align: center;">12901</td>
<td style="text-align: center;">Frankfort, KY Micropolitan Statistical Area</td>
<td style="text-align: center;">0.12</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">2749.76</td>
</tr>
<tr class="even">
<td style="text-align: center;">39</td>
<td style="text-align: center;">12901</td>
<td style="text-align: center;">Lexington-Fayette, KY Metropolitan Statistical Area</td>
<td style="text-align: center;">0.12</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">2749.76</td>
</tr>
<tr class="odd">
<td style="text-align: center;">40</td>
<td style="text-align: center;">35100</td>
<td style="text-align: center;">Nogales, AZ Micropolitan Statistical Area</td>
<td style="text-align: center;">0.12</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">2406.60</td>
</tr>
<tr class="even">
<td style="text-align: center;">40</td>
<td style="text-align: center;">35100</td>
<td style="text-align: center;">Sierra Vista-Douglas, AZ Micropolitan Statistical Area</td>
<td style="text-align: center;">0.12</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">2406.60</td>
</tr>
<tr class="odd">
<td style="text-align: center;">40</td>
<td style="text-align: center;">35100</td>
<td style="text-align: center;">Tucson, AZ Metropolitan Statistical Area</td>
<td style="text-align: center;">0.12</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">2406.60</td>
</tr>
<tr class="even">
<td style="text-align: center;">41</td>
<td style="text-align: center;">10900</td>
<td style="text-align: center;">Fort Walton Beach-Crestview-Destin, FL Metropolitan Statistical Area</td>
<td style="text-align: center;">0.12</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">2574.27</td>
</tr>
<tr class="odd">
<td style="text-align: center;">41</td>
<td style="text-align: center;">10900</td>
<td style="text-align: center;">Pensacola-Ferry Pass-Brent, FL Metropolitan Statistical Area</td>
<td style="text-align: center;">0.12</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">2574.27</td>
</tr>
<tr class="even">
<td style="text-align: center;">42</td>
<td style="text-align: center;">35001</td>
<td style="text-align: center;">Payson, AZ Micropolitan Statistical Area</td>
<td style="text-align: center;">0.12</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">2841.48</td>
</tr>
<tr class="odd">
<td style="text-align: center;">42</td>
<td style="text-align: center;">35001</td>
<td style="text-align: center;">Phoenix-Mesa-Scottsdale, AZ Metropolitan Statistical Area</td>
<td style="text-align: center;">0.12</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">2841.48</td>
</tr>
<tr class="even">
<td style="text-align: center;">43</td>
<td style="text-align: center;">37400</td>
<td style="text-align: center;">Gardnerville Ranchos, NV Micropolitan Statistical Area</td>
<td style="text-align: center;">0.12</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">3537.21</td>
</tr>
<tr class="odd">
<td style="text-align: center;">43</td>
<td style="text-align: center;">37400</td>
<td style="text-align: center;">Sacramento–Arden-Arcade–Roseville, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.12</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">3537.21</td>
</tr>
<tr class="even">
<td style="text-align: center;">43</td>
<td style="text-align: center;">37400</td>
<td style="text-align: center;">Stockton, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.12</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">3537.21</td>
</tr>
<tr class="odd">
<td style="text-align: center;">43</td>
<td style="text-align: center;">37400</td>
<td style="text-align: center;">Truckee-Grass Valley, CA Micropolitan Statistical Area</td>
<td style="text-align: center;">0.12</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">3537.21</td>
</tr>
<tr class="even">
<td style="text-align: center;">44</td>
<td style="text-align: center;">34901</td>
<td style="text-align: center;">Albuquerque, NM Metropolitan Statistical Area</td>
<td style="text-align: center;">0.12</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2334.66</td>
</tr>
<tr class="odd">
<td style="text-align: center;">44</td>
<td style="text-align: center;">34901</td>
<td style="text-align: center;">Grants, NM Micropolitan Statistical Area</td>
<td style="text-align: center;">0.12</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2334.66</td>
</tr>
<tr class="even">
<td style="text-align: center;">45</td>
<td style="text-align: center;">38100</td>
<td style="text-align: center;">El Centro, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.11</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">1849.33</td>
</tr>
<tr class="odd">
<td style="text-align: center;">45</td>
<td style="text-align: center;">38100</td>
<td style="text-align: center;">Yuma, AZ Metropolitan Statistical Area</td>
<td style="text-align: center;">0.11</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">1849.33</td>
</tr>
<tr class="even">
<td style="text-align: center;">46</td>
<td style="text-align: center;">36100</td>
<td style="text-align: center;">Ogden-Clearfield, UT Metropolitan Statistical Area</td>
<td style="text-align: center;">0.10</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2442.83</td>
</tr>
<tr class="odd">
<td style="text-align: center;">46</td>
<td style="text-align: center;">36100</td>
<td style="text-align: center;">Salt Lake City, UT Metropolitan Statistical Area</td>
<td style="text-align: center;">0.10</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2442.83</td>
</tr>
<tr class="even">
<td style="text-align: center;">47</td>
<td style="text-align: center;">36600</td>
<td style="text-align: center;">Red Bluff, CA Micropolitan Statistical Area</td>
<td style="text-align: center;">0.10</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2338.40</td>
</tr>
<tr class="odd">
<td style="text-align: center;">47</td>
<td style="text-align: center;">36600</td>
<td style="text-align: center;">Redding, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.10</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2338.40</td>
</tr>
<tr class="even">
<td style="text-align: center;">48</td>
<td style="text-align: center;">14600</td>
<td style="text-align: center;">Bedford, IN Micropolitan Statistical Area</td>
<td style="text-align: center;">0.10</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2075.80</td>
</tr>
<tr class="odd">
<td style="text-align: center;">48</td>
<td style="text-align: center;">14600</td>
<td style="text-align: center;">Bloomington, IN Metropolitan Statistical Area</td>
<td style="text-align: center;">0.10</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2075.80</td>
</tr>
<tr class="even">
<td style="text-align: center;">48</td>
<td style="text-align: center;">14600</td>
<td style="text-align: center;">Washington, IN Micropolitan Statistical Area</td>
<td style="text-align: center;">0.10</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2075.80</td>
</tr>
<tr class="odd">
<td style="text-align: center;">49</td>
<td style="text-align: center;">34102</td>
<td style="text-align: center;">Anchorage, AK Metropolitan Statistical Area</td>
<td style="text-align: center;">0.09</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2622.15</td>
</tr>
<tr class="even">
<td style="text-align: center;">50</td>
<td style="text-align: center;">1400</td>
<td style="text-align: center;">Fayetteville, NC Metropolitan Statistical Area</td>
<td style="text-align: center;">0.09</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">1697.22</td>
</tr>
<tr class="odd">
<td style="text-align: center;">50</td>
<td style="text-align: center;">1400</td>
<td style="text-align: center;">Laurinburg, NC Micropolitan Statistical Area</td>
<td style="text-align: center;">0.09</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">1697.22</td>
</tr>
<tr class="even">
<td style="text-align: center;">50</td>
<td style="text-align: center;">1400</td>
<td style="text-align: center;">Lumberton, NC Micropolitan Statistical Area</td>
<td style="text-align: center;">0.09</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">1697.22</td>
</tr>
<tr class="odd">
<td style="text-align: center;">50</td>
<td style="text-align: center;">1400</td>
<td style="text-align: center;">Rockingham, NC Micropolitan Statistical Area</td>
<td style="text-align: center;">0.09</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">1697.22</td>
</tr>
<tr class="even">
<td style="text-align: center;">50</td>
<td style="text-align: center;">1400</td>
<td style="text-align: center;">Southern Pines, NC Micropolitan Statistical Area</td>
<td style="text-align: center;">0.09</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">1697.22</td>
</tr>
<tr class="odd">
<td style="text-align: center;">51</td>
<td style="text-align: center;">20401</td>
<td style="text-align: center;">Providence-New Bedford-Fall River, RI-MA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.09</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2179.67</td>
</tr>
<tr class="even">
<td style="text-align: center;">52</td>
<td style="text-align: center;">31201</td>
<td style="text-align: center;">Austin-Round Rock, TX Metropolitan Statistical Area</td>
<td style="text-align: center;">0.09</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2551.18</td>
</tr>
<tr class="odd">
<td style="text-align: center;">53</td>
<td style="text-align: center;">9400</td>
<td style="text-align: center;">Cornelia, GA Micropolitan Statistical Area</td>
<td style="text-align: center;">0.09</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2013.64</td>
</tr>
<tr class="even">
<td style="text-align: center;">53</td>
<td style="text-align: center;">9400</td>
<td style="text-align: center;">Gainesville, GA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.09</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2013.64</td>
</tr>
<tr class="odd">
<td style="text-align: center;">54</td>
<td style="text-align: center;">39400</td>
<td style="text-align: center;">Bremerton-Silverdale, WA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2817.58</td>
</tr>
<tr class="even">
<td style="text-align: center;">54</td>
<td style="text-align: center;">39400</td>
<td style="text-align: center;">Centralia, WA Micropolitan Statistical Area</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2817.58</td>
</tr>
<tr class="odd">
<td style="text-align: center;">54</td>
<td style="text-align: center;">39400</td>
<td style="text-align: center;">Mount Vernon-Anacortes, WA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2817.58</td>
</tr>
<tr class="even">
<td style="text-align: center;">54</td>
<td style="text-align: center;">39400</td>
<td style="text-align: center;">Oak Harbor, WA Micropolitan Statistical Area</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2817.58</td>
</tr>
<tr class="odd">
<td style="text-align: center;">54</td>
<td style="text-align: center;">39400</td>
<td style="text-align: center;">Olympia, WA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2817.58</td>
</tr>
<tr class="even">
<td style="text-align: center;">54</td>
<td style="text-align: center;">39400</td>
<td style="text-align: center;">Seattle-Bellevue-Everett, WA Metropolitan Division</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2817.58</td>
</tr>
<tr class="odd">
<td style="text-align: center;">54</td>
<td style="text-align: center;">39400</td>
<td style="text-align: center;">Shelton, WA Micropolitan Statistical Area</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2817.58</td>
</tr>
<tr class="even">
<td style="text-align: center;">54</td>
<td style="text-align: center;">39400</td>
<td style="text-align: center;">Tacoma, WA Metropolitan Division</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2817.58</td>
</tr>
<tr class="odd">
<td style="text-align: center;">55</td>
<td style="text-align: center;">6800</td>
<td style="text-align: center;">Lakeland-Winter Haven, FL Metropolitan Statistical Area</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">1571.89</td>
</tr>
<tr class="even">
<td style="text-align: center;">55</td>
<td style="text-align: center;">6800</td>
<td style="text-align: center;">Sebring, FL Micropolitan Statistical Area</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">1571.89</td>
</tr>
<tr class="odd">
<td style="text-align: center;">55</td>
<td style="text-align: center;">6800</td>
<td style="text-align: center;">Wauchula, FL Micropolitan Statistical Area</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">1571.89</td>
</tr>
<tr class="even">
<td style="text-align: center;">56</td>
<td style="text-align: center;">23100</td>
<td style="text-align: center;">Baraboo, WI Micropolitan Statistical Area</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2040.49</td>
</tr>
<tr class="odd">
<td style="text-align: center;">56</td>
<td style="text-align: center;">23100</td>
<td style="text-align: center;">Madison, WI Metropolitan Statistical Area</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2040.49</td>
</tr>
<tr class="even">
<td style="text-align: center;">57</td>
<td style="text-align: center;">22100</td>
<td style="text-align: center;">Iowa City, IA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2209.68</td>
</tr>
<tr class="odd">
<td style="text-align: center;">57</td>
<td style="text-align: center;">22100</td>
<td style="text-align: center;">Muscatine, IA Micropolitan Statistical Area</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">2209.68</td>
</tr>
<tr class="even">
<td style="text-align: center;">58</td>
<td style="text-align: center;">30802</td>
<td style="text-align: center;">Levelland, TX Micropolitan Statistical Area</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">1529.46</td>
</tr>
<tr class="odd">
<td style="text-align: center;">58</td>
<td style="text-align: center;">30802</td>
<td style="text-align: center;">Lubbock, TX Metropolitan Statistical Area</td>
<td style="text-align: center;">0.08</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">1529.46</td>
</tr>
<tr class="even">
<td style="text-align: center;">59</td>
<td style="text-align: center;">28101</td>
<td style="text-align: center;">Beatrice, NE Micropolitan Statistical Area</td>
<td style="text-align: center;">0.07</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">1386.91</td>
</tr>
<tr class="odd">
<td style="text-align: center;">59</td>
<td style="text-align: center;">28101</td>
<td style="text-align: center;">Lincoln, NE Metropolitan Statistical Area</td>
<td style="text-align: center;">0.07</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">1386.91</td>
</tr>
<tr class="even">
<td style="text-align: center;">60</td>
<td style="text-align: center;">38601</td>
<td style="text-align: center;">Coeur d’Alene, ID Metropolitan Statistical Area</td>
<td style="text-align: center;">0.07</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1422.24</td>
</tr>
<tr class="odd">
<td style="text-align: center;">60</td>
<td style="text-align: center;">38601</td>
<td style="text-align: center;">Spokane, WA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.07</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1422.24</td>
</tr>
<tr class="even">
<td style="text-align: center;">61</td>
<td style="text-align: center;">19901</td>
<td style="text-align: center;">Dover, DE Metropolitan Statistical Area</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1392.28</td>
</tr>
<tr class="odd">
<td style="text-align: center;">61</td>
<td style="text-align: center;">19901</td>
<td style="text-align: center;">Ocean Pines, MD Micropolitan Statistical Area</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1392.28</td>
</tr>
<tr class="even">
<td style="text-align: center;">61</td>
<td style="text-align: center;">19901</td>
<td style="text-align: center;">Salisbury, MD Metropolitan Statistical Area</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1392.28</td>
</tr>
<tr class="odd">
<td style="text-align: center;">61</td>
<td style="text-align: center;">19901</td>
<td style="text-align: center;">Seaford, DE Micropolitan Statistical Area</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1392.28</td>
</tr>
<tr class="even">
<td style="text-align: center;">62</td>
<td style="text-align: center;">32900</td>
<td style="text-align: center;">Killeen-Temple-Fort Hood, TX Metropolitan Statistical Area</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">1294.78</td>
</tr>
<tr class="odd">
<td style="text-align: center;">63</td>
<td style="text-align: center;">30601</td>
<td style="text-align: center;">El Paso, TX Metropolitan Statistical Area</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">982.83</td>
</tr>
<tr class="even">
<td style="text-align: center;">63</td>
<td style="text-align: center;">30601</td>
<td style="text-align: center;">Las Cruces, NM Metropolitan Statistical Area</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">982.83</td>
</tr>
<tr class="odd">
<td style="text-align: center;">64</td>
<td style="text-align: center;">20902</td>
<td style="text-align: center;">Bennington, VT Micropolitan Statistical Area</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1281.95</td>
</tr>
<tr class="even">
<td style="text-align: center;">64</td>
<td style="text-align: center;">20902</td>
<td style="text-align: center;">Pittsfield, MA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.06</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1281.95</td>
</tr>
<tr class="odd">
<td style="text-align: center;">65</td>
<td style="text-align: center;">6401</td>
<td style="text-align: center;">Chattanooga, TN-GA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1096.19</td>
</tr>
<tr class="even">
<td style="text-align: center;">66</td>
<td style="text-align: center;">20100</td>
<td style="text-align: center;">Augusta-Waterville, ME Micropolitan Statistical Area</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1009.97</td>
</tr>
<tr class="odd">
<td style="text-align: center;">66</td>
<td style="text-align: center;">20100</td>
<td style="text-align: center;">Lewiston-Auburn, ME Metropolitan Statistical Area</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1009.97</td>
</tr>
<tr class="even">
<td style="text-align: center;">66</td>
<td style="text-align: center;">20100</td>
<td style="text-align: center;">Portland-South Portland, ME Metropolitan Statistical Area</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1009.97</td>
</tr>
<tr class="odd">
<td style="text-align: center;">67</td>
<td style="text-align: center;">36000</td>
<td style="text-align: center;">Provo-Orem, UT Metropolitan Statistical Area</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1337.52</td>
</tr>
<tr class="even">
<td style="text-align: center;">68</td>
<td style="text-align: center;">31301</td>
<td style="text-align: center;">San Antonio, TX Metropolitan Statistical Area</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1172.44</td>
</tr>
<tr class="odd">
<td style="text-align: center;">69</td>
<td style="text-align: center;">302</td>
<td style="text-align: center;">Harriman, TN Micropolitan Statistical Area</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">867.41</td>
</tr>
<tr class="even">
<td style="text-align: center;">69</td>
<td style="text-align: center;">302</td>
<td style="text-align: center;">Knoxville, TN Metropolitan Statistical Area</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">867.41</td>
</tr>
<tr class="odd">
<td style="text-align: center;">69</td>
<td style="text-align: center;">302</td>
<td style="text-align: center;">La Follette, TN Micropolitan Statistical Area</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">867.41</td>
</tr>
<tr class="even">
<td style="text-align: center;">70</td>
<td style="text-align: center;">7600</td>
<td style="text-align: center;">Jacksonville, FL Metropolitan Statistical Area</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1088.41</td>
</tr>
<tr class="odd">
<td style="text-align: center;">70</td>
<td style="text-align: center;">7600</td>
<td style="text-align: center;">St. Marys, GA Micropolitan Statistical Area</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1088.41</td>
</tr>
<tr class="even">
<td style="text-align: center;">71</td>
<td style="text-align: center;">17400</td>
<td style="text-align: center;">Chambersburg, PA Micropolitan Statistical Area</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1017.77</td>
</tr>
<tr class="odd">
<td style="text-align: center;">71</td>
<td style="text-align: center;">17400</td>
<td style="text-align: center;">Hagerstown-Martinsburg, MD-WV Metropolitan Statistical Area</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1017.77</td>
</tr>
<tr class="even">
<td style="text-align: center;">71</td>
<td style="text-align: center;">17400</td>
<td style="text-align: center;">Washington-Arlington-Alexandria, DC-VA-MD-WV Metropolitan Division</td>
<td style="text-align: center;">0.05</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1017.77</td>
</tr>
<tr class="odd">
<td style="text-align: center;">72</td>
<td style="text-align: center;">19600</td>
<td style="text-align: center;">Allentown-Bethlehem-Easton, PA-NJ Metropolitan Statistical Area</td>
<td style="text-align: center;">0.04</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1605.35</td>
</tr>
<tr class="even">
<td style="text-align: center;">72</td>
<td style="text-align: center;">19600</td>
<td style="text-align: center;">Edison, NJ Metropolitan Division</td>
<td style="text-align: center;">0.04</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1605.35</td>
</tr>
<tr class="odd">
<td style="text-align: center;">72</td>
<td style="text-align: center;">19600</td>
<td style="text-align: center;">New York-Wayne-White Plains, NY-NJ Metropolitan Division</td>
<td style="text-align: center;">0.04</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1605.35</td>
</tr>
<tr class="even">
<td style="text-align: center;">72</td>
<td style="text-align: center;">19600</td>
<td style="text-align: center;">Newark-Union, NJ-PA Metropolitan Division</td>
<td style="text-align: center;">0.04</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1605.35</td>
</tr>
<tr class="odd">
<td style="text-align: center;">72</td>
<td style="text-align: center;">19600</td>
<td style="text-align: center;">Trenton-Ewing, NJ Metropolitan Statistical Area</td>
<td style="text-align: center;">0.04</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">1605.35</td>
</tr>
<tr class="even">
<td style="text-align: center;">73</td>
<td style="text-align: center;">1100</td>
<td style="text-align: center;">Hickory-Morganton-Lenoir, NC Metropolitan Statistical Area</td>
<td style="text-align: center;">0.04</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">640.30</td>
</tr>
<tr class="odd">
<td style="text-align: center;">73</td>
<td style="text-align: center;">1100</td>
<td style="text-align: center;">Statesville-Mooresville, NC Micropolitan Statistical Area</td>
<td style="text-align: center;">0.04</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">640.30</td>
</tr>
<tr class="even">
<td style="text-align: center;">74</td>
<td style="text-align: center;">36301</td>
<td style="text-align: center;">Blackfoot, ID Micropolitan Statistical Area</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">671.92</td>
</tr>
<tr class="odd">
<td style="text-align: center;">74</td>
<td style="text-align: center;">36301</td>
<td style="text-align: center;">Idaho Falls, ID Metropolitan Statistical Area</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">671.92</td>
</tr>
<tr class="even">
<td style="text-align: center;">74</td>
<td style="text-align: center;">36301</td>
<td style="text-align: center;">Pocatello, ID Metropolitan Statistical Area</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">671.92</td>
</tr>
<tr class="odd">
<td style="text-align: center;">74</td>
<td style="text-align: center;">36301</td>
<td style="text-align: center;">Rexburg, ID Micropolitan Statistical Area</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">671.92</td>
</tr>
<tr class="even">
<td style="text-align: center;">75</td>
<td style="text-align: center;">22900</td>
<td style="text-align: center;">La Crosse, WI-MN Metropolitan Statistical Area</td>
<td style="text-align: center;">0.03</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">634.64</td>
</tr>
<tr class="odd">
<td style="text-align: center;">76</td>
<td style="text-align: center;">3300</td>
<td style="text-align: center;">Bogalusa, LA Micropolitan Statistical Area</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">0.00</td>
<td style="text-align: center;">472.80</td>
</tr>
<tr class="even">
<td style="text-align: center;">76</td>
<td style="text-align: center;">3300</td>
<td style="text-align: center;">New Orleans-Metairie-Kenner, LA Metropolitan Statistical Area</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">0.00</td>
<td style="text-align: center;">472.80</td>
</tr>
<tr class="odd">
<td style="text-align: center;">77</td>
<td style="text-align: center;">2700</td>
<td style="text-align: center;">Gulfport-Biloxi, MS Metropolitan Statistical Area</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">0.00</td>
<td style="text-align: center;">297.78</td>
</tr>
<tr class="even">
<td style="text-align: center;">77</td>
<td style="text-align: center;">2700</td>
<td style="text-align: center;">Pascagoula, MS Metropolitan Statistical Area</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">0.00</td>
<td style="text-align: center;">297.78</td>
</tr>
<tr class="odd">
<td style="text-align: center;">77</td>
<td style="text-align: center;">2700</td>
<td style="text-align: center;">Picayune, MS Micropolitan Statistical Area</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">0.00</td>
<td style="text-align: center;">297.78</td>
</tr>
<tr class="even">
<td style="text-align: center;">78</td>
<td style="text-align: center;">31503</td>
<td style="text-align: center;">Laredo, TX Metropolitan Statistical Area</td>
<td style="text-align: center;">0.02</td>
<td style="text-align: center;">0.00</td>
<td style="text-align: center;">296.21</td>
</tr>
<tr class="odd">
<td style="text-align: center;">79</td>
<td style="text-align: center;">37901</td>
<td style="text-align: center;">Lake Havasu City-Kingman, AZ Micropolitan Statistical Area</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">0.00</td>
<td style="text-align: center;">128.40</td>
</tr>
<tr class="even">
<td style="text-align: center;">79</td>
<td style="text-align: center;">37901</td>
<td style="text-align: center;">Las Vegas-Paradise, NV Metropolitan Statistical Area</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">0.00</td>
<td style="text-align: center;">128.40</td>
</tr>
<tr class="odd">
<td style="text-align: center;">79</td>
<td style="text-align: center;">37901</td>
<td style="text-align: center;">Pahrump, NV Micropolitan Statistical Area</td>
<td style="text-align: center;">0.01</td>
<td style="text-align: center;">0.00</td>
<td style="text-align: center;">128.40</td>
</tr>
<tr class="even">
<td style="text-align: center;">80</td>
<td style="text-align: center;">2400</td>
<td style="text-align: center;">Richmond, VA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">0.00</td>
<td style="text-align: center;">-171.04</td>
</tr>
<tr class="odd">
<td style="text-align: center;">81</td>
<td style="text-align: center;">1701</td>
<td style="text-align: center;">Dunn, NC Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">0.00</td>
<td style="text-align: center;">-275.52</td>
</tr>
<tr class="even">
<td style="text-align: center;">81</td>
<td style="text-align: center;">1701</td>
<td style="text-align: center;">Durham, NC Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">0.00</td>
<td style="text-align: center;">-275.52</td>
</tr>
<tr class="odd">
<td style="text-align: center;">81</td>
<td style="text-align: center;">1701</td>
<td style="text-align: center;">Raleigh-Cary, NC Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">0.00</td>
<td style="text-align: center;">-275.52</td>
</tr>
<tr class="even">
<td style="text-align: center;">81</td>
<td style="text-align: center;">1701</td>
<td style="text-align: center;">Sanford, NC Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">0.00</td>
<td style="text-align: center;">-275.52</td>
</tr>
<tr class="odd">
<td style="text-align: center;">82</td>
<td style="text-align: center;">500</td>
<td style="text-align: center;">Burlington, NC Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">0.00</td>
<td style="text-align: center;">-291.50</td>
</tr>
<tr class="even">
<td style="text-align: center;">82</td>
<td style="text-align: center;">500</td>
<td style="text-align: center;">Danville, VA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">0.00</td>
<td style="text-align: center;">-291.50</td>
</tr>
<tr class="odd">
<td style="text-align: center;">82</td>
<td style="text-align: center;">500</td>
<td style="text-align: center;">Greensboro-High Point, NC Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">0.00</td>
<td style="text-align: center;">-291.50</td>
</tr>
<tr class="even">
<td style="text-align: center;">82</td>
<td style="text-align: center;">500</td>
<td style="text-align: center;">Lexington-Thomasville, NC Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">0.00</td>
<td style="text-align: center;">-291.50</td>
</tr>
<tr class="odd">
<td style="text-align: center;">83</td>
<td style="text-align: center;">11304</td>
<td style="text-align: center;">Bethesda-Frederick-Gaithersburg, MD Metropolitan Division</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">0.00</td>
<td style="text-align: center;">-736.98</td>
</tr>
<tr class="even">
<td style="text-align: center;">83</td>
<td style="text-align: center;">11304</td>
<td style="text-align: center;">Lexington Park, MD Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">0.00</td>
<td style="text-align: center;">-736.98</td>
</tr>
<tr class="odd">
<td style="text-align: center;">83</td>
<td style="text-align: center;">11304</td>
<td style="text-align: center;">Washington-Arlington-Alexandria, DC-VA-MD-WV Metropolitan Division</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">0.00</td>
<td style="text-align: center;">-736.98</td>
</tr>
<tr class="even">
<td style="text-align: center;">84</td>
<td style="text-align: center;">37200</td>
<td style="text-align: center;">Fresno, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-485.69</td>
</tr>
<tr class="odd">
<td style="text-align: center;">84</td>
<td style="text-align: center;">37200</td>
<td style="text-align: center;">Hanford-Corcoran, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-485.69</td>
</tr>
<tr class="even">
<td style="text-align: center;">84</td>
<td style="text-align: center;">37200</td>
<td style="text-align: center;">Madera, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-485.69</td>
</tr>
<tr class="odd">
<td style="text-align: center;">84</td>
<td style="text-align: center;">37200</td>
<td style="text-align: center;">Visalia-Porterville, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-485.69</td>
</tr>
<tr class="even">
<td style="text-align: center;">85</td>
<td style="text-align: center;">100</td>
<td style="text-align: center;">Bristol, VA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-482.94</td>
</tr>
<tr class="odd">
<td style="text-align: center;">85</td>
<td style="text-align: center;">100</td>
<td style="text-align: center;">Greeneville, TN Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-482.94</td>
</tr>
<tr class="even">
<td style="text-align: center;">85</td>
<td style="text-align: center;">100</td>
<td style="text-align: center;">Johnson City, TN Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-482.94</td>
</tr>
<tr class="odd">
<td style="text-align: center;">85</td>
<td style="text-align: center;">100</td>
<td style="text-align: center;">Kingsport-Bristol, TN-VA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-482.94</td>
</tr>
<tr class="even">
<td style="text-align: center;">86</td>
<td style="text-align: center;">19500</td>
<td style="text-align: center;">Edison, NJ Metropolitan Division</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-1073.50</td>
</tr>
<tr class="odd">
<td style="text-align: center;">87</td>
<td style="text-align: center;">14500</td>
<td style="text-align: center;">Danville, IL Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-579.43</td>
</tr>
<tr class="even">
<td style="text-align: center;">87</td>
<td style="text-align: center;">14500</td>
<td style="text-align: center;">Frankfort, IN Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-579.43</td>
</tr>
<tr class="odd">
<td style="text-align: center;">87</td>
<td style="text-align: center;">14500</td>
<td style="text-align: center;">Lafayette, IN Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-579.43</td>
</tr>
<tr class="even">
<td style="text-align: center;">88</td>
<td style="text-align: center;">15000</td>
<td style="text-align: center;">Canton-Massillon, OH Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-491.70</td>
</tr>
<tr class="odd">
<td style="text-align: center;">88</td>
<td style="text-align: center;">15000</td>
<td style="text-align: center;">Coshocton, OH Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-491.70</td>
</tr>
<tr class="even">
<td style="text-align: center;">88</td>
<td style="text-align: center;">15000</td>
<td style="text-align: center;">New Philadelphia-Dover, OH Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-491.70</td>
</tr>
<tr class="odd">
<td style="text-align: center;">88</td>
<td style="text-align: center;">15000</td>
<td style="text-align: center;">Wooster, OH Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-491.70</td>
</tr>
<tr class="even">
<td style="text-align: center;">89</td>
<td style="text-align: center;">3400</td>
<td style="text-align: center;">Houma-Bayou Cane-Thibodaux, LA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-589.14</td>
</tr>
<tr class="odd">
<td style="text-align: center;">89</td>
<td style="text-align: center;">3400</td>
<td style="text-align: center;">Morgan City, LA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-589.14</td>
</tr>
<tr class="even">
<td style="text-align: center;">89</td>
<td style="text-align: center;">3400</td>
<td style="text-align: center;">Pierre Part, LA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-589.14</td>
</tr>
<tr class="odd">
<td style="text-align: center;">90</td>
<td style="text-align: center;">33100</td>
<td style="text-align: center;">Dallas-Plano-Irving, TX Metropolitan Division</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-980.90</td>
</tr>
<tr class="even">
<td style="text-align: center;">90</td>
<td style="text-align: center;">33100</td>
<td style="text-align: center;">Gainesville, TX Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-980.90</td>
</tr>
<tr class="odd">
<td style="text-align: center;">91</td>
<td style="text-align: center;">33000</td>
<td style="text-align: center;">Fort Worth-Arlington, TX Metropolitan Division</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-886.76</td>
</tr>
<tr class="even">
<td style="text-align: center;">91</td>
<td style="text-align: center;">33000</td>
<td style="text-align: center;">Granbury, TX Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-886.76</td>
</tr>
<tr class="odd">
<td style="text-align: center;">91</td>
<td style="text-align: center;">33000</td>
<td style="text-align: center;">Mineral Wells, TX Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-886.76</td>
</tr>
<tr class="even">
<td style="text-align: center;">92</td>
<td style="text-align: center;">6100</td>
<td style="text-align: center;">Albertville, AL Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-515.49</td>
</tr>
<tr class="odd">
<td style="text-align: center;">92</td>
<td style="text-align: center;">6100</td>
<td style="text-align: center;">Gadsden, AL Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-515.49</td>
</tr>
<tr class="even">
<td style="text-align: center;">92</td>
<td style="text-align: center;">6100</td>
<td style="text-align: center;">Scottsboro, AL Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-515.49</td>
</tr>
<tr class="odd">
<td style="text-align: center;">93</td>
<td style="text-align: center;">20001</td>
<td style="text-align: center;">Bangor, ME Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-624.09</td>
</tr>
<tr class="even">
<td style="text-align: center;">93</td>
<td style="text-align: center;">20001</td>
<td style="text-align: center;">Rockland, ME Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-624.09</td>
</tr>
<tr class="odd">
<td style="text-align: center;">94</td>
<td style="text-align: center;">8300</td>
<td style="text-align: center;">Anderson, SC Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.05</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-851.40</td>
</tr>
<tr class="even">
<td style="text-align: center;">94</td>
<td style="text-align: center;">8300</td>
<td style="text-align: center;">Greenville, SC Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.05</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-851.40</td>
</tr>
<tr class="odd">
<td style="text-align: center;">94</td>
<td style="text-align: center;">8300</td>
<td style="text-align: center;">Greenwood, SC Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.05</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-851.40</td>
</tr>
<tr class="even">
<td style="text-align: center;">94</td>
<td style="text-align: center;">8300</td>
<td style="text-align: center;">Seneca, SC Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.05</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-851.40</td>
</tr>
<tr class="odd">
<td style="text-align: center;">95</td>
<td style="text-align: center;">401</td>
<td style="text-align: center;">Mount Airy, NC Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.05</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-1096.26</td>
</tr>
<tr class="even">
<td style="text-align: center;">95</td>
<td style="text-align: center;">401</td>
<td style="text-align: center;">Winston-Salem, NC Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.05</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-1096.26</td>
</tr>
<tr class="odd">
<td style="text-align: center;">96</td>
<td style="text-align: center;">13101</td>
<td style="text-align: center;">Louisville, KY-IN Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-1132.45</td>
</tr>
<tr class="even">
<td style="text-align: center;">97</td>
<td style="text-align: center;">900</td>
<td style="text-align: center;">Albemarle, NC Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-1357.66</td>
</tr>
<tr class="odd">
<td style="text-align: center;">97</td>
<td style="text-align: center;">900</td>
<td style="text-align: center;">Charlotte-Gastonia-Concord, NC-SC Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-1357.66</td>
</tr>
<tr class="even">
<td style="text-align: center;">97</td>
<td style="text-align: center;">900</td>
<td style="text-align: center;">Chester, SC Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-1357.66</td>
</tr>
<tr class="odd">
<td style="text-align: center;">97</td>
<td style="text-align: center;">900</td>
<td style="text-align: center;">Lancaster, SC Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-1357.66</td>
</tr>
<tr class="even">
<td style="text-align: center;">97</td>
<td style="text-align: center;">900</td>
<td style="text-align: center;">Salisbury, NC Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-1357.66</td>
</tr>
<tr class="odd">
<td style="text-align: center;">98</td>
<td style="text-align: center;">31700</td>
<td style="text-align: center;">Alice, TX Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-1309.61</td>
</tr>
<tr class="even">
<td style="text-align: center;">98</td>
<td style="text-align: center;">31700</td>
<td style="text-align: center;">Corpus Christi, TX Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-1309.61</td>
</tr>
<tr class="odd">
<td style="text-align: center;">98</td>
<td style="text-align: center;">31700</td>
<td style="text-align: center;">Kingsville, TX Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-0.01</td>
<td style="text-align: center;">-1309.61</td>
</tr>
<tr class="even">
<td style="text-align: center;">99</td>
<td style="text-align: center;">1900</td>
<td style="text-align: center;">Greenville, NC Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.08</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1425.44</td>
</tr>
<tr class="odd">
<td style="text-align: center;">99</td>
<td style="text-align: center;">1900</td>
<td style="text-align: center;">Jacksonville, NC Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.08</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1425.44</td>
</tr>
<tr class="even">
<td style="text-align: center;">99</td>
<td style="text-align: center;">1900</td>
<td style="text-align: center;">Kinston, NC Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.08</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1425.44</td>
</tr>
<tr class="odd">
<td style="text-align: center;">99</td>
<td style="text-align: center;">1900</td>
<td style="text-align: center;">Morehead City, NC Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.08</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1425.44</td>
</tr>
<tr class="even">
<td style="text-align: center;">99</td>
<td style="text-align: center;">1900</td>
<td style="text-align: center;">New Bern, NC Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.08</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1425.44</td>
</tr>
<tr class="odd">
<td style="text-align: center;">100</td>
<td style="text-align: center;">12200</td>
<td style="text-align: center;">Allegan, MI Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.08</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1529.58</td>
</tr>
<tr class="even">
<td style="text-align: center;">100</td>
<td style="text-align: center;">12200</td>
<td style="text-align: center;">Grand Rapids-Wyoming, MI Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.08</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1529.58</td>
</tr>
<tr class="odd">
<td style="text-align: center;">100</td>
<td style="text-align: center;">12200</td>
<td style="text-align: center;">Holland-Grand Haven, MI Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.08</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1529.58</td>
</tr>
<tr class="even">
<td style="text-align: center;">100</td>
<td style="text-align: center;">12200</td>
<td style="text-align: center;">Muskegon-Norton Shores, MI Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.08</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1529.58</td>
</tr>
<tr class="odd">
<td style="text-align: center;">101</td>
<td style="text-align: center;">2500</td>
<td style="text-align: center;">Virginia Beach-Norfolk-Newport News, VA-NC Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.08</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1663.49</td>
</tr>
<tr class="even">
<td style="text-align: center;">102</td>
<td style="text-align: center;">24300</td>
<td style="text-align: center;">Chicago-Naperville-Joliet, IL Metropolitan Division</td>
<td style="text-align: center;">-0.08</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2519.52</td>
</tr>
<tr class="odd">
<td style="text-align: center;">102</td>
<td style="text-align: center;">24300</td>
<td style="text-align: center;">Lake County-Kenosha County, IL-WI Metropolitan Division</td>
<td style="text-align: center;">-0.08</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2519.52</td>
</tr>
<tr class="even">
<td style="text-align: center;">103</td>
<td style="text-align: center;">8401</td>
<td style="text-align: center;">Augusta-Richmond County, GA-SC Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.09</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1876.20</td>
</tr>
<tr class="odd">
<td style="text-align: center;">104</td>
<td style="text-align: center;">16500</td>
<td style="text-align: center;">Erie, PA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.09</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1608.09</td>
</tr>
<tr class="even">
<td style="text-align: center;">104</td>
<td style="text-align: center;">16500</td>
<td style="text-align: center;">Jamestown-Dunkirk-Fredonia, NY Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.09</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1608.09</td>
</tr>
<tr class="odd">
<td style="text-align: center;">104</td>
<td style="text-align: center;">16500</td>
<td style="text-align: center;">Meadville, PA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.09</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1608.09</td>
</tr>
<tr class="even">
<td style="text-align: center;">104</td>
<td style="text-align: center;">16500</td>
<td style="text-align: center;">Oil City, PA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.09</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1608.09</td>
</tr>
<tr class="odd">
<td style="text-align: center;">104</td>
<td style="text-align: center;">16500</td>
<td style="text-align: center;">Warren, PA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.09</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1608.09</td>
</tr>
<tr class="even">
<td style="text-align: center;">105</td>
<td style="text-align: center;">8900</td>
<td style="text-align: center;">Fort Valley, GA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.09</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1810.54</td>
</tr>
<tr class="odd">
<td style="text-align: center;">105</td>
<td style="text-align: center;">8900</td>
<td style="text-align: center;">Macon, GA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.09</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1810.54</td>
</tr>
<tr class="even">
<td style="text-align: center;">105</td>
<td style="text-align: center;">8900</td>
<td style="text-align: center;">Warner Robins, GA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.09</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1810.54</td>
</tr>
<tr class="odd">
<td style="text-align: center;">106</td>
<td style="text-align: center;">37000</td>
<td style="text-align: center;">Merced, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.09</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2246.95</td>
</tr>
<tr class="even">
<td style="text-align: center;">106</td>
<td style="text-align: center;">37000</td>
<td style="text-align: center;">Modesto, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.09</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2246.95</td>
</tr>
<tr class="odd">
<td style="text-align: center;">106</td>
<td style="text-align: center;">37000</td>
<td style="text-align: center;">Phoenix Lake-Cedar Ridge, CA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.09</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2246.95</td>
</tr>
<tr class="even">
<td style="text-align: center;">107</td>
<td style="text-align: center;">9100</td>
<td style="text-align: center;">Atlanta-Sandy Springs-Marietta, GA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.09</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2356.80</td>
</tr>
<tr class="odd">
<td style="text-align: center;">108</td>
<td style="text-align: center;">23400</td>
<td style="text-align: center;">Bloomington-Normal, IL Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.10</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2045.48</td>
</tr>
<tr class="even">
<td style="text-align: center;">108</td>
<td style="text-align: center;">23400</td>
<td style="text-align: center;">Pontiac, IL Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.10</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2045.48</td>
</tr>
<tr class="odd">
<td style="text-align: center;">109</td>
<td style="text-align: center;">8503</td>
<td style="text-align: center;">Moultrie, GA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.10</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1700.92</td>
</tr>
<tr class="even">
<td style="text-align: center;">109</td>
<td style="text-align: center;">8503</td>
<td style="text-align: center;">Tifton, GA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.10</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1700.92</td>
</tr>
<tr class="odd">
<td style="text-align: center;">109</td>
<td style="text-align: center;">8503</td>
<td style="text-align: center;">Valdosta, GA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.10</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1700.92</td>
</tr>
<tr class="even">
<td style="text-align: center;">110</td>
<td style="text-align: center;">11302</td>
<td style="text-align: center;">Baltimore-Towson, MD Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.10</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2870.19</td>
</tr>
<tr class="odd">
<td style="text-align: center;">111</td>
<td style="text-align: center;">19700</td>
<td style="text-align: center;">Atlantic City, NJ Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.10</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2881.93</td>
</tr>
<tr class="even">
<td style="text-align: center;">111</td>
<td style="text-align: center;">19700</td>
<td style="text-align: center;">Camden, NJ Metropolitan Division</td>
<td style="text-align: center;">-0.10</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2881.93</td>
</tr>
<tr class="odd">
<td style="text-align: center;">111</td>
<td style="text-align: center;">19700</td>
<td style="text-align: center;">Ocean City, NJ Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.10</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2881.93</td>
</tr>
<tr class="even">
<td style="text-align: center;">111</td>
<td style="text-align: center;">19700</td>
<td style="text-align: center;">Philadelphia, PA Metropolitan Division</td>
<td style="text-align: center;">-0.10</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2881.93</td>
</tr>
<tr class="odd">
<td style="text-align: center;">111</td>
<td style="text-align: center;">19700</td>
<td style="text-align: center;">Vineland-Millville-Bridgeton, NJ Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.10</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2881.93</td>
</tr>
<tr class="even">
<td style="text-align: center;">111</td>
<td style="text-align: center;">19700</td>
<td style="text-align: center;">Wilmington, DE-MD-NJ Metropolitan Division</td>
<td style="text-align: center;">-0.10</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2881.93</td>
</tr>
<tr class="odd">
<td style="text-align: center;">112</td>
<td style="text-align: center;">11001</td>
<td style="text-align: center;">Daphne-Fairhope, AL Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.10</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1807.09</td>
</tr>
<tr class="even">
<td style="text-align: center;">112</td>
<td style="text-align: center;">11001</td>
<td style="text-align: center;">Mobile, AL Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.10</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1807.09</td>
</tr>
<tr class="odd">
<td style="text-align: center;">113</td>
<td style="text-align: center;">30903</td>
<td style="text-align: center;">Amarillo, TX Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.10</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2088.52</td>
</tr>
<tr class="even">
<td style="text-align: center;">113</td>
<td style="text-align: center;">30903</td>
<td style="text-align: center;">Hereford, TX Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.10</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2088.52</td>
</tr>
<tr class="odd">
<td style="text-align: center;">114</td>
<td style="text-align: center;">700</td>
<td style="text-align: center;">Gaffney, SC Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.11</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1718.17</td>
</tr>
<tr class="even">
<td style="text-align: center;">114</td>
<td style="text-align: center;">700</td>
<td style="text-align: center;">Spartanburg, SC Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.11</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1718.17</td>
</tr>
<tr class="odd">
<td style="text-align: center;">114</td>
<td style="text-align: center;">700</td>
<td style="text-align: center;">Union, SC Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.11</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-1718.17</td>
</tr>
<tr class="even">
<td style="text-align: center;">115</td>
<td style="text-align: center;">26801</td>
<td style="text-align: center;">Fargo, ND-MN Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.11</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2176.17</td>
</tr>
<tr class="odd">
<td style="text-align: center;">115</td>
<td style="text-align: center;">26801</td>
<td style="text-align: center;">Wahpeton, ND-MN Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.11</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2176.17</td>
</tr>
<tr class="even">
<td style="text-align: center;">116</td>
<td style="text-align: center;">3800</td>
<td style="text-align: center;">Abbeville, LA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.11</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2192.51</td>
</tr>
<tr class="odd">
<td style="text-align: center;">116</td>
<td style="text-align: center;">3800</td>
<td style="text-align: center;">Crowley, LA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.11</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2192.51</td>
</tr>
<tr class="even">
<td style="text-align: center;">116</td>
<td style="text-align: center;">3800</td>
<td style="text-align: center;">Lafayette, LA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.11</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2192.51</td>
</tr>
<tr class="odd">
<td style="text-align: center;">116</td>
<td style="text-align: center;">3800</td>
<td style="text-align: center;">New Iberia, LA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.11</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2192.51</td>
</tr>
<tr class="even">
<td style="text-align: center;">116</td>
<td style="text-align: center;">3800</td>
<td style="text-align: center;">Opelousas-Eunice, LA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.11</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2192.51</td>
</tr>
<tr class="odd">
<td style="text-align: center;">117</td>
<td style="text-align: center;">15900</td>
<td style="text-align: center;">Columbus, OH Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.11</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2583.01</td>
</tr>
<tr class="even">
<td style="text-align: center;">117</td>
<td style="text-align: center;">15900</td>
<td style="text-align: center;">Mount Vernon, OH Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.11</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2583.01</td>
</tr>
<tr class="odd">
<td style="text-align: center;">118</td>
<td style="text-align: center;">20901</td>
<td style="text-align: center;">Bridgeport-Stamford-Norwalk, CT Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.11</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-3740.66</td>
</tr>
<tr class="even">
<td style="text-align: center;">118</td>
<td style="text-align: center;">20901</td>
<td style="text-align: center;">Hartford-West Hartford-East Hartford, CT Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.11</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-3740.66</td>
</tr>
<tr class="odd">
<td style="text-align: center;">118</td>
<td style="text-align: center;">20901</td>
<td style="text-align: center;">New Haven-Milford, CT Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.11</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-3740.66</td>
</tr>
<tr class="even">
<td style="text-align: center;">118</td>
<td style="text-align: center;">20901</td>
<td style="text-align: center;">Norwich-New London, CT Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.11</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-3740.66</td>
</tr>
<tr class="odd">
<td style="text-align: center;">118</td>
<td style="text-align: center;">20901</td>
<td style="text-align: center;">Torrington, CT Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.11</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-3740.66</td>
</tr>
<tr class="even">
<td style="text-align: center;">118</td>
<td style="text-align: center;">20901</td>
<td style="text-align: center;">Willimantic, CT Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.11</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-3740.66</td>
</tr>
<tr class="odd">
<td style="text-align: center;">119</td>
<td style="text-align: center;">19800</td>
<td style="text-align: center;">Wilmington, DE-MD-NJ Metropolitan Division</td>
<td style="text-align: center;">-0.12</td>
<td style="text-align: center;">-0.02</td>
<td style="text-align: center;">-2884.66</td>
</tr>
<tr class="even">
<td style="text-align: center;">120</td>
<td style="text-align: center;">10700</td>
<td style="text-align: center;">Birmingham-Hoover, AL Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.12</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-2546.74</td>
</tr>
<tr class="odd">
<td style="text-align: center;">120</td>
<td style="text-align: center;">10700</td>
<td style="text-align: center;">Cullman, AL Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.12</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-2546.74</td>
</tr>
<tr class="even">
<td style="text-align: center;">121</td>
<td style="text-align: center;">24100</td>
<td style="text-align: center;">Beaver Dam, WI Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.12</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-2632.77</td>
</tr>
<tr class="odd">
<td style="text-align: center;">121</td>
<td style="text-align: center;">24100</td>
<td style="text-align: center;">Milwaukee-Waukesha-West Allis, WI Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.12</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-2632.77</td>
</tr>
<tr class="even">
<td style="text-align: center;">121</td>
<td style="text-align: center;">24100</td>
<td style="text-align: center;">Watertown-Fort Atkinson, WI Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.12</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-2632.77</td>
</tr>
<tr class="odd">
<td style="text-align: center;">122</td>
<td style="text-align: center;">33803</td>
<td style="text-align: center;">Oklahoma City, OK Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.12</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-2624.40</td>
</tr>
<tr class="even">
<td style="text-align: center;">122</td>
<td style="text-align: center;">33803</td>
<td style="text-align: center;">Shawnee, OK Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.12</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-2624.40</td>
</tr>
<tr class="odd">
<td style="text-align: center;">123</td>
<td style="text-align: center;">21501</td>
<td style="text-align: center;">Minneapolis-St. Paul-Bloomington, MN-WI Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.12</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-3261.15</td>
</tr>
<tr class="even">
<td style="text-align: center;">124</td>
<td style="text-align: center;">39000</td>
<td style="text-align: center;">Ellensburg, WA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.14</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-2548.77</td>
</tr>
<tr class="odd">
<td style="text-align: center;">124</td>
<td style="text-align: center;">39000</td>
<td style="text-align: center;">Yakima, WA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.14</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-2548.77</td>
</tr>
<tr class="even">
<td style="text-align: center;">125</td>
<td style="text-align: center;">24000</td>
<td style="text-align: center;">Janesville, WI Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.14</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-2982.16</td>
</tr>
<tr class="odd">
<td style="text-align: center;">125</td>
<td style="text-align: center;">24000</td>
<td style="text-align: center;">Lake County-Kenosha County, IL-WI Metropolitan Division</td>
<td style="text-align: center;">-0.14</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-2982.16</td>
</tr>
<tr class="even">
<td style="text-align: center;">125</td>
<td style="text-align: center;">24000</td>
<td style="text-align: center;">Racine, WI Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.14</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-2982.16</td>
</tr>
<tr class="odd">
<td style="text-align: center;">125</td>
<td style="text-align: center;">24000</td>
<td style="text-align: center;">Whitewater, WI Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.14</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-2982.16</td>
</tr>
<tr class="even">
<td style="text-align: center;">126</td>
<td style="text-align: center;">31600</td>
<td style="text-align: center;">Brownsville-Harlingen, TX Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.15</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-2206.98</td>
</tr>
<tr class="odd">
<td style="text-align: center;">126</td>
<td style="text-align: center;">31600</td>
<td style="text-align: center;">McAllen-Edinburg-Pharr, TX Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.15</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-2206.98</td>
</tr>
<tr class="even">
<td style="text-align: center;">126</td>
<td style="text-align: center;">31600</td>
<td style="text-align: center;">Raymondville, TX Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.15</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-2206.98</td>
</tr>
<tr class="odd">
<td style="text-align: center;">126</td>
<td style="text-align: center;">31600</td>
<td style="text-align: center;">Rio Grande City, TX Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.15</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-2206.98</td>
</tr>
<tr class="even">
<td style="text-align: center;">127</td>
<td style="text-align: center;">32000</td>
<td style="text-align: center;">Brenham, TX Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.15</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-3916.44</td>
</tr>
<tr class="odd">
<td style="text-align: center;">127</td>
<td style="text-align: center;">32000</td>
<td style="text-align: center;">Houston-Baytown-Sugar Land, TX Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.15</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-3916.44</td>
</tr>
<tr class="even">
<td style="text-align: center;">128</td>
<td style="text-align: center;">4200</td>
<td style="text-align: center;">Little Rock-North Little Rock, AR Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.15</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-2899.20</td>
</tr>
<tr class="odd">
<td style="text-align: center;">129</td>
<td style="text-align: center;">37100</td>
<td style="text-align: center;">Bakersfield, CA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.15</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3353.90</td>
</tr>
<tr class="even">
<td style="text-align: center;">130</td>
<td style="text-align: center;">22601</td>
<td style="text-align: center;">Green Bay, WI Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.15</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-2720.98</td>
</tr>
<tr class="odd">
<td style="text-align: center;">131</td>
<td style="text-align: center;">18800</td>
<td style="text-align: center;">Bloomsburg-Berwick, PA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.15</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3504.94</td>
</tr>
<tr class="even">
<td style="text-align: center;">131</td>
<td style="text-align: center;">18800</td>
<td style="text-align: center;">East Stroudsburg, PA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.15</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3504.94</td>
</tr>
<tr class="odd">
<td style="text-align: center;">131</td>
<td style="text-align: center;">18800</td>
<td style="text-align: center;">Newark-Union, NJ-PA Metropolitan Division</td>
<td style="text-align: center;">-0.15</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3504.94</td>
</tr>
<tr class="even">
<td style="text-align: center;">131</td>
<td style="text-align: center;">18800</td>
<td style="text-align: center;">Scranton–Wilkes-Barre, PA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.15</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3504.94</td>
</tr>
<tr class="odd">
<td style="text-align: center;">132</td>
<td style="text-align: center;">19300</td>
<td style="text-align: center;">Kingston, NY Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.16</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-5008.77</td>
</tr>
<tr class="even">
<td style="text-align: center;">132</td>
<td style="text-align: center;">19300</td>
<td style="text-align: center;">Poughkeepsie-Newburgh-Middletown, NY Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.16</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-5008.77</td>
</tr>
<tr class="odd">
<td style="text-align: center;">133</td>
<td style="text-align: center;">28202</td>
<td style="text-align: center;">Fremont, NE Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.16</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-3612.71</td>
</tr>
<tr class="even">
<td style="text-align: center;">133</td>
<td style="text-align: center;">28202</td>
<td style="text-align: center;">Omaha-Council Bluffs, NE-IA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.16</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-3612.71</td>
</tr>
<tr class="odd">
<td style="text-align: center;">134</td>
<td style="text-align: center;">18600</td>
<td style="text-align: center;">Albany-Schenectady-Troy, NY Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.16</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-3765.57</td>
</tr>
<tr class="even">
<td style="text-align: center;">134</td>
<td style="text-align: center;">18600</td>
<td style="text-align: center;">Glens Falls, NY Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.16</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-3765.57</td>
</tr>
<tr class="odd">
<td style="text-align: center;">134</td>
<td style="text-align: center;">18600</td>
<td style="text-align: center;">Hudson, NY Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.16</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-3765.57</td>
</tr>
<tr class="even">
<td style="text-align: center;">135</td>
<td style="text-align: center;">19100</td>
<td style="text-align: center;">Lancaster, PA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.16</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-3175.99</td>
</tr>
<tr class="odd">
<td style="text-align: center;">135</td>
<td style="text-align: center;">19100</td>
<td style="text-align: center;">Lebanon, PA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.16</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-3175.99</td>
</tr>
<tr class="even">
<td style="text-align: center;">135</td>
<td style="text-align: center;">19100</td>
<td style="text-align: center;">Pottsville, PA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.16</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-3175.99</td>
</tr>
<tr class="odd">
<td style="text-align: center;">135</td>
<td style="text-align: center;">19100</td>
<td style="text-align: center;">Reading, PA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.16</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-3175.99</td>
</tr>
<tr class="even">
<td style="text-align: center;">136</td>
<td style="text-align: center;">19200</td>
<td style="text-align: center;">Gettysburg, PA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.17</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3563.49</td>
</tr>
<tr class="odd">
<td style="text-align: center;">136</td>
<td style="text-align: center;">19200</td>
<td style="text-align: center;">Harrisburg-Carlisle, PA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.17</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3563.49</td>
</tr>
<tr class="even">
<td style="text-align: center;">136</td>
<td style="text-align: center;">19200</td>
<td style="text-align: center;">Lewistown, PA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.17</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3563.49</td>
</tr>
<tr class="odd">
<td style="text-align: center;">136</td>
<td style="text-align: center;">19200</td>
<td style="text-align: center;">York-Hanover, PA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.17</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3563.49</td>
</tr>
<tr class="even">
<td style="text-align: center;">137</td>
<td style="text-align: center;">24701</td>
<td style="text-align: center;">St. Louis, MO-IL Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.17</td>
<td style="text-align: center;">-0.03</td>
<td style="text-align: center;">-3732.60</td>
</tr>
<tr class="odd">
<td style="text-align: center;">138</td>
<td style="text-align: center;">13600</td>
<td style="text-align: center;">Michigan City-La Porte, IN Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.17</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3049.38</td>
</tr>
<tr class="even">
<td style="text-align: center;">138</td>
<td style="text-align: center;">13600</td>
<td style="text-align: center;">Niles-Benton Harbor, MI Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.17</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3049.38</td>
</tr>
<tr class="odd">
<td style="text-align: center;">138</td>
<td style="text-align: center;">13600</td>
<td style="text-align: center;">Plymouth, IN Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.17</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3049.38</td>
</tr>
<tr class="even">
<td style="text-align: center;">138</td>
<td style="text-align: center;">13600</td>
<td style="text-align: center;">South Bend-Mishawaka, IN-MI Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.17</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3049.38</td>
</tr>
<tr class="odd">
<td style="text-align: center;">139</td>
<td style="text-align: center;">22500</td>
<td style="text-align: center;">Appleton, WI Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.18</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3193.63</td>
</tr>
<tr class="even">
<td style="text-align: center;">139</td>
<td style="text-align: center;">22500</td>
<td style="text-align: center;">Fond du Lac, WI Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.18</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3193.63</td>
</tr>
<tr class="odd">
<td style="text-align: center;">139</td>
<td style="text-align: center;">22500</td>
<td style="text-align: center;">Oshkosh-Neenah, WI Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.18</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3193.63</td>
</tr>
<tr class="even">
<td style="text-align: center;">140</td>
<td style="text-align: center;">31401</td>
<td style="text-align: center;">Andrews, TX Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.18</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-5274.60</td>
</tr>
<tr class="odd">
<td style="text-align: center;">140</td>
<td style="text-align: center;">31401</td>
<td style="text-align: center;">Midland, TX Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.18</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-5274.60</td>
</tr>
<tr class="even">
<td style="text-align: center;">140</td>
<td style="text-align: center;">31401</td>
<td style="text-align: center;">Odessa, TX Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.18</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-5274.60</td>
</tr>
<tr class="odd">
<td style="text-align: center;">141</td>
<td style="text-align: center;">4002</td>
<td style="text-align: center;">Minden, LA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.18</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3344.52</td>
</tr>
<tr class="even">
<td style="text-align: center;">141</td>
<td style="text-align: center;">4002</td>
<td style="text-align: center;">Natchitoches, LA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.18</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3344.52</td>
</tr>
<tr class="odd">
<td style="text-align: center;">141</td>
<td style="text-align: center;">4002</td>
<td style="text-align: center;">Shreveport-Bossier City, LA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.18</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3344.52</td>
</tr>
<tr class="even">
<td style="text-align: center;">142</td>
<td style="text-align: center;">11600</td>
<td style="text-align: center;">Ann Arbor, MI Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.18</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-4182.40</td>
</tr>
<tr class="odd">
<td style="text-align: center;">142</td>
<td style="text-align: center;">11600</td>
<td style="text-align: center;">Detroit-Livonia-Dearborn, MI Metropolitan Division</td>
<td style="text-align: center;">-0.18</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-4182.40</td>
</tr>
<tr class="even">
<td style="text-align: center;">142</td>
<td style="text-align: center;">11600</td>
<td style="text-align: center;">Flint, MI Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.18</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-4182.40</td>
</tr>
<tr class="odd">
<td style="text-align: center;">142</td>
<td style="text-align: center;">11600</td>
<td style="text-align: center;">Owosso, MI Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.18</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-4182.40</td>
</tr>
<tr class="even">
<td style="text-align: center;">142</td>
<td style="text-align: center;">11600</td>
<td style="text-align: center;">Warren-Farmington Hills-Troy, MI Metropolitan Division</td>
<td style="text-align: center;">-0.18</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-4182.40</td>
</tr>
<tr class="odd">
<td style="text-align: center;">143</td>
<td style="text-align: center;">14700</td>
<td style="text-align: center;">Evansville, IN-KY Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.19</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3497.59</td>
</tr>
<tr class="even">
<td style="text-align: center;">143</td>
<td style="text-align: center;">14700</td>
<td style="text-align: center;">Jasper, IN Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.19</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3497.59</td>
</tr>
<tr class="odd">
<td style="text-align: center;">144</td>
<td style="text-align: center;">14200</td>
<td style="text-align: center;">Indianapolis, IN Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.19</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3839.66</td>
</tr>
<tr class="even">
<td style="text-align: center;">145</td>
<td style="text-align: center;">29502</td>
<td style="text-align: center;">Kansas City, MO-KS Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.19</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-4309.71</td>
</tr>
<tr class="odd">
<td style="text-align: center;">145</td>
<td style="text-align: center;">29502</td>
<td style="text-align: center;">Warrensburg, MO Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.19</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-4309.71</td>
</tr>
<tr class="even">
<td style="text-align: center;">146</td>
<td style="text-align: center;">30300</td>
<td style="text-align: center;">Fayetteville-Springdale-Rogers, AR-MO Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.21</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-4227.34</td>
</tr>
<tr class="odd">
<td style="text-align: center;">147</td>
<td style="text-align: center;">22700</td>
<td style="text-align: center;">Merrill, WI Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.21</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3679.84</td>
</tr>
<tr class="even">
<td style="text-align: center;">147</td>
<td style="text-align: center;">22700</td>
<td style="text-align: center;">Stevens Point, WI Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.21</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3679.84</td>
</tr>
<tr class="odd">
<td style="text-align: center;">147</td>
<td style="text-align: center;">22700</td>
<td style="text-align: center;">Wausau, WI Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.21</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3679.84</td>
</tr>
<tr class="even">
<td style="text-align: center;">147</td>
<td style="text-align: center;">22700</td>
<td style="text-align: center;">Wisconsin Rapids-Marshfield, WI Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.21</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3679.84</td>
</tr>
<tr class="odd">
<td style="text-align: center;">148</td>
<td style="text-align: center;">14100</td>
<td style="text-align: center;">Angola, IN Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.22</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3789.17</td>
</tr>
<tr class="even">
<td style="text-align: center;">148</td>
<td style="text-align: center;">14100</td>
<td style="text-align: center;">Auburn, IN Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.22</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3789.17</td>
</tr>
<tr class="odd">
<td style="text-align: center;">148</td>
<td style="text-align: center;">14100</td>
<td style="text-align: center;">Decatur, IN Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.22</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3789.17</td>
</tr>
<tr class="even">
<td style="text-align: center;">148</td>
<td style="text-align: center;">14100</td>
<td style="text-align: center;">Fort Wayne, IN Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.22</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3789.17</td>
</tr>
<tr class="odd">
<td style="text-align: center;">148</td>
<td style="text-align: center;">14100</td>
<td style="text-align: center;">Huntington, IN Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.22</td>
<td style="text-align: center;">-0.04</td>
<td style="text-align: center;">-3789.17</td>
</tr>
<tr class="even">
<td style="text-align: center;">149</td>
<td style="text-align: center;">5202</td>
<td style="text-align: center;">Memphis, TN-MS-AR Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.23</td>
<td style="text-align: center;">-0.05</td>
<td style="text-align: center;">-5185.26</td>
</tr>
<tr class="odd">
<td style="text-align: center;">150</td>
<td style="text-align: center;">3901</td>
<td style="text-align: center;">Bastrop, LA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.25</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-4656.62</td>
</tr>
<tr class="even">
<td style="text-align: center;">150</td>
<td style="text-align: center;">3901</td>
<td style="text-align: center;">Monroe, LA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.25</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-4656.62</td>
</tr>
<tr class="odd">
<td style="text-align: center;">151</td>
<td style="text-align: center;">22001</td>
<td style="text-align: center;">Waterloo-Cedar Falls, IA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.25</td>
<td style="text-align: center;">-0.05</td>
<td style="text-align: center;">-5679.28</td>
</tr>
<tr class="even">
<td style="text-align: center;">152</td>
<td style="text-align: center;">24802</td>
<td style="text-align: center;">Lincoln, IL Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.26</td>
<td style="text-align: center;">-0.05</td>
<td style="text-align: center;">-4855.41</td>
</tr>
<tr class="odd">
<td style="text-align: center;">152</td>
<td style="text-align: center;">24802</td>
<td style="text-align: center;">Springfield, IL Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.26</td>
<td style="text-align: center;">-0.05</td>
<td style="text-align: center;">-4855.41</td>
</tr>
<tr class="even">
<td style="text-align: center;">152</td>
<td style="text-align: center;">24802</td>
<td style="text-align: center;">Taylorville, IL Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.26</td>
<td style="text-align: center;">-0.05</td>
<td style="text-align: center;">-4855.41</td>
</tr>
<tr class="odd">
<td style="text-align: center;">153</td>
<td style="text-align: center;">16300</td>
<td style="text-align: center;">Indiana, PA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.26</td>
<td style="text-align: center;">-0.05</td>
<td style="text-align: center;">-5363.59</td>
</tr>
<tr class="even">
<td style="text-align: center;">153</td>
<td style="text-align: center;">16300</td>
<td style="text-align: center;">Pittsburgh, PA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.26</td>
<td style="text-align: center;">-0.05</td>
<td style="text-align: center;">-5363.59</td>
</tr>
<tr class="odd">
<td style="text-align: center;">154</td>
<td style="text-align: center;">22200</td>
<td style="text-align: center;">Cedar Rapids, IA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.26</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-5269.67</td>
</tr>
<tr class="even">
<td style="text-align: center;">155</td>
<td style="text-align: center;">23500</td>
<td style="text-align: center;">Champaign-Urbana, IL Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.28</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-5148.18</td>
</tr>
<tr class="odd">
<td style="text-align: center;">155</td>
<td style="text-align: center;">23500</td>
<td style="text-align: center;">Decatur, IL Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.28</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-5148.18</td>
</tr>
<tr class="even">
<td style="text-align: center;">156</td>
<td style="text-align: center;">15200</td>
<td style="text-align: center;">Akron, OH Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.28</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-5736.08</td>
</tr>
<tr class="odd">
<td style="text-align: center;">156</td>
<td style="text-align: center;">15200</td>
<td style="text-align: center;">Ashtabula, OH Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.28</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-5736.08</td>
</tr>
<tr class="even">
<td style="text-align: center;">156</td>
<td style="text-align: center;">15200</td>
<td style="text-align: center;">Cleveland-Elyria-Mentor, OH Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.28</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-5736.08</td>
</tr>
<tr class="odd">
<td style="text-align: center;">157</td>
<td style="text-align: center;">18000</td>
<td style="text-align: center;">Batavia, NY Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.29</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-5944.74</td>
</tr>
<tr class="even">
<td style="text-align: center;">157</td>
<td style="text-align: center;">18000</td>
<td style="text-align: center;">Buffalo-Cheektowaga-Tonawanda, NY Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.29</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-5944.74</td>
</tr>
<tr class="odd">
<td style="text-align: center;">157</td>
<td style="text-align: center;">18000</td>
<td style="text-align: center;">Rochester, NY Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.29</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-5944.74</td>
</tr>
<tr class="even">
<td style="text-align: center;">157</td>
<td style="text-align: center;">18000</td>
<td style="text-align: center;">Seneca Falls, NY Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.29</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-5944.74</td>
</tr>
<tr class="odd">
<td style="text-align: center;">158</td>
<td style="text-align: center;">11500</td>
<td style="text-align: center;">Adrian, MI Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.29</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-4870.49</td>
</tr>
<tr class="even">
<td style="text-align: center;">158</td>
<td style="text-align: center;">11500</td>
<td style="text-align: center;">Jackson, MI Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.29</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-4870.49</td>
</tr>
<tr class="odd">
<td style="text-align: center;">159</td>
<td style="text-align: center;">14000</td>
<td style="text-align: center;">Anderson, IN Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.29</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-4396.79</td>
</tr>
<tr class="even">
<td style="text-align: center;">159</td>
<td style="text-align: center;">14000</td>
<td style="text-align: center;">Marion, IN Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.29</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-4396.79</td>
</tr>
<tr class="odd">
<td style="text-align: center;">159</td>
<td style="text-align: center;">14000</td>
<td style="text-align: center;">Muncie, IN Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.29</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-4396.79</td>
</tr>
<tr class="even">
<td style="text-align: center;">159</td>
<td style="text-align: center;">14000</td>
<td style="text-align: center;">New Castle, IN Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.29</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-4396.79</td>
</tr>
<tr class="odd">
<td style="text-align: center;">160</td>
<td style="text-align: center;">12701</td>
<td style="text-align: center;">Cincinnati-Middletown, OH-KY-IN Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.30</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-6640.49</td>
</tr>
<tr class="even">
<td style="text-align: center;">161</td>
<td style="text-align: center;">12501</td>
<td style="text-align: center;">Bellefontaine, OH Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.30</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-5393.36</td>
</tr>
<tr class="odd">
<td style="text-align: center;">161</td>
<td style="text-align: center;">12501</td>
<td style="text-align: center;">Dayton, OH Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.30</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-5393.36</td>
</tr>
<tr class="even">
<td style="text-align: center;">161</td>
<td style="text-align: center;">12501</td>
<td style="text-align: center;">Greenville, OH Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.30</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-5393.36</td>
</tr>
<tr class="odd">
<td style="text-align: center;">161</td>
<td style="text-align: center;">12501</td>
<td style="text-align: center;">Sidney, OH Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.30</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-5393.36</td>
</tr>
<tr class="even">
<td style="text-align: center;">161</td>
<td style="text-align: center;">12501</td>
<td style="text-align: center;">Springfield, OH Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.30</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-5393.36</td>
</tr>
<tr class="odd">
<td style="text-align: center;">161</td>
<td style="text-align: center;">12501</td>
<td style="text-align: center;">Urbana, OH Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.30</td>
<td style="text-align: center;">-0.06</td>
<td style="text-align: center;">-5393.36</td>
</tr>
<tr class="even">
<td style="text-align: center;">162</td>
<td style="text-align: center;">3500</td>
<td style="text-align: center;">Baton Rouge, LA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.32</td>
<td style="text-align: center;">-0.07</td>
<td style="text-align: center;">-6945.30</td>
</tr>
<tr class="odd">
<td style="text-align: center;">162</td>
<td style="text-align: center;">3500</td>
<td style="text-align: center;">Hammond, LA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.32</td>
<td style="text-align: center;">-0.07</td>
<td style="text-align: center;">-6945.30</td>
</tr>
<tr class="even">
<td style="text-align: center;">163</td>
<td style="text-align: center;">15100</td>
<td style="text-align: center;">Cleveland-Elyria-Mentor, OH Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.34</td>
<td style="text-align: center;">-0.07</td>
<td style="text-align: center;">-6548.46</td>
</tr>
<tr class="odd">
<td style="text-align: center;">163</td>
<td style="text-align: center;">15100</td>
<td style="text-align: center;">Norwalk, OH Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.34</td>
<td style="text-align: center;">-0.07</td>
<td style="text-align: center;">-6548.46</td>
</tr>
<tr class="even">
<td style="text-align: center;">163</td>
<td style="text-align: center;">15100</td>
<td style="text-align: center;">Sandusky, OH Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.34</td>
<td style="text-align: center;">-0.07</td>
<td style="text-align: center;">-6548.46</td>
</tr>
<tr class="odd">
<td style="text-align: center;">164</td>
<td style="text-align: center;">14900</td>
<td style="text-align: center;">Gary, IN Metropolitan Division</td>
<td style="text-align: center;">-0.35</td>
<td style="text-align: center;">-0.07</td>
<td style="text-align: center;">-6918.81</td>
</tr>
<tr class="even">
<td style="text-align: center;">165</td>
<td style="text-align: center;">23801</td>
<td style="text-align: center;">Davenport-Moline-Rock Island, IA-IL Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.38</td>
<td style="text-align: center;">-0.08</td>
<td style="text-align: center;">-7293.04</td>
</tr>
<tr class="odd">
<td style="text-align: center;">165</td>
<td style="text-align: center;">23801</td>
<td style="text-align: center;">Peoria, IL Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.38</td>
<td style="text-align: center;">-0.08</td>
<td style="text-align: center;">-7293.04</td>
</tr>
<tr class="even">
<td style="text-align: center;">166</td>
<td style="text-align: center;">13501</td>
<td style="text-align: center;">Monroe, MI Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.40</td>
<td style="text-align: center;">-0.07</td>
<td style="text-align: center;">-7403.07</td>
</tr>
<tr class="odd">
<td style="text-align: center;">166</td>
<td style="text-align: center;">13501</td>
<td style="text-align: center;">Toledo, OH Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.40</td>
<td style="text-align: center;">-0.07</td>
<td style="text-align: center;">-7403.07</td>
</tr>
<tr class="even">
<td style="text-align: center;">167</td>
<td style="text-align: center;">23900</td>
<td style="text-align: center;">Ottawa-Streator, IL Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.44</td>
<td style="text-align: center;">-0.09</td>
<td style="text-align: center;">-8246.60</td>
</tr>
<tr class="odd">
<td style="text-align: center;">167</td>
<td style="text-align: center;">23900</td>
<td style="text-align: center;">Peoria, IL Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.44</td>
<td style="text-align: center;">-0.09</td>
<td style="text-align: center;">-8246.60</td>
</tr>
<tr class="even">
<td style="text-align: center;">168</td>
<td style="text-align: center;">11900</td>
<td style="text-align: center;">Bay City, MI Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.45</td>
<td style="text-align: center;">-0.08</td>
<td style="text-align: center;">-6969.44</td>
</tr>
<tr class="odd">
<td style="text-align: center;">168</td>
<td style="text-align: center;">11900</td>
<td style="text-align: center;">Midland, MI Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.45</td>
<td style="text-align: center;">-0.08</td>
<td style="text-align: center;">-6969.44</td>
</tr>
<tr class="even">
<td style="text-align: center;">168</td>
<td style="text-align: center;">11900</td>
<td style="text-align: center;">Saginaw-Saginaw Township North, MI Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.45</td>
<td style="text-align: center;">-0.08</td>
<td style="text-align: center;">-6969.44</td>
</tr>
<tr class="odd">
<td style="text-align: center;">169</td>
<td style="text-align: center;">24900</td>
<td style="text-align: center;">St. Louis, MO-IL Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.46</td>
<td style="text-align: center;">-0.09</td>
<td style="text-align: center;">-9285.30</td>
</tr>
<tr class="even">
<td style="text-align: center;">170</td>
<td style="text-align: center;">16200</td>
<td style="text-align: center;">Altoona, PA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.58</td>
<td style="text-align: center;">-0.10</td>
<td style="text-align: center;">-8165.66</td>
</tr>
<tr class="odd">
<td style="text-align: center;">170</td>
<td style="text-align: center;">16200</td>
<td style="text-align: center;">Johnstown, PA Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.58</td>
<td style="text-align: center;">-0.10</td>
<td style="text-align: center;">-8165.66</td>
</tr>
<tr class="even">
<td style="text-align: center;">170</td>
<td style="text-align: center;">16200</td>
<td style="text-align: center;">Somerset, PA Micropolitan Statistical Area</td>
<td style="text-align: center;">-0.58</td>
<td style="text-align: center;">-0.10</td>
<td style="text-align: center;">-8165.66</td>
</tr>
<tr class="odd">
<td style="text-align: center;">171</td>
<td style="text-align: center;">32100</td>
<td style="text-align: center;">Beaumont-Port Arthur, TX Metropolitan Statistical Area</td>
<td style="text-align: center;">-0.62</td>
<td style="text-align: center;">-0.13</td>
<td style="text-align: center;">-11784.40</td>
</tr>
</tbody>
</table>

The economic logic behind amenity value
---------------------------------------

A thought experiment to start off. Imagine three cities within a county:
Acropolis, Upfrum Down, and Spira. In Acropolis and Upfrum Down, the
wage is \$200 per week. In Spira, on the other hand, the wage is \$300 per
week. Continue to imagine that anyone can rent a residence (or purchase
at an equal ownership cost) for $300 per month. In fact, go ahead and
assume that all other prices except for the wage are the same. The
obvious question that arises is why does anyone still live in Acropolis
or Upfrum Down? Couldn’t people just move to Spira and have the same
residence, with an extra $400 a month to spend enjoying other goods and
services? Using examples from before, one wonders if maybe Spira is
similar to Milwaukee or Minneapolis, with Acropolis and Upfrum Down
similar to somplace like Los Angeles and San Francisco. The extra $400 a
month might even seem like a joke to some accustomed to year-round
sunshine and beach access. Hence, we would say that Spira has a high
( &gt; 0) quality of life, measured at 33% of foregone consumption. We
could alternatively say that the quality of life in Acropolis and Upfrum
Down is lower ( &lt; 0), since firms in these cities need to *pay* an
extra 33% wage each month to keep workers from emigrating to higher
quality-of-life Spira.

Jennifer Roback laid-out a simple, formal version of this reasoning in
one equation:

\[p_z = H \frac{dr}{dz} - \frac{dw}{dz}\]
Here, *p*<sub>*z*</sub> is the implied price of amenity *z*; *r* is the
residential rent for the housing unit *H* (this could be defined
variously, like square feet or rooms, as long as it’s consistent), and
*w* is the wage that the worker accepts.

For those who prefer English to mathematics, it’s just the intuition
laid-out above; the value *p*<sub>*z*</sub> of an additional amount of
the local amenity *dz* is revealed by the difference between its
contribution to rent spending and its contribution to workers earnings.
Above, we formulated *z* as the amount of some particular amenity, like
average termperature in January, or distance to national forests. We
could also consider *z* instead to be the value of *every combined
place-based amenity* in a local area. David Albouy writing in 2008
summarises the best intuition for this interpretation of *z*:

“[It] represents the [fraction] of total consumption households are
willing to forego to live in [a city with these rents and wages]
instead of an average city.”

If local amenities are associated with more spending on rent relative to
earnings, and people aren’t moving away from an area, they must value
the amenities at least this much, Otherwise their wellbeing would go
down and they would leave the area, right? Maybe that seems *too*
simple, and while it is simplistic, it seems to do a good job describing
what’s going on with people’s choices.

Hence, we can interpret *z* as a *cardinal measure of quality of life*
separate from earnings or living expenses required to stay in the area.
Even though we use those to measure this quality of life, it’s
independent because it’s the value that’s *revealed* by people’s choices
rather than being a *function of* them.