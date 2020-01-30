<!--
 ___ _            _ _    _ _    __
/ __(_)_ __  _ __| (_)__(_) |_ /_/
\__ \ | '  \| '_ \ | / _| |  _/ -_)
|___/_|_|_|_| .__/_|_\__|_|\__\___|
            |_| 
-->
![](https://docs.simplicite.io//logos/logo250.png)
* * *

`ISOCountries` module definition
================================

Countries (ISO 3166-1)

`ISOCountry` business object definition
---------------------------------------

ISO 3166-1 country

### Fields

| Name                                                         | Type                                     | Required | Updatable | Personal | Description                                                                      | 
| ------------------------------------------------------------ | ---------------------------------------- | -------- | --------- | -------- | -------------------------------------------------------------------------------- |
| `isoCtyName`                                                 | char(100)                                | yes      | yes       |          | Country name                                                                     |
| `isoCtyCode2`                                                | char(2)                                  | yes*     | yes       |          | Country code (2 letters)                                                         |
| `isoCtyCode3`                                                | char(3)                                  |          | yes       |          | Country code (3 letters)                                                         |
| `isoCtyIndependent`                                          | boolean                                  | yes      | yes       |          | Independent country?                                                             |

### Custom actions

No custom action

