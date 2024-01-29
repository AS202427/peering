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
| `12` | Learned at RESERVED, EU |
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
| `202427:101:2` | Learned from Transit provider |
| `202427:101:3` | Learned from IX |
| `202427:101:4` | Learned from Peer |
| `202427:101:5` | Learned from Downstream |

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
| `202427:107:POP_ID` | Originated at [PoP (POP_ID)] |

#### Peer

##### Transit provider

| Community | Description |
| --------- | ----------- |
| `202427:106:835` | Learned from GoCodeIT Inc |
| `202427:106:6939` | Learned from Hurricane Electric LLC |
| `202427:106:21738` | Learned from Rozint Ltd Co |
| `202427:106:34872` | Learned from Servperso Systems |
| `202427:106:34927` | Learned from iFog GmbH |
| `202427:106:41051` | Learned from Freetransit Project (Openfactory GmbH) |
| `202427:106:212271` | Learned from Cinzia Tocci trading as C1V |
| `202427:106:212895` | Learned from ROUTE64.ORG |

##### IX Routeserver

| Community | Description |
| --------- | ----------- |
| `202427:106:24381` | Learned from BGP.Exchange |
| `202427:106:34307` | Learned from NL-ix Route Servers |
| `202427:106:35920` | Learned from HOUIX Route Servers |
| `202427:106:40542` | Learned from KCiX Route Servers |
| `202427:106:42476` | Learned from SwissIX Route Servers |
| `202427:106:46389` | Learned from STLIX Route Servers |
| `202427:106:47498` | Learned from FogIXP Route Servers |
| `202427:106:49245` | Learned from SIIX Route Servers |
| `202427:106:56393` | Learned from Frys-IX Route Servers |
| `202427:106:56584` | Learned from INTERIX |
| `202427:106:57369` | Learned from ONIX Route Servers |
| `202427:106:60438` | Learned from FREMIX Route Servers |
| `202427:106:202409` | Learned from LOCIX Route Servers |
| `202427:106:212100` | Learned from CHIX-CH Route Servers |

##### Peering

| Community | Description |
| --------- | ----------- |
| `202427:106:112` | Learned from AS112 Project |
| `202427:106:714` | Learned from Apple Inc. |
| `202427:106:4775` | Learned from Globe Telecom |
| `202427:106:8283` | Learned from Netwerkvereniging Coloclue |
| `202427:106:13335` | Learned from Cloudflare, Inc. |
| `202427:106:15169` | Learned from Google LLC |
| `202427:106:24940` | Learned from Hetzner Online |
| `202427:106:25091` | Learned from IP-Max |
| `202427:106:30132` | Learned from ISC F-ROOT AMS1 |
| `202427:106:32934` | Learned from Meta Platforms, Inc. |
| `202427:106:35297` | Learned from Dataline Net |
| `202427:106:39614` | Learned from Dawico |
| `202427:106:48200` | Learned from Opteamax |
| `202427:106:48581` | Learned from MythicalKitten |
| `202427:106:51019` | Learned from KTT Iceland |
| `202427:106:58299` | Learned from Openfactory |
| `202427:106:58511` | Learned from Anycast Global Backbone |
| `202427:106:63949` | Learned from Linode |
| `202427:106:200132` | Learned from NetOne NL |
| `202427:106:203069` | Learned from Thomas Riley Brown |
| `202427:106:212635` | Learned from AS212635 |
| `202427:106:212855` | Learned from LUJE.net |
| `202427:106:393577` | Learned from Tritan Development |
| `202427:106:nnn` | Learned from AS$0 |

#### IX
Octets in the function field are the peeringdb id.

| Community | Description |
| --------- | ----------- |
| `202427:105:IX_ID` | Learned at IX (IX_ID) |
| `202427:105:60` | Learned at SwissIX |
| `202427:105:64` | Learned at NL-ix |
| `202427:105:249` | Learned at KCIX |
| `202427:105:2084` | Learned at LOCIX Frankfurt |
| `202427:105:2365` | Learned at CHIX-CH |
| `202427:105:2585` | Learned at STLIX |
| `202427:105:2730` | Learned at LOCIX Dusseldorf |
| `202427:105:2835` | Learned at HOUIX |
| `202427:105:3512` | Learned at Frys-IX |
| `202427:105:3528` | Learned at SIIX |
| `202427:105:3685` | Learned at FREMIX |
| `202427:105:3756` | Learned at FogIXP |
| `202427:105:3829` | Learned at BGP.Exchange - Frankfurt |
| `202427:105:3830` | Learned at BGP.Exchange - Zurich |
| `202427:105:3844` | Learned at BGP.Exchange - Dusseldorf |
| `202427:105:3990` | Learned at INTERIX |
| `202427:105:4059` | Learned at ONIX |

### Action

| Community | Description |
| --------- | ----------- |
| `202427:110:nnn` | Do not announce to AS$0 |
| `202427:130:1` | Prepand 1x |
| `202427:130:2` | Prepand 2x |
| `202427:130:3` | Prepand 3x |
| `202427:131:nnn` | Prepand 1x to AS$0 |
| `202427:132:nnn` | Prepand 2x to AS$0 |
| `202427:133:nnn` | Prepand 3x to AS$0 |

#### Region

| Community | Description |
| --------- | ----------- |
| `202427:111:REGION_ID` | Do not announce in [Region (REGION_ID)] |
| `202427:121:REGION_ID` | Announce only in [Region (REGION_ID)] |
| `202427:141:POP_ID` | Prepand 1x at [PoP (POP_ID)] |
| `202427:142:POP_ID` | Prepand 2x at [PoP (POP_ID)] |
| `202427:143:POP_ID` | Prepand 3x at [PoP (POP_ID)] |

#### Country

Octets in the function field are the numeric country identifier defined by ISO 3166-1.

| Community | Description |
| --------- | ----------- |
| `202427:112:COUNTRY_ID` | Do not announce in [Country (COUNTRY_ID)] |
| `202427:122:COUNTRY_ID` | Announce only in [Country (COUNTRY_ID)] |
| `202427:151:POP_ID` | Prepand 1x at [PoP (POP_ID)] |
| `202427:152:POP_ID` | Prepand 2x at [PoP (POP_ID)] |
| `202427:153:POP_ID` | Prepand 3x at [PoP (POP_ID)] |

#### PoP

| Community | Description |
| --------- | ----------- |
| `202427:113:POP_ID` | Do not announce at [PoP (POP_ID)] |
| `202427:123:POP_ID` | Announce only at [PoP (POP_ID)] |
| `202427:161:POP_ID` | Prepand 1x at [PoP (POP_ID)] |
| `202427:162:POP_ID` | Prepand 2x at [PoP (POP_ID)] |
| `202427:163:POP_ID` | Prepand 3x at [PoP (POP_ID)] |

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
