# Data Dictionary

| Column Name   | Data Type   |   Missing Rate | Used in Recommendation               |
|---------------|-------------|----------------|--------------------------------------|
| show_id       | object      |    0           | Yes – primary identifier             |
| type          | object      |    0           | Yes – content type filter            |
| title         | object      |    0           | Yes – title matching & display       |
| director      | object      |    0.299012    | Optional – content signal (director) |
| cast          | object      |    0.0936542   | Optional – content signal (cast)     |
| country       | object      |    0.0943353   | Optional – regional signal           |
| date_added    | object      |    0.0011352   | No – metadata only (date added)      |
| release_year  | int64       |    0           | No – metadata only (release year)    |
| rating        | object      |    0.000454081 | No – content rating                  |
| duration      | object      |    0.000340561 | No – runtime info                    |
| listed_in     | object      |    0           | Yes – genre similarity               |
| description   | object      |    0           | Yes – core text signal               |
| Unnamed: 12   | float64     |    1           | No – irrelevant (empty column)       |
| Unnamed: 13   | float64     |    1           | No – irrelevant (empty column)       |
| Unnamed: 14   | float64     |    1           | No – irrelevant (empty column)       |
| Unnamed: 15   | float64     |    1           | No – irrelevant (empty column)       |
| Unnamed: 16   | float64     |    1           | No – irrelevant (empty column)       |
| Unnamed: 17   | float64     |    1           | No – irrelevant (empty column)       |
| Unnamed: 18   | float64     |    1           | No – irrelevant (empty column)       |
| Unnamed: 19   | float64     |    1           | No – irrelevant (empty column)       |
| Unnamed: 20   | float64     |    1           | No – irrelevant (empty column)       |
| Unnamed: 21   | float64     |    1           | No – irrelevant (empty column)       |
| Unnamed: 22   | float64     |    1           | No – irrelevant (empty column)       |
| Unnamed: 23   | float64     |    1           | No – irrelevant (empty column)       |
| Unnamed: 24   | float64     |    1           | No – irrelevant (empty column)       |
| Unnamed: 25   | float64     |    1           | No – irrelevant (empty column)       |