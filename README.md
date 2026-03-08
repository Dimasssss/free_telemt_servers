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

# Server Metrics 2026-03-08 04:13:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 41270.4 (11h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58813
telemt_connections_bad_total 5991
telemt_handshake_timeouts_total 424
telemt_upstream_connect_attempt_total 49707
telemt_upstream_connect_success_total 49700
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 49707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2545
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49696
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 2384045274 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 33087225461 (30.81 GB)
telemt_user_msgs_from_client{user="hello"} 1543848
telemt_user_msgs_to_client{user="hello"} 5180028
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 41269.6 (11h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8070
telemt_connections_bad_total 367
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 7565
telemt_upstream_connect_success_total 7557
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 7565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 617
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7551
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 190996327 (182.15 MB)
telemt_user_octets_to_client{user="hello"} 10806602962 (10.06 GB)
telemt_user_msgs_from_client{user="hello"} 346783
telemt_user_msgs_to_client{user="hello"} 2524735
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 41269.5 (11h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5007
telemt_connections_bad_total 258
telemt_handshake_timeouts_total 54
telemt_upstream_connect_attempt_total 4615
telemt_upstream_connect_success_total 4615
telemt_upstream_connect_attempts_per_request{bucket="1"} 4615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4611
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 124611351 (118.84 MB)
telemt_user_octets_to_client{user="hello"} 14478666881 (13.48 GB)
telemt_user_msgs_from_client{user="hello"} 227179
telemt_user_msgs_to_client{user="hello"} 3073696
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 41097.8 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13629
telemt_connections_bad_total 212
telemt_handshake_timeouts_total 49
telemt_upstream_connect_attempt_total 13076
telemt_upstream_connect_success_total 13050
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 13076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10910
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2070
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13046
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 349353957 (333.17 MB)
telemt_user_octets_to_client{user="hello"} 11540137231 (10.75 GB)
telemt_user_msgs_from_client{user="hello"} 374981
telemt_user_msgs_to_client{user="hello"} 3334416
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 41269.7 (11h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16313
telemt_connections_bad_total 7588
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 8472
telemt_upstream_connect_success_total 8464
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 8472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1778
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8460
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 1622766976 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 7822362053 (7.29 GB)
telemt_user_msgs_from_client{user="hello"} 810498
telemt_user_msgs_to_client{user="hello"} 1758611
telemt_user_unique_ips_current{user="hello"} 4
```