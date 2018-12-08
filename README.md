## Disclaimer

Dit project is een initiatief van Code For NL. De documentatie en project componenten vallen volledig onder de verantwoordelijkheid van Code For NL. De genoemde overheidsinstellingen hebben een betrokkenheid bij deze repository.

# INSPIRE
INSPIRE harmonisatie projecten op basis van open data.

## Verantwoording

Diverse Nederlandse overheidspartijen dienen aan [INSPIRE](http://inspire.ec.europa.eu/), het Europese geodata initiatief, open data op te leveren in een door de lidstaten afgestemd formaat. In deze repository proberen we gebruik te maken van open data bronnen van Nederlandse overheden en deze direct naar INSPIRE te vertalen (harmoniseren). Daar waar hiaten optreden in de harmonisatie zullen deze worden geidentificeerd waarna de betrokken Nederlandse bronhouders zullen worden gecontacteerd om te proberen niet alleen aan INSPIRE alle vereiste, afgesproken entiteiten op te leveren, maar om ook direct de al in Nederland geldende open datasets dusdanig aan te passen of uit te breiden dat ook voor de (publieke) gebruikers van b.v. het [nationaal georegister](http://www.nationaalgeoregister.nl) of [PDOK](https://www.pdok.nl/) dezelfde data beschikbaar komt. Deze synchronisatie vinden wij belangrijk om nationaal en internationaal dezelfde beeldvorming te ondersteunen.

Voor dit project wordt gebruik gemaakt van [HALE Studio](https://www.wetransform.to/downloads/) dat beschikbaar is voor iOS, Windows en Linux.

Op de INSPIRE website staan een aantal [best practices](https://inspire-reference.jrc.ec.europa.eu/implementations). Als uitgangspunt voor dit document is de instructie [dataset harmonizatie in Portugal met HALE](https://inspire-reference.jrc.ec.europa.eu/implementations/land-cover-spatial-datasets-harmonization-portugal-using-hale) als uitgangspunt genomen.

Ivm met de internationale samenwerking is de informatie zoveel mogelijk in Engels en Nederlands beschikbaar.

We onderscheiden de bron-data, de documenten, de metadata voor de resultaten en de harmonisatie/mapping. We gaan er vanuit dat de resultaten conform INSPIRE beschikbaar worden gesteld via hosting van Services. Hosting partijen voor Nederland zijn o.a. PDOK, WeTRansform.

In Metadata_INSPIRE.xlsx beheren we het een gecombineerd overzicht van de gevraagde feauturetypes per thema gekoppeld aan de aangeboden data (As-Is).

De subdirectories van de map harmonisation bevatten .halex bestanden en mapping tables. De .halex bestanden kunnen vanuit HALE-Studio worden geopend.

Lijst met AccesPoints naar geharmoniseerde data (HaleConnect) en Accespoints Nationaal Georegister.    

# Transport Networks (TN)
## TN - Common Transport Elements (TN-CTN)
### Source - TN-CTN
[Download](https://haleconnect.com/#/dataset/org/292/2885ef73-e044-4da4-b9b6-8a461a5353aa) of [WFS service](https://www.haleconnect.com/)
 * In de dataset TN-CTN staan de featuretypes:
  * ConditionOfFacility (Kadaster)
  * Markerpost
  * MarkerPost (Kadaster)
  * Measure
  * TransportArea
  * TransportLink
  * TransportLinkSequence
  * TransportLinkSet
  * TransportNetwork (type)
  * TransportNode
  * TransportPoint
  * TransportProperty
  * VerticalPosition
  * VerticalPosition (Kadaster)  
  
### Target - TN-CTN
Description (http://www.nationaalgeoregister.nl/geonetwork/srv/dut/catalog.search#/metadata/eu-43fc1b3-6034-4eu-6-bb0d-2d1967c9ae48)
Services  [Download](http://www.nationaalgeoregister.nl/) of [WFS service](http://www.nationaalgeoregister.nl/)


## Transport Networks - RoadTransportNetwork (TN-RTN)
### Source - TN-RTN
[Download](https://haleconnect.com/) of [WFS service](https://www.haleconnect.com/)
 * In de dataset TN-RTN staan de featuretypes:
  * RoadArea
  * RoadLink  
  * RoadLinkSequence
  * RoadNode

### Target - TN-RTN
Description (http://www.nationaalgeoregister.nl/geonetwork/srv/dut/catalog.search#/metadata/eu-43fc1b3-6034-4eu-6-bb0d-2d1967c9ae48)
Services  [Download](http://www.nationaalgeoregister.nl/) of [WFS service](http://www.nationaalgeoregister.nl/)

## Transport Networks - Roads (TN-RO)
### Source - TN-RO
[Download](https://haleconnect.com/#/dataset/org/292/2885ef73-e044-4da4-b9b6-8a461a5353aa) of [WFS service](https://www.haleconnect.com/)
 * In de dataset TN-RO staan de featuretypes:
  * ERoad (Kadaster)
  * FormOfWay
  * FormOfWay (Kadaster)
  * FunctionalRoadClass
  * FunctionalRoadClass (Kadaster)
  * NumberOfLanes
  * Road
  * Road (Kadaster)
  * RoadArea (Kadaster = TN-RTN)
  * RoadLink (Kadaster = TN-RTN)
  * RoadName 
  * RoadName (Kadaster)
  * RoadNode (Kadaster = TN-RTN)
  * RoadServiceType
  * RoadSurfaceCategory
  * RoadSurfaceCategory (Kadaster)
  * RoadWidth
  * RoadWidth (Kadaster)
  * SpeedLimit
  * VehicleTrafficArea (Kadaster)

### Target - TN-RO
Description (http://www.nationaalgeoregister.nl/geonetwork/srv/dut/catalog.search#/metadata/eu-43fc1b3-6034-4eu-6-bb0d-2d1967c9ae48)
Services  [Download](http://www.nationaalgeoregister.nl/) of [WFS service](http://www.nationaalgeoregister.nl/)


## Transport Networks - WaterTransportNetwork (TN-WTN)
### Source - TN-WTN
[Download](https://haleconnect.com/#/dataset/org/292/2885ef73-e044-4da4-b9b6-8a461a5353aa) of [WFS service](https://www.haleconnect.com/)
 * In de dataset TN-WTN staan de featuretypes:
  * FairwayArea
  * PortArea (Bron:Kadaster)
  * PortNode (Bron:Kadaster)
  * FerryUse (Bron:Kadaster)
  * FerryCrossing (Bron:Kadaster)
  * WaterwayLinkSequence
  * WaterwayLink
  * WaterwayNode

### Target - TN-WTN
Description (http://www.nationaalgeoregister.nl/geonetwork/srv/dut/catalog.search#/metadata/eu-43fc1b3-6034-4eu-6-bb0d-2d1967c9ae48)
Services  [Download](http://www.nationaalgeoregister.nl/) of [WFS service](http://www.nationaalgeoregister.nl/)
  
  
## Transport Networks - Waterways (TN-W)
### Source - TN-W
[Download](https://haleconnect.com/#/dataset/org/292/2885ef73-e044-4da4-b9b6-8a461a5353aa) of [WFS service](https://www.haleconnect.com/)
 * In de dataset TN-W staan de featuretypes:
  * BeaconType
  * InlandWaterwayType
  * MarineWaterwayType
  * MarkerPostType
  * TrafficSeparationSchemeCrossingType
  * TrafficSeparationSchemeSeparatorType
  * TransportNetworkType
  * WaterTrafficFlowDirectionType
  * WaterwayLinkType
  * WaterwayNodeType
  
### Target - TN-W
Description (http://www.nationaalgeoregister.nl/geonetwork/srv/dut/catalog.search#/metadata/eu-43fc1b3-6034-4eu-6-bb0d-2d1967c9ae48)
Services  [Download](http://www.nationaalgeoregister.nl/) of [WFS service](http://www.nationaalgeoregister.nl/)

# Hydrography (HY)
## Hydrography - Network (HY-N)
### Source - HY-N
[Download](https://haleconnect.com/#/dataset/org/292/2885ef73-e044-4da4-b9b6-8a461a5353aa) of [WFS service](https://www.haleconnect.com/)
 * In de dataset HY-N staan de featuretypes:
### Target - HY-N
 * Data (http://www.nationaalgeoregister.nl/geonetwork/srv/dut/catalog.search#/metadata/eu-43fc1b3-6034-4eu-6-bb0d-2d1967c9ae48)
 * Services  [Download](http://www.nationaalgeoregister.nl/) of [WFS service](http://www.nationaalgeoregister.nl/)


## Hydrography - Physical Objects (HY-P)
### Source - HY-P
[Download](https://haleconnect.com/#/dataset/org/292/2885ef73-e044-4da4-b9b6-8a461a5353aa) of [WFS service](https://www.haleconnect.com/)
 * In de dataset HY-P staan de featuretypes:
 
### Target - HY-P
Description (http://www.nationaalgeoregister.nl/geonetwork/srv/dut/catalog.search#/metadata/eu-43fc1b3-6034-4eu-6-bb0d-2d1967c9ae48)
Services  [Download](http://www.nationaalgeoregister.nl/) of [WFS service](http://www.nationaalgeoregister.nl/)

## Hydrography - Physical Objects - ManMadeObject (HY-PMO)
### Source - HY-PMO
[Download](?Kadaster) of [WFS service](?Kadaster)
 * In de dataset HY-PMO staan de featuretypes:
  
### Target - HY-PMO
Description (http://www.nationaalgeoregister.nl/geonetwork/srv/dut/catalog.search#/metadata/eu-43fc1b3-6034-4eu-6-bb0d-2d1967c9ae48)
Services  [Download](http://www.nationaalgeoregister.nl/) of [WFS service](http://www.nationaalgeoregister.nl/)


# Elevation (EL)
## Elevation - Terrain (EL-T)
### Source - EL-T
[Download](https://haleconnect.com/) of [WFS service](https://www.haleconnect.com/)
 * In de dataset EL-T staan de featuretypes:
  * ...
 
### Target - EL-T
Description (http://www.nationaalgeoregister.nl/)
Services  [Download](http://www.nationaalgeoregister.nl/) of [WFS service](http://www.nationaalgeoregister.nl/)
 
## Elevation - InlandWater (EL-I)
### Source - EL-I
[Download](https://haleconnect.com/) of [WFS service](https://www.haleconnect.com/)
 * In de dataset EL-I staan de featuretypes:
  * ...
 
### Target - EL-I
Description (http://www.nationaalgeoregister.nl/)
Services  [Download](http://www.nationaalgeoregister.nl/) of [WFS service](http://www.nationaalgeoregister.nl/)

## Elevation - MarienWater (EL-M)
### Source - EL-M
[Download](https://haleconnect.com/) of [WFS service](https://www.haleconnect.com/)
 * In de dataset EL-M staan de featuretypes:
  * ...
 
### Target - EL-M
Description (http://www.nationaalgeoregister.nl/)
Services  [Download](http://www.nationaalgeoregister.nl/) of [WFS service](http://www.nationaalgeoregister.nl/)


# Human Health and Safety(HH)
## Human Health and Safety - Noise (HH-N)
### Source - HH-N
[Download](https://haleconnect.com/#/dataset/org/292/2885ef73-e044-4da4-b9b6-8a461a5353aa) of [WFS service](https://www.haleconnect.com/)
 * In de dataset HH-N staan de featuretypes:
  * Biomarker
  * EnvHealthDeterminantMeasure
  * GeneralHealthStatistics
  * HealthStatisticalData
  * EnvHealthDeterminantStatisticalData
  * HealthServicesStatistic
  * Disease

### Target - HH-N
Description (http://www.nationaalgeoregister.nl/geonetwork/srv/dut/catalog.search#/metadata/eu-43fc1b3-6034-4eu-6-bb0d-2d1967c9ae48)
Services  [Download](http://www.nationaalgeoregister.nl/) of [WFS service](http://www.nationaalgeoregister.nl/)
