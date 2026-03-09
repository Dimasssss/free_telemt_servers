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

# Server Metrics 2026-03-09 07:02:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 27741.5 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28778
telemt_connections_bad_total 37
telemt_handshake_timeouts_total 569
telemt_upstream_connect_attempt_total 26586
telemt_upstream_connect_success_total 26578
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 26586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1936
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26574
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 248219222 (236.72 MB)
telemt_user_octets_to_client{user="hello"} 14741639329 (13.73 GB)
telemt_user_msgs_from_client{user="hello"} 508248
telemt_user_msgs_to_client{user="hello"} 769642
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 27739.8 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4243
telemt_connections_bad_total 92
telemt_handshake_timeouts_total 75
telemt_upstream_connect_attempt_total 4001
telemt_upstream_connect_success_total 4001
telemt_upstream_connect_attempts_per_request{bucket="1"} 4001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 264
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3997
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 55079439 (52.53 MB)
telemt_user_octets_to_client{user="hello"} 3352130640 (3.12 GB)
telemt_user_msgs_from_client{user="hello"} 119855
telemt_user_msgs_to_client{user="hello"} 656600
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 27740.4 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2302
telemt_connections_bad_total 109
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 2159
telemt_upstream_connect_success_total 2159
telemt_upstream_connect_attempts_per_request{bucket="1"} 2159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 322
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2155
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 912756581 (870.47 MB)
telemt_user_octets_to_client{user="hello"} 1382940455 (1.29 GB)
telemt_user_msgs_from_client{user="hello"} 356104
telemt_user_msgs_to_client{user="hello"} 264740
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 27735.2 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4911
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 351
telemt_upstream_connect_attempt_total 3990
telemt_upstream_connect_success_total 3987
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3990
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 723
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3983
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 131098422 (125.03 MB)
telemt_user_octets_to_client{user="hello"} 2975614112 (2.77 GB)
telemt_user_msgs_from_client{user="hello"} 84421
telemt_user_msgs_to_client{user="hello"} 648234
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 27740.7 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10203
telemt_connections_bad_total 5468
telemt_handshake_timeouts_total 29
telemt_upstream_connect_attempt_total 4498
telemt_upstream_connect_success_total 4498
telemt_upstream_connect_attempts_per_request{bucket="1"} 4498
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4494
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 60086632 (57.30 MB)
telemt_user_octets_to_client{user="hello"} 2953963052 (2.75 GB)
telemt_user_msgs_from_client{user="hello"} 91009
telemt_user_msgs_to_client{user="hello"} 409602
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 5
```