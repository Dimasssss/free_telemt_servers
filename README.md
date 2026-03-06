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

# Server Metrics 2026-03-06 18:35:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 1649.2 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2800
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 2577
telemt_upstream_connect_success_total 2575
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 168
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2573
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 273806557 (261.12 MB)
telemt_user_octets_to_client{user="hello"} 5449741710 (5.08 GB)
telemt_user_msgs_from_client{user="hello"} 180261
telemt_user_msgs_to_client{user="hello"} 905374
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 1647.3 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 864
telemt_connections_bad_total 5
telemt_upstream_connect_attempt_total 850
telemt_upstream_connect_success_total 850
telemt_upstream_connect_attempts_per_request{bucket="1"} 850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 848
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 7229587 (6.89 MB)
telemt_user_octets_to_client{user="hello"} 432107619 (412.09 MB)
telemt_user_msgs_from_client{user="hello"} 16672
telemt_user_msgs_to_client{user="hello"} 124042
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 1647.2 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 547
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 547
telemt_upstream_connect_success_total 547
telemt_upstream_connect_attempts_per_request{bucket="1"} 547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 545
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 8513521 (8.12 MB)
telemt_user_octets_to_client{user="hello"} 117613627 (112.17 MB)
telemt_user_msgs_from_client{user="hello"} 10009
telemt_user_msgs_to_client{user="hello"} 33647
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 1647.3 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 526
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 501
telemt_upstream_connect_success_total 499
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 497
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 21558732 (20.56 MB)
telemt_user_octets_to_client{user="hello"} 375108887 (357.73 MB)
telemt_user_msgs_from_client{user="hello"} 16893
telemt_user_msgs_to_client{user="hello"} 86274
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 1647.7 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1516
telemt_connections_bad_total 304
telemt_upstream_connect_attempt_total 1200
telemt_upstream_connect_success_total 1200
telemt_upstream_connect_attempts_per_request{bucket="1"} 1200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 175
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1198
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 11468082 (10.94 MB)
telemt_user_octets_to_client{user="hello"} 685087366 (653.35 MB)
telemt_user_msgs_from_client{user="hello"} 25135
telemt_user_msgs_to_client{user="hello"} 152433
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 5
```