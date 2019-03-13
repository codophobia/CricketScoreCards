# Scorecards of ODI, T-20 and Test Matches

## Total Scorecards

Format | Male | Female
--- | --- | ---
ODI | 1313 | 104
TEST | 390 | 4
T20 | 556 | 156
IPL | 578 | -

## Features in scorecard

* Batting scorecard for each inning

  ```json
  "batting": [
                {
                    "runs": 10, 
                    "balls": 12, 
                    "name": "SC Ganguly", 
                    "fours": 2, 
                    "six": 0, 
                    "dismissal": "caught JH Kallis bowled Z Khan"
                }, 
                {
                    "runs": 158, 
                    "balls": 73, 
                    "name": "BB McCullum", 
                    "fours": 10, 
                    "six": 13, 
                    "dismissal": "not out"
                }
            ]
  ```

* Bowling scorecard of each inning

  ```json
  "bowling": [
                {
                    "runs": 38, 
                    "overs": 4.0, 
                    "name": "P Kumar", 
                    "maiden": 0, 
                    "wickets": 0
                }, 
                {
                    "runs": 38, 
                    "overs": 4.0, 
                    "name": "Z Khan", 
                    "maiden": 0, 
                    "wickets": 1
                }
             ]
  ```

* Fall of wickets of each inning

  ```json
  "fow": [
                {
                    "over": 5.2, 
                    "score": 61, 
                    "name": "SC Ganguly", 
                    "wkt_nbr": 1
                }, 
                {
                    "over": 12.1, 
                    "score": 112, 
                    "name": "RT Ponting", 
                    "wkt_nbr": 2
                }
         ]
  ```

* Summary of each innings

  ```json
  "summary": {
                "runs": 222, 
                "bowlteam": "Royal Challengers Bangalore", 
                "batteam": "Kolkata Knight Riders", 
                "wickets": 3, 
                "inning_no": 1, 
                "overs": 20
            }
  ```

* Match information

  ```json
  "matchinfo": {
        "city": "Bangalore", 
        "venue": "M Chinnaswamy Stadium", 
        "teams": "Royal Challengers Bangalore vs Kolkata Knight Riders", 
        "mtype": "T20", 
        "mom": "BB McCullum", 
        "date": "2008-04-18", 
        "id": "335982"
    }
  ```
  



