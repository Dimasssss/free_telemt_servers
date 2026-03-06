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

# Server Metrics 2026-03-06 18:56:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 2881.3 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4927
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 64
telemt_upstream_connect_attempt_total 4532
telemt_upstream_connect_success_total 4529
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 319
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4527
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 688945692 (657.03 MB)
telemt_user_octets_to_client{user="hello"} 8150421856 (7.59 GB)
telemt_user_msgs_from_client{user="hello"} 375516
telemt_user_msgs_to_client{user="hello"} 1298453
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 2879.8 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1469
telemt_connections_bad_total 57
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 1392
telemt_upstream_connect_success_total 1392
telemt_upstream_connect_attempts_per_request{bucket="1"} 1392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 65
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1390
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 17788257 (16.96 MB)
telemt_user_octets_to_client{user="hello"} 1397632271 (1.30 GB)
telemt_user_msgs_from_client{user="hello"} 35129
telemt_user_msgs_to_client{user="hello"} 388886
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 2879.7 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 778
telemt_connections_bad_total 3
telemt_upstream_connect_attempt_total 776
telemt_upstream_connect_success_total 776
telemt_upstream_connect_attempts_per_request{bucket="1"} 776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 774
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 11012077 (10.50 MB)
telemt_user_octets_to_client{user="hello"} 491568734 (468.80 MB)
telemt_user_msgs_from_client{user="hello"} 16490
telemt_user_msgs_to_client{user="hello"} 113078
telemt_user_unique_ips_current{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 2879.7 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 765
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 738
telemt_upstream_connect_success_total 735
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 60
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 733
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 23200381 (22.13 MB)
telemt_user_octets_to_client{user="hello"} 389470964 (371.43 MB)
telemt_user_msgs_from_client{user="hello"} 20520
telemt_user_msgs_to_client{user="hello"} 94744
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 2880.2 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2515
telemt_connections_bad_total 525
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 1972
telemt_upstream_connect_success_total 1972
telemt_upstream_connect_attempts_per_request{bucket="1"} 1972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1970
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 21671768 (20.67 MB)
telemt_user_octets_to_client{user="hello"} 1449885143 (1.35 GB)
telemt_user_msgs_from_client{user="hello"} 46101
telemt_user_msgs_to_client{user="hello"} 300515
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 5
```