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

# Server Metrics 2026-03-06 05:04:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 24552.7 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76070
telemt_connections_bad_total 51936
telemt_handshake_timeouts_total 2442
telemt_upstream_connect_attempt_total 20181
telemt_upstream_connect_success_total 20178
telemt_upstream_connect_attempts_per_request{bucket="1"} 20175
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1231
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20174
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 263137708 (250.95 MB)
telemt_user_octets_to_client{user="hello"} 17696401941 (16.48 GB)
telemt_user_msgs_from_client{user="hello"} 488102
telemt_user_msgs_to_client{user="hello"} 2645471
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 24550.7 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2648
telemt_connections_bad_total 142
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 2458
telemt_upstream_connect_success_total 2457
telemt_upstream_connect_attempts_per_request{bucket="1"} 2456
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 95
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2455
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 55565281 (52.99 MB)
telemt_user_octets_to_client{user="hello"} 1152602520 (1.07 GB)
telemt_user_msgs_from_client{user="hello"} 77379
telemt_user_msgs_to_client{user="hello"} 362330
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 24551.0 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1595
telemt_connections_bad_total 214
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1367
telemt_upstream_connect_success_total 1367
telemt_upstream_connect_attempts_per_request{bucket="1"} 1367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 165
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1363
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 37710448 (35.96 MB)
telemt_user_octets_to_client{user="hello"} 1794170074 (1.67 GB)
telemt_user_msgs_from_client{user="hello"} 48940
telemt_user_msgs_to_client{user="hello"} 362042
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 24553.7 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3242
telemt_connections_bad_total 134
telemt_handshake_timeouts_total 303
telemt_upstream_connect_attempt_total 2723
telemt_upstream_connect_success_total 2723
telemt_upstream_connect_attempts_per_request{bucket="1"} 2723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 393
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2719
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 96439364 (91.97 MB)
telemt_user_octets_to_client{user="hello"} 5700220097 (5.31 GB)
telemt_user_msgs_from_client{user="hello"} 136891
telemt_user_msgs_to_client{user="hello"} 1201586
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 24553.6 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8308
telemt_connections_bad_total 4463
telemt_handshake_timeouts_total 154
telemt_upstream_connect_attempt_total 3588
telemt_upstream_connect_success_total 3588
telemt_upstream_connect_attempts_per_request{bucket="1"} 3588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3584
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 76881254 (73.32 MB)
telemt_user_octets_to_client{user="hello"} 15875153429 (14.78 GB)
telemt_user_msgs_from_client{user="hello"} 196958
telemt_user_msgs_to_client{user="hello"} 3023339
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```