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

# Server Metrics 2026-03-06 19:47:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 5962.3 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10848
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 365
telemt_upstream_connect_attempt_total 9726
telemt_upstream_connect_success_total 9722
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 9726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 635
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9720
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 927481340 (884.52 MB)
telemt_user_octets_to_client{user="hello"} 12885238293 (12.00 GB)
telemt_user_msgs_from_client{user="hello"} 582729
telemt_user_msgs_to_client{user="hello"} 2038228
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 5960.7 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2819
telemt_connections_bad_total 63
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 2634
telemt_upstream_connect_success_total 2631
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 2634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 129
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2629
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 63949252 (60.99 MB)
telemt_user_octets_to_client{user="hello"} 1932426384 (1.80 GB)
telemt_user_msgs_from_client{user="hello"} 68758
telemt_user_msgs_to_client{user="hello"} 545962
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 5960.9 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1625
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 1520
telemt_upstream_connect_success_total 1520
telemt_upstream_connect_attempts_per_request{bucket="1"} 1520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 114
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1518
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 16708006 (15.93 MB)
telemt_user_octets_to_client{user="hello"} 660163759 (629.58 MB)
telemt_user_msgs_from_client{user="hello"} 26651
telemt_user_msgs_to_client{user="hello"} 156408
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 5960.7 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1354
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1314
telemt_upstream_connect_success_total 1310
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 100
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1308
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 26198608 (24.98 MB)
telemt_user_octets_to_client{user="hello"} 498296875 (475.21 MB)
telemt_user_msgs_from_client{user="hello"} 27565
telemt_user_msgs_to_client{user="hello"} 130340
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 5961.2 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4617
telemt_connections_bad_total 1097
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 3490
telemt_upstream_connect_success_total 3490
telemt_upstream_connect_attempts_per_request{bucket="1"} 3490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 594
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3488
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 136915759 (130.57 MB)
telemt_user_octets_to_client{user="hello"} 2298521721 (2.14 GB)
telemt_user_msgs_from_client{user="hello"} 108533
telemt_user_msgs_to_client{user="hello"} 523716
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```