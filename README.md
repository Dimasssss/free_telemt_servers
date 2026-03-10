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

# Server Metrics 2026-03-10 13:48:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 138510.3 (38h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 316430
telemt_connections_bad_total 3484
telemt_handshake_timeouts_total 3340
telemt_upstream_connect_attempt_total 296346
telemt_upstream_connect_success_total 296187
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 296346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 273891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22195
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 296173
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 6821853219 (6.35 GB)
telemt_user_octets_to_client{user="hello"} 195241538341 (181.83 GB)
telemt_user_msgs_from_client{user="hello"} 7095222
telemt_user_msgs_to_client{user="hello"} 11584075
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 138509.0 (38h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97694
telemt_connections_bad_total 3275
telemt_handshake_timeouts_total 1299
telemt_upstream_connect_attempt_total 88128
telemt_upstream_connect_success_total 88084
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 88128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8414
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 88070
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 2822547162 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 37675975259 (35.09 GB)
telemt_user_msgs_from_client{user="hello"} 2306028
telemt_user_msgs_to_client{user="hello"} 10896599
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 138509.5 (38h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139437
telemt_connections_bad_total 1237
telemt_handshake_timeouts_total 6489
telemt_upstream_connect_attempt_total 104632
telemt_upstream_connect_success_total 104629
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 104632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11993
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 104615
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 6670389672 (6.21 GB)
telemt_user_octets_to_client{user="hello"} 68955955217 (64.22 GB)
telemt_user_msgs_from_client{user="hello"} 4539593
telemt_user_msgs_to_client{user="hello"} 11684154
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 138504.3 (38h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143511
telemt_connections_bad_total 1063
telemt_handshake_timeouts_total 2967
telemt_upstream_connect_attempt_total 132630
telemt_upstream_connect_success_total 132331
telemt_upstream_connect_fail_total 299
telemt_upstream_connect_attempts_per_request{bucket="1"} 132630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14338
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 82
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 299
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 132317
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 5036524064 (4.69 GB)
telemt_user_octets_to_client{user="hello"} 93924448937 (87.47 GB)
telemt_user_msgs_from_client{user="hello"} 3870910
telemt_user_msgs_to_client{user="hello"} 21258587
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 138509.6 (38h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212767
telemt_connections_bad_total 31009
telemt_handshake_timeouts_total 5901
telemt_upstream_connect_attempt_total 167001
telemt_upstream_connect_success_total 166039
telemt_upstream_connect_fail_total 962
telemt_upstream_connect_attempts_per_request{bucket="1"} 167001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 143693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 962
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 166025
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 3533221188 (3.29 GB)
telemt_user_octets_to_client{user="hello"} 118972445358 (110.80 GB)
telemt_user_msgs_from_client{user="hello"} 3779813
telemt_user_msgs_to_client{user="hello"} 16300004
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 23
```