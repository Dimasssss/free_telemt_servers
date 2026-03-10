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

# Server Metrics 2026-03-10 01:10:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 93048.7 (25h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171930
telemt_connections_bad_total 2327
telemt_handshake_timeouts_total 1725
telemt_upstream_connect_attempt_total 161123
telemt_upstream_connect_success_total 161072
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 161123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 148240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12768
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 161062
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 4881819153 (4.55 GB)
telemt_user_octets_to_client{user="hello"} 98796674997 (92.01 GB)
telemt_user_msgs_from_client{user="hello"} 4366972
telemt_user_msgs_to_client{user="hello"} 6303010
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 93048.5 (25h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53200
telemt_connections_bad_total 3056
telemt_handshake_timeouts_total 794
telemt_upstream_connect_attempt_total 46618
telemt_upstream_connect_success_total 46577
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 46618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4482
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46567
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 2126896846 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 22893463050 (21.32 GB)
telemt_user_msgs_from_client{user="hello"} 1519659
telemt_user_msgs_to_client{user="hello"} 6594070
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 93048.0 (25h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64101
telemt_connections_bad_total 839
telemt_handshake_timeouts_total 3718
telemt_upstream_connect_attempt_total 50628
telemt_upstream_connect_success_total 50626
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 50628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5945
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50616
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 6005023871 (5.59 GB)
telemt_user_octets_to_client{user="hello"} 53926085264 (50.22 GB)
telemt_user_msgs_from_client{user="hello"} 3240473
telemt_user_msgs_to_client{user="hello"} 7784433
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 93042.8 (25h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70600
telemt_connections_bad_total 365
telemt_handshake_timeouts_total 1038
telemt_upstream_connect_attempt_total 65225
telemt_upstream_connect_success_total 65065
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 65225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7883
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 65055
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 2279968358 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 46250462599 (43.07 GB)
telemt_user_msgs_from_client{user="hello"} 1834558
telemt_user_msgs_to_client{user="hello"} 11145592
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 93048.2 (25h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117157
telemt_connections_bad_total 20939
telemt_handshake_timeouts_total 3003
telemt_upstream_connect_attempt_total 88232
telemt_upstream_connect_success_total 88221
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 88232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12760
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 88211
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 1536536242 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 83205478661 (77.49 GB)
telemt_user_msgs_from_client{user="hello"} 2036064
telemt_user_msgs_to_client{user="hello"} 10773796
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 7
```