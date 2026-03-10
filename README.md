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

# Server Metrics 2026-03-10 10:13:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 125614.1 (34h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 264123
telemt_connections_bad_total 3451
telemt_handshake_timeouts_total 2728
telemt_upstream_connect_attempt_total 247274
telemt_upstream_connect_success_total 247187
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 247274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 228272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18837
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 247175
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 6130993255 (5.71 GB)
telemt_user_octets_to_client{user="hello"} 148768090885 (138.55 GB)
telemt_user_msgs_from_client{user="hello"} 5970247
telemt_user_msgs_to_client{user="hello"} 9424463
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 125612.9 (34h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79515
telemt_connections_bad_total 3258
telemt_handshake_timeouts_total 1045
telemt_upstream_connect_attempt_total 71153
telemt_upstream_connect_success_total 71110
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 71153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6713
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 400
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 71098
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 2347484898 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 32888144534 (30.63 GB)
telemt_user_msgs_from_client{user="hello"} 1940658
telemt_user_msgs_to_client{user="hello"} 9412149
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 125613.4 (34h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114395
telemt_connections_bad_total 1156
telemt_handshake_timeouts_total 5645
telemt_upstream_connect_attempt_total 81767
telemt_upstream_connect_success_total 81765
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 81767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9299
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 81753
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 6402152400 (5.96 GB)
telemt_user_octets_to_client{user="hello"} 63215416875 (58.87 GB)
telemt_user_msgs_from_client{user="hello"} 4117459
telemt_user_msgs_to_client{user="hello"} 10183496
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 125608.2 (34h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116643
telemt_connections_bad_total 1025
telemt_handshake_timeouts_total 1344
telemt_upstream_connect_attempt_total 108555
telemt_upstream_connect_success_total 108314
telemt_upstream_connect_fail_total 241
telemt_upstream_connect_attempts_per_request{bucket="1"} 108555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 95928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12066
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 61
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 259
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 241
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 108302
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 2969412470 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 79884940050 (74.40 GB)
telemt_user_msgs_from_client{user="hello"} 2770257
telemt_user_msgs_to_client{user="hello"} 18301979
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 125613.6 (34h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176800
telemt_connections_bad_total 27538
telemt_handshake_timeouts_total 4451
telemt_upstream_connect_attempt_total 137375
telemt_upstream_connect_success_total 136562
telemt_upstream_connect_fail_total 813
telemt_upstream_connect_attempts_per_request{bucket="1"} 137375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 813
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 136548
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 2051175168 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 106987480946 (99.64 GB)
telemt_user_msgs_from_client{user="hello"} 2854742
telemt_user_msgs_to_client{user="hello"} 14582128
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 23
```