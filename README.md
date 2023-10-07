# AS202427 Peering Config

Pathvector peering config

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
| `202427:102:COUNTRY_ID` | Learned in Country (COUNTRY_ID) |
| `202427:102:124` | Learned in Canada |
| `202427:102:276` | Learned in Germany |
| `202427:102:380` | Learned in Italy |
| `202427:102:528` | Learned in Netherlands |
| `202427:102:578` | Learned in Norway |
| `202427:102:756` | Learned in Switzerland |
| `202427:102:840` | Learned in United States of America |

#### Region

| Community | Description |
| --------- | ----------- |
| `202427:103:REGION_ID` | Learned in Region (REGION_ID) |
| `202427:103:1` | Learned in Europe |
| `202427:103:2` | Learned in North America |

#### PoP

##### Import

| Community | Description |
| --------- | ----------- |
| `202427:104:POP_ID` | Learned at PoP (POP_ID) |
| `202427:104:1` | Learned at RMA01, CH |
| `202427:104:2` | Learned at FRA01, DE |
| `202427:104:3` | Learned at RESERVED, EU |
| `202427:104:4` | Learned at ZRH02, CH |
| `202427:104:5` | Learned at POM01, IT |
| `202427:104:6` | Learned at DUS01, DE |
| `202427:104:7` | Learned at AMS01, NL |
| `202427:104:9` | Learned at VAN01, CA |
| `202427:104:10` | Learned at TOR01, CA |
| `202427:104:11` | Learned at FNC01, US |
| `202427:104:12` | Learned at RESERVED, EU |
| `202427:104:13` | Learned at RESERVED, EU |
| `202427:104:14` | Learned at RESERVED, EU |
| `202427:104:15` | Learned at RESERVED, EU |

##### Export

| Community | Description |
| --------- | ----------- |
| `202427:105:POP_ID` | Exported at PoP (POP_ID) |
| `202427:105:1` | Exported at RMA01, CH |
| `202427:105:2` | Exported at FRA01, DE |
| `202427:105:3` | Exported at RESERVED, EU |
| `202427:105:4` | Exported at ZRH02, CH |
| `202427:105:5` | Exported at POM01, IT |
| `202427:105:6` | Exported at DUS01, DE |
| `202427:105:7` | Exported at AMS01, NL |
| `202427:105:9` | Exported at VAN01, CA |
| `202427:105:10` | Exported at TOR01, CA |
| `202427:105:11` | Exported at FNC01, US |
| `202427:105:12` | Exported at RESERVED, EU |
| `202427:105:13` | Exported at RESERVED, EU |
| `202427:105:14` | Exported at RESERVED, EU |
| `202427:105:15` | Exported at RESERVED, EU |


##### Originated

| Community | Description |
| --------- | ----------- |
| `202427:106:POP_ID` | Originated at PoP (POP_ID) |
| `202427:106:1` | Originated at RMA01, CH |
| `202427:106:2` | Originated at FRA01, DE |
| `202427:106:3` | Originated at RESERVED, EU |
| `202427:106:4` | Originated at ZRH02, CH |
| `202427:106:5` | Originated at POM01, IT |
| `202427:106:6` | Originated at DUS01, DE |
| `202427:106:7` | Originated at AMS01, NL |
| `202427:106:9` | Originated at VAN01, CA |
| `202427:106:10` | Originated at TOR01, CA |
| `202427:106:11` | Originated at FNC01, US |
| `202427:106:12` | Originated at RESERVED, EU |
| `202427:106:13` | Originated at RESERVED, EU |
| `202427:106:14` | Originated at RESERVED, EU |
| `202427:106:15` | Originated at RESERVED, EU |

#### Peer

##### Transit provider

| Community | Description |
| --------- | ----------- |
| `202427:106:835` | Learned from Transit - GoCodeIT Inc |
| `202427:106:6939` | Learned from Transit - Hurricane Electric LLC |
| `202427:106:34872` | Learned from Transit - Servperso Systems |
| `202427:106:34927` | Learned from Transit - iFog GmbH |
| `202427:106:41051` | Learned from Transit - Freetransit Project (Openfactory GmbH) |
| `202427:106:62513` | Learned from Transit - GoCodeIT Inc |
| `202427:106:212271` | Learned from Transit - Cinzia Tocci trading as C1V |
| `202427:106:212895` | Learned from Transit - Johannes Ernst |

##### IX Routeserver

