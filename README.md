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

# Server Metrics 2026-03-08 08:29:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 4856.2 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9934
telemt_connections_bad_total 1116
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 8355
telemt_upstream_connect_success_total 8350
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 8355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8348
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 242763132 (231.52 MB)
telemt_user_octets_to_client{user="hello"} 5531082514 (5.15 GB)
telemt_user_msgs_from_client{user="hello"} 199102
telemt_user_msgs_to_client{user="hello"} 267839
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 4855.5 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2174
telemt_connections_bad_total 46
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2053
telemt_upstream_connect_success_total 2053
telemt_upstream_connect_attempts_per_request{bucket="1"} 2053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 128
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2051
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 25742818 (24.55 MB)
telemt_user_octets_to_client{user="hello"} 1181072112 (1.10 GB)
telemt_user_msgs_from_client{user="hello"} 44100
telemt_user_msgs_to_client{user="hello"} 279174
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 4855.1 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1869
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1826
telemt_upstream_connect_success_total 1826
telemt_upstream_connect_attempts_per_request{bucket="1"} 1826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 176
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1824
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 24520547 (23.38 MB)
telemt_user_octets_to_client{user="hello"} 421463236 (401.94 MB)
telemt_user_msgs_from_client{user="hello"} 17390
telemt_user_msgs_to_client{user="hello"} 73690
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 4855.1 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1809
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 1744
telemt_upstream_connect_success_total 1741
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 1744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1739
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 39997015 (38.14 MB)
telemt_user_octets_to_client{user="hello"} 459655354 (438.36 MB)
telemt_user_msgs_from_client{user="hello"} 26848
telemt_user_msgs_to_client{user="hello"} 129060
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 4855.3 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3138
telemt_connections_bad_total 870
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2239
telemt_upstream_connect_success_total 2239
telemt_upstream_connect_attempts_per_request{bucket="1"} 2239
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 423
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2237
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 21741813 (20.73 MB)
telemt_user_octets_to_client{user="hello"} 606423962 (578.33 MB)
telemt_user_msgs_from_client{user="hello"} 33168
telemt_user_msgs_to_client{user="hello"} 111343
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```