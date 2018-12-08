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

# Physical waters

# Transport Networks (TN)
## TN - Common Transport Elements (TN-CTN)
### Source - TN-CTN
 * [Download](https://www.haleconnect.com/) of [WFS service](https://www.haleconnect.com/)
 * In de dataset vinden data voor de featuretypes.
  * Markerpost
  * Measure
  * TransportArea
  * TransportLink
  * TransportLinkSequence
  * TransportLinkSet
  * TransportNetwork (type)
  * TransportNode
  * TransportPoint
  * TransportProperty
  * VertivalPosition
### Target - TN-CTN
 * Data (http://www.nationaalgeoregister.nl/geonetwork/srv/dut/catalog.search#/metadata/eu-43fc1b3-6034-4eu-6-bb0d-2d1967c9ae48)
 * Services  [Download](https://www.haleconnect.com/) of [WFS service](https://www.haleconnect.com/)

# Transport Networks - Roads (TN-RO)


# Transport Networks - Waterways (TN-WW)

# Hydrography
## Hydrography - Network
## Hydrography - Physical Objects
