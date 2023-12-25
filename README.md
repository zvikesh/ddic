# DDIC Overview

https://link.excalidraw.com/l/5eMbpiBu0l3/99xUHIsdcjJ

# Test data wihtout line break

## Flight

```
    lt_flight = VALUE #(
    ( airport_from_id = 'SFO' airport_to_id = 'SIN' airline_id = 'SQ' flight_date = lv_current_date departure_time = '011500' arrival_time = '115000' distance = '13523' distance_unit = 'KM' price = '10818.00' currency_code = 'SGD' plane_type_id = '767-200'  seats_max = '260' seats_occupied = '223' )
    ( airport_from_id = 'SIN' airport_to_id = 'SFO' airline_id = 'SQ' flight_date = lv_current_date departure_time = '063000' arrival_time = '091500' distance = '13523' distance_unit = 'KM' price = '11765.00' currency_code = 'SGD' plane_type_id = '747-400'  seats_max = '385' seats_occupied = '350' )
    ( airport_from_id = 'NRT' airport_to_id = 'SIN' airline_id = 'SQ' flight_date = lv_current_date departure_time = '145500' arrival_time = '205000' distance = '5363'  distance_unit = 'KM' price = '2359.00'  currency_code = 'SGD' plane_type_id = '767-200'  seats_max = '260' seats_occupied = '132' )
    ( airport_from_id = 'SIN' airport_to_id = 'NRT' airline_id = 'SQ' flight_date = lv_current_date departure_time = '095300' arrival_time = '175400' distance = '5363'  distance_unit = 'KM' price = '4665.00'  currency_code = 'SGD' plane_type_id = '767-200'  seats_max = '260' seats_occupied = '236' )
    ( airport_from_id = 'SFO' airport_to_id = 'FRA' airline_id = 'UA' flight_date = lv_current_date departure_time = '134500' arrival_time = '095500' distance = '9608'  distance_unit = 'KM' price = '6629.00'  currency_code = 'USD' plane_type_id = '767-200'  seats_max = '260' seats_occupied = '200' )
    ( airport_from_id = 'FRA' airport_to_id = 'SFO' airline_id = 'UA' flight_date = lv_current_date departure_time = '135500' arrival_time = '163000' distance = '9608'  distance_unit = 'KM' price = '4131.00'  currency_code = 'USD' plane_type_id = 'A340-600' seats_max = '330' seats_occupied = '161' )
    ( airport_from_id = 'EWR' airport_to_id = 'MIA' airline_id = 'UA' flight_date = lv_current_date departure_time = '215600' arrival_time = '004700' distance = '1752'  distance_unit = 'KM' price = '893.00'   currency_code = 'USD' plane_type_id = 'A321-200' seats_max = '150' seats_occupied = '88'  )
    ( airport_from_id = 'MIA' airport_to_id = 'EWR' airline_id = 'AA' flight_date = lv_current_date departure_time = '201700' arrival_time = '231900' distance = '1752'  distance_unit = 'KM' price = '1103.00'  currency_code = 'USD' plane_type_id = 'A320-200' seats_max = '130' seats_occupied = '93'  )
    ( airport_from_id = 'MIA' airport_to_id = 'HAV' airline_id = 'AA' flight_date = lv_current_date departure_time = '071900' arrival_time = '080300' distance = '520'   distance_unit = 'KM' price = '462.00'   currency_code = 'USD' plane_type_id = 'A321-200' seats_max = '150' seats_occupied = '139' )
    ( airport_from_id = 'HAV' airport_to_id = 'MIA' airline_id = 'AA' flight_date = lv_current_date departure_time = '061500' arrival_time = '103000' distance = '520'   distance_unit = 'KM' price = '473.00'   currency_code = 'USD' plane_type_id = 'A321-200' seats_max = '150' seats_occupied = '141' )
    ( airport_from_id = 'JFK' airport_to_id = 'SFO' airline_id = 'AA' flight_date = lv_current_date departure_time = '071300' arrival_time = '100400' distance = '4156'  distance_unit = 'KM' price = '1911.00'  currency_code = 'USD' plane_type_id = '767-200'  seats_max = '260' seats_occupied = '137' )
    ( airport_from_id = 'SFO' airport_to_id = 'JFK' airline_id = 'AA' flight_date = lv_current_date departure_time = '064000' arrival_time = '150600' distance = '4156'  distance_unit = 'KM' price = '3781.00'  currency_code = 'USD' plane_type_id = 'A380-800' seats_max = '475' seats_occupied = '446' )
    ( airport_from_id = 'FRA' airport_to_id = 'JFK' airline_id = 'LH' flight_date = lv_current_date departure_time = '101000' arrival_time = '113400' distance = '6162'  distance_unit = 'KM' price = '5484.00'  currency_code = 'EUR' plane_type_id = 'A340-600' seats_max = '330' seats_occupied = '306' )
    ( airport_from_id = 'JFK' airport_to_id = 'FRA' airline_id = 'LH' flight_date = lv_current_date departure_time = '183000' arrival_time = '074500' distance = '6162'  distance_unit = 'KM' price = '3697.00'  currency_code = 'EUR' plane_type_id = '747-400'  seats_max = '385' seats_occupied = '265' )
    ( airport_from_id = 'FRA' airport_to_id = 'EWR' airline_id = 'LH' flight_date = lv_current_date departure_time = '133000' arrival_time = '153500' distance = '6217'  distance_unit = 'KM' price = '4911.00'  currency_code = 'EUR' plane_type_id = '767-200'  seats_max = '260' seats_occupied = '221' )
    ( airport_from_id = 'EWR' airport_to_id = 'FRA' airline_id = 'LH' flight_date = lv_current_date departure_time = '180900' arrival_time = '073000' distance = '6217'  distance_unit = 'KM' price = '2797.00'  currency_code = 'EUR' plane_type_id = 'A340-600' seats_max = '330' seats_occupied = '171' )
    ( airport_from_id = 'NRT' airport_to_id = 'FRA' airline_id = 'JL' flight_date = lv_current_date departure_time = '132300' arrival_time = '155600' distance = '9379'  distance_unit = 'KM' price = '5346.00'  currency_code = 'JPY' plane_type_id = '747-400'  seats_max = '385' seats_occupied = '254' )
    ( airport_from_id = 'FRA' airport_to_id = 'NRT' airline_id = 'JL' flight_date = lv_current_date departure_time = '202500' arrival_time = '154000' distance = '9379'  distance_unit = 'KM' price = '8159.00'  currency_code = 'JPY' plane_type_id = 'A380-800' seats_max = '475' seats_occupied = '432' )
    ( airport_from_id = 'VCE' airport_to_id = 'NRT' airline_id = 'AZ' flight_date = lv_current_date departure_time = '132500' arrival_time = '101300' distance = '9595'  distance_unit = 'KM' price = '7580.00'  currency_code = 'EUR' plane_type_id = '767-200'  seats_max = '260' seats_occupied = '221' )
    ( airport_from_id = 'NRT' airport_to_id = 'VCE' airline_id = 'AZ' flight_date = lv_current_date departure_time = '142600' arrival_time = '213100' distance = '9595'  distance_unit = 'KM' price = '8539.00'  currency_code = 'EUR' plane_type_id = 'A380-800' seats_max = '475' seats_occupied = '441' )
     ).
```

