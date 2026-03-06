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

# Server Metrics 2026-03-06 16:11:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 20987.6 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49455
telemt_connections_bad_total 3101
telemt_handshake_timeouts_total 197
telemt_upstream_connect_attempt_total 42612
telemt_upstream_connect_success_total 42600
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 42612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2308
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42598
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 2324544309 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 27333799893 (25.46 GB)
telemt_user_msgs_from_client{user="hello"} 1535357
telemt_user_msgs_to_client{user="hello"} 4331778
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 20986.9 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9387
telemt_connections_bad_total 169
telemt_handshake_timeouts_total 96
telemt_upstream_connect_attempt_total 8898
telemt_upstream_connect_success_total 8880
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 8898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 534
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8878
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 96489668 (92.02 MB)
telemt_user_octets_to_client{user="hello"} 5101745530 (4.75 GB)
telemt_user_msgs_from_client{user="hello"} 179840
telemt_user_msgs_to_client{user="hello"} 1588066
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 20986.1 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7704
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 7419
telemt_upstream_connect_success_total 7417
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7415
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 111202113 (106.05 MB)
telemt_user_octets_to_client{user="hello"} 4569237459 (4.26 GB)
telemt_user_msgs_from_client{user="hello"} 168556
telemt_user_msgs_to_client{user="hello"} 1078300
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 20985.5 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10992
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 54
telemt_upstream_connect_attempt_total 10214
telemt_upstream_connect_success_total 10178
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 10214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 646
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10176
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 145936864 (139.18 MB)
telemt_user_octets_to_client{user="hello"} 3400743492 (3.17 GB)
telemt_user_msgs_from_client{user="hello"} 180250
telemt_user_msgs_to_client{user="hello"} 882252
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 20986.8 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15437
telemt_connections_bad_total 5330
telemt_handshake_timeouts_total 556
telemt_upstream_connect_attempt_total 9276
telemt_upstream_connect_success_total 9276
telemt_upstream_connect_attempts_per_request{bucket="1"} 9276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1254
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9274
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 228557159 (217.97 MB)
telemt_user_octets_to_client{user="hello"} 20942705290 (19.50 GB)
telemt_user_msgs_from_client{user="hello"} 374808
telemt_user_msgs_to_client{user="hello"} 3767393
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```