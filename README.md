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

# Server Metrics 2026-03-10 01:36:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 94582.8 (26h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173786
telemt_connections_bad_total 2331
telemt_handshake_timeouts_total 1728
telemt_upstream_connect_attempt_total 162939
telemt_upstream_connect_success_total 162888
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 162939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 149909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 162878
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 4897069543 (4.56 GB)
telemt_user_octets_to_client{user="hello"} 101487002939 (94.52 GB)
telemt_user_msgs_from_client{user="hello"} 4403133
telemt_user_msgs_to_client{user="hello"} 6398645
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 94581.7 (26h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54036
telemt_connections_bad_total 3056
telemt_handshake_timeouts_total 795
telemt_upstream_connect_attempt_total 47411
telemt_upstream_connect_success_total 47370
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 47411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4650
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47360
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 2130959420 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 23237462526 (21.64 GB)
telemt_user_msgs_from_client{user="hello"} 1529599
telemt_user_msgs_to_client{user="hello"} 6679057
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 94582.3 (26h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64746
telemt_connections_bad_total 840
telemt_handshake_timeouts_total 3725
telemt_upstream_connect_attempt_total 51145
telemt_upstream_connect_success_total 51143
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 51145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6048
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51133
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 6014655953 (5.60 GB)
telemt_user_octets_to_client{user="hello"} 54398637592 (50.66 GB)
telemt_user_msgs_from_client{user="hello"} 3286011
telemt_user_msgs_to_client{user="hello"} 7876034
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 94577.2 (26h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71601
telemt_connections_bad_total 367
telemt_handshake_timeouts_total 1039
telemt_upstream_connect_attempt_total 66182
telemt_upstream_connect_success_total 66022
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 66182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7983
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 162
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 66012
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 2284276308 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 46602037964 (43.40 GB)
telemt_user_msgs_from_client{user="hello"} 1844894
telemt_user_msgs_to_client{user="hello"} 11202251
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 94582.5 (26h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118772
telemt_connections_bad_total 21215
telemt_handshake_timeouts_total 3004
telemt_upstream_connect_attempt_total 89526
telemt_upstream_connect_success_total 89514
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 89526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13003
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 89504
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 1547081904 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 83413429761 (77.68 GB)
telemt_user_msgs_from_client{user="hello"} 2057680
telemt_user_msgs_to_client{user="hello"} 10823575
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 11
```