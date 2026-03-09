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

# Server Metrics 2026-03-09 05:15:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 21319.0 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19793
telemt_connections_bad_total 32
telemt_handshake_timeouts_total 556
telemt_upstream_connect_attempt_total 17904
telemt_upstream_connect_success_total 17899
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 17904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1343
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17897
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 169792338 (161.93 MB)
telemt_user_octets_to_client{user="hello"} 9978048872 (9.29 GB)
telemt_user_msgs_from_client{user="hello"} 327032
telemt_user_msgs_to_client{user="hello"} 484795
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 21317.3 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2541
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 68
telemt_upstream_connect_attempt_total 2365
telemt_upstream_connect_success_total 2365
telemt_upstream_connect_attempts_per_request{bucket="1"} 2365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 163
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2363
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 37972714 (36.21 MB)
telemt_user_octets_to_client{user="hello"} 2015138692 (1.88 GB)
telemt_user_msgs_from_client{user="hello"} 79685
telemt_user_msgs_to_client{user="hello"} 389836
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 21317.8 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1478
telemt_connections_bad_total 86
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1377
telemt_upstream_connect_success_total 1377
telemt_upstream_connect_attempts_per_request{bucket="1"} 1377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 233
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1373
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 906019782 (864.05 MB)
telemt_user_octets_to_client{user="hello"} 1041044204 (992.82 MB)
telemt_user_msgs_from_client{user="hello"} 344455
telemt_user_msgs_to_client{user="hello"} 206550
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 21312.6 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2859
telemt_connections_bad_total 53
telemt_handshake_timeouts_total 277
telemt_upstream_connect_attempt_total 2339
telemt_upstream_connect_success_total 2339
telemt_upstream_connect_attempts_per_request{bucket="1"} 2339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 521
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2335
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 19177472 (18.29 MB)
telemt_user_octets_to_client{user="hello"} 1645328089 (1.53 GB)
telemt_user_msgs_from_client{user="hello"} 49188
telemt_user_msgs_to_client{user="hello"} 381665
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 21318.1 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6636
telemt_connections_bad_total 4133
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 2417
telemt_upstream_connect_success_total 2417
telemt_upstream_connect_attempts_per_request{bucket="1"} 2417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2118
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 297
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2415
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 19463967 (18.56 MB)
telemt_user_octets_to_client{user="hello"} 2280915272 (2.12 GB)
telemt_user_msgs_from_client{user="hello"} 47834
telemt_user_msgs_to_client{user="hello"} 274512
telemt_user_unique_ips_current{user="hello"} 8
```