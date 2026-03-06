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

# Server Metrics 2026-03-06 23:23:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 18897.0 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27962
telemt_connections_bad_total 134
telemt_handshake_timeouts_total 476
telemt_upstream_connect_attempt_total 26066
telemt_upstream_connect_success_total 26060
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 26066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1585
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26058
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 2039245863 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 29682730886 (27.64 GB)
telemt_user_msgs_from_client{user="hello"} 1283245
telemt_user_msgs_to_client{user="hello"} 4663290
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 18896.0 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6197
telemt_connections_bad_total 144
telemt_handshake_timeouts_total 101
telemt_upstream_connect_attempt_total 5803
telemt_upstream_connect_success_total 5800
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 5803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 330
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5798
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 213722109 (203.82 MB)
telemt_user_octets_to_client{user="hello"} 3841155033 (3.58 GB)
telemt_user_msgs_from_client{user="hello"} 198167
telemt_user_msgs_to_client{user="hello"} 1075809
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 18895.9 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2948
telemt_connections_bad_total 136
telemt_handshake_timeouts_total 13
telemt_upstream_connect_attempt_total 2706
telemt_upstream_connect_success_total 2706
telemt_upstream_connect_attempts_per_request{bucket="1"} 2706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 208
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2704
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 64534023 (61.54 MB)
telemt_user_octets_to_client{user="hello"} 1850491168 (1.72 GB)
telemt_user_msgs_from_client{user="hello"} 62512
telemt_user_msgs_to_client{user="hello"} 388620
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 18895.8 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3870
telemt_connections_bad_total 69
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 3738
telemt_upstream_connect_success_total 3731
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 3738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 264
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3729
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 88503873 (84.40 MB)
telemt_user_octets_to_client{user="hello"} 1306907451 (1.22 GB)
telemt_user_msgs_from_client{user="hello"} 77140
telemt_user_msgs_to_client{user="hello"} 328962
telemt_user_unique_ips_current{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 18896.2 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10583
telemt_connections_bad_total 4319
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 6125
telemt_upstream_connect_success_total 6124
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 970
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6122
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 224378672 (213.98 MB)
telemt_user_octets_to_client{user="hello"} 7110957922 (6.62 GB)
telemt_user_msgs_from_client{user="hello"} 205534
telemt_user_msgs_to_client{user="hello"} 1467153
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 1
```