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

# Server Metrics 2026-03-07 17:20:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 2149.3 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4900
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 37
telemt_upstream_connect_attempt_total 4652
telemt_upstream_connect_success_total 4651
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 276
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4649
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 57431126 (54.77 MB)
telemt_user_octets_to_client{user="hello"} 1863161049 (1.74 GB)
telemt_user_msgs_from_client{user="hello"} 88903
telemt_user_msgs_to_client{user="hello"} 309982
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 2148.4 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1081
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 1054
telemt_upstream_connect_success_total 1053
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 69
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1051
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 20237306 (19.30 MB)
telemt_user_octets_to_client{user="hello"} 928095159 (885.10 MB)
telemt_user_msgs_from_client{user="hello"} 33032
telemt_user_msgs_to_client{user="hello"} 274524
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 2148.1 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 337
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 334
telemt_upstream_connect_success_total 334
telemt_upstream_connect_attempts_per_request{bucket="1"} 334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 332
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 2161390 (2.06 MB)
telemt_user_octets_to_client{user="hello"} 164431492 (156.81 MB)
telemt_user_msgs_from_client{user="hello"} 5686
telemt_user_msgs_to_client{user="hello"} 34525
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 1976.4 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 619
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 600
telemt_upstream_connect_success_total 599
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 57
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 597
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 9528862 (9.09 MB)
telemt_user_octets_to_client{user="hello"} 211997797 (202.18 MB)
telemt_user_msgs_from_client{user="hello"} 8938
telemt_user_msgs_to_client{user="hello"} 54714
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 2148.3 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1330
telemt_connections_bad_total 392
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 899
telemt_upstream_connect_success_total 899
telemt_upstream_connect_attempts_per_request{bucket="1"} 899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 276
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 897
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 17122689 (16.33 MB)
telemt_user_octets_to_client{user="hello"} 410418140 (391.41 MB)
telemt_user_msgs_from_client{user="hello"} 24995
telemt_user_msgs_to_client{user="hello"} 95650
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 3
```