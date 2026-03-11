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

# Server Metrics 2026-03-11 12:08:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 78128.7 (21h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 242741
telemt_connections_bad_total 3634
telemt_handshake_timeouts_total 4565
telemt_upstream_connect_attempt_total 223652
telemt_upstream_connect_success_total 223581
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 223652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 204631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18893
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 223573
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 4586321995 (4.27 GB)
telemt_user_octets_to_client{user="hello"} 123502331600 (115.02 GB)
telemt_user_msgs_from_client{user="hello"} 5154223
telemt_user_msgs_to_client{user="hello"} 9524155
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 78127.6 (21h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94904
telemt_connections_bad_total 895
telemt_handshake_timeouts_total 3306
telemt_upstream_connect_attempt_total 86453
telemt_upstream_connect_success_total 86437
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 86453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 273
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 86429
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 5158909990 (4.80 GB)
telemt_user_octets_to_client{user="hello"} 58618552591 (54.59 GB)
telemt_user_msgs_from_client{user="hello"} 3397035
telemt_user_msgs_to_client{user="hello"} 15803083
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 78127.2 (21h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132543
telemt_connections_bad_total 1098
telemt_handshake_timeouts_total 6693
telemt_upstream_connect_attempt_total 117285
telemt_upstream_connect_success_total 117271
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 117285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 104027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13149
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 117263
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 12414955876 (11.56 GB)
telemt_user_octets_to_client{user="hello"} 88535358345 (82.45 GB)
telemt_user_msgs_from_client{user="hello"} 6109343
telemt_user_msgs_to_client{user="hello"} 17711999
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 78126.3 (21h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144042
telemt_connections_bad_total 339
telemt_handshake_timeouts_total 1855
telemt_upstream_connect_attempt_total 135988
telemt_upstream_connect_success_total 135671
telemt_upstream_connect_fail_total 316
telemt_upstream_connect_attempts_per_request{bucket="1"} 135987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17515
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 71
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 316
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 135663
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 6017687605 (5.60 GB)
telemt_user_octets_to_client{user="hello"} 101326115509 (94.37 GB)
telemt_user_msgs_from_client{user="hello"} 4117676
telemt_user_msgs_to_client{user="hello"} 29120432
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 78127.5 (21h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218973
telemt_connections_bad_total 17074
telemt_handshake_timeouts_total 3834
telemt_upstream_connect_attempt_total 177128
telemt_upstream_connect_success_total 176724
telemt_upstream_connect_fail_total 404
telemt_upstream_connect_attempts_per_request{bucket="1"} 177128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 152443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23962
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 319
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 404
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 176716
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 4651056344 (4.33 GB)
telemt_user_octets_to_client{user="hello"} 147432017038 (137.31 GB)
telemt_user_msgs_from_client{user="hello"} 4300479
telemt_user_msgs_to_client{user="hello"} 20160463
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 57096.9 (15h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 428
telemt_connections_bad_total 406
telemt_handshake_timeouts_total 10
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