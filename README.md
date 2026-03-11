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

# Server Metrics 2026-03-11 10:56:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 73825.6 (20h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221921
telemt_connections_bad_total 3619
telemt_handshake_timeouts_total 4432
telemt_upstream_connect_attempt_total 203854
telemt_upstream_connect_success_total 203790
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 203854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 186394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 203782
telemt_user_connections_current{user="hello"} 357
telemt_user_octets_from_client{user="hello"} 4357386544 (4.06 GB)
telemt_user_octets_to_client{user="hello"} 117499051138 (109.43 GB)
telemt_user_msgs_from_client{user="hello"} 4804885
telemt_user_msgs_to_client{user="hello"} 8906337
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 73825.0 (20h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87024
telemt_connections_bad_total 801
telemt_handshake_timeouts_total 3200
telemt_upstream_connect_attempt_total 79015
telemt_upstream_connect_success_total 78999
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 79015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10569
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 261
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 78991
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 5038339720 (4.69 GB)
telemt_user_octets_to_client{user="hello"} 56789831507 (52.89 GB)
telemt_user_msgs_from_client{user="hello"} 3266047
telemt_user_msgs_to_client{user="hello"} 14891286
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 73825.0 (20h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120340
telemt_connections_bad_total 1078
telemt_handshake_timeouts_total 5338
telemt_upstream_connect_attempt_total 107000
telemt_upstream_connect_success_total 106996
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 107000
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 94906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12024
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 106988
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 12316703866 (11.47 GB)
telemt_user_octets_to_client{user="hello"} 87132453055 (81.15 GB)
telemt_user_msgs_from_client{user="hello"} 5935657
telemt_user_msgs_to_client{user="hello"} 17169037
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 73823.6 (20h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131805
telemt_connections_bad_total 325
telemt_handshake_timeouts_total 1233
telemt_upstream_connect_attempt_total 124981
telemt_upstream_connect_success_total 124686
telemt_upstream_connect_fail_total 294
telemt_upstream_connect_attempts_per_request{bucket="1"} 124980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16330
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 66
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 294
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 124678
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 5668407916 (5.28 GB)
telemt_user_octets_to_client{user="hello"} 91594623865 (85.30 GB)
telemt_user_msgs_from_client{user="hello"} 3826260
telemt_user_msgs_to_client{user="hello"} 24855076
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 73824.9 (20h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204795
telemt_connections_bad_total 16026
telemt_handshake_timeouts_total 3428
telemt_upstream_connect_attempt_total 164768
telemt_upstream_connect_success_total 164366
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 164768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 141309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22752
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 305
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 164358
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 3635367406 (3.39 GB)
telemt_user_octets_to_client{user="hello"} 143118285126 (133.29 GB)
telemt_user_msgs_from_client{user="hello"} 3789460
telemt_user_msgs_to_client{user="hello"} 19104189
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 52794.2 (14h 39m)
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