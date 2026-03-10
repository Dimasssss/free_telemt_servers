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

# Server Metrics 2026-03-10 09:22:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 122544.1 (34h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 252157
telemt_connections_bad_total 3429
telemt_handshake_timeouts_total 2170
telemt_upstream_connect_attempt_total 236518
telemt_upstream_connect_success_total 236441
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 236518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 218230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18143
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 236429
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 5921228473 (5.51 GB)
telemt_user_octets_to_client{user="hello"} 142765412216 (132.96 GB)
telemt_user_msgs_from_client{user="hello"} 5750156
telemt_user_msgs_to_client{user="hello"} 8941543
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 122542.7 (34h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75901
telemt_connections_bad_total 3249
telemt_handshake_timeouts_total 1023
telemt_upstream_connect_attempt_total 67723
telemt_upstream_connect_success_total 67681
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 67723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 399
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 67669
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 2314372961 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 31951212159 (29.76 GB)
telemt_user_msgs_from_client{user="hello"} 1883844
telemt_user_msgs_to_client{user="hello"} 9105587
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 122543.1 (34h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109392
telemt_connections_bad_total 1143
telemt_handshake_timeouts_total 5209
telemt_upstream_connect_attempt_total 77364
telemt_upstream_connect_success_total 77362
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 77364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8795
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 77350
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 6343571100 (5.91 GB)
telemt_user_octets_to_client{user="hello"} 60883789648 (56.70 GB)
telemt_user_msgs_from_client{user="hello"} 4020866
telemt_user_msgs_to_client{user="hello"} 9752567
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 122537.9 (34h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110561
telemt_connections_bad_total 953
telemt_handshake_timeouts_total 1306
telemt_upstream_connect_attempt_total 102790
telemt_upstream_connect_success_total 102563
telemt_upstream_connect_fail_total 227
telemt_upstream_connect_attempts_per_request{bucket="1"} 102790
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90777
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11482
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 227
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 102551
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 2925162415 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 76642032440 (71.38 GB)
telemt_user_msgs_from_client{user="hello"} 2666587
telemt_user_msgs_to_client{user="hello"} 17446505
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 122543.3 (34h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169029
telemt_connections_bad_total 26925
telemt_handshake_timeouts_total 4237
telemt_upstream_connect_attempt_total 130748
telemt_upstream_connect_success_total 129946
telemt_upstream_connect_fail_total 802
telemt_upstream_connect_attempts_per_request{bucket="1"} 130748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 802
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 129934
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 2006368103 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 104882263915 (97.68 GB)
telemt_user_msgs_from_client{user="hello"} 2761248
telemt_user_msgs_to_client{user="hello"} 14198239
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 16
```