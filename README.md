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

# Server Metrics 2026-03-06 11:08:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 2817.7 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8012
telemt_connections_bad_total 1928
telemt_handshake_timeouts_total 91
telemt_upstream_connect_attempt_total 5744
telemt_upstream_connect_success_total 5744
telemt_upstream_connect_attempts_per_request{bucket="1"} 5744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 292
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5742
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 99980003 (95.35 MB)
telemt_user_octets_to_client{user="hello"} 3945622613 (3.67 GB)
telemt_user_msgs_from_client{user="hello"} 138171
telemt_user_msgs_to_client{user="hello"} 625614
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 2817.2 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1261
telemt_connections_bad_total 30
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 1203
telemt_upstream_connect_success_total 1202
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 74
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1200
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 15244128 (14.54 MB)
telemt_user_octets_to_client{user="hello"} 513380321 (489.60 MB)
telemt_user_msgs_from_client{user="hello"} 30587
telemt_user_msgs_to_client{user="hello"} 160349
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 2817.0 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1015
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 986
telemt_upstream_connect_success_total 986
telemt_upstream_connect_attempts_per_request{bucket="1"} 986
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 984
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 29559703 (28.19 MB)
telemt_user_octets_to_client{user="hello"} 475710716 (453.67 MB)
telemt_user_msgs_from_client{user="hello"} 28844
telemt_user_msgs_to_client{user="hello"} 100070
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 2815.7 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2362
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 2164
telemt_upstream_connect_success_total 2154
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2164
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 93
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2152
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 29728907 (28.35 MB)
telemt_user_octets_to_client{user="hello"} 382141946 (364.44 MB)
telemt_user_msgs_from_client{user="hello"} 30558
telemt_user_msgs_to_client{user="hello"} 117336
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 2816.9 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2049
telemt_connections_bad_total 509
telemt_handshake_timeouts_total 295
telemt_upstream_connect_attempt_total 1195
telemt_upstream_connect_success_total 1195
telemt_upstream_connect_attempts_per_request{bucket="1"} 1195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 128
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1193
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 27547104 (26.27 MB)
telemt_user_octets_to_client{user="hello"} 306829164 (292.62 MB)
telemt_user_msgs_from_client{user="hello"} 23044
telemt_user_msgs_to_client{user="hello"} 71043
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```