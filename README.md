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

# Server Metrics 2026-03-10 22:11:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 27934.5 (7h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93377
telemt_connections_bad_total 3290
telemt_handshake_timeouts_total 2183
telemt_upstream_connect_attempt_total 83755
telemt_upstream_connect_success_total 83723
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 83755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 83719
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 2533971790 (2.36 GB)
telemt_user_octets_to_client{user="hello"} 66453228007 (61.89 GB)
telemt_user_msgs_from_client{user="hello"} 2424757
telemt_user_msgs_to_client{user="hello"} 4372262
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 27934.1 (7h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35482
telemt_connections_bad_total 319
telemt_handshake_timeouts_total 710
telemt_upstream_connect_attempt_total 32316
telemt_upstream_connect_success_total 32307
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 32316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4739
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32303
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 1665665820 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 33546239924 (31.24 GB)
telemt_user_msgs_from_client{user="hello"} 1337395
telemt_user_msgs_to_client{user="hello"} 8485850
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 27933.8 (7h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57889
telemt_connections_bad_total 430
telemt_handshake_timeouts_total 3976
telemt_upstream_connect_attempt_total 50188
telemt_upstream_connect_success_total 50186
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 50188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4827
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50182
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 767457432 (731.90 MB)
telemt_user_octets_to_client{user="hello"} 46802910414 (43.59 GB)
telemt_user_msgs_from_client{user="hello"} 1067969
telemt_user_msgs_to_client{user="hello"} 7042730
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 27932.6 (7h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53031
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 327
telemt_upstream_connect_attempt_total 50922
telemt_upstream_connect_success_total 50780
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 50922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5996
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50776
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 818729862 (780.80 MB)
telemt_user_octets_to_client{user="hello"} 37068611531 (34.52 GB)
telemt_user_msgs_from_client{user="hello"} 1105661
telemt_user_msgs_to_client{user="hello"} 7071239
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 27934.0 (7h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76665
telemt_connections_bad_total 6974
telemt_handshake_timeouts_total 1409
telemt_upstream_connect_attempt_total 65248
telemt_upstream_connect_success_total 65004
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 65248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8536
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 65000
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 2023356535 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 50248732504 (46.80 GB)
telemt_user_msgs_from_client{user="hello"} 1845573
telemt_user_msgs_to_client{user="hello"} 7325978
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 6903.4 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```