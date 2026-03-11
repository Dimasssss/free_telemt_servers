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

# Server Metrics 2026-03-11 18:59:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 7121.1 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28679
telemt_connections_bad_total 1664
telemt_handshake_timeouts_total 128
telemt_upstream_connect_attempt_total 25761
telemt_upstream_connect_success_total 25755
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 25761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2445
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25753
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 672564468 (641.41 MB)
telemt_user_octets_to_client{user="hello"} 16092698858 (14.99 GB)
telemt_user_msgs_from_client{user="hello"} 642131
telemt_user_msgs_to_client{user="hello"} 1225366
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 7109.5 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13569
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 235
telemt_upstream_connect_attempt_total 12245
telemt_upstream_connect_success_total 12244
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1375
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 264
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12242
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 185743814 (177.14 MB)
telemt_user_octets_to_client{user="hello"} 7922716039 (7.38 GB)
telemt_user_msgs_from_client{user="hello"} 290250
telemt_user_msgs_to_client{user="hello"} 2999664
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 7129.3 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15750
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 113
telemt_upstream_connect_attempt_total 14743
telemt_upstream_connect_success_total 14741
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 14743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13459
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1265
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14739
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 153783910 (146.66 MB)
telemt_user_octets_to_client{user="hello"} 6155048135 (5.73 GB)
telemt_user_msgs_from_client{user="hello"} 303662
telemt_user_msgs_to_client{user="hello"} 1745293
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 7125.0 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15875
telemt_connections_bad_total 994
telemt_handshake_timeouts_total 251
telemt_upstream_connect_attempt_total 14029
telemt_upstream_connect_success_total 13991
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 14029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1313
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13989
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 502918532 (479.62 MB)
telemt_user_octets_to_client{user="hello"} 9084865155 (8.46 GB)
telemt_user_msgs_from_client{user="hello"} 372240
telemt_user_msgs_to_client{user="hello"} 2160543
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 7132.9 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17709
telemt_connections_bad_total 1405
telemt_handshake_timeouts_total 132
telemt_upstream_connect_attempt_total 15488
telemt_upstream_connect_success_total 15486
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2041
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15484
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 278020799 (265.14 MB)
telemt_user_octets_to_client{user="hello"} 4151196394 (3.87 GB)
telemt_user_msgs_from_client{user="hello"} 318258
telemt_user_msgs_to_client{user="hello"} 1245440
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 81739.4 (22h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 515
telemt_connections_bad_total 489
telemt_handshake_timeouts_total 16
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