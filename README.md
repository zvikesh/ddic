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

## Travel

```
VALUE #(
( TRAVEL_ID = '00034567' AGENCY_ID = '000000' CUSTOMER_ID = '000000' BEGIN_DATE = '20231101' END_DATE = '20231124' BOOKING_FEE = '122.00 ' TOTAL_PRICE = '1234.00 ' CURRENCY_CODE = 'INR' DESCRIPTION = 'Travel creation' STATUS = 'A' )
( TRAVEL_ID = '00008699' AGENCY_ID = '000000' CUSTOMER_ID = '000000' BEGIN_DATE = '00000000' END_DATE = '00000000' BOOKING_FEE = '0.00 ' TOTAL_PRICE = '0.00 ' CURRENCY_CODE = '' DESCRIPTION = '' STATUS = 'B' )
( TRAVEL_ID = '00004555' AGENCY_ID = '000000' CUSTOMER_ID = '000006' BEGIN_DATE = '00000000' END_DATE = '00000000' BOOKING_FEE = '0.00 ' TOTAL_PRICE = '0.00 ' CURRENCY_CODE = '' DESCRIPTION = '' STATUS = '' )
( TRAVEL_ID = '00020205' AGENCY_ID = '070001' CUSTOMER_ID = '000003' BEGIN_DATE = '20231124' END_DATE = '20231229' BOOKING_FEE = '100.00 ' TOTAL_PRICE = '1900.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = 'My travel booking' STATUS = 'O' )
( TRAVEL_ID = '00003029' AGENCY_ID = '070001' CUSTOMER_ID = '000011' BEGIN_DATE = '20230722' END_DATE = '20230722' BOOKING_FEE = '10.00 ' TOTAL_PRICE = '2815.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'Vacation' STATUS = 'N' )
( TRAVEL_ID = '00004224' AGENCY_ID = '070001' CUSTOMER_ID = '000004' BEGIN_DATE = '20231001' END_DATE = '20231031' BOOKING_FEE = '2500.00 ' TOTAL_PRICE = '2500.00 ' CURRENCY_CODE = 'INR' DESCRIPTION = 'Not Applicable' STATUS = 'N')
( TRAVEL_ID = '00004467' AGENCY_ID = '070001' CUSTOMER_ID = '000003' BEGIN_DATE = '20231122' END_DATE = '20231123' BOOKING_FEE = '0.00 ' TOTAL_PRICE = '0.00 ' CURRENCY_CODE = '' DESCRIPTION = '' STATUS = 'N'  'CB9980008423' )
( TRAVEL_ID = '00003285' AGENCY_ID = '070001' CUSTOMER_ID = '000093' BEGIN_DATE = '20230722' END_DATE = '20230722' BOOKING_FEE = '10.00 ' TOTAL_PRICE = '1888.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'Vacation' STATUS = 'N' )
( TRAVEL_ID = '00004227' AGENCY_ID = '070001' CUSTOMER_ID = '000002' BEGIN_DATE = '20231015' END_DATE = '20231016' BOOKING_FEE = '1.00 ' TOTAL_PRICE = '1.00 ' CURRENCY_CODE = 'AFN' DESCRIPTION = 'test' STATUS = 'N' )
( TRAVEL_ID = '00004472' AGENCY_ID = '070001' CUSTOMER_ID = '000005' BEGIN_DATE = '20231125' END_DATE = '20231129' BOOKING_FEE = '0.00 ' TOTAL_PRICE = '0.00 ' CURRENCY_CODE = 'ANG' DESCRIPTION = 'PRUEBA' STATUS = 'N')
( TRAVEL_ID = '00000544' AGENCY_ID = '070001' CUSTOMER_ID = '000019' BEGIN_DATE = '20240515' END_DATE = '20240515' BOOKING_FEE = '20.00 ' TOTAL_PRICE = '10405.00 ' CURRENCY_CODE = 'SGD' DESCRIPTION = 'Vacation' STATUS = 'N' )
( TRAVEL_ID = '00004220' AGENCY_ID = '070001' CUSTOMER_ID = '000001' BEGIN_DATE = '20231009' END_DATE = '20231011' BOOKING_FEE = '0.00 ' TOTAL_PRICE = '0.00 ' CURRENCY_CODE = '' DESCRIPTION = '' STATUS = 'B' )
( TRAVEL_ID = '00000120' AGENCY_ID = '070001' CUSTOMER_ID = '000100' BEGIN_DATE = '20230718' END_DATE = '20230718' BOOKING_FEE = '20.00 ' TOTAL_PRICE = '3305.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'Vacation' STATUS = 'N' )
( TRAVEL_ID = '00004158' AGENCY_ID = '070001' CUSTOMER_ID = '000002' BEGIN_DATE = '20231009' END_DATE = '20231009' BOOKING_FEE = '0.00 ' TOTAL_PRICE = '0.00 ' CURRENCY_CODE = '' DESCRIPTION = 'aaaa' STATUS = 'N')
( TRAVEL_ID = '00002280' AGENCY_ID = '070001' CUSTOMER_ID = '000054' BEGIN_DATE = '20240517' END_DATE = '20240517' BOOKING_FEE = '20.00 ' TOTAL_PRICE = '7004.00 ' CURRENCY_CODE = 'JPY' DESCRIPTION = 'Vacation' STATUS = 'N')
( TRAVEL_ID = '00004453' AGENCY_ID = '070001' CUSTOMER_ID = '000001' BEGIN_DATE = '20231102' END_DATE = '20231202' BOOKING_FEE = '800.00 ' TOTAL_PRICE = '800.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = 'KURNOOL' STATUS = 'N' )
( TRAVEL_ID = '00004155' AGENCY_ID = '070001' CUSTOMER_ID = '000001' BEGIN_DATE = '20231009' END_DATE = '20231009' BOOKING_FEE = '0.00 ' TOTAL_PRICE = '0.00 ' CURRENCY_CODE = '' DESCRIPTION = '' STATUS = 'N')
( TRAVEL_ID = '00004461' AGENCY_ID = '070001' CUSTOMER_ID = '000004' BEGIN_DATE = '20231116' END_DATE = '20231116' BOOKING_FEE = '0.00 ' TOTAL_PRICE = '0.00 ' CURRENCY_CODE = 'CNY' DESCRIPTION = '54455544' STATUS = 'N' )
( TRAVEL_ID = '00004440' AGENCY_ID = '070001' CUSTOMER_ID = '000002' BEGIN_DATE = '20231106' END_DATE = '20231130' BOOKING_FEE = '1399.00 ' TOTAL_PRICE = '1399.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = '' STATUS = 'N' )
( TRAVEL_ID = '00004432' AGENCY_ID = '070001' CUSTOMER_ID = '000001' BEGIN_DATE = '20231102' END_DATE = '20231108' BOOKING_FEE = '1000.00 ' TOTAL_PRICE = '1000.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = 'Test Travel' STATUS = 'N' )
( TRAVEL_ID = '00004465' AGENCY_ID = '070001' CUSTOMER_ID = '000004' BEGIN_DATE = '20231121' END_DATE = '20231124' BOOKING_FEE = '0.00 ' TOTAL_PRICE = '0.00 ' CURRENCY_CODE = '' DESCRIPTION = '' STATUS = 'N' )
( TRAVEL_ID = '00004403' AGENCY_ID = '070001' CUSTOMER_ID = '000001' BEGIN_DATE = '20231019' END_DATE = '20231027' BOOKING_FEE = '0.00 ' TOTAL_PRICE = '0.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = '' STATUS = 'N' )
( TRAVEL_ID = '00003665' AGENCY_ID = '070001' CUSTOMER_ID = '000093' BEGIN_DATE = '20240517' END_DATE = '20240517' BOOKING_FEE = '30.00 ' TOTAL_PRICE = '7271.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'Vacation' STATUS = 'N' )
( TRAVEL_ID = '00004311' AGENCY_ID = '070001' CUSTOMER_ID = '000001' BEGIN_DATE = '20231016' END_DATE = '20231017' BOOKING_FEE = '300.00 ' TOTAL_PRICE = '300.00 ' CURRENCY_CODE = 'INR' DESCRIPTION = 'vacation' STATUS = 'N' )
( TRAVEL_ID = '00004437' AGENCY_ID = '070001' CUSTOMER_ID = '000009' BEGIN_DATE = '20231101' END_DATE = '20231130' BOOKING_FEE = '2500.00 ' TOTAL_PRICE = '5617.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = '' STATUS = 'B' )
( TRAVEL_ID = '00001743' AGENCY_ID = '070001' CUSTOMER_ID = '000001' BEGIN_DATE = '20230718' END_DATE = '20230718' BOOKING_FEE = '20.00 ' TOTAL_PRICE = '3164.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'Vacation' STATUS = 'N' )
( TRAVEL_ID = '00004167' AGENCY_ID = '070001' CUSTOMER_ID = '000001' BEGIN_DATE = '20231011' END_DATE = '20231017' BOOKING_FEE = '12.00 ' TOTAL_PRICE = '12.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = 'Test' STATUS = 'N' )
( TRAVEL_ID = '00004438' AGENCY_ID = '070001' CUSTOMER_ID = '000007' BEGIN_DATE = '20231101' END_DATE = '20231130' BOOKING_FEE = '1300.00 ' TOTAL_PRICE = '7531.56 ' CURRENCY_CODE = 'USD' DESCRIPTION = 'Test - AAA' STATUS = 'N' )
( TRAVEL_ID = '00004168' AGENCY_ID = '070001' CUSTOMER_ID = '000002' BEGIN_DATE = '20231011' END_DATE = '20231011' BOOKING_FEE = '10.00 ' TOTAL_PRICE = '10.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = '' STATUS = 'N' )
( TRAVEL_ID = '00004464' AGENCY_ID = '070001' CUSTOMER_ID = '000001' BEGIN_DATE = '20231120' END_DATE = '20231120' BOOKING_FEE = '12.00 ' TOTAL_PRICE = '12.00 ' CURRENCY_CODE = 'AMD' DESCRIPTION = '' STATUS = 'N' )
( TRAVEL_ID = '00004433' AGENCY_ID = '070001' CUSTOMER_ID = '000002' BEGIN_DATE = '20231103' END_DATE = '20231109' BOOKING_FEE = '100.00 ' TOTAL_PRICE = '100.00 ' CURRENCY_CODE = 'AED' DESCRIPTION = 'hello' STATUS = 'N' )
( TRAVEL_ID = '00004381' AGENCY_ID = '070001' CUSTOMER_ID = '000001' BEGIN_DATE = '20231019' END_DATE = '20231019' BOOKING_FEE = '0.00 ' TOTAL_PRICE = '0.00 ' CURRENCY_CODE = 'PLN' DESCRIPTION = '' STATUS = 'N' )
( TRAVEL_ID = '00001269' AGENCY_ID = '070001' CUSTOMER_ID = '000070' BEGIN_DATE = '20230721' END_DATE = '20230721' BOOKING_FEE = '10.00 ' TOTAL_PRICE = '10693.00 ' CURRENCY_CODE = 'SGD' DESCRIPTION = 'Vacation' STATUS = 'N' )
( TRAVEL_ID = '00004475' AGENCY_ID = '070001' CUSTOMER_ID = '000003' BEGIN_DATE = '20231211' END_DATE = '20231212' BOOKING_FEE = '100.00 ' TOTAL_PRICE = '100.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'test' STATUS = 'N' )
( TRAVEL_ID = '00004435' AGENCY_ID = '070001' CUSTOMER_ID = '000004' BEGIN_DATE = '20231101' END_DATE = '20231130' BOOKING_FEE = '1500.00 ' TOTAL_PRICE = '1500.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = 'Test - AAA' STATUS = 'N' )
( TRAVEL_ID = '00004163' AGENCY_ID = '070001' CUSTOMER_ID = '000002' BEGIN_DATE = '20231010' END_DATE = '20231011' BOOKING_FEE = '33.00 ' TOTAL_PRICE = '33.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'first test' STATUS = 'N' )
( TRAVEL_ID = '00004156' AGENCY_ID = '070001' CUSTOMER_ID = '000002' BEGIN_DATE = '20231009' END_DATE = '20231009' BOOKING_FEE = '0.00 ' TOTAL_PRICE = '0.00 ' CURRENCY_CODE = '' DESCRIPTION = '' STATUS = 'N' )
( TRAVEL_ID = '00004449' AGENCY_ID = '070001' CUSTOMER_ID = '000003' BEGIN_DATE = '20231110' END_DATE = '20231110' BOOKING_FEE = '0.00 ' TOTAL_PRICE = '0.00 ' CURRENCY_CODE = '' DESCRIPTION = '' STATUS = 'N' )
( TRAVEL_ID = '00004312' AGENCY_ID = '070001' CUSTOMER_ID = '000001' BEGIN_DATE = '20231017' END_DATE = '20231017' BOOKING_FEE = '0.00 ' TOTAL_PRICE = '0.00 ' CURRENCY_CODE = 'INR' DESCRIPTION = '  test' STATUS = 'N' )
( TRAVEL_ID = '00004223' AGENCY_ID = '070001' CUSTOMER_ID = '000003' BEGIN_DATE = '20231001' END_DATE = '20231031' BOOKING_FEE = '50000.00 ' TOTAL_PRICE = '50000.00 ' CURRENCY_CODE = 'INR' DESCRIPTION = 'NA' STATUS = 'N' )
( TRAVEL_ID = '00004452' AGENCY_ID = '070001' CUSTOMER_ID = '000001' BEGIN_DATE = '20231124' END_DATE = '20231201' BOOKING_FEE = '306.00 ' TOTAL_PRICE = '306.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = 'KURNOOL' STATUS = 'N' )
( TRAVEL_ID = '00004145' AGENCY_ID = '070001' CUSTOMER_ID = '000010' BEGIN_DATE = '20231002' END_DATE = '20231010' BOOKING_FEE = '500000.00 ' TOTAL_PRICE = '500000.00 ' CURRENCY_CODE = 'INR' DESCRIPTION = 'air india' STATUS = 'N' )
( TRAVEL_ID = '00004313' AGENCY_ID = '070001' CUSTOMER_ID = '000005' BEGIN_DATE = '20231017' END_DATE = '20231018' BOOKING_FEE = '400.00 ' TOTAL_PRICE = '400.00 ' CURRENCY_CODE = 'INR' DESCRIPTION = 'test' STATUS = 'N' )
( TRAVEL_ID = '00004454' AGENCY_ID = '070001' CUSTOMER_ID = '000002' BEGIN_DATE = '20231124' END_DATE = '20231201' BOOKING_FEE = '800.00 ' TOTAL_PRICE = '800.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = 'KURNOOL' STATUS = 'N' )
( TRAVEL_ID = '00004154' AGENCY_ID = '070001' CUSTOMER_ID = '000001' BEGIN_DATE = '20231009' END_DATE = '20231009' BOOKING_FEE = '0.00 ' TOTAL_PRICE = '0.00 ' CURRENCY_CODE = '' DESCRIPTION = '' STATUS = 'N' )
( TRAVEL_ID = '00004226' AGENCY_ID = '070001' CUSTOMER_ID = '000001' BEGIN_DATE = '20231015' END_DATE = '20231016' BOOKING_FEE = '11.00 ' TOTAL_PRICE = '7043.48 ' CURRENCY_CODE = 'AED' DESCRIPTION = 'Test' STATUS = 'N' )
( TRAVEL_ID = '00001111' AGENCY_ID = '070001' CUSTOMER_ID = '000040' BEGIN_DATE = '20240513' END_DATE = '20240513' BOOKING_FEE = '30.00 ' TOTAL_PRICE = '10152.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = 'Vacation' STATUS = 'N' )
( TRAVEL_ID = '00012106' AGENCY_ID = '070001' CUSTOMER_ID = '000021' BEGIN_DATE = '20231122' END_DATE = '20231203' BOOKING_FEE = '100.00 ' TOTAL_PRICE = '39318.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = 'Thanks giving' STATUS = 'O' )
( TRAVEL_ID = '00001988' AGENCY_ID = '070001' CUSTOMER_ID = '000055' BEGIN_DATE = '20240518' END_DATE = '20240518' BOOKING_FEE = '30.00 ' TOTAL_PRICE = '4869.00 ' CURRENCY_CODE = 'SGD' DESCRIPTION = 'Vacation' STATUS = 'N' )
( TRAVEL_ID = '00004436' AGENCY_ID = '070001' CUSTOMER_ID = '000008' BEGIN_DATE = '20231101' END_DATE = '20231130' BOOKING_FEE = '2000.00 ' TOTAL_PRICE = '2000.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = '' STATUS = 'N' )
( TRAVEL_ID = '00004479' AGENCY_ID = '070001' CUSTOMER_ID = '000006' BEGIN_DATE = '20231226' END_DATE = '20240101' BOOKING_FEE = '40.00 ' TOTAL_PRICE = '40.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = 'US Travel' STATUS = 'N' )
( TRAVEL_ID = '00004384' AGENCY_ID = '070002' CUSTOMER_ID = '000004' BEGIN_DATE = '20231026' END_DATE = '20231027' BOOKING_FEE = '0.00 ' TOTAL_PRICE = '0.00 ' CURRENCY_CODE = '' DESCRIPTION = '' STATUS = 'N'  )
( TRAVEL_ID = '00000919' AGENCY_ID = '070002' CUSTOMER_ID = '000064' BEGIN_DATE = '20230722' END_DATE = '20230722' BOOKING_FEE = '10.00 ' TOTAL_PRICE = '2636.00 ' CURRENCY_CODE = 'JPY' DESCRIPTION = 'Vacation' STATUS = 'N' )
( TRAVEL_ID = '00000815' AGENCY_ID = '070002' CUSTOMER_ID = '000014' BEGIN_DATE = '20240514' END_DATE = '20240514' BOOKING_FEE = '10.00 ' TOTAL_PRICE = '2424.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = 'Vacation' STATUS = 'N' )
( TRAVEL_ID = '00001364' AGENCY_ID = '070002' CUSTOMER_ID = '000020' BEGIN_DATE = '20230722' END_DATE = '20230722' BOOKING_FEE = '10.00 ' TOTAL_PRICE = '2545.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = 'Vacation' STATUS = 'N' )
( TRAVEL_ID = '00004380' AGENCY_ID = '070002' CUSTOMER_ID = '000006' BEGIN_DATE = '20231019' END_DATE = '20231020' BOOKING_FEE = '0.00 ' TOTAL_PRICE = '0.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = 'CY test' STATUS = 'N' )
( TRAVEL_ID = '00002017' AGENCY_ID = '070002' CUSTOMER_ID = '000052' BEGIN_DATE = '20240518' END_DATE = '20240518' BOOKING_FEE = '20.00 ' TOTAL_PRICE = '4546.00 ' CURRENCY_CODE = 'SGD' DESCRIPTION = 'Vacation' STATUS = 'N' )
( TRAVEL_ID = '00003372' AGENCY_ID = '070002' CUSTOMER_ID = '000043' BEGIN_DATE = '20230722' END_DATE = '20230722' BOOKING_FEE = '10.00 ' TOTAL_PRICE = '3362.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'Vacation' STATUS = 'N' )
( TRAVEL_ID = '00004308' AGENCY_ID = '070002' CUSTOMER_ID = '000005' BEGIN_DATE = '20231020' END_DATE = '20231025' BOOKING_FEE = '4.00 ' TOTAL_PRICE = '4.00 ' CURRENCY_CODE = 'AMD' DESCRIPTION = 'asdf' STATUS = 'N' )
( TRAVEL_ID = '00004152' AGENCY_ID = '070002' CUSTOMER_ID = '000005' BEGIN_DATE = '20231009' END_DATE = '20231009' BOOKING_FEE = '123.00 ' TOTAL_PRICE = '123.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = '' STATUS = 'N' )
( TRAVEL_ID = '00001285' AGENCY_ID = '070002' CUSTOMER_ID = '000012' BEGIN_DATE = '20230722' END_DATE = '20230722' BOOKING_FEE = '30.00 ' TOTAL_PRICE = '3175.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = 'Vacation' STATUS = 'N' )
( TRAVEL_ID = '00004316' AGENCY_ID = '070002' CUSTOMER_ID = '000003' BEGIN_DATE = '20231017' END_DATE = '20231018' BOOKING_FEE = '22.00 ' TOTAL_PRICE = '22.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = '' STATUS = 'N' )
( TRAVEL_ID = '00004225' AGENCY_ID = '070002' CUSTOMER_ID = '000002' BEGIN_DATE = '20231012' END_DATE = '20231013' BOOKING_FEE = '222.00 ' TOTAL_PRICE = '3649.41 ' CURRENCY_CODE = 'USD' DESCRIPTION = 'Test' STATUS = 'N' )
( TRAVEL_ID = '00003673' AGENCY_ID = '070002' CUSTOMER_ID = '000069' BEGIN_DATE = '20240517' END_DATE = '20240517' BOOKING_FEE = '10.00 ' TOTAL_PRICE = '2497.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'Vacation' STATUS = 'N')
( TRAVEL_ID = '00004320' AGENCY_ID = '070002' CUSTOMER_ID = '000011' BEGIN_DATE = '20231018' END_DATE = '20231024' BOOKING_FEE = '100.00 ' TOTAL_PRICE = '100.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'Test' STATUS = 'B'  )
( TRAVEL_ID = '00003266' AGENCY_ID = '070002' CUSTOMER_ID = '000024' BEGIN_DATE = '20230722' END_DATE = '20230722' BOOKING_FEE = '30.00 ' TOTAL_PRICE = '5293.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'Vacation' STATUS = 'N')
( TRAVEL_ID = '00003757' AGENCY_ID = '070002' CUSTOMER_ID = '000018' BEGIN_DATE = '20240517' END_DATE = '20240517' BOOKING_FEE = '10.00 ' TOTAL_PRICE = '3321.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Deichgraeber' CREATEDAT = '20230921090520.0000000 ' LASTCHANGEDBY = 'Hunter' LASTCHANGEDAT = '20230921191938.0000000 '  )
( TRAVEL_ID = '00004153' AGENCY_ID = '070002' CUSTOMER_ID = '000001' BEGIN_DATE = '20231009' END_DATE = '20231009' BOOKING_FEE = '123.00 ' TOTAL_PRICE = '123.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = '' STATUS = 'N' 
 'CB9980004107' CREATEDAT = '20231009141910.7543620 ' LASTCHANGEDBY = 'CB9980004107' LASTCHANGEDAT = '20231009141910.7543620 '  )
( TRAVEL_ID = '00004379' AGENCY_ID = '070002' CUSTOMER_ID = '000003' BEGIN_DATE = '20231020' END_DATE = '20251031' BOOKING_FEE = '0.00 ' TOTAL_PRICE = '0.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = 'Test' STATUS = 'N' 
 'CB9980007943' CREATEDAT = '20231019074824.8880960 ' LASTCHANGEDBY = 'CB9980007943' LASTCHANGEDAT = '20231019074824.8880960 '  )
( TRAVEL_ID = '00003310' AGENCY_ID = '070002' CUSTOMER_ID = '000020' BEGIN_DATE = '20230722' END_DATE = '20230722' BOOKING_FEE = '10.00 ' TOTAL_PRICE = '2170.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Müller' CREATEDAT = '20230703131156.0000000 ' LASTCHANGEDBY = 'Pratt' LASTCHANGEDAT = '20230703223614.0000000 '  )
( TRAVEL_ID = '00002895' AGENCY_ID = '070003' CUSTOMER_ID = '000051' BEGIN_DATE = '20230721' END_DATE = '20230721' BOOKING_FEE = '10.00 ' TOTAL_PRICE = '2586.00 ' CURRENCY_CODE = 'SGD' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Sessler' CREATEDAT = '20230628111108.0000000 ' LASTCHANGEDBY = 'Cesari' LASTCHANGEDAT = '20230629153143.0000000 '  )
( TRAVEL_ID = '00001089' AGENCY_ID = '070003' CUSTOMER_ID = '000015' BEGIN_DATE = '20240513' END_DATE = '20240513' BOOKING_FEE = '20.00 ' TOTAL_PRICE = '5417.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Eichbaum' CREATEDAT = '20230921151143.0000000 ' LASTCHANGEDBY = 'Sessler' LASTCHANGEDAT = '20230921173034.0000000 '  )
( TRAVEL_ID = '00002051' AGENCY_ID = '070003' CUSTOMER_ID = '000050' BEGIN_DATE = '20240518' END_DATE = '20240518' BOOKING_FEE = '20.00 ' TOTAL_PRICE = '7131.00 ' CURRENCY_CODE = 'SGD' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'D´Oultrement' CREATEDAT = '20230921055026.0000000 ' LASTCHANGEDBY = 'Dumbach' LASTCHANGEDAT = '20230921095335.0000000 '  )
( TRAVEL_ID = '00002373' AGENCY_ID = '070003' CUSTOMER_ID = '000044' BEGIN_DATE = '20240517' END_DATE = '20240517' BOOKING_FEE = '10.00 ' TOTAL_PRICE = '1745.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Jeremias' CREATEDAT = '20230921174652.0000000 ' LASTCHANGEDBY = 'Sudhoff' LASTCHANGEDAT = '20230921012155.0000000 '  )
( TRAVEL_ID = '00004404' AGENCY_ID = '070003' CUSTOMER_ID = '000006' BEGIN_DATE = '20231005' END_DATE = '20231103' BOOKING_FEE = '0.00 ' TOTAL_PRICE = '0.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = '' STATUS = 'N'  'CB9980007951' 
CREATEDAT = '20231019142934.8755420 ' LASTCHANGEDBY = 'CB9980007951' LASTCHANGEDAT = '20231019142934.8755420 '  )
( TRAVEL_ID = '00000874' AGENCY_ID = '070003' CUSTOMER_ID = '000051' BEGIN_DATE = '20240514' END_DATE = '20240514' BOOKING_FEE = '10.00 ' TOTAL_PRICE = '3666.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Domenech' CREATEDAT = '20230921012509.0000000 ' LASTCHANGEDBY = 'Columbo' LASTCHANGEDAT = '20230922154809.0000000 '  )
( TRAVEL_ID = '00002066' AGENCY_ID = '070003' CUSTOMER_ID = '000070' BEGIN_DATE = '20240518' END_DATE = '20240518' BOOKING_FEE = '30.00 ' TOTAL_PRICE = '13146.00 ' CURRENCY_CODE = 'SGD' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Gahl' CREATEDAT = '20230921023805.0000000 ' LASTCHANGEDBY = 'Detemple' LASTCHANGEDAT = '20230921132751.0000000 '  )
( TRAVEL_ID = '00001452' AGENCY_ID = '070003' CUSTOMER_ID = '000024' BEGIN_DATE = '20230723' END_DATE = '20230723' BOOKING_FEE = '20.00 ' TOTAL_PRICE = '3751.00 ' CURRENCY_CODE = 'SGD' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Kreiss' CREATEDAT = '20230625000547.0000000 ' LASTCHANGEDBY = 'Vrsic' LASTCHANGEDAT = '20230625105945.0000000 '  )
( TRAVEL_ID = '00004169' AGENCY_ID = '070003' CUSTOMER_ID = '000002' BEGIN_DATE = '20231011' END_DATE = '20231011' BOOKING_FEE = '10.00 ' TOTAL_PRICE = '10.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = '' STATUS = 'N'  'CB9980004107' 
CREATEDAT = '20231011104821.6851690 ' LASTCHANGEDBY = 'CB9980004107' LASTCHANGEDAT = '20231011104821.6851690 '  )
( TRAVEL_ID = '00000303' AGENCY_ID = '070003' CUSTOMER_ID = '000078' BEGIN_DATE = '20230723' END_DATE = '20230723' BOOKING_FEE = '10.00 ' TOTAL_PRICE = '1690.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Jeremias' CREATEDAT = '20230630204808.0000000 ' LASTCHANGEDBY = 'Sisko' LASTCHANGEDAT = '20230701013414.0000000 '  )
( TRAVEL_ID = '00001409' AGENCY_ID = '070003' CUSTOMER_ID = '000074' BEGIN_DATE = '20230723' END_DATE = '20230723' BOOKING_FEE = '30.00 ' TOTAL_PRICE = '4333.00 ' CURRENCY_CODE = 'SGD' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Weiss' CREATEDAT = '20230622141835.0000000 ' LASTCHANGEDBY = 'Miguel' LASTCHANGEDAT = '20230623144401.0000000 '  )
( TRAVEL_ID = '00004222' AGENCY_ID = '070003' CUSTOMER_ID = '000002' BEGIN_DATE = '20231014' END_DATE = '20231014' BOOKING_FEE = '2000.00 ' TOTAL_PRICE = '2000.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = '' STATUS = 'N' 
 'CB9980004107' CREATEDAT = '20231014054918.9452520 ' LASTCHANGEDBY = 'CB9980004107' LASTCHANGEDAT = '20231014054918.9452520 '  )
( TRAVEL_ID = '00002213' AGENCY_ID = '070003' CUSTOMER_ID = '000017' BEGIN_DATE = '20240517' END_DATE = '20240517' BOOKING_FEE = '20.00 ' TOTAL_PRICE = '4746.00 ' CURRENCY_CODE = 'JPY' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Prinz' CREATEDAT = '20230921092530.0000000 ' LASTCHANGEDBY = 'Jacqmain' LASTCHANGEDAT = '20230921191027.0000000 '  )
( TRAVEL_ID = '00002479' AGENCY_ID = '070003' CUSTOMER_ID = '000066' BEGIN_DATE = '20230723' END_DATE = '20230723' BOOKING_FEE = '20.00 ' TOTAL_PRICE = '4708.00 ' CURRENCY_CODE = 'JPY' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Hansmann' CREATEDAT = '20230706080419.0000000 ' LASTCHANGEDBY = 'Legrand' LASTCHANGEDAT = '20230707032700.0000000 '  )
( TRAVEL_ID = '00003695' AGENCY_ID = '070003' CUSTOMER_ID = '000083' BEGIN_DATE = '20240517' END_DATE = '20240517' BOOKING_FEE = '20.00 ' TOTAL_PRICE = '5038.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Hansmann' CREATEDAT = '20230921124855.0000000 ' LASTCHANGEDBY = 'Kramer' LASTCHANGEDAT = '20230922041102.0000000 '  )
( TRAVEL_ID = '00001515' AGENCY_ID = '070003' CUSTOMER_ID = '000072' BEGIN_DATE = '20240518' END_DATE = '20240518' BOOKING_FEE = '10.00 ' TOTAL_PRICE = '2716.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Buchholm' CREATEDAT = '20230921111629.0000000 ' LASTCHANGEDBY = 'Cesari' LASTCHANGEDAT = '20230921003749.0000000 '  )
( TRAVEL_ID = '00004157' AGENCY_ID = '070003' CUSTOMER_ID = '000002' BEGIN_DATE = '20231009' END_DATE = '20231009' BOOKING_FEE = '0.00 ' TOTAL_PRICE = '0.00 ' CURRENCY_CODE = '' DESCRIPTION = '' STATUS = 'N'  'CB9980001351' 
CREATEDAT = '20231010021411.2917910 ' LASTCHANGEDBY = 'CB9980001351' LASTCHANGEDAT = '20231010021411.2917910 '  )
( TRAVEL_ID = '00002416' AGENCY_ID = '070003' CUSTOMER_ID = '000025' BEGIN_DATE = '20240517' END_DATE = '20240517' BOOKING_FEE = '10.00 ' TOTAL_PRICE = '2306.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Simonen' CREATEDAT = '20230921222937.0000000 ' LASTCHANGEDBY = 'Müller' LASTCHANGEDAT = '20230921071842.0000000 '  )
( TRAVEL_ID = '00001878' AGENCY_ID = '070003' CUSTOMER_ID = '000043' BEGIN_DATE = '20230718' END_DATE = '20230718' BOOKING_FEE = '20.00 ' TOTAL_PRICE = '5421.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Dumbach' CREATEDAT = '20230703175715.0000000 ' LASTCHANGEDBY = 'Sudhoff' LASTCHANGEDAT = '20230704051934.0000000 '  )
( TRAVEL_ID = '00002735' AGENCY_ID = '070004' CUSTOMER_ID = '000024' BEGIN_DATE = '20240518' END_DATE = '20240518' BOOKING_FEE = '20.00 ' TOTAL_PRICE = '6349.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Picard' CREATEDAT = '20230921110858.0000000 ' LASTCHANGEDBY = 'Cesari' LASTCHANGEDAT = '20230922200733.0000000 '  )
( TRAVEL_ID = '00001742' AGENCY_ID = '070004' CUSTOMER_ID = '000073' BEGIN_DATE = '20230718' END_DATE = '20230718' BOOKING_FEE = '20.00 ' TOTAL_PRICE = '3136.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Fischer' CREATEDAT = '20230620200646.0000000 ' LASTCHANGEDBY = 'Picard' LASTCHANGEDAT = '20230621232231.0000000 '  )
( TRAVEL_ID = '00000614' AGENCY_ID = '070004' CUSTOMER_ID = '000038' BEGIN_DATE = '20240516' END_DATE = '20240516' BOOKING_FEE = '10.00 ' TOTAL_PRICE = '8415.00 ' CURRENCY_CODE = 'SGD' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Matthaeus' CREATEDAT = '20230921060719.0000000 ' LASTCHANGEDBY = 'Mechler' LASTCHANGEDAT = '20230922112024.0000000 '  )
( TRAVEL_ID = '00004406' AGENCY_ID = '070004' CUSTOMER_ID = '000004' BEGIN_DATE = '20231020' END_DATE = '20231027' BOOKING_FEE = '900.00 ' TOTAL_PRICE = '2232682.00 ' CURRENCY_CODE = 'INR' DESCRIPTION = 'plnned for vacation' STATUS = 'N' 
 'CB9980006452' CREATEDAT = '20231020033914.1551430 ' LASTCHANGEDBY = 'CB9980006452' LASTCHANGEDAT = '20231020055058.4891830 '  )
( TRAVEL_ID = '00004144' AGENCY_ID = '070004' CUSTOMER_ID = '000005' BEGIN_DATE = '20231030' END_DATE = '20231130' BOOKING_FEE = '1000.00 ' TOTAL_PRICE = '1000.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'SK My Test Travel' STATUS = 'N' 
 'CB9980005690' CREATEDAT = '20231008103239.9712360 ' LASTCHANGEDBY = 'CB9980005690' LASTCHANGEDAT = '20231008103239.9712360 '  )
( TRAVEL_ID = '00004388' AGENCY_ID = '070004' CUSTOMER_ID = '000005' BEGIN_DATE = '20231019' END_DATE = '20231026' BOOKING_FEE = '0.00 ' TOTAL_PRICE = '0.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = 'My First Travel to Holululu' STATUS = 'N' 
 'CB9980007938' CREATEDAT = '20231019083043.0101930 ' LASTCHANGEDBY = 'CB9980007938' LASTCHANGEDAT = '20231019083043.0101930 '  )
( TRAVEL_ID = '00000764' AGENCY_ID = '070004' CUSTOMER_ID = '000038' BEGIN_DATE = '20240515' END_DATE = '20240515' BOOKING_FEE = '10.00 ' TOTAL_PRICE = '243.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Ryan' CREATEDAT = '20230921222240.0000000 ' LASTCHANGEDBY = 'Rahn' LASTCHANGEDAT = '20230922182822.0000000 '  )
( TRAVEL_ID = '00002773' AGENCY_ID = '070004' CUSTOMER_ID = '000006' BEGIN_DATE = '20240518' END_DATE = '20240518' BOOKING_FEE = '30.00 ' TOTAL_PRICE = '13569.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Meier' CREATEDAT = '20230921025441.0000000 ' LASTCHANGEDBY = 'Martin' LASTCHANGEDAT = '20230922213756.0000000 '  )
( TRAVEL_ID = '00003819' AGENCY_ID = '070004' CUSTOMER_ID = '000023' BEGIN_DATE = '20240517' END_DATE = '20240517' BOOKING_FEE = '20.00 ' TOTAL_PRICE = '10066.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Delon' CREATEDAT = '20230921061722.0000000 ' LASTCHANGEDBY = 'Goelke' LASTCHANGEDAT = '20230922104322.0000000 '  )
( TRAVEL_ID = '00000237' AGENCY_ID = '070004' CUSTOMER_ID = '000014' BEGIN_DATE = '20230723' END_DATE = '20230723' BOOKING_FEE = '20.00 ' TOTAL_PRICE = '542.00 ' CURRENCY_CODE = 'USD' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Buehler' CREATEDAT = '20230624151735.0000000 ' LASTCHANGEDBY = 'Domenech' LASTCHANGEDAT = '20230625071153.0000000 '  )
( TRAVEL_ID = '00002777' AGENCY_ID = '070004' CUSTOMER_ID = '000083' BEGIN_DATE = '20240518' END_DATE = '20240518' BOOKING_FEE = '10.00 ' TOTAL_PRICE = '4746.00 ' CURRENCY_CODE = 'EUR' DESCRIPTION = 'Vacation' STATUS = 'N' 
 'Sisko' CREATEDAT = '20230921112827.0000000 ' LASTCHANGEDBY = 'Trensch' LASTCHANGEDAT = '20230922214007.0000000 '  )
 )
```
