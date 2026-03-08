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

# Server Metrics 2026-03-08 19:27:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 44328.9 (12h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101745
telemt_connections_bad_total 5057
telemt_handshake_timeouts_total 1260
telemt_upstream_connect_attempt_total 92139
telemt_upstream_connect_success_total 92107
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 92139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5320
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 92101
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 2238257371 (2.08 GB)
telemt_user_octets_to_client{user="hello"} 57508023700 (53.56 GB)
telemt_user_msgs_from_client{user="hello"} 2240953
telemt_user_msgs_to_client{user="hello"} 3143449
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 44327.9 (12h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23550
telemt_connections_bad_total 230
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 22787
telemt_upstream_connect_success_total 22782
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 22787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1482
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 128
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22778
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 749339344 (714.63 MB)
telemt_user_octets_to_client{user="hello"} 20996365094 (19.55 GB)
telemt_user_msgs_from_client{user="hello"} 886574
telemt_user_msgs_to_client{user="hello"} 5715152
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 44327.7 (12h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14062
telemt_connections_bad_total 176
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 12726
telemt_upstream_connect_success_total 12650
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 12726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 926
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12646
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 264167847 (251.93 MB)
telemt_user_octets_to_client{user="hello"} 4498335153 (4.19 GB)
telemt_user_msgs_from_client{user="hello"} 222120
telemt_user_msgs_to_client{user="hello"} 803891
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 44327.4 (12h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18091
telemt_connections_bad_total 182
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 17328
telemt_upstream_connect_success_total 17291
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 17328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1285
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17287
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 1041110314 (992.88 MB)
telemt_user_octets_to_client{user="hello"} 6228994370 (5.80 GB)
telemt_user_msgs_from_client{user="hello"} 547627
telemt_user_msgs_to_client{user="hello"} 1396697
telemt_user_unique_ips_current{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 44327.7 (12h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26222
telemt_connections_bad_total 8376
telemt_handshake_timeouts_total 236
telemt_upstream_connect_attempt_total 17199
telemt_upstream_connect_success_total 17192
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 17199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2947
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17186
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 320930989 (306.06 MB)
telemt_user_octets_to_client{user="hello"} 13506864297 (12.58 GB)
telemt_user_msgs_from_client{user="hello"} 426435
telemt_user_msgs_to_client{user="hello"} 1770022
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```