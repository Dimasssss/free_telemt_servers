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

# Server Metrics 2026-03-04 09:24:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 3703.0 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6643
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 112
telemt_upstream_connect_attempt_total 5792
telemt_upstream_connect_success_total 5792
telemt_upstream_connect_attempts_per_request{bucket="1"} 5792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5790
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 74007519 (70.58 MB)
telemt_user_octets_to_client{user="hello"} 2720522669 (2.53 GB)
telemt_user_msgs_from_client{user="hello"} 116358
telemt_user_msgs_to_client{user="hello"} 469852
telemt_user_unique_ips_current{user="hello"} 7
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 3714.4 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 602
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 562
telemt_upstream_connect_success_total 562
telemt_upstream_connect_attempts_per_request{bucket="1"} 562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 560
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 12554214 (11.97 MB)
telemt_user_octets_to_client{user="hello"} 233226963 (222.42 MB)
telemt_user_msgs_from_client{user="hello"} 17078
telemt_user_msgs_to_client{user="hello"} 71692
telemt_user_unique_ips_current{user="hello"} 4
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 3699.1 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 569
telemt_connections_bad_total 56
telemt_upstream_connect_attempt_total 496
telemt_upstream_connect_success_total 496
telemt_upstream_connect_attempts_per_request{bucket="1"} 496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 494
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 7271903 (6.94 MB)
telemt_user_octets_to_client{user="hello"} 967730077 (922.90 MB)
telemt_user_msgs_from_client{user="hello"} 20388
telemt_user_msgs_to_client{user="hello"} 164949
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 3689.5 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1053
telemt_connections_bad_total 28
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 953
telemt_upstream_connect_success_total 953
telemt_upstream_connect_attempts_per_request{bucket="1"} 953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 951
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 4678315 (4.46 MB)
telemt_user_octets_to_client{user="hello"} 175155902 (167.04 MB)
telemt_user_msgs_from_client{user="hello"} 9220
telemt_user_msgs_to_client{user="hello"} 53506
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 3700.9 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1427
telemt_connections_bad_total 650
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 728
telemt_upstream_connect_success_total 728
telemt_upstream_connect_attempts_per_request{bucket="1"} 728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 120
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 726
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 10210428 (9.74 MB)
telemt_user_octets_to_client{user="hello"} 373088061 (355.80 MB)
telemt_user_msgs_from_client{user="hello"} 23209
telemt_user_msgs_to_client{user="hello"} 97743
```