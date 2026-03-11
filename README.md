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

# Server Metrics 2026-03-11 10:10:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 71061.1 (19h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210075
telemt_connections_bad_total 3614
telemt_handshake_timeouts_total 4385
telemt_upstream_connect_attempt_total 192504
telemt_upstream_connect_success_total 192443
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 192504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 175935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 192435
telemt_user_connections_current{user="hello"} 367
telemt_user_octets_from_client{user="hello"} 4189823188 (3.90 GB)
telemt_user_octets_to_client{user="hello"} 113064808430 (105.30 GB)
telemt_user_msgs_from_client{user="hello"} 4556577
telemt_user_msgs_to_client{user="hello"} 8475220
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 71060.1 (19h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82202
telemt_connections_bad_total 782
telemt_handshake_timeouts_total 3153
telemt_upstream_connect_attempt_total 74399
telemt_upstream_connect_success_total 74383
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 74399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10023
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 255
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 74375
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 5010502467 (4.67 GB)
telemt_user_octets_to_client{user="hello"} 55961573318 (52.12 GB)
telemt_user_msgs_from_client{user="hello"} 3203001
telemt_user_msgs_to_client{user="hello"} 14476846
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 71060.5 (19h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113792
telemt_connections_bad_total 1076
telemt_handshake_timeouts_total 5266
telemt_upstream_connect_attempt_total 100996
telemt_upstream_connect_success_total 100992
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 100996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 89557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11371
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 100984
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 12026989278 (11.20 GB)
telemt_user_octets_to_client{user="hello"} 83124034372 (77.42 GB)
telemt_user_msgs_from_client{user="hello"} 5727626
telemt_user_msgs_to_client{user="hello"} 16132221
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 71058.7 (19h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124981
telemt_connections_bad_total 255
telemt_handshake_timeouts_total 1218
telemt_upstream_connect_attempt_total 118470
telemt_upstream_connect_success_total 118199
telemt_upstream_connect_fail_total 271
telemt_upstream_connect_attempts_per_request{bucket="1"} 118470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 102125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15693
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 321
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 271
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 118191
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 5533993514 (5.15 GB)
telemt_user_octets_to_client{user="hello"} 82974882061 (77.28 GB)
telemt_user_msgs_from_client{user="hello"} 3656704
telemt_user_msgs_to_client{user="hello"} 21556318
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 71060.1 (19h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196486
telemt_connections_bad_total 15472
telemt_handshake_timeouts_total 3371
telemt_upstream_connect_attempt_total 157318
telemt_upstream_connect_success_total 156915
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 157317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 134653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21970
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 292
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 156907
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 3166708367 (2.95 GB)
telemt_user_octets_to_client{user="hello"} 137531384140 (128.09 GB)
telemt_user_msgs_from_client{user="hello"} 3521985
telemt_user_msgs_to_client{user="hello"} 18110618
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 50029.5 (13h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422
telemt_connections_bad_total 400
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 17
telemt_upstream_connect_success_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```