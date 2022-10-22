# Repair Checker API
Repair Check Results for testing purposes across product lookup and repair details
Returns up to 100 test records

Full API: https://mockend.com/AndreaRichardson/RepairChecker/Repair

## Product Lookup
Product search for testing purposes.
Returns up to 100 test records

Query API: https://mockend.com/AndreaRichardson/RepairChecker/Repair?product_contains={product}&country_eq={country}&language_eq={language}

Example: https://mockend.com/AndreaRichardson/RepairChecker/Repair?product_contains=TX&country_eq=RO&language_eq=fi

## Repair Checker
Repair Check Results for testing purposes.
Returns up to 100 test records

### Product Name and Last Name
Query API: https://mockend.com/AndreaRichardson/RepairChecker/Repair?product_eq={product}&country_eq={country}&lastName_eq={lastname}

Example
https://mockend.com/AndreaRichardson/RepairChecker/Repair?product_eq=HC-V160%20-%20CAMCORDER&country_eq=IT&lastName_eq=Freeman

## Post Code and Last Name
Query API: https://mockend.com/AndreaRichardson/RepairChecker/Repair?postCode_eq={postcode}&country_eq={country}&lastName_eq={lastname}

Example
https://mockend.com/AndreaRichardson/RepairChecker/Repair?postCode_eq=TA3 5DB&country_eq=IT&lastName_eq=Freeman

## Email Address and Last Name
Query API:
https://mockend.com/AndreaRichardson/RepairChecker/Repair?postCode_eq={postcode}&country_eq={country}&lastName_eq={lastname}

Example
https://mockend.com/AndreaRichardson/RepairChecker/Repair?emailAddress_eq=loislewis@tamanta.net
&country_eq=IT&lastName_eq=Freeman

## Repair ID
Query API:
https://mockend.com/AndreaRichardson/RepairChecker/Repair?repairID_eq{repairID}

Example
https://mockend.com/AndreaRichardson/RepairChecker/Repair?repairID_eq=R000000015
