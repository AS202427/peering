# AS202427 Peering Config

Pathvector peering config

## Region

| Region | Description |
| ------ | ----------- |
| `1` | Europe |
| `2` | North America |

## Country

Numeric country identifier defined by ISO 3166-1

| Country | Description |
| ------- | ----------- |
| `124` | Canada |
| `208` | Denmark |
| `276` | Germany |
| `380` | Italy |
| `528` | Netherlands |
| `578` | Norway |
| `724` | Spain |
| `756` | Switzerland |
| `840` | United States of America |

## POP

| POP ID | Description |
| ------ | ----------- |
| `1` | Learned at RMA01, CH |
| `2` | Learned at FRA01, DE |
| `3` | Learned at AMS01, NL |
| `4` | Learned at TOR01, CA |
| `5` | Learned at MKC01, US |
| `6` | Learned at BCN01, ES |
| `7` | Learned at OTT01, CA |
| `8` | Learned at FNC01, US |
| `9` | Learned at RESERVED, EU |
| `10` | Learned at RESERVED, EU |
| `11` | Learned at RESERVED, EU |
| `12` | Learned at VAN01, CA |
| `13` | Learned at DUS01, DE|
| `14` | Learned at ZRH02, CH |
| `15` | Learned at POM01, IT |

## BGP Community Support

### Informational

Informational BGP communities offer insight into AS202427's routing policies.

#### Origin

| Community | Description |
| --------- | ----------- |
| `202427:101:1` | Originated by AS202427 |
| `202427:101:2` | Learned from transit provider |
| `202427:101:3` | Learned from IX |
| `202427:101:4` | Learned from peer |
| `202427:101:5` | Learned from customer |

#### Country

Octets in the function field are the numeric country identifier defined by ISO 3166-1.

| Community | Description |
| --------- | ----------- |
| `202427:102:COUNTRY_ID` | Learned in [Country (COUNTRY_ID)] |

#### Region

| Community | Description |
| --------- | ----------- |
| `202427:103:REGION_ID` | Learned in [Region (REGION_ID)] |

#### PoP

| Community | Description |
| --------- | ----------- |
| `202427:104:POP_ID` | Learned at [PoP (POP_ID)] |
| `202427:105:POP_ID` | Exported at [PoP (POP_ID)] |
| `202427:106:POP_ID` | Originated at [PoP (POP_ID)] |

#### Peer

##### Transit provider

| Community | Description |
| --------- | ----------- |
| `202427:107:835` | Learned from GoCodeIT AS835 |
| `202427:107:6939` | Learned from Hurricane Electric LLC |
| `202427:107:34872` | Learned from Servperso Systems |
| `202427:107:34927` | Learned from iFog GmbH |
| `202427:107:41051` | Learned from Freetransit Project (Openfactory GmbH) |
| `202427:107:62513` | Learned from GoCodeIT Inc |
| `202427:107:212271` | Learned from C1V - AS212271 |
| `202427:107:212895` | Learned from ROUTE64.ORG |

##### IX Routeserver

| Community | Description |
| --------- | ----------- |
| `202427:107:24381` | Learned from BGP.Exchange |
| `202427:107:34307` | Learned from NL-ix Route Servers |
| `202427:107:35708` | Learned from 4b42 Internet Exchange Point Route Servers |
| `202427:107:42476` | Learned from SwissIX Route Servers |
| `202427:107:47422` | Learned from SBIX RS Zurich |
| `202427:107:47498` | Learned from FogIXP Route Servers |
| `202427:107:49245` | Learned from SIIX Route Servers |
| `202427:107:56393` | Learned from Frys-IX Route Servers |
| `202427:107:56584` | Learned from INTERIX |
| `202427:107:57369` | Learned from CLDY Route Servers |
| `202427:107:65513` | Learned from UNM-Exch Canada-West |
| `202427:107:202409` | Learned from LOCIX Route Servers |
| `202427:107:212100` | Learned from CHIX-CH Route Servers |

##### Peering

