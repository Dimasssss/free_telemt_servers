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

# Server Metrics 2026-03-10 22:32:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 29158.8 (8h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94967
telemt_connections_bad_total 3292
telemt_handshake_timeouts_total 2199
telemt_upstream_connect_attempt_total 85255
telemt_upstream_connect_success_total 85223
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 85255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7471
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 85219
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 2555103615 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 68493149181 (63.79 GB)
telemt_user_msgs_from_client{user="hello"} 2473332
telemt_user_msgs_to_client{user="hello"} 4518884
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 29158.1 (8h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36288
telemt_connections_bad_total 323
telemt_handshake_timeouts_total 733
telemt_upstream_connect_attempt_total 33065
telemt_upstream_connect_success_total 33056
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 33065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4853
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33052
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 1678842119 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 34562309103 (32.19 GB)
telemt_user_msgs_from_client{user="hello"} 1360547
telemt_user_msgs_to_client{user="hello"} 8686812
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 29158.0 (8h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58780
telemt_connections_bad_total 446
telemt_handshake_timeouts_total 4009
telemt_upstream_connect_attempt_total 50959
telemt_upstream_connect_success_total 50957
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 50959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4942
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50953
telemt_user_connections_current{user="hello"} 46
telemt_user_octets_from_client{user="hello"} 771326717 (735.59 MB)
telemt_user_octets_to_client{user="hello"} 47831840264 (44.55 GB)
telemt_user_msgs_from_client{user="hello"} 1078173
telemt_user_msgs_to_client{user="hello"} 7170513
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 29156.9 (8h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53934
telemt_connections_bad_total 87
telemt_handshake_timeouts_total 329
telemt_upstream_connect_attempt_total 51781
telemt_upstream_connect_success_total 51637
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 51781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6129
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51633
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 822276853 (784.18 MB)
telemt_user_octets_to_client{user="hello"} 37162906389 (34.61 GB)
telemt_user_msgs_from_client{user="hello"} 1114613
telemt_user_msgs_to_client{user="hello"} 7101829
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 29158.2 (8h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78764
telemt_connections_bad_total 7231
telemt_handshake_timeouts_total 1456
telemt_upstream_connect_attempt_total 66998
telemt_upstream_connect_success_total 66750
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 66998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8874
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 66746
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 2047878693 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 52654462096 (49.04 GB)
telemt_user_msgs_from_client{user="hello"} 1890414
telemt_user_msgs_to_client{user="hello"} 7731021
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 8127.6 (2h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```