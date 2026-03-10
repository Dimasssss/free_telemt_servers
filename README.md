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

# Server Metrics 2026-03-10 13:07:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 136052.1 (37h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 306472
telemt_connections_bad_total 3470
telemt_handshake_timeouts_total 3121
telemt_upstream_connect_attempt_total 287117
telemt_upstream_connect_success_total 286963
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 287117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 265390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21483
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 286949
telemt_user_connections_current{user="hello"} 318
telemt_user_octets_from_client{user="hello"} 6712957726 (6.25 GB)
telemt_user_octets_to_client{user="hello"} 190353672929 (177.28 GB)
telemt_user_msgs_from_client{user="hello"} 6921876
telemt_user_msgs_to_client{user="hello"} 11260417
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 136051.1 (37h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94468
telemt_connections_bad_total 3271
telemt_handshake_timeouts_total 1278
telemt_upstream_connect_attempt_total 85049
telemt_upstream_connect_success_total 85005
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 85049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8134
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 425
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 84991
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 2795866797 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 35754929913 (33.30 GB)
telemt_user_msgs_from_client{user="hello"} 2251164
telemt_user_msgs_to_client{user="hello"} 10375597
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 136051.5 (37h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134047
telemt_connections_bad_total 1227
telemt_handshake_timeouts_total 6367
telemt_upstream_connect_attempt_total 99634
telemt_upstream_connect_success_total 99631
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 99634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11321
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 99617
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 6639582774 (6.18 GB)
telemt_user_octets_to_client{user="hello"} 67582472561 (62.94 GB)
telemt_user_msgs_from_client{user="hello"} 4447046
telemt_user_msgs_to_client{user="hello"} 11326327
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 136046.3 (37h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139101
telemt_connections_bad_total 1056
telemt_handshake_timeouts_total 2919
telemt_upstream_connect_attempt_total 128379
telemt_upstream_connect_success_total 128096
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 128379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 113739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13952
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 81
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 324
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 128082
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 4708199342 (4.38 GB)
telemt_user_octets_to_client{user="hello"} 88516334340 (82.44 GB)
telemt_user_msgs_from_client{user="hello"} 3661021
telemt_user_msgs_to_client{user="hello"} 20178479
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 136051.7 (37h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205145
telemt_connections_bad_total 30407
telemt_handshake_timeouts_total 5574
telemt_upstream_connect_attempt_total 160591
telemt_upstream_connect_success_total 159629
telemt_upstream_connect_fail_total 962
telemt_upstream_connect_attempts_per_request{bucket="1"} 160591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 138231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21177
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 962
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 159615
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 3473417065 (3.23 GB)
telemt_user_octets_to_client{user="hello"} 117024735321 (108.99 GB)
telemt_user_msgs_from_client{user="hello"} 3683022
telemt_user_msgs_to_client{user="hello"} 15946038
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 26
```