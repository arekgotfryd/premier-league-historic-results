# premier-league-historic-results  
This repository contains detailed statistics about every premier league game between 1993 and 2016.  
Each season has it's own json file. Statistics include events like yellow cards, substitutions and their exact timestamps.

## file structure
Each file contains array of games of given season. All properties of game object are pretty self-descriptive.  
If there is a need to add description for game object properties because something is unclear please raise an issue I will add it then.  
Example of a game object below:  
```json
  {
    "matchDate": "SAT 14 AUGUST 1993",
    "homeTeamEvents": {
      "cards": [],
      "substitutions": [
        {
          "playerOn": "99. Eddie McGoldrick",
          "playerOff": "99. Paul Merson",
          "eventType": "Substitution",
          "minute": "67"
        },
        {
          "playerOn": "99. Martin Keown",
          "playerOff": "99. John Jensen",
          "eventType": "Substitution",
          "minute": "73"
        }
      ],
      "goals": []
    },
    "awayTeam": "Coventry City",
    "fullTimeHomeScore": "0",
    "stadium": "Highbury, London",
    "homeTeam": "Arsenal",
    "fullTimeAwayScore": "3",
    "halfTimeAwayScore": "1",
    "matchStartTime": "",
    "awayTeamEvents": {
      "cards": [
        {
          "eventType": "Yellow Card",
          "minute": "89",
          "player": "99. Phil Babb"
        },
        {
          "eventType": "Yellow Card",
          "minute": "89",
          "player": "99. Mick Quinn"
        }
      ],
      "substitutions": [
        {
          "playerOn": "99. Steve Morgan",
          "playerOff": "99. Stewart Robson",
          "eventType": "Substitution",
          "minute": "10"
        }
      ],
      "assists": [
        {
          "assisting": "Roy Wegerle",
          "minute": "62"
        },
        {
          "assisting": "Roy Wegerle",
          "minute": "65"
        }
      ],
      "goals": [
        {
          "eventType": "Goal",
          "minute": "34",
          "player": "99. Mick Quinn"
        },
        {
          "eventType": "Goal",
          "minute": "62",
          "player": "99. Mick Quinn"
        },
        {
          "eventType": "Goal",
          "minute": "65",
          "player": "99. Mick Quinn"
        }
      ]
    },
    "referee": "Alan Wilkie",
    "halfTimeHomeScore": "0"
  },
```
