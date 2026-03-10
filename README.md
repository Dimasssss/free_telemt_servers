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

# Server Metrics 2026-03-10 10:03:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 125000.1 (34h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 261757
telemt_connections_bad_total 3451
telemt_handshake_timeouts_total 2681
telemt_upstream_connect_attempt_total 245065
telemt_upstream_connect_success_total 244977
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 245064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 226251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18648
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 244965
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 6106879097 (5.69 GB)
telemt_user_octets_to_client{user="hello"} 146976928263 (136.88 GB)
telemt_user_msgs_from_client{user="hello"} 5931562
telemt_user_msgs_to_client{user="hello"} 9344818
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 124998.9 (34h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78897
telemt_connections_bad_total 3258
telemt_handshake_timeouts_total 1038
telemt_upstream_connect_attempt_total 70581
telemt_upstream_connect_success_total 70539
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 70581
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 400
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 70527
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 2333575945 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 32800441478 (30.55 GB)
telemt_user_msgs_from_client{user="hello"} 1929256
telemt_user_msgs_to_client{user="hello"} 9375664
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 124999.4 (34h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113222
telemt_connections_bad_total 1149
telemt_handshake_timeouts_total 5585
telemt_upstream_connect_attempt_total 80705
telemt_upstream_connect_success_total 80700
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 80702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9184
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 80688
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 6380016228 (5.94 GB)
telemt_user_octets_to_client{user="hello"} 63133741237 (58.80 GB)
telemt_user_msgs_from_client{user="hello"} 4099896
telemt_user_msgs_to_client{user="hello"} 10144860
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 124994.2 (34h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115433
telemt_connections_bad_total 1023
telemt_handshake_timeouts_total 1338
telemt_upstream_connect_attempt_total 107399
telemt_upstream_connect_success_total 107160
telemt_upstream_connect_fail_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 107399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 94874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11974
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 239
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 107148
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 2961954399 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 79422530013 (73.97 GB)
telemt_user_msgs_from_client{user="hello"} 2750828
telemt_user_msgs_to_client{user="hello"} 18207408
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 124999.6 (34h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175088
telemt_connections_bad_total 27389
telemt_handshake_timeouts_total 4432
telemt_upstream_connect_attempt_total 135897
telemt_upstream_connect_success_total 135091
telemt_upstream_connect_fail_total 806
telemt_upstream_connect_attempts_per_request{bucket="1"} 135897
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 116744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 806
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 135077
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 2040957850 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 106781391507 (99.45 GB)
telemt_user_msgs_from_client{user="hello"} 2836735
telemt_user_msgs_to_client{user="hello"} 14527885
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 19
```