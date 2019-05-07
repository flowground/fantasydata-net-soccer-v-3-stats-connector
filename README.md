# ![LOGO](logo.png) Soccer v3 Stats **flow**ground Connector

## Description

A generated **flow**ground connector for the Soccer v3 Stats API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/fantasydata.net/soccer-v3-stats/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:40:40+03:00

## API Description



## Authorization

Supported authorization schemes:
- API Key- API Key
## Actions

### Memberships (Active)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.

### Areas (Countries)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.

### Box Score

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `gameid` - _required_ - The GameID of a Soccer game.  GameIDs can be found in the Games API.  Valid entries are <code>702</code>, <code>1274</code>, etc.

### Box Scores by Date

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `date` - _required_ - The date of the game(s).
<br>Examples: <code>2017-02-27</code>, <code>2017-09-01</code>.

### Box Scores by Date by Competition

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `competition` - _required_ - An indication of a soccer competition/league. This value can be the CompetitionId or the Competition Key. Possible values include: <code>EPL</code>, <code>1</code>, <code>MLS</code>, <code>8</code>, etc.
* `date` - _required_ - The date of the game(s).
<br>Examples: <code>2017-02-27</code>, <code>2017-09-01</code>.

### Box Scores by Date Delta

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `date` - _required_ - The date of the game(s).
<br>Examples: <code>2017-02-27</code>, <code>2017-09-01</code>.
* `minutes` - _required_ - Only returns player statistics that have changed in the last X minutes.  You specify how many minutes in time to go back. Valid entries are:
<code>1</code>, <code>2</code> ... <code>all</code>.

### Box Scores Delta by Date by Competition

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `competition` - _required_ - An indication of a soccer competition/league. This value can be the CompetitionId or the Competition Key. Possible values include: <code>EPL</code>, <code>1</code>, <code>MLS</code>, <code>8</code>, etc.
* `date` - _required_ - The date of the game(s).
<br>Examples: <code>2017-02-27</code>, <code>2017-09-01</code>.
* `minutes` - _required_ - Only returns player statistics that have changed in the last X minutes.  You specify how many minutes in time to go back. Valid entries are:
<code>1</code>, <code>2</code> ... <code>all</code>.

### Competition Fixtures (League Details)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `competition` - _required_ - An indication of a soccer competition/league. This value can be the CompetitionId or the Competition Key. Possible values include: <code>EPL</code>, <code>1</code>, <code>MLS</code>, <code>8</code>, etc.

### Competition Hierarchy (League Hierarchy)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.

### Competitions (Leagues)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.

### Games by Date

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `date` - _required_ - The date of the game(s).
<br>Examples: <code>2017-02-27</code>, <code>2017-09-01</code>.

### Memberships (Historical)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.

### Memberships by Competition (Historical)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `competition` - _required_ - An indication of a soccer competition/league. This value can be the CompetitionId or the Competition Key. Possible values include: <code>EPL</code>, <code>1</code>, <code>MLS</code>, <code>8</code>, etc.

### Memberships by Team (Historical)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `teamid` - _required_ - Unique FantasyData Team ID. 
Example:<code>516</code>.

### Memberships by Competition (Active)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `competition` - _required_ - An indication of a soccer competition/league. This value can be the CompetitionId or the Competition Key. Possible values include: <code>EPL</code>, <code>1</code>, <code>MLS</code>, <code>8</code>, etc.

### Memberships by Team (Active)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `teamid` - _required_ - Unique FantasyData Team ID. 
Example:<code>516</code>.

### Player

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `playerid` - _required_ - Unique FantasyData Player ID.
Example:<code>90026231</code>.

### Player Game Stats by Date

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `date` - _required_ - The date of the game(s).
<br>Examples: <code>2017-02-27</code>, <code>2017-09-01</code>.

### Player Game Stats by Player

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `date` - _required_ - The date of the game(s).
<br>Examples: <code>2017-02-27</code>, <code>2017-09-01</code>.
* `playerid` - _required_ - Unique FantasyData Player ID.
Example:<code>90026231</code>.

### Player Season Stats

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `roundid` - _required_ - Unique FantasyData Round ID. RoundIDs can be found in the Competition Hierarchy (League Hierarchy). 
Examples: <code>1</code>, <code>2</code>, <code>3</code>, etc

### Player Season Stats by Player

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `roundid` - _required_ - Unique FantasyData Round ID. RoundIDs can be found in the Competition Hierarchy (League Hierarchy). 
Examples: <code>1</code>, <code>2</code>, <code>3</code>, etc
* `playerid` - _required_ - Unique FantasyData Player ID.
Example:<code>90026231</code>.

### Player Season Stats by Team

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `roundid` - _required_ - Unique FantasyData Round ID. RoundIDs can be found in the Competition Hierarchy (League Hierarchy). 
Examples: <code>1</code>, <code>2</code>, <code>3</code>, etc
* `team` - _required_ - Unique FantasyData Team ID. 
Example:<code>516</code>.

### Players

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.

### Players by Team

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `teamid` - _required_ - Unique FantasyData Team ID. 
Example:<code>516</code>.

### Memberships (Recently Changed)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `days` - _required_ - The number of days since memberships were updated. For example, if you pass <code>3</code>, you'll receive all memberships that have been updated in the past 3 days. Valid entries are: <code>1</code>, <code>2</code> ... <code>30</code>

### Schedule

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `roundid` - _required_ - Unique FantasyData Round ID. RoundIDs can be found in the Competition Hierarchy (League Hierarchy). 
Examples: <code>1</code>, <code>2</code>, <code>3</code>, etc

### Season Teams

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `seasonid` - _required_ - Unique FantasyData Season ID. SeasonIDs can be found in the Competition Hierarchy (League Hierarchy). 
Examples: <code>1</code>, <code>2</code>, <code>3</code>, etc

### Standings

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `roundid` - _required_ - Unique FantasyData Round ID. RoundIDs can be found in the Competition Hierarchy (League Hierarchy). 
Examples: <code>1</code>, <code>2</code>, <code>3</code>, etc

### Team Game Stats by Date

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `date` - _required_ - The date of the game(s).
<br>Examples: <code>2017-02-27</code>, <code>2017-09-01</code>.

### Team Season Stats

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `roundid` - _required_ - Unique FantasyData Round ID. RoundIDs can be found in the Competition Hierarchy (League Hierarchy). 
Examples: <code>1</code>, <code>2</code>, <code>3</code>, etc

### Teams

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.

### Upcoming Schedule By Player

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `playerid` - _required_ - Unique FantasyData Player ID.
Example:<code>90026231</code>.

### Venues

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.

## License

**flow**ground :- Telekom iPaaS / fantasydata-net-soccer-v-3-stats-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
