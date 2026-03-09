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

# Server Metrics 2026-03-09 16:59:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 63601.7 (17h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117880
telemt_connections_bad_total 1659
telemt_handshake_timeouts_total 984
telemt_upstream_connect_attempt_total 110425
telemt_upstream_connect_success_total 110385
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 110425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 101954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8372
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 110379
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 2965970537 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 60696289163 (56.53 GB)
telemt_user_msgs_from_client{user="hello"} 2762776
telemt_user_msgs_to_client{user="hello"} 3897284
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 63600.6 (17h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31641
telemt_connections_bad_total 222
telemt_handshake_timeouts_total 356
telemt_upstream_connect_attempt_total 29837
telemt_upstream_connect_success_total 29819
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 29837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2583
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29813
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 1007684476 (961.00 MB)
telemt_user_octets_to_client{user="hello"} 15980363621 (14.88 GB)
telemt_user_msgs_from_client{user="hello"} 859385
telemt_user_msgs_to_client{user="hello"} 4432772
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 63601.0 (17h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40477
telemt_connections_bad_total 657
telemt_handshake_timeouts_total 1770
telemt_upstream_connect_attempt_total 30952
telemt_upstream_connect_success_total 30952
telemt_upstream_connect_attempts_per_request{bucket="1"} 30952
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3370
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30946
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 4480483225 (4.17 GB)
telemt_user_octets_to_client{user="hello"} 18657025430 (17.38 GB)
telemt_user_msgs_from_client{user="hello"} 2004904
telemt_user_msgs_to_client{user="hello"} 2497555
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 63595.8 (17h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46114
telemt_connections_bad_total 198
telemt_handshake_timeouts_total 886
telemt_upstream_connect_attempt_total 42206
telemt_upstream_connect_success_total 42104
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 42206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5911
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42096
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 1960734871 (1.83 GB)
telemt_user_octets_to_client{user="hello"} 31561949681 (29.39 GB)
telemt_user_msgs_from_client{user="hello"} 1301790
telemt_user_msgs_to_client{user="hello"} 7971833
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 63601.2 (17h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74898
telemt_connections_bad_total 15363
telemt_handshake_timeouts_total 1688
telemt_upstream_connect_attempt_total 54408
telemt_upstream_connect_success_total 54406
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 54408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 54398
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 923458449 (880.68 MB)
telemt_user_octets_to_client{user="hello"} 55926088250 (52.09 GB)
telemt_user_msgs_from_client{user="hello"} 1258410
telemt_user_msgs_to_client{user="hello"} 6880429
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 16
```