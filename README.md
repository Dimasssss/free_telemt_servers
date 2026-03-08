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

# Server Metrics 2026-03-08 11:14:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 14719.8 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30777
telemt_connections_bad_total 2561
telemt_handshake_timeouts_total 190
telemt_upstream_connect_attempt_total 26797
telemt_upstream_connect_success_total 26782
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 26797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26780
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 964347394 (919.67 MB)
telemt_user_octets_to_client{user="hello"} 15173655705 (14.13 GB)
telemt_user_msgs_from_client{user="hello"} 747672
telemt_user_msgs_to_client{user="hello"} 866063
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 14719.1 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7779
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 97
telemt_upstream_connect_attempt_total 7421
telemt_upstream_connect_success_total 7421
telemt_upstream_connect_attempts_per_request{bucket="1"} 7421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7419
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 108252364 (103.24 MB)
telemt_user_octets_to_client{user="hello"} 5022774682 (4.68 GB)
telemt_user_msgs_from_client{user="hello"} 195223
telemt_user_msgs_to_client{user="hello"} 1298316
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 14718.8 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4923
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 4796
telemt_upstream_connect_success_total 4796
telemt_upstream_connect_attempts_per_request{bucket="1"} 4796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 342
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4794
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 109496087 (104.42 MB)
telemt_user_octets_to_client{user="hello"} 1353064624 (1.26 GB)
telemt_user_msgs_from_client{user="hello"} 76848
telemt_user_msgs_to_client{user="hello"} 233305
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 14718.8 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6859
telemt_connections_bad_total 79
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 6540
telemt_upstream_connect_success_total 6530
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 6540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 423
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6528
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 878555899 (837.86 MB)
telemt_user_octets_to_client{user="hello"} 2726392221 (2.54 GB)
telemt_user_msgs_from_client{user="hello"} 367381
telemt_user_msgs_to_client{user="hello"} 594742
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 14719.0 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9182
telemt_connections_bad_total 2749
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 6286
telemt_upstream_connect_success_total 6285
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6283
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 102205018 (97.47 MB)
telemt_user_octets_to_client{user="hello"} 4354229956 (4.06 GB)
telemt_user_msgs_from_client{user="hello"} 144496
telemt_user_msgs_to_client{user="hello"} 614915
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 3
```