| Community | Description |
| --------- | ----------- |
| `202427:107:112` | Learned from AS112 Project |
| `202427:107:714` | Learned from Apple Inc. |
| `202427:107:4775` | Learned from Globe Telecom |
| `202427:107:8283` | Learned from Netwerkvereniging Coloclue |
| `202427:107:13335` | Learned from Cloudflare, Inc. |
| `202427:107:15169` | Learned from Google LLC |
| `202427:107:24940` | Learned from Hetzner Online |
| `202427:107:25091` | Learned from IP-Max |
| `202427:107:30132` | Learned from ISC F-ROOT AMS1 |
| `202427:107:32934` | Learned from Meta Platforms, Inc. |
| `202427:107:35297` | Learned from Dataline Net |
| `202427:107:39614` | Learned from Dawico |
| `202427:107:48200` | Learned from Opteamax |
| `202427:107:48581` | Learned from MythicalKitten |
| `202427:107:51019` | Learned from KTT Iceland |
| `202427:107:58299` | Learned from Openfactory |
| `202427:107:58511` | Learned from Anycast Global Backbone |
| `202427:107:63949` | Learned from Linode |
| `202427:107:200132` | Learned from NetOne NL |
| `202427:107:203069` | Learned from Thomas Riley Brown |
| `202427:107:212635` | Learned from AS212635 |
| `202427:107:212855` | Learned from LUJE.net |
| `202427:107:393577` | Learned from Tritan Development |

#### IX
Octets in the function field are the peeringdb id.

| Community | Description |
| --------- | ----------- |
| `202427:108:IX_ID` | Learned at IX (IX_ID) |
| `202427:108:60` | Learned at SwissIX |
| `202427:108:64` | Learned at NL-ix |
| `202427:108:2084` | Learned at LOCIX Frankfurt |
| `202427:108:2365` | Learned at CHIX-CH |
| `202427:108:2447` | Learned at 4b42 Internet Exchange Point |
| `202427:108:2452` | Learned at UNM-Exch Canada-West |
| `202427:108:2730` | Learned at LOCIX Dusseldorf |
| `202427:108:3512` | Learned at Frys-IX |
| `202427:108:3528` | Learned at SIIX |
| `202427:108:3685` | Learned at FREMIX |
| `202427:108:3756` | Learned at FogIXP |
| `202427:108:3829` | Learned at BGP.Exchange - Frankfurt |
| `202427:108:3830` | Learned at BGP.Exchange - Zurich |
| `202427:108:3836` | Learned at BGP.Exchange - Toronto |
| `202427:108:3844` | Learned at BGP.Exchange - Dusseldorf |
| `202427:108:3990` | Learned at INTERIX |
| `202427:108:4059` | Learned at ONIX |

## Pref

### Upstream

| Pref | Description |
| ---- | ----------- |
| `100` | Default |
| `110` | Tunnel  |
| `120` | IXP    |
| `130` | PNI    |

### Routeserver

| Pref | Description |
| ---- | ----------- |
| `200` | Default |
| `210` | Tunnel  |
| `220` | IXP     |

### Peer

| Pref | Description |
| ---- | ----------- |
| `300` | Default |
| `310` | Tunnel  |
| `320` | IXP     |
| `330` | PNI     |

### Downstream

| Pref | Description |
| ---- | ----------- |
| `400` | Default |
| `410` | IXP     |
| `420` | PNI     |

### Internal

| Pref | Description |
| ---- | ----------- |
| `180` | Default |
| `190` | PNI     |

# Action 

| Community | Description |
| --------- | ----------- |
| `202427:111:REGION_ID` | Announce Only in Region (REGION_ID) |
| `202427:112:REGION_ID` | Announce not in Region (REGION_ID) |

| Community | Description |
| --------- | ----------- |
| `202427:113:COUNTRY_ID` | Announce Only in Country (COUNTRY_ID) |
| `202427:114:COUNTRY_ID` | Announce not in Country (COUNTRY_ID) |

| Community | Description |
| --------- | ----------- |
| `202427:115:POP_ID` | Announce Only at PoP (POP_ID) |
| `202427:116:POP_ID` | Announce not at PoP (POP_ID) |
