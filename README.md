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

# Server Metrics 2026-03-06 16:47:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 23143.6 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54641
telemt_connections_bad_total 3111
telemt_handshake_timeouts_total 219
telemt_upstream_connect_attempt_total 47623
telemt_upstream_connect_success_total 47611
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 47623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2715
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47607
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 2467230130 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 31008390468 (28.88 GB)
telemt_user_msgs_from_client{user="hello"} 1678386
telemt_user_msgs_to_client{user="hello"} 4903655
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 23142.8 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10273
telemt_connections_bad_total 176
telemt_handshake_timeouts_total 99
telemt_upstream_connect_attempt_total 9746
telemt_upstream_connect_success_total 9728
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 9746
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 593
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9726
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 127160895 (121.27 MB)
telemt_user_octets_to_client{user="hello"} 5583630983 (5.20 GB)
telemt_user_msgs_from_client{user="hello"} 205673
telemt_user_msgs_to_client{user="hello"} 1726336
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 23142.1 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8471
telemt_connections_bad_total 142
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 8157
telemt_upstream_connect_success_total 8155
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 444
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8153
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 121831471 (116.19 MB)
telemt_user_octets_to_client{user="hello"} 4907984445 (4.57 GB)
telemt_user_msgs_from_client{user="hello"} 182726
telemt_user_msgs_to_client{user="hello"} 1155318
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 23141.5 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12119
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 117
telemt_upstream_connect_attempt_total 11209
telemt_upstream_connect_success_total 11172
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 11209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 726
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11170
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 155225446 (148.03 MB)
telemt_user_octets_to_client{user="hello"} 3797279542 (3.54 GB)
telemt_user_msgs_from_client{user="hello"} 193687
telemt_user_msgs_to_client{user="hello"} 963569
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 23142.7 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16690
telemt_connections_bad_total 5721
telemt_handshake_timeouts_total 556
telemt_upstream_connect_attempt_total 10123
telemt_upstream_connect_success_total 10123
telemt_upstream_connect_attempts_per_request{bucket="1"} 10123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1468
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10121
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 239067904 (227.99 MB)
telemt_user_octets_to_client{user="hello"} 21745091195 (20.25 GB)
telemt_user_msgs_from_client{user="hello"} 399020
telemt_user_msgs_to_client{user="hello"} 3925902
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```