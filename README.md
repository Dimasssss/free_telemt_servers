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

# Server Metrics 2026-03-06 17:44:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 26533.8 (7h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61825
telemt_connections_bad_total 3258
telemt_handshake_timeouts_total 254
telemt_upstream_connect_attempt_total 54264
telemt_upstream_connect_success_total 54251
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 54264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3068
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 54247
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 2748171641 (2.56 GB)
telemt_user_octets_to_client{user="hello"} 36248686880 (33.76 GB)
telemt_user_msgs_from_client{user="hello"} 1900643
telemt_user_msgs_to_client{user="hello"} 5723090
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 26533.8 (7h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12125
telemt_connections_bad_total 203
telemt_handshake_timeouts_total 102
telemt_upstream_connect_attempt_total 11550
telemt_upstream_connect_success_total 11531
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 11550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 674
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11527
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 149157965 (142.25 MB)
telemt_user_octets_to_client{user="hello"} 6305068458 (5.87 GB)
telemt_user_msgs_from_client{user="hello"} 242828
telemt_user_msgs_to_client{user="hello"} 1942202
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 26533.0 (7h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9498
telemt_connections_bad_total 147
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 9160
telemt_upstream_connect_success_total 9158
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 9160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9156
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 132037272 (125.92 MB)
telemt_user_octets_to_client{user="hello"} 5494811072 (5.12 GB)
telemt_user_msgs_from_client{user="hello"} 209290
telemt_user_msgs_to_client{user="hello"} 1294707
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 26532.4 (7h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13414
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 120
telemt_upstream_connect_attempt_total 12494
telemt_upstream_connect_success_total 12451
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 12494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 846
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12447
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 186760046 (178.11 MB)
telemt_user_octets_to_client{user="hello"} 5413324437 (5.04 GB)
telemt_user_msgs_from_client{user="hello"} 230647
telemt_user_msgs_to_client{user="hello"} 1292419
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 26533.7 (7h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18890
telemt_connections_bad_total 6328
telemt_handshake_timeouts_total 573
telemt_upstream_connect_attempt_total 11660
telemt_upstream_connect_success_total 11660
telemt_upstream_connect_attempts_per_request{bucket="1"} 11660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1847
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11656
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 261967335 (249.83 MB)
telemt_user_octets_to_client{user="hello"} 24339520019 (22.67 GB)
telemt_user_msgs_from_client{user="hello"} 450819
telemt_user_msgs_to_client{user="hello"} 4423148
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```