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

# Server Metrics 2026-03-12 00:24:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 9554.9 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18371
telemt_connections_bad_total 1803
telemt_handshake_timeouts_total 124
telemt_upstream_connect_attempt_total 15934
telemt_upstream_connect_success_total 15929
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 15934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15927
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 191958308 (183.07 MB)
telemt_user_octets_to_client{user="hello"} 6446927789 (6.00 GB)
telemt_user_msgs_from_client{user="hello"} 330339
telemt_user_msgs_to_client{user="hello"} 860251
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 9543.0 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7334
telemt_connections_bad_total 37
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 7027
telemt_upstream_connect_success_total 7027
telemt_upstream_connect_attempts_per_request{bucket="1"} 7027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 903
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7025
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 41171763 (39.26 MB)
telemt_user_octets_to_client{user="hello"} 1626636825 (1.51 GB)
telemt_user_msgs_from_client{user="hello"} 101171
telemt_user_msgs_to_client{user="hello"} 622731
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 9516.5 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12418
telemt_connections_bad_total 273
telemt_handshake_timeouts_total 779
telemt_upstream_connect_attempt_total 9934
telemt_upstream_connect_success_total 9934
telemt_upstream_connect_attempts_per_request{bucket="1"} 9934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1410
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9932
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 63270422 (60.34 MB)
telemt_user_octets_to_client{user="hello"} 5997839983 (5.59 GB)
telemt_user_msgs_from_client{user="hello"} 198612
telemt_user_msgs_to_client{user="hello"} 1388857
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 9541.9 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11506
telemt_connections_bad_total 2211
telemt_handshake_timeouts_total 250
telemt_upstream_connect_attempt_total 8691
telemt_upstream_connect_success_total 8680
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 8691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1048
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8678
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 64710887 (61.71 MB)
telemt_user_octets_to_client{user="hello"} 3869097438 (3.60 GB)
telemt_user_msgs_from_client{user="hello"} 135226
telemt_user_msgs_to_client{user="hello"} 1391514
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 9542.7 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9356
telemt_connections_bad_total 78
telemt_handshake_timeouts_total 109
telemt_upstream_connect_attempt_total 8284
telemt_upstream_connect_success_total 8284
telemt_upstream_connect_attempts_per_request{bucket="1"} 8284
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1358
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8282
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 118826813 (113.32 MB)
telemt_user_octets_to_client{user="hello"} 16742936470 (15.59 GB)
telemt_user_msgs_from_client{user="hello"} 246993
telemt_user_msgs_to_client{user="hello"} 1483215
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 8
```