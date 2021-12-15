
## Test plan

## High Level Test Plan

| Test_Id  |   Desciption                      |  Expected_Input | Expected_output  | Actual_Output | Type_of_Test |
| -------- |   ----------------------------    |  -------------- | ---------------  | ------------- | -------------|
| HP01     |  User able to select desired choice in the Interface  |  Techniques   | Cipher techniques | cipher Techniques| Requirement |
| HP02     | Caesar cipher key length  |  0-9   | Encrypted text | Encrypted text| Requirement |
| HP03     | Caesar cipher Key Length | a-z | Blank | Fail | Requirements |
| HP04     | Caesar cipher Key Length | Special_Char | Blank | Fail | Requirements |
| HP05     | PlayFair cipher key length  |  a-z   | Encrypted text | Encrypted text| Requirement |
| HP06    | PlayFair cipher Key Length | 0-26,a-z,Special_Char | Blank | Fail | Requirements |
| HP07     | RailFence cipher  Depth  |  0-25  | Encrypted text | Encrypted text| Requirement |
| HP08     | RailFence cipher Key Length | a-z | Blank | Fail | Requirements |
| HP09     | User able to select Decryption  |  Enter Decryption   | Decrypted text |Decrypted text| Requirement |
## Low Level Test Plan

| Test_Id  |   Desciption                              |  Expected_Input | Expected_output      | Actual_Output | Type_of_Test |
| -------- |   --------------                          |  -------------- | ---------------      | ------------- | -------------|
| LP01     |   User able to understand the functionality     |  Encryption techniques    | Output Screen |Output Screen          | Requrirement |
| LP02     |   user has to enter valid message             |  a-z   |Encrypted Text             | Encrypted Text          | Requrirement |
| LP03     | Key Length                                | Non_Categorigy sysmbols                | Blank |FAIL            | Requirements |

