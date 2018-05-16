# nps-gtfs

A repository of General Transit Feeds Specification (GTFS) for National Park Service transit systems.

Feeds are organized according to the system of `/[alpha_code]/[system_name]/gtfs.zip`. Direct download links are: `http://nationalparkservice.github.io/nps-gtfs/[alpha_code]/[system_name]/gtfs.zip`. Feeds maintained and hosted by partners have a different organization structure. Please see the tables below for more details.

## Index

#### Maintained by NPS and Hosted on GitHub
Park Name | System Name | Feed Valid Thru | Feed Link | Dependencies
--------- | ----------- | --------------- | --------- | -----
[Boston Harbor Islands National Park](http://www.nps.gov/boha/index.htm "Boston Harbor Islands National Park") <code>boha</code> | [Boston Harbor Islands Ferries](http://www.bostonharborislands.org/ferryschedule "Boston Harbor Islands Ferries") <code>ferries</code> |  May 4, 2019 | [Link](http://nationalparkservice.github.io/nps-gtfs/boha/ferries/gtfs.zip "Link to BOHA Ferries GTFS") | [Massachusetts Bay Transportation Authority's GTFS feed](https://mbta.com/developers/gtfs "Massachusetts Bay Transportation Authority's GTFS feed") for shared routes (very important). Note: All MBTA ferry service to Grape Island and Georges Island is NPS-related. [See note.](https://github.com/nationalparkservice/nps-gtfs/blob/gh-pages/boha/ferries/IMPORTANT.txt "Note regarding adding MBTA trips to BOHA GTFS")
[Cuyahoga Valley National Park](http://www.nps.gov/cuva "Cuyahoga Valley National Park") <code>cuva</code> | [Cuyahoga Valley Scenic Railroad](http://www.cvsr.com/take-the-train/national-park-scenic/ "Cuyahoga Valley Scenic Railroad") <code>scenic-rail</code> | May 31, 2018 | [Link](http://nationalparkservice.github.io/nps-gtfs/cuva/scenic-rail/gtfs.zip "Link to CUVA Railroad GTFS") | N/A
[Rocky Mountain National Park](http://www.nps.gov/romo/index.htm "Rocky Mountain National Park") <code>romo</code> | [Rocky Mountain National Park Shuttles](http://www.nps.gov/romo/planyourvisit/shuttle_bus_route.htm "Rocky Mountain National Park Shuttles") <code>shuttles</code> | May 25, 2019 | [Link](http://nationalparkservice.github.io/nps-gtfs/romo/shuttles/gtfs.zip "Link to ROMO GTFS") | Town of Estes Park GTFS - See Below
[Town of Estes Park Free Shuttles](http://www.estes.org/shuttles "Town of Estes Park Free Shuttles") <code>romo-epshuttles</code> | [Town of Estes Park Free Shuttles](http://www.estes.org/shuttles "Town of Estes Park Free Shuttles") <code>shuttles</code> | June 23, 2017 | [Link](http://nationalparkservice.github.io/nps-gtfs/romo-epshuttles/shuttles/gtfs.zip "Link to Town of Estes Park GTFS") | Rocky Mountain National Park GTFS - See Above

#### Maintained and Hosted by Partners
Park Name | System Name | Maintained By | Feed Link | License
--------- | ----------- | ------------- | --------- | -----
[Acadia National Park](http://www.nps.gov/acad "Acadia National Park") | [Acadia Island Explorer](http://www.exploreacadia.com/ "Acadia Island Explorer") | Downeast Transportation and Avail Technologies | Pending | Pending
[Yosemite National Park](http://www.nps.gov/yose "Yosemite National Park") | [Yosemite Area Regional Transportation System](http://www.yarts.com "Yosemite Area Regional Transportation System") | YARTS and Trillium Transit | [Link](http://data.trilliumtransit.com/gtfs/yosemite-ca-us/yosemite-ca-us.zip "Link to YARTS GTFS") | Public Domain; See Below


## Public domain

This project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.md):

> This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.
