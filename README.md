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

# Server Metrics 2026-03-10 13:33:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 137588.5 (38h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313070
telemt_connections_bad_total 3472
telemt_handshake_timeouts_total 3261
telemt_upstream_connect_attempt_total 293211
telemt_upstream_connect_success_total 293054
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 293211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 271045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 293040
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 6777364455 (6.31 GB)
telemt_user_octets_to_client{user="hello"} 193959719933 (180.64 GB)
telemt_user_msgs_from_client{user="hello"} 7040975
telemt_user_msgs_to_client{user="hello"} 11474577
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 137587.4 (38h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96508
telemt_connections_bad_total 3273
telemt_handshake_timeouts_total 1287
telemt_upstream_connect_attempt_total 87011
telemt_upstream_connect_success_total 86967
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 87011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8287
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 430
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 86953
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 2816752338 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 37411388910 (34.84 GB)
telemt_user_msgs_from_client{user="hello"} 2292500
telemt_user_msgs_to_client{user="hello"} 10802740
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 137587.9 (38h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137169
telemt_connections_bad_total 1229
telemt_handshake_timeouts_total 6475
telemt_upstream_connect_attempt_total 102486
telemt_upstream_connect_success_total 102483
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 102486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90766
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11678
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 102469
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 6661685076 (6.20 GB)
telemt_user_octets_to_client{user="hello"} 68736076466 (64.02 GB)
telemt_user_msgs_from_client{user="hello"} 4512643
telemt_user_msgs_to_client{user="hello"} 11600405
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 137582.9 (38h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142002
telemt_connections_bad_total 1061
telemt_handshake_timeouts_total 2933
telemt_upstream_connect_attempt_total 131193
telemt_upstream_connect_success_total 130899
telemt_upstream_connect_fail_total 294
telemt_upstream_connect_attempts_per_request{bucket="1"} 131193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 116271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14215
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 82
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 331
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 294
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 130885
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 5009812222 (4.67 GB)
telemt_user_octets_to_client{user="hello"} 92971286169 (86.59 GB)
telemt_user_msgs_from_client{user="hello"} 3839455
telemt_user_msgs_to_client{user="hello"} 21056273
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 137588.0 (38h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209323
telemt_connections_bad_total 30697
telemt_handshake_timeouts_total 5788
telemt_upstream_connect_attempt_total 164066
telemt_upstream_connect_success_total 163104
telemt_upstream_connect_fail_total 962
telemt_upstream_connect_attempts_per_request{bucket="1"} 164066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 141190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21693
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 962
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 163090
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 3497064714 (3.26 GB)
telemt_user_octets_to_client{user="hello"} 117989973173 (109.89 GB)
telemt_user_msgs_from_client{user="hello"} 3734679
telemt_user_msgs_to_client{user="hello"} 16158206
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 20
```