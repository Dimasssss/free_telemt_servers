# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

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

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-11 19:50:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 10185.7 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38687
telemt_connections_bad_total 2207
telemt_handshake_timeouts_total 185
telemt_upstream_connect_attempt_total 34823
telemt_upstream_connect_success_total 34814
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 34823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3247
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34812
telemt_user_connections_current{user="hello"} 280
telemt_user_octets_from_client{user="hello"} 844312877 (805.20 MB)
telemt_user_octets_to_client{user="hello"} 19902698881 (18.54 GB)
telemt_user_msgs_from_client{user="hello"} 862536
telemt_user_msgs_to_client{user="hello"} 1660463
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 10173.9 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18549
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 250
telemt_upstream_connect_attempt_total 17052
telemt_upstream_connect_success_total 17013
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 17052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 322
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17011
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 213293204 (203.41 MB)
telemt_user_octets_to_client{user="hello"} 8737833663 (8.14 GB)
telemt_user_msgs_from_client{user="hello"} 355680
telemt_user_msgs_to_client{user="hello"} 3375419
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 10193.8 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21434
telemt_connections_bad_total 25
telemt_handshake_timeouts_total 180
telemt_upstream_connect_attempt_total 20010
telemt_upstream_connect_success_total 20008
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 20010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20006
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 202687180 (193.30 MB)
telemt_user_octets_to_client{user="hello"} 8956217774 (8.34 GB)
telemt_user_msgs_from_client{user="hello"} 403909
telemt_user_msgs_to_client{user="hello"} 2222399
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 10189.0 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23469
telemt_connections_bad_total 1791
telemt_handshake_timeouts_total 376
telemt_upstream_connect_attempt_total 20336
telemt_upstream_connect_success_total 20275
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 20336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1850
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20273
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 612954161 (584.56 MB)
telemt_user_octets_to_client{user="hello"} 11196338226 (10.43 GB)
telemt_user_msgs_from_client{user="hello"} 497066
telemt_user_msgs_to_client{user="hello"} 3064345
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 10197.3 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25382
telemt_connections_bad_total 1954
telemt_handshake_timeouts_total 161
telemt_upstream_connect_attempt_total 22437
telemt_upstream_connect_success_total 22436
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 22437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2746
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22434
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 417487792 (398.15 MB)
telemt_user_octets_to_client{user="hello"} 8052386406 (7.50 GB)
telemt_user_msgs_from_client{user="hello"} 496970
telemt_user_msgs_to_client{user="hello"} 2805923
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 84803.7 (23h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 575
telemt_connections_bad_total 492
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 65
telemt_upstream_connect_success_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 205929 (201.10 KB)
telemt_user_octets_to_client{user="hello"} 1308904 (1.25 MB)
telemt_user_msgs_from_client{user="hello"} 263
telemt_user_msgs_to_client{user="hello"} 401
```