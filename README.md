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

# Server Metrics 2026-03-07 22:34:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 20941.3 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32329
telemt_connections_bad_total 223
telemt_handshake_timeouts_total 183
telemt_upstream_connect_attempt_total 31101
telemt_upstream_connect_success_total 31097
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 31101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31095
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 2119588795 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 22478855051 (20.94 GB)
telemt_user_msgs_from_client{user="hello"} 1128730
telemt_user_msgs_to_client{user="hello"} 3479601
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 20940.3 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6064
telemt_connections_bad_total 177
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 5778
telemt_upstream_connect_success_total 5771
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 5778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 325
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5767
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 101782886 (97.07 MB)
telemt_user_octets_to_client{user="hello"} 3876637609 (3.61 GB)
telemt_user_msgs_from_client{user="hello"} 156657
telemt_user_msgs_to_client{user="hello"} 1092647
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 20940.0 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3629
telemt_connections_bad_total 118
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 3449
telemt_upstream_connect_success_total 3449
telemt_upstream_connect_attempts_per_request{bucket="1"} 3449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 448
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3447
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 98028336 (93.49 MB)
telemt_user_octets_to_client{user="hello"} 8873977405 (8.26 GB)
telemt_user_msgs_from_client{user="hello"} 154251
telemt_user_msgs_to_client{user="hello"} 1772949
telemt_user_unique_ips_current{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 20768.2 (5h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9605
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 9236
telemt_upstream_connect_success_total 9213
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 9236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1491
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9211
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 175928659 (167.78 MB)
telemt_user_octets_to_client{user="hello"} 9357972443 (8.72 GB)
telemt_user_msgs_from_client{user="hello"} 246880
telemt_user_msgs_to_client{user="hello"} 2758890
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 20940.2 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10515
telemt_connections_bad_total 3889
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 6429
telemt_upstream_connect_success_total 6421
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 6429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1531
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6419
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 1589732953 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 4529151733 (4.22 GB)
telemt_user_msgs_from_client{user="hello"} 722738
telemt_user_msgs_to_client{user="hello"} 1053289
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```