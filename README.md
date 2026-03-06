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

# Server Metrics 2026-03-06 10:58:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 2202.0 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4793
telemt_handshake_timeouts_total 85
telemt_upstream_connect_attempt_total 4477
telemt_upstream_connect_success_total 4477
telemt_upstream_connect_attempts_per_request{bucket="1"} 4477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4475
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 70500792 (67.23 MB)
telemt_user_octets_to_client{user="hello"} 2068978069 (1.93 GB)
telemt_user_msgs_from_client{user="hello"} 98971
telemt_user_msgs_to_client{user="hello"} 359624
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 2200.9 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 847
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 801
telemt_upstream_connect_success_total 801
telemt_upstream_connect_attempts_per_request{bucket="1"} 801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 799
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 9876734 (9.42 MB)
telemt_user_octets_to_client{user="hello"} 328359382 (313.15 MB)
telemt_user_msgs_from_client{user="hello"} 21757
telemt_user_msgs_to_client{user="hello"} 105502
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 2200.7 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 718
telemt_connections_bad_total 6
telemt_upstream_connect_attempt_total 697
telemt_upstream_connect_success_total 697
telemt_upstream_connect_attempts_per_request{bucket="1"} 697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 695
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 15038798 (14.34 MB)
telemt_user_octets_to_client{user="hello"} 393456134 (375.23 MB)
telemt_user_msgs_from_client{user="hello"} 20763
telemt_user_msgs_to_client{user="hello"} 81550
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 2199.4 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1756
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1614
telemt_upstream_connect_success_total 1605
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 60
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1603
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 21166971 (20.19 MB)
telemt_user_octets_to_client{user="hello"} 261114729 (249.02 MB)
telemt_user_msgs_from_client{user="hello"} 23292
telemt_user_msgs_to_client{user="hello"} 77926
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 2200.9 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1565
telemt_connections_bad_total 398
telemt_handshake_timeouts_total 290
telemt_upstream_connect_attempt_total 829
telemt_upstream_connect_success_total 829
telemt_upstream_connect_attempts_per_request{bucket="1"} 829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 827
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 17039807 (16.25 MB)
telemt_user_octets_to_client{user="hello"} 204084737 (194.63 MB)
telemt_user_msgs_from_client{user="hello"} 14395
telemt_user_msgs_to_client{user="hello"} 46433
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```