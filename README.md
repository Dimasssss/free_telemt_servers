# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

-----

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

# Server Metrics 2026-03-08 08:09:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 3624.0 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6175
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 5966
telemt_upstream_connect_success_total 5962
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 5966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 333
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5960
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 89126678 (85.00 MB)
telemt_user_octets_to_client{user="hello"} 2245587130 (2.09 GB)
telemt_user_msgs_from_client{user="hello"} 124697
telemt_user_msgs_to_client{user="hello"} 158628
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 3623.4 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1633
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1575
telemt_upstream_connect_success_total 1575
telemt_upstream_connect_attempts_per_request{bucket="1"} 1575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 97
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1573
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 18458645 (17.60 MB)
telemt_user_octets_to_client{user="hello"} 884408612 (843.44 MB)
telemt_user_msgs_from_client{user="hello"} 33955
telemt_user_msgs_to_client{user="hello"} 215958
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 3622.9 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1284
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1253
telemt_upstream_connect_success_total 1253
telemt_upstream_connect_attempts_per_request{bucket="1"} 1253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1251
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 20326531 (19.38 MB)
telemt_user_octets_to_client{user="hello"} 335219549 (319.69 MB)
telemt_user_msgs_from_client{user="hello"} 11875
telemt_user_msgs_to_client{user="hello"} 53711
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 3622.8 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1399
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 1351
telemt_upstream_connect_success_total 1348
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 1351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 82
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1346
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 36979802 (35.27 MB)
telemt_user_octets_to_client{user="hello"} 372631546 (355.37 MB)
telemt_user_msgs_from_client{user="hello"} 21435
telemt_user_msgs_to_client{user="hello"} 100893
telemt_user_unique_ips_current{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 3623.2 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2476
telemt_connections_bad_total 648
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 1805
telemt_upstream_connect_success_total 1805
telemt_upstream_connect_attempts_per_request{bucket="1"} 1805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1803
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 15088478 (14.39 MB)
telemt_user_octets_to_client{user="hello"} 484313352 (461.88 MB)
telemt_user_msgs_from_client{user="hello"} 26153
telemt_user_msgs_to_client{user="hello"} 88663
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```