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

# Server Metrics 2026-03-08 08:24:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 4548.1 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8552
telemt_connections_bad_total 736
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 7543
telemt_upstream_connect_success_total 7538
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 7543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 422
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7536
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 219355163 (209.19 MB)
telemt_user_octets_to_client{user="hello"} 4150572346 (3.87 GB)
telemt_user_msgs_from_client{user="hello"} 172427
telemt_user_msgs_to_client{user="hello"} 228553
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 4547.3 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2020
telemt_connections_bad_total 46
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1910
telemt_upstream_connect_success_total 1910
telemt_upstream_connect_attempts_per_request{bucket="1"} 1910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1908
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 23775870 (22.67 MB)
telemt_user_octets_to_client{user="hello"} 986826757 (941.11 MB)
telemt_user_msgs_from_client{user="hello"} 39666
telemt_user_msgs_to_client{user="hello"} 242306
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 4546.8 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1682
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1640
telemt_upstream_connect_success_total 1640
telemt_upstream_connect_attempts_per_request{bucket="1"} 1640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 160
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1638
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 21782524 (20.77 MB)
telemt_user_octets_to_client{user="hello"} 368053026 (351.00 MB)
telemt_user_msgs_from_client{user="hello"} 15260
telemt_user_msgs_to_client{user="hello"} 65111
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 4546.7 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1702
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 1642
telemt_upstream_connect_success_total 1639
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 1642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 98
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1637
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 39487632 (37.66 MB)
telemt_user_octets_to_client{user="hello"} 435405225 (415.23 MB)
telemt_user_msgs_from_client{user="hello"} 25622
telemt_user_msgs_to_client{user="hello"} 119911
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 4547.0 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2956
telemt_connections_bad_total 814
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2113
telemt_upstream_connect_success_total 2113
telemt_upstream_connect_attempts_per_request{bucket="1"} 2113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 398
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2111
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 20419545 (19.47 MB)
telemt_user_octets_to_client{user="hello"} 578654341 (551.85 MB)
telemt_user_msgs_from_client{user="hello"} 31608
telemt_user_msgs_to_client{user="hello"} 105946
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```