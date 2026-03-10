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

# Server Metrics 2026-03-10 20:07:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 20464.6 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77373
telemt_connections_bad_total 2791
telemt_handshake_timeouts_total 2069
telemt_upstream_connect_attempt_total 68955
telemt_upstream_connect_success_total 68942
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 68955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6034
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 68940
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 2296929050 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 53499642989 (49.83 GB)
telemt_user_msgs_from_client{user="hello"} 2083029
telemt_user_msgs_to_client{user="hello"} 3775594
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 20463.7 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30096
telemt_connections_bad_total 239
telemt_handshake_timeouts_total 472
telemt_upstream_connect_attempt_total 27575
telemt_upstream_connect_success_total 27567
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 27575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27565
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 1345630653 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 23051283270 (21.47 GB)
telemt_user_msgs_from_client{user="hello"} 1077531
telemt_user_msgs_to_client{user="hello"} 6883286
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 20463.4 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48046
telemt_connections_bad_total 221
telemt_handshake_timeouts_total 3659
telemt_upstream_connect_attempt_total 41384
telemt_upstream_connect_success_total 41382
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 41383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41378
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 630379085 (601.18 MB)
telemt_user_octets_to_client{user="hello"} 38455988100 (35.81 GB)
telemt_user_msgs_from_client{user="hello"} 878453
telemt_user_msgs_to_client{user="hello"} 5792272
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 20462.4 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42640
telemt_connections_bad_total 65
telemt_handshake_timeouts_total 294
telemt_upstream_connect_attempt_total 40879
telemt_upstream_connect_success_total 40757
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 40879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4709
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 40753
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 697344685 (665.04 MB)
telemt_user_octets_to_client{user="hello"} 31647929519 (29.47 GB)
telemt_user_msgs_from_client{user="hello"} 889418
telemt_user_msgs_to_client{user="hello"} 5962543
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 20463.7 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61450
telemt_connections_bad_total 5450
telemt_handshake_timeouts_total 1307
telemt_upstream_connect_attempt_total 52126
telemt_upstream_connect_success_total 51882
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 52126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6312
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 184
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51880
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 1569149850 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 39567111591 (36.85 GB)
telemt_user_msgs_from_client{user="hello"} 1443821
telemt_user_msgs_to_client{user="hello"} 5559322
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 19
```