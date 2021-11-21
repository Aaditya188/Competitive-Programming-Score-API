# Competitive-Programming-Score-API
An API to get user details for competitive coding platforms - Codeforces, Codechef, SPOJ, Interviewbit

## Platforms Available 
* Codeforces
* Codechef
* SPOJ
* Interviewbit
* Leetcode (new)
* Atcoder
### More Platforms will be Added Soon

## Base URL
https://competitive-programming-score.herokuapp.com/api/

## Request Format
https://competitive-programming-score.herokuapp.com/api/{platform_name}/{user_name}

### Example URL
https://competitive-programming-score.herokuapp.com/api/codechef/prakashaaditya18

### Example Badges for your Github Repositories

Replace `<USERNAME>` with your username on that platform.

#### <a href="https://codeforces.com/profile/prakashaaditya18"><img src="https://img.shields.io/badge/dynamic/json?&color=1f8acb&logo=codeforces&label=Codeforces&url=https://competitive-programming-score.herokuapp.com/api/codeforces/prakashaaditya18&query=%24.rating&prefix=Rating%20&style=for-the-badge&cacheSeconds=259200" alt="prakashaaditya18's profile on Codeforces" title="prakashaaditya18's profile on Codeforces"></a>

`https://img.shields.io/badge/dynamic/json?&color=1f8acb&logo=codeforces&label=Codeforces&url=https://competitive-programming-score.herokuapp.com/api/codeforces/<USERNAME>&query=%24.<FIELD>&prefix=<TEXT>&style=for-the-badge&cacheSeconds=86400`

Suggested use,
* `<FIELD>` = `rating`
* `<TEXT>` = `Rating%20`

#### <a href="https://www.codechef.com/users/prakashaaditya"><img src="https://img.shields.io/badge/dynamic/json?label=CodeChef&query=%24.country_rank&url=https://competitive-programming-score.herokuapp.com/api/codechef/prakashaaditya&logo=codechef&logoColor=f5f5dc&labelColor=7b5e47&style=for-the-badge&cacheSeconds=259200" alt="prakashaaditya's profile on CodeChef" title="prakashaaditya's profile on CodeChef"></a>

`https://img.shields.io/badge/dynamic/json?label=CodeChef&query=%24.global_rank&url=https://competitive-programming-score.herokuapp.com/api/codechef/<USERNAME>&prefix=<TEXT>&logo=codechef&logoColor=f5f5dc&labelColor=7b5e47&style=for-the-badge&cacheSeconds=86400`

Suggested use,
* `<FIELD>` = `global_rank`, `country_rank` or `rating`
* `<TEXT>` = `Rank%20`, country abbreviation (e.g., `US%20%23`) or `Rating%20`

### Pro Tip 💡
Use this [JSON Formatter Chrome Extension](https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa?hl=en) to view in a structured format.


