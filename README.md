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

# Server Metrics 2026-03-06 03:37:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 19319.1 (5h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69245
telemt_connections_bad_total 51932
telemt_handshake_timeouts_total 2353
telemt_upstream_connect_attempt_total 13600
telemt_upstream_connect_success_total 13598
telemt_upstream_connect_attempts_per_request{bucket="1"} 13596
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 826
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13596
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 186828280 (178.17 MB)
telemt_user_octets_to_client{user="hello"} 13246881293 (12.34 GB)
telemt_user_msgs_from_client{user="hello"} 334416
telemt_user_msgs_to_client{user="hello"} 1949852
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 19317.2 (5h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1753
telemt_connections_bad_total 134
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1594
telemt_upstream_connect_success_total 1593
telemt_upstream_connect_attempts_per_request{bucket="1"} 1592
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1591
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 47312009 (45.12 MB)
telemt_user_octets_to_client{user="hello"} 732690557 (698.75 MB)
telemt_user_msgs_from_client{user="hello"} 57886
telemt_user_msgs_to_client{user="hello"} 232932
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 19317.5 (5h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1258
telemt_connections_bad_total 192
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1057
telemt_upstream_connect_success_total 1057
telemt_upstream_connect_attempts_per_request{bucket="1"} 1057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 156
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1053
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 35957135 (34.29 MB)
telemt_user_octets_to_client{user="hello"} 1698766791 (1.58 GB)
telemt_user_msgs_from_client{user="hello"} 44501
telemt_user_msgs_to_client{user="hello"} 338270
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 19320.3 (5h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2464
telemt_connections_bad_total 126
telemt_handshake_timeouts_total 295
telemt_upstream_connect_attempt_total 1978
telemt_upstream_connect_success_total 1978
telemt_upstream_connect_attempts_per_request{bucket="1"} 1978
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 359
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1974
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 94181381 (89.82 MB)
telemt_user_octets_to_client{user="hello"} 5619054746 (5.23 GB)
telemt_user_msgs_from_client{user="hello"} 131656
telemt_user_msgs_to_client{user="hello"} 1175258
telemt_user_unique_ips_current{user="hello"} 1
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 19320.0 (5h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6235
telemt_connections_bad_total 3530
telemt_handshake_timeouts_total 142
telemt_upstream_connect_attempt_total 2502
telemt_upstream_connect_success_total 2502
telemt_upstream_connect_attempts_per_request{bucket="1"} 2502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 309
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2500
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 49432624 (47.14 MB)
telemt_user_octets_to_client{user="hello"} 11279109300 (10.50 GB)
telemt_user_msgs_from_client{user="hello"} 130382
telemt_user_msgs_to_client{user="hello"} 2047315
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```