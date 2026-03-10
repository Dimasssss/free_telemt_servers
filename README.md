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

# Server Metrics 2026-03-10 20:12:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 20771.5 (5h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78442
telemt_connections_bad_total 2836
telemt_handshake_timeouts_total 2077
telemt_upstream_connect_attempt_total 69944
telemt_upstream_connect_success_total 69931
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 69944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 69929
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 2315911370 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 55300265234 (51.50 GB)
telemt_user_msgs_from_client{user="hello"} 2111129
telemt_user_msgs_to_client{user="hello"} 3830410
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 20770.4 (5h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30416
telemt_connections_bad_total 239
telemt_handshake_timeouts_total 472
telemt_upstream_connect_attempt_total 27883
telemt_upstream_connect_success_total 27875
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 27883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4143
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27873
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 1361484622 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 23907667007 (22.27 GB)
telemt_user_msgs_from_client{user="hello"} 1091278
telemt_user_msgs_to_client{user="hello"} 7036031
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 20770.3 (5h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48630
telemt_connections_bad_total 278
telemt_handshake_timeouts_total 3668
telemt_upstream_connect_attempt_total 41880
telemt_upstream_connect_success_total 41879
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 41880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3939
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41875
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 650382667 (620.25 MB)
telemt_user_octets_to_client{user="hello"} 38676440080 (36.02 GB)
telemt_user_msgs_from_client{user="hello"} 892459
telemt_user_msgs_to_client{user="hello"} 5835834
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 20769.1 (5h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43247
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 304
telemt_upstream_connect_attempt_total 41435
telemt_upstream_connect_success_total 41312
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 41435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4772
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 128
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41308
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 712151792 (679.16 MB)
telemt_user_octets_to_client{user="hello"} 32032735168 (29.83 GB)
telemt_user_msgs_from_client{user="hello"} 904950
telemt_user_msgs_to_client{user="hello"} 6080216
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 20770.4 (5h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62082
telemt_connections_bad_total 5505
telemt_handshake_timeouts_total 1321
telemt_upstream_connect_attempt_total 52674
telemt_upstream_connect_success_total 52430
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 52674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6385
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 184
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 52428
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 1581380763 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 40616571705 (37.83 GB)
telemt_user_msgs_from_client{user="hello"} 1461699
telemt_user_msgs_to_client{user="hello"} 5652968
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 18
```