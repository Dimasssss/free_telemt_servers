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

# Server Metrics 2026-03-06 05:25:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 25783.6 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77723
telemt_connections_bad_total 51936
telemt_handshake_timeouts_total 2444
telemt_upstream_connect_attempt_total 21808
telemt_upstream_connect_success_total 21805
telemt_upstream_connect_attempts_per_request{bucket="1"} 21802
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1334
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21801
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 287742163 (274.41 MB)
telemt_user_octets_to_client{user="hello"} 18875202270 (17.58 GB)
telemt_user_msgs_from_client{user="hello"} 532175
telemt_user_msgs_to_client{user="hello"} 2842207
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 25781.7 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2869
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 2674
telemt_upstream_connect_success_total 2673
telemt_upstream_connect_attempts_per_request{bucket="1"} 2672
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2671
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 58067944 (55.38 MB)
telemt_user_octets_to_client{user="hello"} 1223500501 (1.14 GB)
telemt_user_msgs_from_client{user="hello"} 81714
telemt_user_msgs_to_client{user="hello"} 389625
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 25782.0 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1754
telemt_connections_bad_total 214
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 1521
telemt_upstream_connect_success_total 1521
telemt_upstream_connect_attempts_per_request{bucket="1"} 1521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 167
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1517
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 39477064 (37.65 MB)
telemt_user_octets_to_client{user="hello"} 1949126306 (1.82 GB)
telemt_user_msgs_from_client{user="hello"} 53519
telemt_user_msgs_to_client{user="hello"} 395741
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 25784.8 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3639
telemt_connections_bad_total 137
telemt_handshake_timeouts_total 309
telemt_upstream_connect_attempt_total 3065
telemt_upstream_connect_success_total 3065
telemt_upstream_connect_attempts_per_request{bucket="1"} 3065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 399
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3061
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 97373090 (92.86 MB)
telemt_user_octets_to_client{user="hello"} 5727385499 (5.33 GB)
telemt_user_msgs_from_client{user="hello"} 139086
telemt_user_msgs_to_client{user="hello"} 1211334
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 25784.6 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8721
telemt_connections_bad_total 4684
telemt_handshake_timeouts_total 156
telemt_upstream_connect_attempt_total 3777
telemt_upstream_connect_success_total 3777
telemt_upstream_connect_attempts_per_request{bucket="1"} 3777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3773
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 78090316 (74.47 MB)
telemt_user_octets_to_client{user="hello"} 15936933124 (14.84 GB)
telemt_user_msgs_from_client{user="hello"} 199700
telemt_user_msgs_to_client{user="hello"} 3037000
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```