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

# Server Metrics 2026-03-04 23:43:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 44199.3 (12h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66912
telemt_connections_bad_total 127
telemt_handshake_timeouts_total 1556
telemt_upstream_connect_attempt_total 60344
telemt_upstream_connect_success_total 60329
telemt_upstream_connect_attempts_per_request{bucket="1"} 60314
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3766
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60323
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 2329830563 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 46904284513 (43.68 GB)
telemt_user_msgs_from_client{user="hello"} 1984585
telemt_user_msgs_to_client{user="hello"} 7474638
telemt_user_unique_ips_current{user="hello"} 12
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 44202.3 (12h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12373
telemt_connections_bad_total 241
telemt_handshake_timeouts_total 39
telemt_upstream_connect_attempt_total 11403
telemt_upstream_connect_success_total 11401
telemt_upstream_connect_attempts_per_request{bucket="1"} 11399
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10488
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11397
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 1056229099 (1007.30 MB)
telemt_user_octets_to_client{user="hello"} 11090730699 (10.33 GB)
telemt_user_msgs_from_client{user="hello"} 649342
telemt_user_msgs_to_client{user="hello"} 3736217
telemt_user_unique_ips_current{user="hello"} 4
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 44200.5 (12h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11193
telemt_connections_bad_total 170
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 7306
telemt_upstream_connect_success_total 7306
telemt_upstream_connect_attempts_per_request{bucket="1"} 7306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7300
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 308061352 (293.79 MB)
telemt_user_octets_to_client{user="hello"} 5253483943 (4.89 GB)
telemt_user_msgs_from_client{user="hello"} 268544
telemt_user_msgs_to_client{user="hello"} 1133470
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 44198.4 (12h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15031
telemt_connections_bad_total 681
telemt_handshake_timeouts_total 75
telemt_upstream_connect_attempt_total 13116
telemt_upstream_connect_success_total 13111
telemt_upstream_connect_attempts_per_request{bucket="1"} 13106
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1070
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13105
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 392028124 (373.87 MB)
telemt_user_octets_to_client{user="hello"} 5576579310 (5.19 GB)
telemt_user_msgs_from_client{user="hello"} 302121
telemt_user_msgs_to_client{user="hello"} 1389386
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 44200.1 (12h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17476
telemt_connections_bad_total 7943
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 9177
telemt_upstream_connect_success_total 9173
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9171
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1391
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9167
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 512791304 (489.04 MB)
telemt_user_octets_to_client{user="hello"} 21169980790 (19.72 GB)
telemt_user_msgs_from_client{user="hello"} 542485
telemt_user_msgs_to_client{user="hello"} 4004653
telemt_user_unique_ips_current{user="hello"} 1
```