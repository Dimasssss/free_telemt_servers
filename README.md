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

# Server Metrics 2026-03-08 09:41:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 9168.9 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19609
telemt_connections_bad_total 2558
telemt_handshake_timeouts_total 121
telemt_upstream_connect_attempt_total 16198
telemt_upstream_connect_success_total 16185
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 16198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 921
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16183
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 512439886 (488.70 MB)
telemt_user_octets_to_client{user="hello"} 10286429276 (9.58 GB)
telemt_user_msgs_from_client{user="hello"} 445294
telemt_user_msgs_to_client{user="hello"} 543454
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 9168.1 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4179
telemt_connections_bad_total 51
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 3972
telemt_upstream_connect_success_total 3972
telemt_upstream_connect_attempts_per_request{bucket="1"} 3972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 227
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3970
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 51221928 (48.85 MB)
telemt_user_octets_to_client{user="hello"} 2808224884 (2.62 GB)
telemt_user_msgs_from_client{user="hello"} 97202
telemt_user_msgs_to_client{user="hello"} 723388
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 9167.8 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3423
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 3343
telemt_upstream_connect_success_total 3343
telemt_upstream_connect_attempts_per_request{bucket="1"} 3343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 281
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3341
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 33801798 (32.24 MB)
telemt_user_octets_to_client{user="hello"} 1153961729 (1.07 GB)
telemt_user_msgs_from_client{user="hello"} 36376
telemt_user_msgs_to_client{user="hello"} 181708
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 9167.7 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3895
telemt_connections_bad_total 31
telemt_handshake_timeouts_total 26
telemt_upstream_connect_attempt_total 3724
telemt_upstream_connect_success_total 3719
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 3724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3717
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 82651382 (78.82 MB)
telemt_user_octets_to_client{user="hello"} 1549417296 (1.44 GB)
telemt_user_msgs_from_client{user="hello"} 70283
telemt_user_msgs_to_client{user="hello"} 360352
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 9168.0 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5632
telemt_connections_bad_total 1742
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 3832
telemt_upstream_connect_success_total 3832
telemt_upstream_connect_attempts_per_request{bucket="1"} 3832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 704
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3830
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 48788654 (46.53 MB)
telemt_user_octets_to_client{user="hello"} 3329615746 (3.10 GB)
telemt_user_msgs_from_client{user="hello"} 89422
telemt_user_msgs_to_client{user="hello"} 394054
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 5
```