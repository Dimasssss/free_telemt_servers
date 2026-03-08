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

# Server Metrics 2026-03-08 18:41:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 41556.3 (11h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96685
telemt_connections_bad_total 5047
telemt_handshake_timeouts_total 1252
telemt_upstream_connect_attempt_total 87207
telemt_upstream_connect_success_total 87178
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 87207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 82080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5048
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 87172
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 2141072103 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 54167818246 (50.45 GB)
telemt_user_msgs_from_client{user="hello"} 2117437
telemt_user_msgs_to_client{user="hello"} 2981249
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 41555.3 (11h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21849
telemt_connections_bad_total 188
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 21154
telemt_upstream_connect_success_total 21149
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 21154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1377
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21145
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 731880668 (697.98 MB)
telemt_user_octets_to_client{user="hello"} 19792216328 (18.43 GB)
telemt_user_msgs_from_client{user="hello"} 846505
telemt_user_msgs_to_client{user="hello"} 5420202
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 41555.0 (11h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13466
telemt_connections_bad_total 172
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 12142
telemt_upstream_connect_success_total 12066
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 12142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 863
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12062
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 240965324 (229.80 MB)
telemt_user_octets_to_client{user="hello"} 4213073851 (3.92 GB)
telemt_user_msgs_from_client{user="hello"} 205841
telemt_user_msgs_to_client{user="hello"} 752784
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 41554.7 (11h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17282
telemt_connections_bad_total 180
telemt_handshake_timeouts_total 58
telemt_upstream_connect_attempt_total 16531
telemt_upstream_connect_success_total 16497
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 16531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1231
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16493
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 1037806545 (989.73 MB)
telemt_user_octets_to_client{user="hello"} 5892013314 (5.49 GB)
telemt_user_msgs_from_client{user="hello"} 539002
telemt_user_msgs_to_client{user="hello"} 1336328
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 41555.1 (11h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24477
telemt_connections_bad_total 7878
telemt_handshake_timeouts_total 229
telemt_upstream_connect_attempt_total 16003
telemt_upstream_connect_success_total 15997
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 16003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2668
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15993
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 306612760 (292.41 MB)
telemt_user_octets_to_client{user="hello"} 12194556304 (11.36 GB)
telemt_user_msgs_from_client{user="hello"} 392222
telemt_user_msgs_to_client{user="hello"} 1605973
telemt_user_unique_ips_current{user="hello"} 8
```