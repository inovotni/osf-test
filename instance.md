### OSF instance
| port | ime instance	| deployani branch | mobilna okolina | fiksna okolina | mdm okolina |
| --- | --- | --- | --- | --- | --- |
| 7009 | OCV_TEST |	master | WPOSPP | compass test   |  test  |
| 7019 | OCV_TEST_2 | external_policy | WPOSPP | compass test | test |
| 7029 | OCV_TEST_3 | bonus_insurance | WPOSPP | compass test | test |
| 7039 | OCV_TEST_4 | sepa_admin | WPOSPP | compass test | test |
| 7049 | OCV_TEST_5 | bus_spec_price | WPOSPP | compass test | test |
| 7059 | OCV_TEST_6 | multiscreen | WPOSPP | compass test | test |
| 7069 | OCV_TEST_7 | webpos_cache | WPOSPP | compass test | test |
| 7079 (7078 https) | OCV_TEST_8 | mudbug | WPOSPP | compass test | test |


### Branchevi
| branch | opis | razvoj | test |
| --- | --- | --- | --- |
| master | ono što je trenutno na produkciji ili bugfiksevi koji idu na produkciju u sljedećem deployu | | |
| steckerleiste  | | hrvoje, vice | |
| temp_canc | privremeno iskljucenje | novotni |  |
| mdmAddressSynchro | uskladivanje mdm dostavne adrese | hrvoje |  |
| biometryPh2 | | novotni | |
| bonus_insurance | | hrvoje | domagoj |
| sepa, sancta_domenica, slavonia, nexTv, multiscreen | | matija | |
| vpn_limit | | hrvoje | balic, bojan |
| new_mdm_contacts | | hrvoje | domagoj |
| sepa_admin | | hrvoje | darko |
| webpos_cache | | hrvoje | balic |
| magenta_tablet | | novotni | darko |
| mudbug | | novotni | darko |
| bus_spec_price | | hrvoje | darko |
| external_policy | | vuglec | domagoj |


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
