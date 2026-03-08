# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

-----

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-08 18:36:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 41247.8 (11h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96246
telemt_connections_bad_total 5047
telemt_handshake_timeouts_total 1251
telemt_upstream_connect_attempt_total 86776
telemt_upstream_connect_success_total 86747
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 86776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5025
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 86741
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 2127173377 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 53912362813 (50.21 GB)
telemt_user_msgs_from_client{user="hello"} 2102119
telemt_user_msgs_to_client{user="hello"} 2960235
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 41247.4 (11h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21705
telemt_connections_bad_total 188
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 21011
telemt_upstream_connect_success_total 21006
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 21011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1377
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21002
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 730530293 (696.69 MB)
telemt_user_octets_to_client{user="hello"} 19750112326 (18.39 GB)
telemt_user_msgs_from_client{user="hello"} 844114
telemt_user_msgs_to_client{user="hello"} 5404935
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 41246.9 (11h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13382
telemt_connections_bad_total 171
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 12059
telemt_upstream_connect_success_total 11983
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 12059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 857
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11979
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 240857960 (229.70 MB)
telemt_user_octets_to_client{user="hello"} 4212795320 (3.92 GB)
telemt_user_msgs_from_client{user="hello"} 205448
telemt_user_msgs_to_client{user="hello"} 752149
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 41246.7 (11h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17120
telemt_connections_bad_total 180
telemt_handshake_timeouts_total 58
telemt_upstream_connect_attempt_total 16371
telemt_upstream_connect_success_total 16337
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 16371
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1225
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16333
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 1037229337 (989.18 MB)
telemt_user_octets_to_client{user="hello"} 5853121562 (5.45 GB)
telemt_user_msgs_from_client{user="hello"} 537647
telemt_user_msgs_to_client{user="hello"} 1327725
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 41247.0 (11h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24300
telemt_connections_bad_total 7817
telemt_handshake_timeouts_total 229
telemt_upstream_connect_attempt_total 15888
telemt_upstream_connect_success_total 15882
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 15888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15878
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 299614334 (285.73 MB)
telemt_user_octets_to_client{user="hello"} 12132884387 (11.30 GB)
telemt_user_msgs_from_client{user="hello"} 387114
telemt_user_msgs_to_client{user="hello"} 1597552
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```