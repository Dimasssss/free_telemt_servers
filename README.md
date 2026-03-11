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

# Server Metrics 2026-03-11 01:25:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 39549.4 (10h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107961
telemt_connections_bad_total 3352
telemt_handshake_timeouts_total 2521
telemt_upstream_connect_attempt_total 97326
telemt_upstream_connect_success_total 97291
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 97326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 97287
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 2739473577 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 77912963018 (72.56 GB)
telemt_user_msgs_from_client{user="hello"} 2780078
telemt_user_msgs_to_client{user="hello"} 5352632
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 39548.6 (10h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43786
telemt_connections_bad_total 354
telemt_handshake_timeouts_total 1463
telemt_upstream_connect_attempt_total 39464
telemt_upstream_connect_success_total 39455
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 39464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39451
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 2021320048 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 38666511419 (36.01 GB)
telemt_user_msgs_from_client{user="hello"} 1612938
telemt_user_msgs_to_client{user="hello"} 9595643
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 39548.4 (10h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65973
telemt_connections_bad_total 583
telemt_handshake_timeouts_total 4127
telemt_upstream_connect_attempt_total 57533
telemt_upstream_connect_success_total 57531
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 57533
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6056
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 57527
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 8730256277 (8.13 GB)
telemt_user_octets_to_client{user="hello"} 64910674125 (60.45 GB)
telemt_user_msgs_from_client{user="hello"} 4021195
telemt_user_msgs_to_client{user="hello"} 11358689
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 39547.3 (10h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64081
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 531
telemt_upstream_connect_attempt_total 61305
telemt_upstream_connect_success_total 61150
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 61305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7511
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 61146
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 1741769572 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 41813016795 (38.94 GB)
telemt_user_msgs_from_client{user="hello"} 1553022
telemt_user_msgs_to_client{user="hello"} 8155538
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 39548.8 (10h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92525
telemt_connections_bad_total 9281
telemt_handshake_timeouts_total 1493
telemt_upstream_connect_attempt_total 78370
telemt_upstream_connect_success_total 78122
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 78370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10159
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 78118
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 2130423909 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 62265437260 (57.99 GB)
telemt_user_msgs_from_client{user="hello"} 2094950
telemt_user_msgs_to_client{user="hello"} 9068232
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 18518.0 (5h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53
telemt_connections_bad_total 49
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```