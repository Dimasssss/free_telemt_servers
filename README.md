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

# Server Metrics 2026-03-04 10:10:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 6473.3 (1h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11404
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 176
telemt_upstream_connect_attempt_total 10226
telemt_upstream_connect_success_total 10226
telemt_upstream_connect_attempts_per_request{bucket="1"} 10226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 668
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10224
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 137659851 (131.28 MB)
telemt_user_octets_to_client{user="hello"} 5044937809 (4.70 GB)
telemt_user_msgs_from_client{user="hello"} 223693
telemt_user_msgs_to_client{user="hello"} 852840
telemt_user_unique_ips_current{user="hello"} 10
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 6485.0 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1477
telemt_connections_bad_total 40
telemt_handshake_timeouts_total 32
telemt_upstream_connect_attempt_total 1348
telemt_upstream_connect_success_total 1346
telemt_upstream_connect_attempts_per_request{bucket="1"} 1344
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1344
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 59188547 (56.45 MB)
telemt_user_octets_to_client{user="hello"} 708630953 (675.80 MB)
telemt_user_msgs_from_client{user="hello"} 50717
telemt_user_msgs_to_client{user="hello"} 213460
telemt_user_unique_ips_current{user="hello"} 3
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 6469.4 (1h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1306
telemt_connections_bad_total 68
telemt_upstream_connect_attempt_total 1215
telemt_upstream_connect_success_total 1215
telemt_upstream_connect_attempts_per_request{bucket="1"} 1215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1213
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 26643985 (25.41 MB)
telemt_user_octets_to_client{user="hello"} 2482573890 (2.31 GB)
telemt_user_msgs_from_client{user="hello"} 67301
telemt_user_msgs_to_client{user="hello"} 478675
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 6460.0 (1h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2604
telemt_connections_bad_total 57
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 2324
telemt_upstream_connect_success_total 2323
telemt_upstream_connect_attempts_per_request{bucket="1"} 2322
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 58
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2321
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 15556597 (14.84 MB)
telemt_user_octets_to_client{user="hello"} 457002177 (435.83 MB)
telemt_user_msgs_from_client{user="hello"} 24348
telemt_user_msgs_to_client{user="hello"} 125588
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 6471.4 (1h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2323
telemt_connections_bad_total 1174
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1089
telemt_upstream_connect_success_total 1089
telemt_upstream_connect_attempts_per_request{bucket="1"} 1089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 158
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1087
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 16123496 (15.38 MB)
telemt_user_octets_to_client{user="hello"} 564902651 (538.73 MB)
telemt_user_msgs_from_client{user="hello"} 33966
telemt_user_msgs_to_client{user="hello"} 144837
telemt_user_unique_ips_current{user="hello"} 1
```