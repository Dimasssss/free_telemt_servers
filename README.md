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

# Server Metrics 2026-03-10 09:58:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 124693.3 (34h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 260634
telemt_connections_bad_total 3450
telemt_handshake_timeouts_total 2673
telemt_upstream_connect_attempt_total 244049
telemt_upstream_connect_success_total 243962
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 244049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 225297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18587
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 243950
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 6096015035 (5.68 GB)
telemt_user_octets_to_client{user="hello"} 146549558656 (136.48 GB)
telemt_user_msgs_from_client{user="hello"} 5914127
telemt_user_msgs_to_client{user="hello"} 9302483
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 124691.9 (34h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78529
telemt_connections_bad_total 3258
telemt_handshake_timeouts_total 1038
telemt_upstream_connect_attempt_total 70223
telemt_upstream_connect_success_total 70181
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 70223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6630
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 400
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 70169
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 2331330510 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 32681438216 (30.44 GB)
telemt_user_msgs_from_client{user="hello"} 1924254
telemt_user_msgs_to_client{user="hello"} 9348436
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 124692.5 (34h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112656
telemt_connections_bad_total 1149
telemt_handshake_timeouts_total 5563
telemt_upstream_connect_attempt_total 80185
telemt_upstream_connect_success_total 80183
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 80185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 80171
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 6373474998 (5.94 GB)
telemt_user_octets_to_client{user="hello"} 62734584250 (58.43 GB)
telemt_user_msgs_from_client{user="hello"} 4088863
telemt_user_msgs_to_client{user="hello"} 10079354
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 124687.1 (34h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114791
telemt_connections_bad_total 966
telemt_handshake_timeouts_total 1313
telemt_upstream_connect_attempt_total 106864
telemt_upstream_connect_success_total 106626
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 106864
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 94399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11915
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 106614
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 2958761605 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 79308422060 (73.86 GB)
telemt_user_msgs_from_client{user="hello"} 2742867
telemt_user_msgs_to_client{user="hello"} 18174401
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 124692.6 (34h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 174282
telemt_connections_bad_total 27329
telemt_handshake_timeouts_total 4431
telemt_upstream_connect_attempt_total 135184
telemt_upstream_connect_success_total 134378
telemt_upstream_connect_fail_total 806
telemt_upstream_connect_attempts_per_request{bucket="1"} 135184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 116126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18059
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 806
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 134366
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 2035958289 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 106125077038 (98.84 GB)
telemt_user_msgs_from_client{user="hello"} 2825300
telemt_user_msgs_to_client{user="hello"} 14455862
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 22
```