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

# Server Metrics 2026-03-08 17:14:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 36318.7 (10h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87314
telemt_connections_bad_total 5045
telemt_handshake_timeouts_total 1110
telemt_upstream_connect_attempt_total 78237
telemt_upstream_connect_success_total 78210
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 78237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4631
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 78204
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 1958732567 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 45334168477 (42.22 GB)
telemt_user_msgs_from_client{user="hello"} 1855731
telemt_user_msgs_to_client{user="hello"} 2599145
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 36317.8 (10h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18983
telemt_connections_bad_total 145
telemt_handshake_timeouts_total 124
telemt_upstream_connect_attempt_total 18382
telemt_upstream_connect_success_total 18378
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 18382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1273
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18374
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 665614318 (634.78 MB)
telemt_user_octets_to_client{user="hello"} 18285496214 (17.03 GB)
telemt_user_msgs_from_client{user="hello"} 723376
telemt_user_msgs_to_client{user="hello"} 4979704
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 36317.5 (10h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11609
telemt_connections_bad_total 162
telemt_handshake_timeouts_total 37
telemt_upstream_connect_attempt_total 10952
telemt_upstream_connect_success_total 10876
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 10952
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10046
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 758
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10872
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 228134185 (217.57 MB)
telemt_user_octets_to_client{user="hello"} 3961898407 (3.69 GB)
telemt_user_msgs_from_client{user="hello"} 189689
telemt_user_msgs_to_client{user="hello"} 693998
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 36317.5 (10h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15472
telemt_connections_bad_total 168
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 14762
telemt_upstream_connect_success_total 14731
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 14762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1062
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14727
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 1013868781 (966.90 MB)
telemt_user_octets_to_client{user="hello"} 5278780249 (4.92 GB)
telemt_user_msgs_from_client{user="hello"} 516668
telemt_user_msgs_to_client{user="hello"} 1194491
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 36317.6 (10h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20819
telemt_connections_bad_total 6715
telemt_handshake_timeouts_total 228
telemt_upstream_connect_attempt_total 13565
telemt_upstream_connect_success_total 13561
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 13565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2176
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13557
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 257547060 (245.62 MB)
telemt_user_octets_to_client{user="hello"} 11192301055 (10.42 GB)
telemt_user_msgs_from_client{user="hello"} 337676
telemt_user_msgs_to_client{user="hello"} 1464989
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```