### OSF instance
| port | ime instance	| deployani branch | mobilna okolina | fiksna okolina | mdm okolina |
| --- | --- | --- | --- | --- | --- |
| 7009 | OCV_TEST |	master | WPOSPP | compass test   |  test  |
| 7019 | OCV_TEST_2 | master | WPOST | acc1 dev | dev |
| 7029 | OCV_TEST_3 | webtemplatei | WPOSPP | compass test | test |
| 7039 | OCV_TEST_4 |  | WPOSPP | compass test | test |
| 7049 | OCV_TEST_5 | steckerleiste | WPOSPP | compass dev | test |
| 7059 | OCV_TEST_6 | privole | WPOSPP | compass test | test |
| 7069 | OCV_TEST_7 | bundliranje | WPOSPP | compass test | test |
| 7079 (7078 https) | OCV_TEST_8 | filter_list_upgrade | WPOSPP | compass test | test |


### Branchevi
| branch | opis | razvoj | test |
| --- | --- | --- | --- |
| master | ono što je trenutno na produkciji ili bugfiksevi koji idu na produkciju u sljedećem deployu | | |
| biometry | biometrija faza 2. Slanje dokumentacije na mail | hrvoje, darko | |
| privole | privole u MDM-u | hrvoje | |
| steckerleiste  | | hrvoje, vice | |
| sales2015  | ono sto je jos ostalo od sales projekta + masovni edit adresa | novotni, andro, hrvoje | darko |
| bundliranje | | hrvoje, domagoj | domagoj |
| zaba  | | iva, jopa | rus | |
| magenta  | | iva, darko, balic, hrvoje | | |
| filter_list_upgrade  | | hrvoje, vice | | |
| webtemplatei?  | | matija | | |

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
