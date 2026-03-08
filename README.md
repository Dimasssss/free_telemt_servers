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

# Server Metrics 2026-03-08 08:50:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 6087.9 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13171
telemt_connections_bad_total 2234
telemt_handshake_timeouts_total 51
telemt_upstream_connect_attempt_total 10357
telemt_upstream_connect_success_total 10351
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 10357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 597
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10349
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 273699050 (261.02 MB)
telemt_user_octets_to_client{user="hello"} 6431570649 (5.99 GB)
telemt_user_msgs_from_client{user="hello"} 243058
telemt_user_msgs_to_client{user="hello"} 324820
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 6087.0 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2814
telemt_connections_bad_total 48
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 2674
telemt_upstream_connect_success_total 2674
telemt_upstream_connect_attempts_per_request{bucket="1"} 2674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 153
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2672
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 36491344 (34.80 MB)
telemt_user_octets_to_client{user="hello"} 2042846426 (1.90 GB)
telemt_user_msgs_from_client{user="hello"} 67870
telemt_user_msgs_to_client{user="hello"} 507927
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 6086.7 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2365
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 2301
telemt_upstream_connect_success_total 2301
telemt_upstream_connect_attempts_per_request{bucket="1"} 2301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 225
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2299
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 25838863 (24.64 MB)
telemt_user_octets_to_client{user="hello"} 475190675 (453.18 MB)
telemt_user_msgs_from_client{user="hello"} 21402
telemt_user_msgs_to_client{user="hello"} 89165
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 6086.7 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2218
telemt_connections_bad_total 28
telemt_handshake_timeouts_total 19
telemt_upstream_connect_attempt_total 2122
telemt_upstream_connect_success_total 2118
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 2122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 133
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2116
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 48288523 (46.05 MB)
telemt_user_octets_to_client{user="hello"} 610278517 (582.01 MB)
telemt_user_msgs_from_client{user="hello"} 34874
telemt_user_msgs_to_client{user="hello"} 165175
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 6087.0 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3903
telemt_connections_bad_total 1135
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2736
telemt_upstream_connect_success_total 2736
telemt_upstream_connect_attempts_per_request{bucket="1"} 2736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2734
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 36368922 (34.68 MB)
telemt_user_octets_to_client{user="hello"} 2769274776 (2.58 GB)
telemt_user_msgs_from_client{user="hello"} 61351
telemt_user_msgs_to_client{user="hello"} 288748
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 4
```