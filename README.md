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

# Server Metrics 2026-03-10 11:35:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 130523.8 (36h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283888
telemt_connections_bad_total 3460
telemt_handshake_timeouts_total 3043
telemt_upstream_connect_attempt_total 265353
telemt_upstream_connect_success_total 265205
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 265353
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 245025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20094
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 265193
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 6382165343 (5.94 GB)
telemt_user_octets_to_client{user="hello"} 167770235342 (156.25 GB)
telemt_user_msgs_from_client{user="hello"} 6414511
telemt_user_msgs_to_client{user="hello"} 10280044
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 130522.5 (36h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86664
telemt_connections_bad_total 3269
telemt_handshake_timeouts_total 1227
telemt_upstream_connect_attempt_total 77646
telemt_upstream_connect_success_total 77602
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 77646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7333
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 413
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 77588
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 2710519523 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 34271864532 (31.92 GB)
telemt_user_msgs_from_client{user="hello"} 2131718
telemt_user_msgs_to_client{user="hello"} 9861185
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 130522.9 (36h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122922
telemt_connections_bad_total 1199
telemt_handshake_timeouts_total 6231
telemt_upstream_connect_attempt_total 89215
telemt_upstream_connect_success_total 89213
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 89215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10360
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 89201
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 6456162153 (6.01 GB)
telemt_user_octets_to_client{user="hello"} 64954917176 (60.49 GB)
telemt_user_msgs_from_client{user="hello"} 4250687
telemt_user_msgs_to_client{user="hello"} 10715423
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 130517.8 (36h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125553
telemt_connections_bad_total 1036
telemt_handshake_timeouts_total 1378
telemt_upstream_connect_attempt_total 117080
telemt_upstream_connect_success_total 116829
telemt_upstream_connect_fail_total 251
telemt_upstream_connect_attempts_per_request{bucket="1"} 117080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 103553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12923
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 71
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 282
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 251
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 116817
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 3137314178 (2.92 GB)
telemt_user_octets_to_client{user="hello"} 82050561203 (76.42 GB)
telemt_user_msgs_from_client{user="hello"} 2938739
telemt_user_msgs_to_client{user="hello"} 18857358
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 130523.2 (36h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190556
telemt_connections_bad_total 28422
telemt_handshake_timeouts_total 4875
telemt_upstream_connect_attempt_total 149178
telemt_upstream_connect_success_total 148217
telemt_upstream_connect_fail_total 961
telemt_upstream_connect_attempts_per_request{bucket="1"} 149178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 128161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19847
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 209
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 961
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 148203
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 3331066313 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 111380690583 (103.73 GB)
telemt_user_msgs_from_client{user="hello"} 3443619
telemt_user_msgs_to_client{user="hello"} 15158009
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 19
```