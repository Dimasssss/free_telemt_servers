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

# Server Metrics 2026-03-09 00:19:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 3584.2 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3065
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 166
telemt_upstream_connect_attempt_total 2575
telemt_upstream_connect_success_total 2574
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 218
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2572
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 27179731 (25.92 MB)
telemt_user_octets_to_client{user="hello"} 3355340759 (3.12 GB)
telemt_user_msgs_from_client{user="hello"} 68826
telemt_user_msgs_to_client{user="hello"} 121089
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 3582.3 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 237
telemt_upstream_connect_success_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 235
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 1683458 (1.61 MB)
telemt_user_octets_to_client{user="hello"} 45570123 (43.46 MB)
telemt_user_msgs_from_client{user="hello"} 4623
telemt_user_msgs_to_client{user="hello"} 13836
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 3582.7 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288
telemt_connections_bad_total 27
telemt_upstream_connect_attempt_total 258
telemt_upstream_connect_success_total 258
telemt_upstream_connect_attempts_per_request{bucket="1"} 258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 256
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 15753254 (15.02 MB)
telemt_user_octets_to_client{user="hello"} 23754497 (22.65 MB)
telemt_user_msgs_from_client{user="hello"} 8347
telemt_user_msgs_to_client{user="hello"} 8598
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 3577.6 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 474
telemt_connections_bad_total 3
telemt_upstream_connect_attempt_total 466
telemt_upstream_connect_success_total 466
telemt_upstream_connect_attempts_per_request{bucket="1"} 466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 79
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 464
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 3235317 (3.09 MB)
telemt_user_octets_to_client{user="hello"} 164899265 (157.26 MB)
telemt_user_msgs_from_client{user="hello"} 8008
telemt_user_msgs_to_client{user="hello"} 32652
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 3583.2 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1057
telemt_connections_bad_total 641
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 410
telemt_upstream_connect_success_total 410
telemt_upstream_connect_attempts_per_request{bucket="1"} 410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 408
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 5198317 (4.96 MB)
telemt_user_octets_to_client{user="hello"} 1121543835 (1.04 GB)
telemt_user_msgs_from_client{user="hello"} 14771
telemt_user_msgs_to_client{user="hello"} 138692
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```