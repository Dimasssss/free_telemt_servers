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

# Server Metrics 2026-03-09 01:36:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 8170.6 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6852
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 177
telemt_upstream_connect_attempt_total 6209
telemt_upstream_connect_success_total 6207
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 562
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6205
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 71151761 (67.86 MB)
telemt_user_octets_to_client{user="hello"} 7190468795 (6.70 GB)
telemt_user_msgs_from_client{user="hello"} 158355
telemt_user_msgs_to_client{user="hello"} 264924
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 8168.7 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 476
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 454
telemt_upstream_connect_success_total 454
telemt_upstream_connect_attempts_per_request{bucket="1"} 454
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 452
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 6579270 (6.27 MB)
telemt_user_octets_to_client{user="hello"} 422568398 (402.99 MB)
telemt_user_msgs_from_client{user="hello"} 18555
telemt_user_msgs_to_client{user="hello"} 82099
telemt_user_unique_ips_current{user="hello"} 6
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 8169.1 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 584
telemt_connections_bad_total 71
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 501
telemt_upstream_connect_success_total 501
telemt_upstream_connect_attempts_per_request{bucket="1"} 501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 499
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 29815994 (28.43 MB)
telemt_user_octets_to_client{user="hello"} 81035285 (77.28 MB)
telemt_user_msgs_from_client{user="hello"} 16486
telemt_user_msgs_to_client{user="hello"} 25812
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 8163.9 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1046
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 62
telemt_upstream_connect_attempt_total 938
telemt_upstream_connect_success_total 938
telemt_upstream_connect_attempts_per_request{bucket="1"} 938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 723
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 211
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 936
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 7604984 (7.25 MB)
telemt_user_octets_to_client{user="hello"} 555777778 (530.03 MB)
telemt_user_msgs_from_client{user="hello"} 19841
telemt_user_msgs_to_client{user="hello"} 153902
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 8169.5 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2330
telemt_connections_bad_total 1467
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 844
telemt_upstream_connect_success_total 844
telemt_upstream_connect_attempts_per_request{bucket="1"} 844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 724
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 120
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 842
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 6934088 (6.61 MB)
telemt_user_octets_to_client{user="hello"} 1286043494 (1.20 GB)
telemt_user_msgs_from_client{user="hello"} 19309
telemt_user_msgs_to_client{user="hello"} 159189
telemt_user_unique_ips_current{user="hello"} 7
```