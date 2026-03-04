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

# Server Metrics 2026-03-04 10:05:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 6165.9 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10911
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 176
telemt_upstream_connect_attempt_total 9751
telemt_upstream_connect_success_total 9751
telemt_upstream_connect_attempts_per_request{bucket="1"} 9751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 631
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9749
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 129068053 (123.09 MB)
telemt_user_octets_to_client{user="hello"} 4777224630 (4.45 GB)
telemt_user_msgs_from_client{user="hello"} 210717
telemt_user_msgs_to_client{user="hello"} 809542
telemt_user_unique_ips_current{user="hello"} 9
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 6176.9 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1363
telemt_connections_bad_total 40
telemt_handshake_timeouts_total 32
telemt_upstream_connect_attempt_total 1242
telemt_upstream_connect_success_total 1242
telemt_upstream_connect_attempts_per_request{bucket="1"} 1242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1240
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 52911328 (50.46 MB)
telemt_user_octets_to_client{user="hello"} 663056315 (632.34 MB)
telemt_user_msgs_from_client{user="hello"} 46393
telemt_user_msgs_to_client{user="hello"} 198862
telemt_user_unique_ips_current{user="hello"} 1
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 6161.6 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1205
telemt_connections_bad_total 67
telemt_upstream_connect_attempt_total 1116
telemt_upstream_connect_success_total 1116
telemt_upstream_connect_attempts_per_request{bucket="1"} 1116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 147
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1114
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 24072682 (22.96 MB)
telemt_user_octets_to_client{user="hello"} 2300757323 (2.14 GB)
telemt_user_msgs_from_client{user="hello"} 60284
telemt_user_msgs_to_client{user="hello"} 441745
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 6152.1 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2551
telemt_connections_bad_total 57
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 2273
telemt_upstream_connect_success_total 2272
telemt_upstream_connect_attempts_per_request{bucket="1"} 2271
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 58
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2270
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 15193897 (14.49 MB)
telemt_user_octets_to_client{user="hello"} 442129366 (421.65 MB)
telemt_user_msgs_from_client{user="hello"} 23383
telemt_user_msgs_to_client{user="hello"} 120812
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 6163.5 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2237
telemt_connections_bad_total 1119
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1060
telemt_upstream_connect_success_total 1060
telemt_upstream_connect_attempts_per_request{bucket="1"} 1060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1058
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 15883118 (15.15 MB)
telemt_user_octets_to_client{user="hello"} 555202790 (529.48 MB)
telemt_user_msgs_from_client{user="hello"} 33506
telemt_user_msgs_to_client{user="hello"} 142279
telemt_user_unique_ips_current{user="hello"} 1
```