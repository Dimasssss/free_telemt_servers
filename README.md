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

# Server Metrics 2026-03-09 16:18:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 61138.5 (16h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111880
telemt_connections_bad_total 1656
telemt_handshake_timeouts_total 972
telemt_upstream_connect_attempt_total 104629
telemt_upstream_connect_success_total 104590
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 104629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7969
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 104584
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 2764616943 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 54881373164 (51.11 GB)
telemt_user_msgs_from_client{user="hello"} 2573439
telemt_user_msgs_to_client{user="hello"} 3648479
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 61137.3 (16h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29218
telemt_connections_bad_total 220
telemt_handshake_timeouts_total 348
telemt_upstream_connect_attempt_total 27544
telemt_upstream_connect_success_total 27527
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 27544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2245
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27521
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 983890137 (938.31 MB)
telemt_user_octets_to_client{user="hello"} 15487640449 (14.42 GB)
telemt_user_msgs_from_client{user="hello"} 821442
telemt_user_msgs_to_client{user="hello"} 4257157
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 61138.3 (16h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36741
telemt_connections_bad_total 655
telemt_handshake_timeouts_total 1644
telemt_upstream_connect_attempt_total 27595
telemt_upstream_connect_success_total 27595
telemt_upstream_connect_attempts_per_request{bucket="1"} 27595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2892
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27589
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 4410003301 (4.11 GB)
telemt_user_octets_to_client{user="hello"} 17537765708 (16.33 GB)
telemt_user_msgs_from_client{user="hello"} 1935547
telemt_user_msgs_to_client{user="hello"} 2314639
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 61132.5 (16h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41859
telemt_connections_bad_total 197
telemt_handshake_timeouts_total 865
telemt_upstream_connect_attempt_total 38413
telemt_upstream_connect_success_total 38317
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 38413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5415
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38311
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 1936194377 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 30043533934 (27.98 GB)
telemt_user_msgs_from_client{user="hello"} 1251833
telemt_user_msgs_to_client{user="hello"} 7709046
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 61138.1 (16h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69796
telemt_connections_bad_total 14922
telemt_handshake_timeouts_total 1590
telemt_upstream_connect_attempt_total 50056
telemt_upstream_connect_success_total 50054
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 50056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7741
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50048
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 837008646 (798.23 MB)
telemt_user_octets_to_client{user="hello"} 52525771973 (48.92 GB)
telemt_user_msgs_from_client{user="hello"} 1160849
telemt_user_msgs_to_client{user="hello"} 6440822
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 16
```