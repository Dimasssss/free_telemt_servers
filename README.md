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

# Server Metrics 2026-03-06 11:03:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 2510.0 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5475
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 89
telemt_upstream_connect_attempt_total 5135
telemt_upstream_connect_success_total 5135
telemt_upstream_connect_attempts_per_request{bucket="1"} 5135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 250
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5133
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 86794080 (82.77 MB)
telemt_user_octets_to_client{user="hello"} 3168814310 (2.95 GB)
telemt_user_msgs_from_client{user="hello"} 121237
telemt_user_msgs_to_client{user="hello"} 513548
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 2509.1 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1062
telemt_connections_bad_total 30
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 1010
telemt_upstream_connect_success_total 1009
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 61
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1007
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 11906776 (11.36 MB)
telemt_user_octets_to_client{user="hello"} 423334147 (403.72 MB)
telemt_user_msgs_from_client{user="hello"} 25942
telemt_user_msgs_to_client{user="hello"} 134191
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 2508.8 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 882
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 855
telemt_upstream_connect_success_total 855
telemt_upstream_connect_attempts_per_request{bucket="1"} 855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 853
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 18922328 (18.05 MB)
telemt_user_octets_to_client{user="hello"} 433177914 (413.11 MB)
telemt_user_msgs_from_client{user="hello"} 23589
telemt_user_msgs_to_client{user="hello"} 90295
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 2507.6 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2024
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 1861
telemt_upstream_connect_success_total 1852
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 72
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1850
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 22368203 (21.33 MB)
telemt_user_octets_to_client{user="hello"} 306163986 (291.98 MB)
telemt_user_msgs_from_client{user="hello"} 26359
telemt_user_msgs_to_client{user="hello"} 93911
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 2509.0 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1798
telemt_connections_bad_total 454
telemt_handshake_timeouts_total 295
telemt_upstream_connect_attempt_total 1001
telemt_upstream_connect_success_total 1001
telemt_upstream_connect_attempts_per_request{bucket="1"} 1001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 111
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 999
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 24781863 (23.63 MB)
telemt_user_octets_to_client{user="hello"} 257450949 (245.52 MB)
telemt_user_msgs_from_client{user="hello"} 19924
telemt_user_msgs_to_client{user="hello"} 58785
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```