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

# Server Metrics 2026-03-10 13:22:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 136974.0 (38h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 310449
telemt_connections_bad_total 3472
telemt_handshake_timeouts_total 3222
telemt_upstream_connect_attempt_total 290799
telemt_upstream_connect_success_total 290642
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 290799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 268828
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21723
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 290628
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 6750947614 (6.29 GB)
telemt_user_octets_to_client{user="hello"} 192257447163 (179.05 GB)
telemt_user_msgs_from_client{user="hello"} 6995809
telemt_user_msgs_to_client{user="hello"} 11385086
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 136972.7 (38h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95707
telemt_connections_bad_total 3273
telemt_handshake_timeouts_total 1284
telemt_upstream_connect_attempt_total 86237
telemt_upstream_connect_success_total 86193
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 86237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8225
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 427
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 86179
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 2810402772 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 36674079217 (34.16 GB)
telemt_user_msgs_from_client{user="hello"} 2277320
telemt_user_msgs_to_client{user="hello"} 10606596
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 136973.1 (38h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135916
telemt_connections_bad_total 1229
telemt_handshake_timeouts_total 6428
telemt_upstream_connect_attempt_total 101327
telemt_upstream_connect_success_total 101324
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 101327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 89736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 101310
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 6654467868 (6.20 GB)
telemt_user_octets_to_client{user="hello"} 68542598050 (63.84 GB)
telemt_user_msgs_from_client{user="hello"} 4490976
telemt_user_msgs_to_client{user="hello"} 11539296
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 136967.9 (38h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140944
telemt_connections_bad_total 1060
telemt_handshake_timeouts_total 2931
telemt_upstream_connect_attempt_total 130160
telemt_upstream_connect_success_total 129869
telemt_upstream_connect_fail_total 291
telemt_upstream_connect_attempts_per_request{bucket="1"} 130160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 115365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14093
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 82
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 329
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 291
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 129855
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 4915138669 (4.58 GB)
telemt_user_octets_to_client{user="hello"} 90190870300 (84.00 GB)
telemt_user_msgs_from_client{user="hello"} 3772550
telemt_user_msgs_to_client{user="hello"} 20439506
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 136973.3 (38h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207726
telemt_connections_bad_total 30573
telemt_handshake_timeouts_total 5639
telemt_upstream_connect_attempt_total 162789
telemt_upstream_connect_success_total 161827
telemt_upstream_connect_fail_total 962
telemt_upstream_connect_attempts_per_request{bucket="1"} 162789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 140087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21519
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 962
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 161813
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 3489512497 (3.25 GB)
telemt_user_octets_to_client{user="hello"} 117695611555 (109.61 GB)
telemt_user_msgs_from_client{user="hello"} 3716611
telemt_user_msgs_to_client{user="hello"} 16075160
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 23
```