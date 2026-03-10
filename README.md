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

# Server Metrics 2026-03-10 00:34:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 90900.3 (25h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169482
telemt_connections_bad_total 2326
telemt_handshake_timeouts_total 1702
telemt_upstream_connect_attempt_total 158754
telemt_upstream_connect_success_total 158704
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 158754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 146033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12607
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 158694
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 4860289312 (4.53 GB)
telemt_user_octets_to_client{user="hello"} 95491030232 (88.93 GB)
telemt_user_msgs_from_client{user="hello"} 4310506
telemt_user_msgs_to_client{user="hello"} 6133520
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 90899.2 (25h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52322
telemt_connections_bad_total 3051
telemt_handshake_timeouts_total 730
telemt_upstream_connect_attempt_total 45859
telemt_upstream_connect_success_total 45818
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 45859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4312
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45808
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 2120580891 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 22692620380 (21.13 GB)
telemt_user_msgs_from_client{user="hello"} 1503164
telemt_user_msgs_to_client{user="hello"} 6519965
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 90899.9 (25h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63243
telemt_connections_bad_total 832
telemt_handshake_timeouts_total 3667
telemt_upstream_connect_attempt_total 49965
telemt_upstream_connect_success_total 49963
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 49965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5869
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49953
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 5993677295 (5.58 GB)
telemt_user_octets_to_client{user="hello"} 53834992360 (50.14 GB)
telemt_user_msgs_from_client{user="hello"} 3183541
telemt_user_msgs_to_client{user="hello"} 7701452
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 90894.6 (25h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69253
telemt_connections_bad_total 362
telemt_handshake_timeouts_total 1034
telemt_upstream_connect_attempt_total 63924
telemt_upstream_connect_success_total 63764
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 63924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7787
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63754
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 2266569893 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 45729748900 (42.59 GB)
telemt_user_msgs_from_client{user="hello"} 1815155
telemt_user_msgs_to_client{user="hello"} 11045392
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 90900.1 (25h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115204
telemt_connections_bad_total 20553
telemt_handshake_timeouts_total 3002
telemt_upstream_connect_attempt_total 86700
telemt_upstream_connect_success_total 86689
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 86700
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12587
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 86679
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 1459361931 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 83069731976 (77.36 GB)
telemt_user_msgs_from_client{user="hello"} 2013104
telemt_user_msgs_to_client{user="hello"} 10738981
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 9
```