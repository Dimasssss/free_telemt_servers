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

# Server Metrics 2026-03-08 09:31:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 8552.6 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18348
telemt_connections_bad_total 2557
telemt_handshake_timeouts_total 109
telemt_upstream_connect_attempt_total 14987
telemt_upstream_connect_success_total 14975
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 14987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 865
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14973
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 493272639 (470.42 MB)
telemt_user_octets_to_client{user="hello"} 9517552113 (8.86 GB)
telemt_user_msgs_from_client{user="hello"} 414652
telemt_user_msgs_to_client{user="hello"} 496042
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 8551.9 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3956
telemt_connections_bad_total 50
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 3755
telemt_upstream_connect_success_total 3755
telemt_upstream_connect_attempts_per_request{bucket="1"} 3755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3753
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 47737557 (45.53 MB)
telemt_user_octets_to_client{user="hello"} 2666174223 (2.48 GB)
telemt_user_msgs_from_client{user="hello"} 90469
telemt_user_msgs_to_client{user="hello"} 679606
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 8551.4 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3217
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 3139
telemt_upstream_connect_success_total 3139
telemt_upstream_connect_attempts_per_request{bucket="1"} 3139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3137
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 32547391 (31.04 MB)
telemt_user_octets_to_client{user="hello"} 931157395 (888.02 MB)
telemt_user_msgs_from_client{user="hello"} 32702
telemt_user_msgs_to_client{user="hello"} 146582
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 8551.2 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3659
telemt_connections_bad_total 30
telemt_handshake_timeouts_total 26
telemt_upstream_connect_attempt_total 3492
telemt_upstream_connect_success_total 3487
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 3492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 237
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3485
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 80768744 (77.03 MB)
telemt_user_octets_to_client{user="hello"} 1437148087 (1.34 GB)
telemt_user_msgs_from_client{user="hello"} 65128
telemt_user_msgs_to_client{user="hello"} 333055
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 8551.5 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5213
telemt_connections_bad_total 1630
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 3532
telemt_upstream_connect_success_total 3532
telemt_upstream_connect_attempts_per_request{bucket="1"} 3532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 677
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3530
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 43964559 (41.93 MB)
telemt_user_octets_to_client{user="hello"} 3036443033 (2.83 GB)
telemt_user_msgs_from_client{user="hello"} 76558
telemt_user_msgs_to_client{user="hello"} 343688
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 7
```