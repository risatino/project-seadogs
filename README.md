### Project Seadogs: NFL Player Analysis

#### Data Sources
__The following APIs are Open Source or trial data sets__

**APIs:** 
[Fantasy Data](https://developer.fantasydata.com/) was difficult to obtain with the free trial so we have sample data to develop data analysis process to answer our questions.

**NFL Fantasy Points Scoring System**

#### Overview
* Fantasy Data API awards points to individual defensive players (IDP Scoring)
* They use fractional points
* They use negative points

#### Offensive Players
* Passing Yards: 1 point per 25 yards
* Passing Touchdowns: 4 points
* Passing Interceptions: -2 points
* Rushing Yards: 1 point per 10 yards
* Rushing Touchdowns: 6 points
* Receptions: 1 points (only if using PPR scoring)
* Receiving Yards: 1 point per 10 yards
* Receiving Touchdowns: 6 points
* 2-Point Conversions: 2 points
* Fumbles Lost: -2 points
* Fumble Recovered for a Touchdown: 6 points

#### Team Defense / Special Teams
* Sacks: 1 point
* Interceptions: 2 points
* Fumbles Recovered: 2 points
* Safeties: 2 points
* Defensive Touchdowns: 6 points
* Kick and Punt Return Touchdowns: 6 points
* 2-Point Conversion Returns: 2 points
* Points Allowed (0): 10 points
* Points Allowed (1-6): 7 points
* Points Allowed (7-13): 4 points
* Points Allowed (14-20): 1 points
* Points Allowed (21-27): 0 points
* Points Allowed (28-34): -1 points
* Points Allowed (35+): -4 points

#### Individual Defensive Players
* Solo Tackles: 1 point
* Assisted Tackles: ½ point
* Sacks: 2 points
* Sack Yards: 1 point per 10 yards
* Tackles For Loss: 1 point
* Quarterback Hits: 1 point
* Passes Defended: 1 point
* Interceptions: 3 points
* Fumbles Forced: 3 points
* Fumbles Recovered: 3 points
* Defensive Touchdowns: 6 points
* 2-Point Conversion Returns: 2 points

#### Kicking
* PAT Made: 1 point
* FG Made (0-49 yards): 3 points
* FG Made (50+ yards): 5 points

#### Other Tips
* Average Draft Position (ADP)

#### Script Build: fetch data from web scraping Fantasy Data sets

'''
python Exporter.py --querysearch "Nigel Bradham" --since 2018-03-07 --until 2018-03-21 --maxtweets 100000
'''