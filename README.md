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

# Server Metrics 2026-03-10 19:10:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 17090.6 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66774
telemt_connections_bad_total 2138
telemt_handshake_timeouts_total 1927
telemt_upstream_connect_attempt_total 59475
telemt_upstream_connect_success_total 59460
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 59472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 59458
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 1926979178 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 43879353363 (40.87 GB)
telemt_user_msgs_from_client{user="hello"} 1750207
telemt_user_msgs_to_client{user="hello"} 3293603
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 17090.0 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25285
telemt_connections_bad_total 210
telemt_handshake_timeouts_total 429
telemt_upstream_connect_attempt_total 23103
telemt_upstream_connect_success_total 23096
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 23103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3306
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23094
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 775340372 (739.42 MB)
telemt_user_octets_to_client{user="hello"} 14192379853 (13.22 GB)
telemt_user_msgs_from_client{user="hello"} 733353
telemt_user_msgs_to_client{user="hello"} 4425293
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 17089.7 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38963
telemt_connections_bad_total 125
telemt_handshake_timeouts_total 3428
telemt_upstream_connect_attempt_total 33031
telemt_upstream_connect_success_total 33031
telemt_upstream_connect_attempts_per_request{bucket="1"} 33031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33029
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 528105618 (503.64 MB)
telemt_user_octets_to_client{user="hello"} 33279401231 (30.99 GB)
telemt_user_msgs_from_client{user="hello"} 727378
telemt_user_msgs_to_client{user="hello"} 4887127
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 17088.6 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36505
telemt_connections_bad_total 61
telemt_handshake_timeouts_total 270
telemt_upstream_connect_attempt_total 34944
telemt_upstream_connect_success_total 34843
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 34944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4106
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34841
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 591845892 (564.43 MB)
telemt_user_octets_to_client{user="hello"} 28499428774 (26.54 GB)
telemt_user_msgs_from_client{user="hello"} 739149
telemt_user_msgs_to_client{user="hello"} 5164130
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 17089.8 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53538
telemt_connections_bad_total 4815
telemt_handshake_timeouts_total 1197
telemt_upstream_connect_attempt_total 45296
telemt_upstream_connect_success_total 45053
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 45295
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45051
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 1463366987 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 31898737192 (29.71 GB)
telemt_user_msgs_from_client{user="hello"} 1267066
telemt_user_msgs_to_client{user="hello"} 4811859
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 26
```