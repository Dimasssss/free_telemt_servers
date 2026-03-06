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

# Server Metrics 2026-03-06 19:06:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 3497.6 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5981
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 96
telemt_upstream_connect_attempt_total 5488
telemt_upstream_connect_success_total 5485
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 5488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 413
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5483
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 840788950 (801.84 MB)
telemt_user_octets_to_client{user="hello"} 9971397020 (9.29 GB)
telemt_user_msgs_from_client{user="hello"} 464574
telemt_user_msgs_to_client{user="hello"} 1566200
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 3496.5 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1830
telemt_connections_bad_total 57
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1713
telemt_upstream_connect_success_total 1713
telemt_upstream_connect_attempts_per_request{bucket="1"} 1713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 88
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1711
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 20799871 (19.84 MB)
telemt_user_octets_to_client{user="hello"} 1512141623 (1.41 GB)
telemt_user_msgs_from_client{user="hello"} 40116
telemt_user_msgs_to_client{user="hello"} 418479
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 3496.5 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 919
telemt_connections_bad_total 10
telemt_upstream_connect_attempt_total 904
telemt_upstream_connect_success_total 904
telemt_upstream_connect_attempts_per_request{bucket="1"} 904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 902
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 11354209 (10.83 MB)
telemt_user_octets_to_client{user="hello"} 502975041 (479.67 MB)
telemt_user_msgs_from_client{user="hello"} 17493
telemt_user_msgs_to_client{user="hello"} 117176
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 3496.5 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 857
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 829
telemt_upstream_connect_success_total 826
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 69
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 824
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 23986800 (22.88 MB)
telemt_user_octets_to_client{user="hello"} 420569842 (401.09 MB)
telemt_user_msgs_from_client{user="hello"} 22722
telemt_user_msgs_to_client{user="hello"} 105946
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 3496.9 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2994
telemt_connections_bad_total 635
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2339
telemt_upstream_connect_success_total 2339
telemt_upstream_connect_attempts_per_request{bucket="1"} 2339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2337
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 24107024 (22.99 MB)
telemt_user_octets_to_client{user="hello"} 1844163008 (1.72 GB)
telemt_user_msgs_from_client{user="hello"} 53059
telemt_user_msgs_to_client{user="hello"} 386648
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```