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

# Server Metrics 2026-03-10 11:19:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 129602.4 (36h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280278
telemt_connections_bad_total 3455
telemt_handshake_timeouts_total 3020
telemt_upstream_connect_attempt_total 261956
telemt_upstream_connect_success_total 261808
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 261956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 241806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19917
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 261796
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 6348278395 (5.91 GB)
telemt_user_octets_to_client{user="hello"} 165638764448 (154.26 GB)
telemt_user_msgs_from_client{user="hello"} 6353513
telemt_user_msgs_to_client{user="hello"} 10154951
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 129601.2 (36h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85296
telemt_connections_bad_total 3267
telemt_handshake_timeouts_total 1200
telemt_upstream_connect_attempt_total 76367
telemt_upstream_connect_success_total 76324
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 76367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68717
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7198
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 408
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 76310
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 2430976114 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 34032955636 (31.70 GB)
telemt_user_msgs_from_client{user="hello"} 2020243
telemt_user_msgs_to_client{user="hello"} 9773754
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 129601.8 (36h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121095
telemt_connections_bad_total 1164
telemt_handshake_timeouts_total 6138
telemt_upstream_connect_attempt_total 87635
telemt_upstream_connect_success_total 87633
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 87635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 87621
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 6437938220 (6.00 GB)
telemt_user_octets_to_client{user="hello"} 64698189277 (60.25 GB)
telemt_user_msgs_from_client{user="hello"} 4223559
telemt_user_msgs_to_client{user="hello"} 10626451
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 129596.6 (35h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123790
telemt_connections_bad_total 1032
telemt_handshake_timeouts_total 1368
telemt_upstream_connect_attempt_total 115413
telemt_upstream_connect_success_total 115164
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 115413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 102011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12805
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 69
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 279
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 115152
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 3124674890 (2.91 GB)
telemt_user_octets_to_client{user="hello"} 81614278642 (76.01 GB)
telemt_user_msgs_from_client{user="hello"} 2913400
telemt_user_msgs_to_client{user="hello"} 18742301
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 129602.0 (36h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187925
telemt_connections_bad_total 28256
telemt_handshake_timeouts_total 4707
telemt_upstream_connect_attempt_total 147054
telemt_upstream_connect_success_total 146094
telemt_upstream_connect_fail_total 960
telemt_upstream_connect_attempts_per_request{bucket="1"} 147054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 126239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19648
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 960
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 146080
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 3279102937 (3.05 GB)
telemt_user_octets_to_client{user="hello"} 110898088934 (103.28 GB)
telemt_user_msgs_from_client{user="hello"} 3399481
telemt_user_msgs_to_client{user="hello"} 15070448
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 20
```