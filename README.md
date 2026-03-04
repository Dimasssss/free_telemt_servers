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

# Server Metrics 2026-03-04 14:12:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 9914.8 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16267
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 523
telemt_upstream_connect_attempt_total 15321
telemt_upstream_connect_success_total 15318
telemt_upstream_connect_attempts_per_request{bucket="1"} 15315
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14624
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 688
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15316
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 435031794 (414.88 MB)
telemt_user_octets_to_client{user="hello"} 14053023891 (13.09 GB)
telemt_user_msgs_from_client{user="hello"} 483915
telemt_user_msgs_to_client{user="hello"} 2214001
telemt_user_unique_ips_current{user="hello"} 11
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 9917.2 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3541
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 3305
telemt_upstream_connect_success_total 3304
telemt_upstream_connect_attempts_per_request{bucket="1"} 3303
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3302
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 196620552 (187.51 MB)
telemt_user_octets_to_client{user="hello"} 3558288446 (3.31 GB)
telemt_user_msgs_from_client{user="hello"} 145842
telemt_user_msgs_to_client{user="hello"} 1130681
telemt_user_unique_ips_current{user="hello"} 4
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 9915.5 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1657
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 1601
telemt_upstream_connect_success_total 1601
telemt_upstream_connect_attempts_per_request{bucket="1"} 1601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 77
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1599
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 65998925 (62.94 MB)
telemt_user_octets_to_client{user="hello"} 713685531 (680.62 MB)
telemt_user_msgs_from_client{user="hello"} 62518
telemt_user_msgs_to_client{user="hello"} 177830
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 9913.5 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3920
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 31
telemt_upstream_connect_attempt_total 3583
telemt_upstream_connect_success_total 3581
telemt_upstream_connect_attempts_per_request{bucket="1"} 3579
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 270
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3579
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 29171500 (27.82 MB)
telemt_user_octets_to_client{user="hello"} 2828931839 (2.63 GB)
telemt_user_msgs_from_client{user="hello"} 63700
telemt_user_msgs_to_client{user="hello"} 626467
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 9915.2 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4317
telemt_connections_bad_total 1781
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 2392
telemt_upstream_connect_success_total 2391
telemt_upstream_connect_attempts_per_request{bucket="1"} 2390
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 342
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2389
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 45964487 (43.84 MB)
telemt_user_octets_to_client{user="hello"} 6824537301 (6.36 GB)
telemt_user_msgs_from_client{user="hello"} 110165
telemt_user_msgs_to_client{user="hello"} 1242838
telemt_user_unique_ips_current{user="hello"} 1
```