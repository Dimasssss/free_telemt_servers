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

# Server Metrics 2026-03-06 05:45:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 27014.7 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79043
telemt_connections_bad_total 51939
telemt_handshake_timeouts_total 2446
telemt_upstream_connect_attempt_total 23105
telemt_upstream_connect_success_total 23102
telemt_upstream_connect_attempts_per_request{bucket="1"} 23099
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23098
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 327779501 (312.59 MB)
telemt_user_octets_to_client{user="hello"} 20839325089 (19.41 GB)
telemt_user_msgs_from_client{user="hello"} 584202
telemt_user_msgs_to_client{user="hello"} 3129651
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 27012.4 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3037
telemt_connections_bad_total 144
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 2841
telemt_upstream_connect_success_total 2840
telemt_upstream_connect_attempts_per_request{bucket="1"} 2839
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2836
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 59105806 (56.37 MB)
telemt_user_octets_to_client{user="hello"} 1252426153 (1.17 GB)
telemt_user_msgs_from_client{user="hello"} 84023
telemt_user_msgs_to_client{user="hello"} 398868
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 27012.8 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2024
telemt_connections_bad_total 214
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 1787
telemt_upstream_connect_success_total 1787
telemt_upstream_connect_attempts_per_request{bucket="1"} 1787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 179
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1783
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 45224177 (43.13 MB)
telemt_user_octets_to_client{user="hello"} 2231768824 (2.08 GB)
telemt_user_msgs_from_client{user="hello"} 61333
telemt_user_msgs_to_client{user="hello"} 452270
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 27015.6 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4063
telemt_connections_bad_total 138
telemt_handshake_timeouts_total 309
telemt_upstream_connect_attempt_total 3451
telemt_upstream_connect_success_total 3451
telemt_upstream_connect_attempts_per_request{bucket="1"} 3451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 426
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3447
telemt_user_octets_from_client{user="hello"} 98540615 (93.98 MB)
telemt_user_octets_to_client{user="hello"} 5782531029 (5.39 GB)
telemt_user_msgs_from_client{user="hello"} 142189
telemt_user_msgs_to_client{user="hello"} 1226667
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 27015.4 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9108
telemt_connections_bad_total 4903
telemt_handshake_timeouts_total 162
telemt_upstream_connect_attempt_total 3938
telemt_upstream_connect_success_total 3938
telemt_upstream_connect_attempts_per_request{bucket="1"} 3938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 564
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3934
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 79018529 (75.36 MB)
telemt_user_octets_to_client{user="hello"} 15967527979 (14.87 GB)
telemt_user_msgs_from_client{user="hello"} 201606
telemt_user_msgs_to_client{user="hello"} 3044492
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```