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

# Server Metrics 2026-03-08 23:03:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 57263.2 (15h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119598
telemt_connections_bad_total 5801
telemt_handshake_timeouts_total 1282
telemt_upstream_connect_attempt_total 108650
telemt_upstream_connect_success_total 108612
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 108650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 101966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6577
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 108606
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 2620665729 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 76974700387 (71.69 GB)
telemt_user_msgs_from_client{user="hello"} 2735089
telemt_user_msgs_to_client{user="hello"} 4123387
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 57262.2 (15h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27617
telemt_connections_bad_total 320
telemt_handshake_timeouts_total 131
telemt_upstream_connect_attempt_total 26692
telemt_upstream_connect_success_total 26685
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 26692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1671
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26679
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 841977262 (802.97 MB)
telemt_user_octets_to_client{user="hello"} 22927495176 (21.35 GB)
telemt_user_msgs_from_client{user="hello"} 987656
telemt_user_msgs_to_client{user="hello"} 6210573
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 57262.0 (15h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15720
telemt_connections_bad_total 252
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 14283
telemt_upstream_connect_success_total 14207
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 14283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1080
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14201
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 1576144805 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 5709663648 (5.32 GB)
telemt_user_msgs_from_client{user="hello"} 706811
telemt_user_msgs_to_client{user="hello"} 983850
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 57261.8 (15h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21621
telemt_connections_bad_total 225
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 20737
telemt_upstream_connect_success_total 20696
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 20737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1578
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20690
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 1068902242 (1019.38 MB)
telemt_user_octets_to_client{user="hello"} 6653312412 (6.20 GB)
telemt_user_msgs_from_client{user="hello"} 578726
telemt_user_msgs_to_client{user="hello"} 1517758
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 57262.1 (15h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32664
telemt_connections_bad_total 10878
telemt_handshake_timeouts_total 241
telemt_upstream_connect_attempt_total 21028
telemt_upstream_connect_success_total 21021
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 21028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3474
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21015
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 388643906 (370.64 MB)
telemt_user_octets_to_client{user="hello"} 18312151411 (17.05 GB)
telemt_user_msgs_from_client{user="hello"} 561145
telemt_user_msgs_to_client{user="hello"} 2365037
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```