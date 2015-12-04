### OSF instance
| port | ime instance	| deployani branch | mobilna okolina | fiksna okolina | mdm okolina |
| --- | --- | --- | --- | --- | --- |
| 7009 | OCV_TEST |	master | WPOSPP | compass test   |  test  |
| 7019 | OCV_TEST_2 | master | WPOST | acc1 dev | test |
| 7029 | OCV_TEST_3 | privole | WPOSPP | compass test | test |
| 7039 | OCV_TEST_4 | ebill | WPOSPP | compass test | test |
| 7049 | OCV_TEST_5 | steckerleiste | WPOSPP | compass test | test |
| 7059 | OCV_TEST_6 | mdm_multiple_oib | WPOSPP | compass test | test |
| 7069 | OCV_TEST_7 | bundliranje | WPOSPP | compass test | test |
| 7079 (7078 https) | OCV_TEST_8 | mdm_prikljucci | WPOSPP | compass test | test |


### Branchevi
| branch | opis | razvoj | test |
| --- | --- | --- | --- |
| master | ono što je trenutno na produkciji ili bugfiksevi koji idu na produkciju u sljedećem deployu | | |
| ebill | | | |
| privole | | hrvoje | |
| steckerleiste  | | hrvoje, vice | |
| mdm_multiple_oib  | | | |
| bundliranje | | hrvoje, domagoj | domagoj |
| mdm_prikljucci  | | tonci, hrvoje | | |

### Okoline
1. mobilna
 *	WPOSPP - test
 *	WPOST - dev

2. fiksna
 * compass test - MasterDataServices:6324
 * acc1 dev - MasterDataServices:7324

3. mdm
 * test - MDMServices:6312/6311
 * dev - MDMServices:5312/5311
 * ? - MDMServices:7312/7311
