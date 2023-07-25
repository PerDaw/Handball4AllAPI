# Handball4AllAPI
Inofficial API for handball4all.de

## Short documentation
Don't take this for granted. It's more like a quick note
### Commands
| Command | Parameter | Description |
| ------ | ------ | ------ |
| pcu | ... | Vereinsseite (ClubDetailControl) |
| pgy | ... | Hallenspielplan (GymnasiumMatchesControl) |
| ps | ... | Ligaseite (LeagueDetailControl) |
| cs | ... | Vereinssuche (ClubSearch) |
| gs | ... | Hallensuche (GymnasiumSearch) |
| gi | ... | Hallen-Detailseite (GymnasiumDetailControl) |
| po | ... | Bereichs-Spielplan (ScheduleDetailControl) |
| ical | ... | Spieltermin-Export (iCal Format) |

### Parameters
| Command | DataType | Value | Description |
| ------ | ------ | ------ | ------ |
| debug | number | 1 \|\| 0 | Replaces JSON with custom format |
| cmd | string | Varies | Defines which model to use |
| og | number | Varies > 0 | OrganisationID (VerbandsID) |
| o | number | Varies > 0 | RegionID (RegionsID) |
| p | number | Varies > 0 | PeriodID (SaisonID) |
| do | string | yyyy-mm-dd | Date (Datum) |
| g | number | Varies > 0 | GymID (SporthallenID) |
| c | number | Varies > 0 | ClubID (VereinsID) |
| cl | number | Varies > 0 | LeagueID (LigaID) |
| ca | number | 1 \|\| 0 | ShowAllGames (AlleSpieleAusgeben) |
| ct | number | Varies > 0 | TeamID (MannschaftsID) |
