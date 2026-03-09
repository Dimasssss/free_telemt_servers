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

# Server Metrics 2026-03-09 14:52:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 55933.9 (15h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99454
telemt_connections_bad_total 1649
telemt_handshake_timeouts_total 944
telemt_upstream_connect_attempt_total 92556
telemt_upstream_connect_success_total 92518
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 92556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 85328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7132
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 92512
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 2448812766 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 47521728652 (44.26 GB)
telemt_user_msgs_from_client{user="hello"} 2262393
telemt_user_msgs_to_client{user="hello"} 3155854
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 55932.6 (15h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24135
telemt_connections_bad_total 207
telemt_handshake_timeouts_total 291
telemt_upstream_connect_attempt_total 22808
telemt_upstream_connect_success_total 22791
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 22808
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1591
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22785
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 809114216 (771.63 MB)
telemt_user_octets_to_client{user="hello"} 12976098635 (12.08 GB)
telemt_user_msgs_from_client{user="hello"} 689201
telemt_user_msgs_to_client{user="hello"} 3505297
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 55933.5 (15h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30547
telemt_connections_bad_total 642
telemt_handshake_timeouts_total 1513
telemt_upstream_connect_attempt_total 21856
telemt_upstream_connect_success_total 21856
telemt_upstream_connect_attempts_per_request{bucket="1"} 21856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21850
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 4345573334 (4.05 GB)
telemt_user_octets_to_client{user="hello"} 12867666719 (11.98 GB)
telemt_user_msgs_from_client{user="hello"} 1832128
telemt_user_msgs_to_client{user="hello"} 1781724
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 55927.7 (15h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32730
telemt_connections_bad_total 184
telemt_handshake_timeouts_total 809
telemt_upstream_connect_attempt_total 30014
telemt_upstream_connect_success_total 29937
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 30014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3635
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29931
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 1817931906 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 21735131900 (20.24 GB)
telemt_user_msgs_from_client{user="hello"} 1055641
telemt_user_msgs_to_client{user="hello"} 5271411
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 55933.3 (15h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59325
telemt_connections_bad_total 13569
telemt_handshake_timeouts_total 1452
telemt_upstream_connect_attempt_total 41451
telemt_upstream_connect_success_total 41449
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 41451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6420
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41443
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 712463499 (679.46 MB)
telemt_user_octets_to_client{user="hello"} 39562834793 (36.85 GB)
telemt_user_msgs_from_client{user="hello"} 915827
telemt_user_msgs_to_client{user="hello"} 4906720
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 23
```