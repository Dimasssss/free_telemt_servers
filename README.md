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

# Server Metrics 2026-03-06 06:26:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 29478.4 (8h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83139
telemt_connections_bad_total 51942
telemt_handshake_timeouts_total 2472
telemt_upstream_connect_attempt_total 26933
telemt_upstream_connect_success_total 26929
telemt_upstream_connect_attempts_per_request{bucket="1"} 26925
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1681
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26925
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 389446394 (371.41 MB)
telemt_user_octets_to_client{user="hello"} 23019840524 (21.44 GB)
telemt_user_msgs_from_client{user="hello"} 677374
telemt_user_msgs_to_client{user="hello"} 3497559
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 29475.8 (8h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3527
telemt_connections_bad_total 150
telemt_handshake_timeouts_total 19
telemt_upstream_connect_attempt_total 3316
telemt_upstream_connect_success_total 3315
telemt_upstream_connect_attempts_per_request{bucket="1"} 3314
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3311
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 69455460 (66.24 MB)
telemt_user_octets_to_client{user="hello"} 1417275917 (1.32 GB)
telemt_user_msgs_from_client{user="hello"} 96755
telemt_user_msgs_to_client{user="hello"} 453772
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 29476.1 (8h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2796
telemt_connections_bad_total 223
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 2543
telemt_upstream_connect_success_total 2543
telemt_upstream_connect_attempts_per_request{bucket="1"} 2543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 231
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2539
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 59057724 (56.32 MB)
telemt_user_octets_to_client{user="hello"} 2722523027 (2.54 GB)
telemt_user_msgs_from_client{user="hello"} 85958
telemt_user_msgs_to_client{user="hello"} 582371
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 29478.9 (8h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5321
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 311
telemt_upstream_connect_attempt_total 4592
telemt_upstream_connect_success_total 4591
telemt_upstream_connect_attempts_per_request{bucket="1"} 4590
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 488
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4587
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 108166178 (103.16 MB)
telemt_user_octets_to_client{user="hello"} 7122815060 (6.63 GB)
telemt_user_msgs_from_client{user="hello"} 167089
telemt_user_msgs_to_client{user="hello"} 1524785
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 29478.7 (8h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10063
telemt_connections_bad_total 5392
telemt_handshake_timeouts_total 165
telemt_upstream_connect_attempt_total 4390
telemt_upstream_connect_success_total 4390
telemt_upstream_connect_attempts_per_request{bucket="1"} 4390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 622
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4386
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 97751188 (93.22 MB)
telemt_user_octets_to_client{user="hello"} 19983161688 (18.61 GB)
telemt_user_msgs_from_client{user="hello"} 247425
telemt_user_msgs_to_client{user="hello"} 3745295
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```