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

# Server Metrics 2026-03-07 20:10:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 12316.2 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21491
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 175
telemt_upstream_connect_attempt_total 20670
telemt_upstream_connect_success_total 20667
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 20670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1062
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20665
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 1776627972 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 14516534344 (13.52 GB)
telemt_user_msgs_from_client{user="hello"} 793660
telemt_user_msgs_to_client{user="hello"} 2211704
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 12315.4 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4695
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 4513
telemt_upstream_connect_success_total 4511
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4509
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 73022399 (69.64 MB)
telemt_user_octets_to_client{user="hello"} 2856160874 (2.66 GB)
telemt_user_msgs_from_client{user="hello"} 116471
telemt_user_msgs_to_client{user="hello"} 820710
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 12315.0 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2386
telemt_connections_bad_total 93
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 2264
telemt_upstream_connect_success_total 2264
telemt_upstream_connect_attempts_per_request{bucket="1"} 2264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2046
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 218
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2262
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 74659249 (71.20 MB)
telemt_user_octets_to_client{user="hello"} 3551676632 (3.31 GB)
telemt_user_msgs_from_client{user="hello"} 88221
telemt_user_msgs_to_client{user="hello"} 733837
telemt_user_unique_ips_current{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 12143.4 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5185
telemt_connections_bad_total 90
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 4987
telemt_upstream_connect_success_total 4975
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 4987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 814
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4973
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 75526350 (72.03 MB)
telemt_user_octets_to_client{user="hello"} 4923319281 (4.59 GB)
telemt_user_msgs_from_client{user="hello"} 128314
telemt_user_msgs_to_client{user="hello"} 1532594
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 12315.3 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7260
telemt_connections_bad_total 2267
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 4849
telemt_upstream_connect_success_total 4842
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1306
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4840
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 1566535909 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 3050040136 (2.84 GB)
telemt_user_msgs_from_client{user="hello"} 663380
telemt_user_msgs_to_client{user="hello"} 720424
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 4
```