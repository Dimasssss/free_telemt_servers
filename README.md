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

# Server Metrics 2026-03-07 00:34:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 23206.6 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31147
telemt_connections_bad_total 145
telemt_handshake_timeouts_total 486
telemt_upstream_connect_attempt_total 29048
telemt_upstream_connect_success_total 29041
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 29048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29037
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 2068988129 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 32332826386 (30.11 GB)
telemt_user_msgs_from_client{user="hello"} 1354413
telemt_user_msgs_to_client{user="hello"} 5098847
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 23205.4 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6673
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 103
telemt_upstream_connect_attempt_total 6256
telemt_upstream_connect_success_total 6253
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6249
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 215178958 (205.21 MB)
telemt_user_octets_to_client{user="hello"} 3894238783 (3.63 GB)
telemt_user_msgs_from_client{user="hello"} 201487
telemt_user_msgs_to_client{user="hello"} 1088566
telemt_user_unique_ips_current{user="hello"} 4
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 23205.4 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3100
telemt_connections_bad_total 148
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 2833
telemt_upstream_connect_success_total 2833
telemt_upstream_connect_attempts_per_request{bucket="1"} 2833
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 230
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2829
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 64978999 (61.97 MB)
telemt_user_octets_to_client{user="hello"} 1861617162 (1.73 GB)
telemt_user_msgs_from_client{user="hello"} 63755
telemt_user_msgs_to_client{user="hello"} 392269
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 23205.5 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4223
telemt_connections_bad_total 77
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 4079
telemt_upstream_connect_success_total 4072
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 346
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4068
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 100169572 (95.53 MB)
telemt_user_octets_to_client{user="hello"} 1349469883 (1.26 GB)
telemt_user_msgs_from_client{user="hello"} 84427
telemt_user_msgs_to_client{user="hello"} 345547
telemt_user_unique_ips_current{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 23205.9 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11800
telemt_connections_bad_total 5109
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 6549
telemt_upstream_connect_success_total 6548
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1025
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6544
telemt_user_octets_from_client{user="hello"} 227519513 (216.98 MB)
telemt_user_octets_to_client{user="hello"} 7413200953 (6.90 GB)
telemt_user_msgs_from_client{user="hello"} 213913
telemt_user_msgs_to_client{user="hello"} 1524858
```