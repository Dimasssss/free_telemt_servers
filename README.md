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

# Server Metrics 2026-03-05 17:46:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.0

telemt_uptime_seconds 1892.6 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7046
telemt_connections_bad_total 4852
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 2151
telemt_upstream_connect_success_total 2150
telemt_upstream_connect_attempts_per_request{bucket="1"} 2149
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 167
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2148
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 36007717 (34.34 MB)
telemt_user_octets_to_client{user="hello"} 858434252 (818.67 MB)
telemt_user_msgs_from_client{user="hello"} 68531
telemt_user_msgs_to_client{user="hello"} 172360
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.0

telemt_uptime_seconds 1894.1 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 461
telemt_upstream_connect_attempt_total 463
telemt_upstream_connect_success_total 463
telemt_upstream_connect_attempts_per_request{bucket="1"} 463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 461
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 3681744 (3.51 MB)
telemt_user_octets_to_client{user="hello"} 157271801 (149.99 MB)
telemt_user_msgs_from_client{user="hello"} 9155
telemt_user_msgs_to_client{user="hello"} 47891
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.0

telemt_uptime_seconds 1892.2 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 683
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 530
telemt_upstream_connect_success_total 530
telemt_upstream_connect_attempts_per_request{bucket="1"} 530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 57
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 528
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 2694936 (2.57 MB)
telemt_user_octets_to_client{user="hello"} 160345804 (152.92 MB)
telemt_user_msgs_from_client{user="hello"} 7287
telemt_user_msgs_to_client{user="hello"} 38729
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.0

telemt_uptime_seconds 1889.9 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 545
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 534
telemt_upstream_connect_success_total 534
telemt_upstream_connect_attempts_per_request{bucket="1"} 534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 532
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 2984110 (2.85 MB)
telemt_user_octets_to_client{user="hello"} 135079464 (128.82 MB)
telemt_user_msgs_from_client{user="hello"} 6819
telemt_user_msgs_to_client{user="hello"} 36147
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.0

telemt_uptime_seconds 1891.7 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 975
telemt_connections_bad_total 333
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 625
telemt_upstream_connect_success_total 625
telemt_upstream_connect_attempts_per_request{bucket="1"} 625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 623
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 25247067 (24.08 MB)
telemt_user_octets_to_client{user="hello"} 742479312 (708.08 MB)
telemt_user_msgs_from_client{user="hello"} 28647
telemt_user_msgs_to_client{user="hello"} 146648
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```