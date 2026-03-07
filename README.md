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

# Server Metrics 2026-03-07 22:49:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 21865.5 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33300
telemt_connections_bad_total 224
telemt_handshake_timeouts_total 183
telemt_upstream_connect_attempt_total 32023
telemt_upstream_connect_success_total 32019
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 32023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32017
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 2125941372 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 22614490941 (21.06 GB)
telemt_user_msgs_from_client{user="hello"} 1140121
telemt_user_msgs_to_client{user="hello"} 3505745
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 21864.6 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6151
telemt_connections_bad_total 177
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 5864
telemt_upstream_connect_success_total 5857
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 5864
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5853
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 109529977 (104.46 MB)
telemt_user_octets_to_client{user="hello"} 4210753296 (3.92 GB)
telemt_user_msgs_from_client{user="hello"} 171715
telemt_user_msgs_to_client{user="hello"} 1172072
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 21864.4 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3750
telemt_connections_bad_total 120
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 3566
telemt_upstream_connect_success_total 3566
telemt_upstream_connect_attempts_per_request{bucket="1"} 3566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 491
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3564
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 103108078 (98.33 MB)
telemt_user_octets_to_client{user="hello"} 10244458220 (9.54 GB)
telemt_user_msgs_from_client{user="hello"} 168859
telemt_user_msgs_to_client{user="hello"} 2108872
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 21692.7 (6h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9815
telemt_connections_bad_total 125
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 9441
telemt_upstream_connect_success_total 9418
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 9441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1509
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9416
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 182102698 (173.67 MB)
telemt_user_octets_to_client{user="hello"} 9368776359 (8.73 GB)
telemt_user_msgs_from_client{user="hello"} 250640
telemt_user_msgs_to_client{user="hello"} 2763525
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 21864.5 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10940
telemt_connections_bad_total 4055
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 6678
telemt_upstream_connect_success_total 6670
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 6678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1578
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6668
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 1600394816 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 5681656723 (5.29 GB)
telemt_user_msgs_from_client{user="hello"} 751200
telemt_user_msgs_to_client{user="hello"} 1327590
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```