# Airline

```
VALUE #(
( CLIENT = '100' CARRIER_ID = 'AA' NAME = 'American Airlines Inc.' CURRENCY_CODE = 'USD' IS_COMPLETE = '' NO_OF_CONNECTIONS = '0' LOCAL_CREATED_BY = 'GENERATOR' LOCAL_CREATED_AT = '20231007173522.0000000 ' LOCAL_LAST_CHANGED_BY = 'GENERATOR' 
LOCAL_LAST_CHANGED_AT = '20231007173522.0000000 ' LAST_CHANGED_AT = '20231007173522.0000000 '  )
( CLIENT = '100' CARRIER_ID = 'AC' NAME = 'Air Canada' CURRENCY_CODE = 'CAD' IS_COMPLETE = '' NO_OF_CONNECTIONS = '0' LOCAL_CREATED_BY = 'GENERATOR' LOCAL_CREATED_AT = '20231007173522.0000000 ' LOCAL_LAST_CHANGED_BY = 'GENERATOR' 
LOCAL_LAST_CHANGED_AT = '20231007173522.0000000 ' LAST_CHANGED_AT = '20231007173522.0000000 '  )
( CLIENT = '100' CARRIER_ID = 'AF' NAME = 'Air France' CURRENCY_CODE = 'EUR' IS_COMPLETE = '' NO_OF_CONNECTIONS = '0' LOCAL_CREATED_BY = 'GENERATOR' LOCAL_CREATED_AT = '20231007173522.0000000 ' LOCAL_LAST_CHANGED_BY = 'GENERATOR' 
LOCAL_LAST_CHANGED_AT = '20231007173522.0000000 ' LAST_CHANGED_AT = '20231007173522.0000000 '  )
( CLIENT = '100' CARRIER_ID = 'AZ' NAME = 'Alitalia Societa Aerea Italiana S.p.A.' CURRENCY_CODE = 'EUR' IS_COMPLETE = '' NO_OF_CONNECTIONS = '0' LOCAL_CREATED_BY = 'GENERATOR' LOCAL_CREATED_AT = '20231007173522.0000000 ' 
LOCAL_LAST_CHANGED_BY = 'GENERATOR' LOCAL_LAST_CHANGED_AT = '20231007173522.0000000 ' LAST_CHANGED_AT = '20231007173522.0000000 '  )
( CLIENT = '100' CARRIER_ID = 'BA' NAME = 'British Airways p.l.c.' CURRENCY_CODE = 'GBP' IS_COMPLETE = '' NO_OF_CONNECTIONS = '0' LOCAL_CREATED_BY = 'GENERATOR' LOCAL_CREATED_AT = '20231007173522.0000000 ' LOCAL_LAST_CHANGED_BY = 'GENERATOR' 
LOCAL_LAST_CHANGED_AT = '20231007173522.0000000 ' LAST_CHANGED_AT = '20231007173522.0000000 '  )
( CLIENT = '100' CARRIER_ID = 'FJ' NAME = 'Air Pacific Limited t/a Fiji Airway' CURRENCY_CODE = 'USD' IS_COMPLETE = '' NO_OF_CONNECTIONS = '0' LOCAL_CREATED_BY = 'GENERATOR' LOCAL_CREATED_AT = '20231007173522.0000000 ' LOCAL_LAST_CHANGED_BY = 'GENERATOR' 
LOCAL_LAST_CHANGED_AT = '20231007173522.0000000 ' LAST_CHANGED_AT = '20231007173522.0000000 '  )
( CLIENT = '100' CARRIER_ID = 'CO' NAME = 'Cobaltair Ltd. dba Cobalt' CURRENCY_CODE = 'USD' IS_COMPLETE = '' NO_OF_CONNECTIONS = '0' LOCAL_CREATED_BY = 'GENERATOR' LOCAL_CREATED_AT = '20231007173522.0000000 ' LOCAL_LAST_CHANGED_BY = 'GENERATOR' 
LOCAL_LAST_CHANGED_AT = '20231007173522.0000000 ' LAST_CHANGED_AT = '20231007173522.0000000 '  )
( CLIENT = '100' CARRIER_ID = 'DL' NAME = 'Delta Air Lines, Inc.' CURRENCY_CODE = 'USD' IS_COMPLETE = '' NO_OF_CONNECTIONS = '0' LOCAL_CREATED_BY = 'GENERATOR' LOCAL_CREATED_AT = '20231007173522.0000000 ' LOCAL_LAST_CHANGED_BY = 'GENERATOR' 
LOCAL_LAST_CHANGED_AT = '20231007173522.0000000 ' LAST_CHANGED_AT = '20231007173522.0000000 '  )
( CLIENT = '100' CARRIER_ID = 'LH' NAME = 'Deutsche Lufthansa AG' CURRENCY_CODE = 'EUR' IS_COMPLETE = '' NO_OF_CONNECTIONS = '0' LOCAL_CREATED_BY = 'GENERATOR' LOCAL_CREATED_AT = '20231007173522.0000000 ' LOCAL_LAST_CHANGED_BY = 'GENERATOR' 
LOCAL_LAST_CHANGED_AT = '20231007173522.0000000 ' LAST_CHANGED_AT = '20231007173522.0000000 '  )
( CLIENT = '100' CARRIER_ID = 'NG' NAME = 'AL-Naser Wings' CURRENCY_CODE = 'EUR' IS_COMPLETE = '' NO_OF_CONNECTIONS = '0' LOCAL_CREATED_BY = 'GENERATOR' LOCAL_CREATED_AT = '20231007173522.0000000 ' LOCAL_LAST_CHANGED_BY = 'GENERATOR' 
LOCAL_LAST_CHANGED_AT = '20231007173522.0000000 ' LAST_CHANGED_AT = '20231007173522.0000000 '  )
( CLIENT = '100' CARRIER_ID = 'JL' NAME = 'Japan Airlines Co., Ltd.' CURRENCY_CODE = 'JPY' IS_COMPLETE = '' NO_OF_CONNECTIONS = '0' LOCAL_CREATED_BY = 'GENERATOR' LOCAL_CREATED_AT = '20231007173522.0000000 ' LOCAL_LAST_CHANGED_BY = 'GENERATOR' 
LOCAL_LAST_CHANGED_AT = '20231007173522.0000000 ' LAST_CHANGED_AT = '20231007173522.0000000 '  )
( CLIENT = '100' CARRIER_ID = 'QF' NAME = 'Qantas Airways Ltd.' CURRENCY_CODE = 'AUD' IS_COMPLETE = '' NO_OF_CONNECTIONS = '0' LOCAL_CREATED_BY = 'GENERATOR' LOCAL_CREATED_AT = '20231007173522.0000000 ' LOCAL_LAST_CHANGED_BY = 'GENERATOR' 
LOCAL_LAST_CHANGED_AT = '20231007173522.0000000 ' LAST_CHANGED_AT = '20231007173522.0000000 '  )
( CLIENT = '100' CARRIER_ID = 'SA' NAME = 'South African Airways' CURRENCY_CODE = 'ZAR' IS_COMPLETE = '' NO_OF_CONNECTIONS = '0' LOCAL_CREATED_BY = 'GENERATOR' LOCAL_CREATED_AT = '20231007173522.0000000 ' LOCAL_LAST_CHANGED_BY = 'GENERATOR' 
LOCAL_LAST_CHANGED_AT = '20231007173522.0000000 ' LAST_CHANGED_AT = '20231007173522.0000000 '  )
( CLIENT = '100' CARRIER_ID = 'SQ' NAME = 'Singapore Airlines Limited' CURRENCY_CODE = 'SGD' IS_COMPLETE = '' NO_OF_CONNECTIONS = '0' LOCAL_CREATED_BY = 'GENERATOR' LOCAL_CREATED_AT = '20231007173522.0000000 ' LOCAL_LAST_CHANGED_BY = 'GENERATOR' 
LOCAL_LAST_CHANGED_AT = '20231007173522.0000000 ' LAST_CHANGED_AT = '20231007173522.0000000 '  )
( CLIENT = '100' CARRIER_ID = 'SR' NAME = 'Sundair GmbH' CURRENCY_CODE = 'CHF' IS_COMPLETE = '' NO_OF_CONNECTIONS = '0' LOCAL_CREATED_BY = 'GENERATOR' LOCAL_CREATED_AT = '20231007173522.0000000 ' LOCAL_LAST_CHANGED_BY = 'GENERATOR' 
LOCAL_LAST_CHANGED_AT = '20231007173522.0000000 ' LAST_CHANGED_AT = '20231007173522.0000000 '  )
( CLIENT = '100' CARRIER_ID = 'UA' NAME = 'United Airlines, Inc.' CURRENCY_CODE = 'USD' IS_COMPLETE = '' NO_OF_CONNECTIONS = '0' LOCAL_CREATED_BY = 'GENERATOR' LOCAL_CREATED_AT = '20231007173522.0000000 ' LOCAL_LAST_CHANGED_BY = 'GENERATOR' 
LOCAL_LAST_CHANGED_AT = '20231007173522.0000000 ' LAST_CHANGED_AT = '20231007173522.0000000 '  )
 )
```
