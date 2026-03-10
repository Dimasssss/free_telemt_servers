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

# Server Metrics 2026-03-10 00:55:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 92128.1 (25h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170889
telemt_connections_bad_total 2326
telemt_handshake_timeouts_total 1707
telemt_upstream_connect_attempt_total 160118
telemt_upstream_connect_success_total 160068
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 160118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 147295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 160058
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 4874817825 (4.54 GB)
telemt_user_octets_to_client{user="hello"} 97711059117 (91.00 GB)
telemt_user_msgs_from_client{user="hello"} 4348677
telemt_user_msgs_to_client{user="hello"} 6241397
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 92127.1 (25h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52768
telemt_connections_bad_total 3055
telemt_handshake_timeouts_total 730
telemt_upstream_connect_attempt_total 46277
telemt_upstream_connect_success_total 46236
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 46277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4411
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46226
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 2124734972 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 22850417403 (21.28 GB)
telemt_user_msgs_from_client{user="hello"} 1514371
telemt_user_msgs_to_client{user="hello"} 6575074
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 92127.7 (25h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63819
telemt_connections_bad_total 838
telemt_handshake_timeouts_total 3698
telemt_upstream_connect_attempt_total 50416
telemt_upstream_connect_success_total 50414
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 50416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50404
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 5999912345 (5.59 GB)
telemt_user_octets_to_client{user="hello"} 53879354117 (50.18 GB)
telemt_user_msgs_from_client{user="hello"} 3215806
telemt_user_msgs_to_client{user="hello"} 7739973
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 92122.3 (25h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70011
telemt_connections_bad_total 364
telemt_handshake_timeouts_total 1036
telemt_upstream_connect_attempt_total 64655
telemt_upstream_connect_success_total 64495
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 64655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7839
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 64485
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 2269484104 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 45832684403 (42.69 GB)
telemt_user_msgs_from_client{user="hello"} 1822451
telemt_user_msgs_to_client{user="hello"} 11070846
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 92127.9 (25h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116337
telemt_connections_bad_total 20772
telemt_handshake_timeouts_total 3003
telemt_upstream_connect_attempt_total 87593
telemt_upstream_connect_success_total 87582
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 87593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12711
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 87572
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 1533855864 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 83173053113 (77.46 GB)
telemt_user_msgs_from_client{user="hello"} 2029743
telemt_user_msgs_to_client{user="hello"} 10761857
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 10
```