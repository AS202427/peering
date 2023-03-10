# AS202427 Peering Config

Pathvector peering config

## BGP Community Support

### Informational

Informational BGP communities offer insight into AS202427's routing policies.

#### Origin

| Community | Description |
| --------- | ----------- |
| `202427:101:1` | Originated by you |
| `202427:101:2` | Learned from transit provider |
| `202427:101:3` | Learned from IX |
| `202427:101:4` | Learned from peer |
| `202427:101:5` | Learned from customer |

#### Region

Octets in the function field are the numeric country identifier defined by ISO 3166-1.

| Community | Description |
| --------- | ----------- |
| `202427:102:124` | Learned in Canada |
| `202427:102:276` | Learned in Germany |
| `202427:102:380` | Learned in Italy |
| `202427:102:528` | Learned in Netherlands |
| `202427:102:578` | Learned in Norway |
| `202427:102:756` | Learned in Switzerland |
| `202427:102:840` | Learned in United States of America |

#### Site

| Community | Description |
| --------- | ----------- |
| `202427:103:1` | Learned at Core01 Nuremberg, DE |
| `202427:103:2` | Learned at Edge01 Frankfurt, DE |
| `202427:103:3` | Learned at Edge01 Zurich, CH |
| `202427:103:4` | Learned at Edge02 Zurich, CH |
| `202427:103:5` | Learned at Edge01 Milan, IT |
| `202427:103:6` | Learned at Edge01 Dusseldorf, DE |
| `202427:103:7` | Learned at Edge01 Amsterdam, NL |
| `202427:103:8` | Learned at Edge01 Oslo, NO |
| `202427:103:9` | Learned at Edge01 Vancouver, CA |
| `202427:103:10` | Learned at Edge01 Toronto, CA |
| `202427:103:11` | Learned at Edge01 Fremont, US |

#### Peer

##### Transit provider

| Community | Description |
| --------- | ----------- |
| `202427:104:835` | Learned from AS6939 - GoCodeIT Inc |
| `202427:104:6939` | Learned from AS6939 - Hurricane Electric LLC |
| `202427:104:34927` | Learned from AS34927 - iFog GmbH |
| `202427:104:35619` | Learned from AS35619 - Kevin Buehl |
| `202427:104:34872` | Learned from AS34872 - Servperso Systems |
| `202427:104:41051` | Learned from AS41051 - Freetransit Project (Openfactory GmbH) |
| `202427:104:44570` | Learned from AS44570 - Route48.org Tunnel Broker |
| `202427:104:50058` | Learned from AS50058 - August Internet Limited |
| `202427:104:58057` | Learned from AS58057 - Securebit AG |
| `202427:104:62513` | Learned from AS62513 - GoCodeIT Inc |
| `202427:104:212271` | Learned from AS212271 - Cinzia Tocci trading as C1V |
| `202427:104:212895` | Learned from AS212895 - Johannes Ernst |
##### IX Routeserver

| Community | Description |
| --------- | ----------- |
| `202427:104:24381` | Learned from AS24381 - BGP.Exchange |
| `202427:104:34307` | Learned from AS34307 - NL-ix |
| `202427:104:35708` | Learned from AS35708 - 4b42 Internet Exchange Point |
| `202427:104:47422` | Learned from AS47422 - SBIX ZRH |
| `202427:104:47498` | Learned from AS47498 - FogIXP |
| `202427:104:49245` | Learned from AS49245 - SIIX |
| `202427:104:49459` | Learned from AS49459 - IXP FI HEL, IXP LI VAD, IXP NL DRO, IXP UK LON, IXP US FRE |
| `202427:104:56393` | Learned from AS56393 - Frys-IX |
| `202427:104:56738` | Learned from AS56738 - SBG-IX |
| `202427:104:57369` | Learned from AS212100 - FREMIX / ONIX |
| `202427:104:65513` | Learned from AS65513 - UNM-Exch Canada-West |
| `202427:104:202409` | Learned from AS202409 - LOCIX Frankfurt, LOCIX Dusseldorf |
| `202427:104:212100` | Learned from AS212100 - CHIX-CH |

##### Peering

| Community | Description |
| --------- | ----------- |
| `202427:104:112` | Learned from AS112 - AS112 Project |
| `202427:104:13335` | Learned from AS13335 - Cloudflare, Inc. |
| `202427:104:15169` | Learned from AS15169 - Google LLC |
| `202427:104:32934` | Learned from AS32934 - Meta Platforms, Inc. |
| `202427:104:41732` | Learned from AS41732 - HostingFuze Network |
| `202427:104:51019` | Learned from AS51019 - Kjartan Hrafnkelsson |
| `202427:104:203069` | Learned from AS203069 - Thomas Riley Brown |
| `202427:104:211380` | Learned from AS211380 - Simulhost Limited |

#### IX
Octets in the function field are the peeringdb id.

| Community | Description |
| --------- | ----------- |
| `202427:105:64` | Learned at NL-ix |
| `202427:105:2084` | Learned at LOCIX Frankfurt |
| `202427:105:2365` | Learned at CHIX-CH |
| `202427:105:2447` | Learned at 4b42 Internet Exchange Point |
| `202427:105:2452` | Learned at UNM-Exch Canada-West |
| `202427:105:2571` | Learned at SBIX ZRH |
| `202427:105:2700` | Learned at IXP FI HEL |
| `202427:105:2704` | Learned at IXP UK LON |
| `202427:105:2705` | Learned at IXP NL DRO |
| `202427:105:2728` | Learned at IXP LI VAD |
| `202427:105:2730` | Learned at LOCIX Dusseldorf |
| `202427:105:2746` | Learned at IXP US FRE |
| `202427:105:3512` | Learned at Frys-IX |
| `202427:105:3528` | Learned at SIIX |
| `202427:105:3756` | Learned at FogIXP |
| `202427:105:3829` | Learned at BGP.Exchange - Frankfurt |
| `202427:105:3830` | Learned at BGP.Exchange - Zurich |
| `202427:105:3836` | Learned at BGP.Exchange - Toronto |
| `202427:105:3844` | Learned at BGP.Exchange - Dusseldorf |
| `202427:105:4058` | Learned at SBG-IX |
| `202427:105:4059` | Learned at ONIX |
