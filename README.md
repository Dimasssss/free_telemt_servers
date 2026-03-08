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

# Server Metrics 2026-03-08 17:34:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 37550.7 (10h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89550
telemt_connections_bad_total 5045
telemt_handshake_timeouts_total 1234
telemt_upstream_connect_attempt_total 80248
telemt_upstream_connect_success_total 80220
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 80248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75459
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4716
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 80214
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 1991861853 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 48316015428 (45.00 GB)
telemt_user_msgs_from_client{user="hello"} 1922330
telemt_user_msgs_to_client{user="hello"} 2709239
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 37549.9 (10h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19642
telemt_connections_bad_total 188
telemt_handshake_timeouts_total 126
telemt_upstream_connect_attempt_total 18988
telemt_upstream_connect_success_total 18984
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 18988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1293
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18980
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 686497308 (654.69 MB)
telemt_user_octets_to_client{user="hello"} 18591110716 (17.31 GB)
telemt_user_msgs_from_client{user="hello"} 740588
telemt_user_msgs_to_client{user="hello"} 5052711
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 37549.7 (10h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11974
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 145
telemt_upstream_connect_attempt_total 11207
telemt_upstream_connect_success_total 11131
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 11207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 769
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11127
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 230008566 (219.35 MB)
telemt_user_octets_to_client{user="hello"} 3994716577 (3.72 GB)
telemt_user_msgs_from_client{user="hello"} 192754
telemt_user_msgs_to_client{user="hello"} 704148
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 37549.4 (10h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15788
telemt_connections_bad_total 171
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 15074
telemt_upstream_connect_success_total 15041
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 15074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1087
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15037
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 1015319574 (968.28 MB)
telemt_user_octets_to_client{user="hello"} 5329493078 (4.96 GB)
telemt_user_msgs_from_client{user="hello"} 520083
telemt_user_msgs_to_client{user="hello"} 1206850
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 37549.7 (10h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21542
telemt_connections_bad_total 6935
telemt_handshake_timeouts_total 228
telemt_upstream_connect_attempt_total 14062
telemt_upstream_connect_success_total 14058
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 14062
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2282
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14054
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 261438716 (249.33 MB)
telemt_user_octets_to_client{user="hello"} 11317504537 (10.54 GB)
telemt_user_msgs_from_client{user="hello"} 347533
telemt_user_msgs_to_client{user="hello"} 1488995
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```