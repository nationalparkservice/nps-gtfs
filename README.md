# nps-gtfs
A repository of General Transit Feeds Specification (GTFS) for National Park Service transit systems.

Feeds are organized according to the system of <code>/[park code]/[system name]/google_transit.zip</code>

## Index
- Rocky Mountain National Park <code>romo</code>
 - Shuttle Bus Routes <code>shuttles</code>
- Cuyahoga Valley National Park <code>cuva</code>
 - Cuyahoga Valley Scenic Railroad <code>scenic-rail</code>
- Boston Harbor Islands National Park <code>boha</code>
 - Harbor Islands Ferries <code>ferries</code>*

### Notes 
 NOTE: Certain routes that are part of the Boston Harbor Islands Ferries are shared with and operated by the Massachusetts Bay Transportation Authority (MBTA), the Boston area's public transit agency and operator of regional commuter ferries. These routes are not included in the NPS feed. Developers should ensure they also incorporate the [MBTA's GTFS feed](http://www.mbta.com/rider_tools/developers/default.asp?id=21895) in order to fully reflect the Harbor Islands Ferries schedule.