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

# Server Metrics 2026-03-10 17:49:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 12181.9 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49308
telemt_connections_bad_total 808
telemt_handshake_timeouts_total 1414
telemt_upstream_connect_attempt_total 44464
telemt_upstream_connect_success_total 44454
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 44464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3734
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44452
telemt_user_connections_current{user="hello"} 333
telemt_user_octets_from_client{user="hello"} 1372998029 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 32981285016 (30.72 GB)
telemt_user_msgs_from_client{user="hello"} 1259022
telemt_user_msgs_to_client{user="hello"} 2509624
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 12180.8 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17935
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 328
telemt_upstream_connect_attempt_total 16350
telemt_upstream_connect_success_total 16346
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 16349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2298
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16344
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 521595673 (497.43 MB)
telemt_user_octets_to_client{user="hello"} 8640021310 (8.05 GB)
telemt_user_msgs_from_client{user="hello"} 486353
telemt_user_msgs_to_client{user="hello"} 2694206
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 12180.6 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27685
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 2512
telemt_upstream_connect_attempt_total 23484
telemt_upstream_connect_success_total 23484
telemt_upstream_connect_attempts_per_request{bucket="1"} 23484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2431
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23482
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 285281894 (272.07 MB)
telemt_user_octets_to_client{user="hello"} 16009019596 (14.91 GB)
telemt_user_msgs_from_client{user="hello"} 475699
telemt_user_msgs_to_client{user="hello"} 2874560
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 12179.5 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27081
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 258
telemt_upstream_connect_attempt_total 25842
telemt_upstream_connect_success_total 25769
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 25842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3044
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25767
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 368114972 (351.06 MB)
telemt_user_octets_to_client{user="hello"} 24245699584 (22.58 GB)
telemt_user_msgs_from_client{user="hello"} 534355
telemt_user_msgs_to_client{user="hello"} 4268295
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 12180.8 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37531
telemt_connections_bad_total 2797
telemt_handshake_timeouts_total 654
telemt_upstream_connect_attempt_total 32599
telemt_upstream_connect_success_total 32362
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 32599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3873
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32360
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 1299676975 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 20855305753 (19.42 GB)
telemt_user_msgs_from_client{user="hello"} 967997
telemt_user_msgs_to_client{user="hello"} 3013716
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 30
```