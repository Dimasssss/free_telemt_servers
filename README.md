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

# Server Metrics 2026-03-11 17:52:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 3120.9 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13037
telemt_connections_bad_total 728
telemt_handshake_timeouts_total 66
telemt_upstream_connect_attempt_total 11561
telemt_upstream_connect_success_total 11558
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 11561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11556
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 400358210 (381.81 MB)
telemt_user_octets_to_client{user="hello"} 8001662981 (7.45 GB)
telemt_user_msgs_from_client{user="hello"} 321597
telemt_user_msgs_to_client{user="hello"} 585491
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 3109.2 (0h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6813
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 125
telemt_upstream_connect_attempt_total 6188
telemt_upstream_connect_success_total 6187
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6185
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 77168566 (73.59 MB)
telemt_user_octets_to_client{user="hello"} 4082930952 (3.80 GB)
telemt_user_msgs_from_client{user="hello"} 137898
telemt_user_msgs_to_client{user="hello"} 1609639
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 3128.7 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7643
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 85
telemt_upstream_connect_attempt_total 7083
telemt_upstream_connect_success_total 7082
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 720
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7080
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 60119044 (57.33 MB)
telemt_user_octets_to_client{user="hello"} 3235880012 (3.01 GB)
telemt_user_msgs_from_client{user="hello"} 144736
telemt_user_msgs_to_client{user="hello"} 927945
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 3124.5 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6902
telemt_connections_bad_total 46
telemt_handshake_timeouts_total 178
telemt_upstream_connect_attempt_total 6444
telemt_upstream_connect_success_total 6430
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 6444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 702
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6428
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 374625436 (357.27 MB)
telemt_user_octets_to_client{user="hello"} 2960987202 (2.76 GB)
telemt_user_msgs_from_client{user="hello"} 217137
telemt_user_msgs_to_client{user="hello"} 710077
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 3132.5 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8010
telemt_connections_bad_total 663
telemt_handshake_timeouts_total 63
telemt_upstream_connect_attempt_total 7078
telemt_upstream_connect_success_total 7078
telemt_upstream_connect_attempts_per_request{bucket="1"} 7078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 970
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7076
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 44693657 (42.62 MB)
telemt_user_octets_to_client{user="hello"} 1024573000 (977.11 MB)
telemt_user_msgs_from_client{user="hello"} 98524
telemt_user_msgs_to_client{user="hello"} 338427
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 77739.0 (21h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 495
telemt_connections_bad_total 471
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 19
telemt_upstream_connect_success_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```