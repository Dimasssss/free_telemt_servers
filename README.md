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

# Server Metrics 2026-03-04 23:58:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 45123.3 (12h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67399
telemt_connections_bad_total 128
telemt_handshake_timeouts_total 1557
telemt_upstream_connect_attempt_total 60814
telemt_upstream_connect_success_total 60799
telemt_upstream_connect_attempts_per_request{bucket="1"} 60784
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3819
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60793
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 2336922976 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 47013878915 (43.79 GB)
telemt_user_msgs_from_client{user="hello"} 1993544
telemt_user_msgs_to_client{user="hello"} 7496067
telemt_user_unique_ips_current{user="hello"} 13
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 45126.4 (12h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12798
telemt_connections_bad_total 251
telemt_handshake_timeouts_total 39
telemt_upstream_connect_attempt_total 11409
telemt_upstream_connect_success_total 11407
telemt_upstream_connect_attempts_per_request{bucket="1"} 11405
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10494
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11403
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 1056289690 (1007.36 MB)
telemt_user_octets_to_client{user="hello"} 11090945538 (10.33 GB)
telemt_user_msgs_from_client{user="hello"} 649588
telemt_user_msgs_to_client{user="hello"} 3736465
telemt_user_unique_ips_current{user="hello"} 3
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 45124.5 (12h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11215
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 7324
telemt_upstream_connect_success_total 7324
telemt_upstream_connect_attempts_per_request{bucket="1"} 7324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7318
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 308110181 (293.84 MB)
telemt_user_octets_to_client{user="hello"} 5254013650 (4.89 GB)
telemt_user_msgs_from_client{user="hello"} 268686
telemt_user_msgs_to_client{user="hello"} 1133788
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 45122.3 (12h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15127
telemt_connections_bad_total 686
telemt_handshake_timeouts_total 75
telemt_upstream_connect_attempt_total 13196
telemt_upstream_connect_success_total 13191
telemt_upstream_connect_attempts_per_request{bucket="1"} 13186
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1076
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13185
telemt_user_octets_from_client{user="hello"} 392238539 (374.07 MB)
telemt_user_octets_to_client{user="hello"} 5583147351 (5.20 GB)
telemt_user_msgs_from_client{user="hello"} 302770
telemt_user_msgs_to_client{user="hello"} 1391814
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 45124.1 (12h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17679
telemt_connections_bad_total 8110
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 9212
telemt_upstream_connect_success_total 9208
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9206
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1395
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9202
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 512845332 (489.09 MB)
telemt_user_octets_to_client{user="hello"} 21170684527 (19.72 GB)
telemt_user_msgs_from_client{user="hello"} 542631
telemt_user_msgs_to_client{user="hello"} 4005003
```