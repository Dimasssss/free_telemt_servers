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

# Server Metrics 2026-03-05 01:26:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 50356.4 (13h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71062
telemt_connections_bad_total 162
telemt_handshake_timeouts_total 1562
telemt_upstream_connect_attempt_total 64370
telemt_upstream_connect_success_total 64355
telemt_upstream_connect_attempts_per_request{bucket="1"} 64340
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4150
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 64349
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 2360425078 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 48809626840 (45.46 GB)
telemt_user_msgs_from_client{user="hello"} 2047117
telemt_user_msgs_to_client{user="hello"} 7773523
telemt_user_unique_ips_current{user="hello"} 9
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 50359.3 (13h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15989
telemt_connections_bad_total 252
telemt_handshake_timeouts_total 41
telemt_upstream_connect_attempt_total 11479
telemt_upstream_connect_success_total 11477
telemt_upstream_connect_attempts_per_request{bucket="1"} 11475
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11471
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 1056703319 (1007.75 MB)
telemt_user_octets_to_client{user="hello"} 11094598832 (10.33 GB)
telemt_user_msgs_from_client{user="hello"} 650917
telemt_user_msgs_to_client{user="hello"} 3738714
telemt_user_unique_ips_current{user="hello"} 2
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 50357.5 (13h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11395
telemt_connections_bad_total 184
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 7490
telemt_upstream_connect_success_total 7490
telemt_upstream_connect_attempts_per_request{bucket="1"} 7490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 509
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7484
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 308696949 (294.40 MB)
telemt_user_octets_to_client{user="hello"} 5271120505 (4.91 GB)
telemt_user_msgs_from_client{user="hello"} 270215
telemt_user_msgs_to_client{user="hello"} 1140894
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 50355.4 (13h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17095
telemt_connections_bad_total 711
telemt_handshake_timeouts_total 88
telemt_upstream_connect_attempt_total 14900
telemt_upstream_connect_success_total 14895
telemt_upstream_connect_attempts_per_request{bucket="1"} 14890
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1121
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14889
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 399257859 (380.76 MB)
telemt_user_octets_to_client{user="hello"} 5673818804 (5.28 GB)
telemt_user_msgs_from_client{user="hello"} 313883
telemt_user_msgs_to_client{user="hello"} 1431128
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 50357.1 (13h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19329
telemt_connections_bad_total 9065
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 9891
telemt_upstream_connect_success_total 9887
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9885
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8294
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9881
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 520146952 (496.05 MB)
telemt_user_octets_to_client{user="hello"} 22419526252 (20.88 GB)
telemt_user_msgs_from_client{user="hello"} 561802
telemt_user_msgs_to_client{user="hello"} 4255748
telemt_user_unique_ips_current{user="hello"} 1
```