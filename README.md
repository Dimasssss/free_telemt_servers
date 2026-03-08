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

# Server Metrics 2026-03-08 09:10:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 7320.6 (2h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16024
telemt_connections_bad_total 2451
telemt_handshake_timeouts_total 77
telemt_upstream_connect_attempt_total 12892
telemt_upstream_connect_success_total 12883
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 12892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12881
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 367104575 (350.10 MB)
telemt_user_octets_to_client{user="hello"} 8136011875 (7.58 GB)
telemt_user_msgs_from_client{user="hello"} 326570
telemt_user_msgs_to_client{user="hello"} 415719
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 7320.0 (2h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3377
telemt_connections_bad_total 50
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 3195
telemt_upstream_connect_success_total 3195
telemt_upstream_connect_attempts_per_request{bucket="1"} 3195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 176
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3193
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 40995031 (39.10 MB)
telemt_user_octets_to_client{user="hello"} 2268571404 (2.11 GB)
telemt_user_msgs_from_client{user="hello"} 77264
telemt_user_msgs_to_client{user="hello"} 568314
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 7319.3 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2998
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 2924
telemt_upstream_connect_success_total 2924
telemt_upstream_connect_attempts_per_request{bucket="1"} 2924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2922
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 30396729 (28.99 MB)
telemt_user_octets_to_client{user="hello"} 565901214 (539.69 MB)
telemt_user_msgs_from_client{user="hello"} 26353
telemt_user_msgs_to_client{user="hello"} 104815
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 7319.2 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2929
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 26
telemt_upstream_connect_attempt_total 2775
telemt_upstream_connect_success_total 2771
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 2775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2769
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 56717802 (54.09 MB)
telemt_user_octets_to_client{user="hello"} 896031710 (854.52 MB)
telemt_user_msgs_from_client{user="hello"} 48111
telemt_user_msgs_to_client{user="hello"} 233168
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 7319.5 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4536
telemt_connections_bad_total 1368
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 3133
telemt_upstream_connect_success_total 3133
telemt_upstream_connect_attempts_per_request{bucket="1"} 3133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 609
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3131
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 41365563 (39.45 MB)
telemt_user_octets_to_client{user="hello"} 2959826007 (2.76 GB)
telemt_user_msgs_from_client{user="hello"} 71184
telemt_user_msgs_to_client{user="hello"} 325856
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```