| Community | Description |
| --------- | ----------- |
| `202427:106:24381` | Learned from Routeserver - BGP.Exchange |
| `202427:106:34307` | Learned from Routeserver - NL-ix |
| `202427:106:35708` | Learned from Routeserver - 4b42 Internet Exchange Point |
| `202427:106:42476` | Learned from Routeserver - SwissIX |
| `202427:106:47422` | Learned from Routeserver - SBIX ZRH |
| `202427:106:47498` | Learned from Routeserver - FogIXP |
| `202427:106:49245` | Learned from Routeserver - SIIX |
| `202427:106:56393` | Learned from Routeserver - Frys-IX |
| `202427:106:56584` | Learned from Routeserver - INTERIX |
| `202427:106:57369` | Learned from Routeserver - FREMIX / ONIX |
| `202427:106:65513` | Learned from Routeserver - UNM-Exch Canada-West |
| `202427:106:202409` | Learned from Routeserver - LOCIX Frankfurt, LOCIX Dusseldorf |
| `202427:106:212100` | Learned from Routeserver - CHIX-CH |

##### Peering

| Community | Description |
| --------- | ----------- |
| `202427:106:112` | Learned from Peer - AS112 Project |
| `202427:106:714` | Learned from Peer - Apple Inc. |
| `202427:106:4775` | Learned from Peer - Globe Telecom |
| `202427:106:8283` | Learned from Peer - Netwerkvereniging Coloclue |
| `202427:106:13335` | Learned from Peer - Cloudflare, Inc. |
| `202427:106:15169` | Learned from Peer - Google LLC |
| `202427:106:24940` | Learned from Peer - Hetzner Online |
| `202427:106:25091` | Learned from Peer - IP-Max |
| `202427:106:30132` | Learned from Peer - ISC F-ROOT AMS1 |
| `202427:106:32934` | Learned from Peer - Meta Platforms, Inc. |
| `202427:106:35297` | Learned from Peer - Dataline Net	|
| `202427:106:39614` | Learned from Peer - Dawico |
| `202427:106:48200` | Learned from Peer - Opteamax	|
| `202427:106:48581` | Learned from Peer - MythicalKitten |
| `202427:106:51019` | Learned from Peer - KTT Iceland |
| `202427:106:58299` | Learned from Peer - Openfactory |
| `202427:106:58511` | Learned from Peer - Anycast Global Backbone |
| `202427:106:63949` | Learned from Peer - Linode |
| `202427:106:200132` | Learned from Peer - NetOne NL |
| `202427:106:203069` | Learned from Peer - Thomas Riley Brown |
| `202427:106:212635` | Learned from Peer - AS212635 |
| `202427:106:212855` | Learned from Peer - LUJE.net |
| `202427:106:393577` | Learned from Peer - Tritan Development |

#### IX
Octets in the function field are the peeringdb id.

| Community | Description |
| --------- | ----------- |
| `202427:107:IX_ID` | Learned at IX (IX_ID) |
| `202427:107:60` | Learned at SwissIX |
| `202427:107:64` | Learned at NL-ix |
| `202427:107:2084` | Learned at LOCIX Frankfurt |
| `202427:107:2365` | Learned at CHIX-CH |
| `202427:107:2447` | Learned at 4b42 Internet Exchange Point |
| `202427:107:2452` | Learned at UNM-Exch Canada-West |
| `202427:107:2730` | Learned at LOCIX Dusseldorf |
| `202427:107:3512` | Learned at Frys-IX |
| `202427:107:3528` | Learned at SIIX |
| `202427:107:3685` | Learned at FREMIX |
| `202427:107:3756` | Learned at FogIXP |
| `202427:107:3829` | Learned at BGP.Exchange - Frankfurt |
| `202427:107:3830` | Learned at BGP.Exchange - Zurich |
| `202427:107:3836` | Learned at BGP.Exchange - Toronto |
| `202427:107:3844` | Learned at BGP.Exchange - Dusseldorf |
| `202427:107:3990` | Learned at INTERIX |
| `202427:107:4059` | Learned at ONIX |

## Pref

### Upstream

| Pref | Description |
| ---- | ----------- |
| `100` | Default |
| `110` | Tunnel  |
| `120` | Paid    |
| `130` | Free    |

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
| `202427:111:1` | Announce Only in Europe |
| `202427:111:2` | Announce Only in North America |

| Community | Description |
| --------- | ----------- |
| `202427:112:REGION_ID` | Announce not in Region (REGION_ID) |
| `202427:112:1` | Announce not in Europe |
| `202427:112:2` | Announce not in North America |

| Community | Description |
| --------- | ----------- |
| `202427:113:COUNTRY_ID` | Announce Only in Country (COUNTRY_ID) |
| `202427:114:COUNTRY_ID` | Announce not in Country (COUNTRY_ID) |

| Community | Description |
| --------- | ----------- |
| `202427:115:POP_ID` | Announce Only at PoP (POP_ID) |
| `202427:116:POP_ID` | Announce not at PoP (POP_ID) |
