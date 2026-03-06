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

# Server Metrics 2026-03-06 05:40:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 26706.7 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78744
telemt_connections_bad_total 51939
telemt_handshake_timeouts_total 2446
telemt_upstream_connect_attempt_total 22807
telemt_upstream_connect_success_total 22804
telemt_upstream_connect_attempts_per_request{bucket="1"} 22801
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1412
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22800
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 324057299 (309.05 MB)
telemt_user_octets_to_client{user="hello"} 20664277992 (19.25 GB)
telemt_user_msgs_from_client{user="hello"} 575695
telemt_user_msgs_to_client{user="hello"} 3100187
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 26704.5 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3002
telemt_connections_bad_total 144
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 2804
telemt_upstream_connect_success_total 2803
telemt_upstream_connect_attempts_per_request{bucket="1"} 2802
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2801
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 58951994 (56.22 MB)
telemt_user_octets_to_client{user="hello"} 1251201278 (1.17 GB)
telemt_user_msgs_from_client{user="hello"} 83654
telemt_user_msgs_to_client{user="hello"} 397758
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 26705.0 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1930
telemt_connections_bad_total 214
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 1694
telemt_upstream_connect_success_total 1694
telemt_upstream_connect_attempts_per_request{bucket="1"} 1694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 167
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1690
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 42510506 (40.54 MB)
telemt_user_octets_to_client{user="hello"} 2120101958 (1.97 GB)
telemt_user_msgs_from_client{user="hello"} 57797
telemt_user_msgs_to_client{user="hello"} 429979
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 26707.7 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3976
telemt_connections_bad_total 138
telemt_handshake_timeouts_total 309
telemt_upstream_connect_attempt_total 3366
telemt_upstream_connect_success_total 3366
telemt_upstream_connect_attempts_per_request{bucket="1"} 3366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 425
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3362
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 98403497 (93.84 MB)
telemt_user_octets_to_client{user="hello"} 5772519310 (5.38 GB)
telemt_user_msgs_from_client{user="hello"} 141822
telemt_user_msgs_to_client{user="hello"} 1224469
telemt_user_unique_ips_current{user="hello"} 1
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 26707.6 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8985
telemt_connections_bad_total 4848
telemt_handshake_timeouts_total 160
telemt_upstream_connect_attempt_total 3871
telemt_upstream_connect_success_total 3871
telemt_upstream_connect_attempts_per_request{bucket="1"} 3871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 559
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3867
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 78749971 (75.10 MB)
telemt_user_octets_to_client{user="hello"} 15954874956 (14.86 GB)
telemt_user_msgs_from_client{user="hello"} 201036
telemt_user_msgs_to_client{user="hello"} 3041685
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```