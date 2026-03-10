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

# Server Metrics 2026-03-10 10:33:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 126841.7 (35h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268683
telemt_connections_bad_total 3452
telemt_handshake_timeouts_total 2888
telemt_upstream_connect_attempt_total 251388
telemt_upstream_connect_success_total 251260
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 251388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 232042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19138
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 251248
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 6172222534 (5.75 GB)
telemt_user_octets_to_client{user="hello"} 152412036626 (141.94 GB)
telemt_user_msgs_from_client{user="hello"} 6058168
telemt_user_msgs_to_client{user="hello"} 9588985
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 126840.6 (35h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81099
telemt_connections_bad_total 3260
telemt_handshake_timeouts_total 1055
telemt_upstream_connect_attempt_total 72617
telemt_upstream_connect_success_total 72574
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 72617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6835
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 402
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 72562
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 2371757349 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 33117153040 (30.84 GB)
telemt_user_msgs_from_client{user="hello"} 1964819
telemt_user_msgs_to_client{user="hello"} 9509854
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 126841.1 (35h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116818
telemt_connections_bad_total 1162
telemt_handshake_timeouts_total 5953
telemt_upstream_connect_attempt_total 83727
telemt_upstream_connect_success_total 83725
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 83727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9704
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 83713
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 6415752705 (5.98 GB)
telemt_user_octets_to_client{user="hello"} 64177403573 (59.77 GB)
telemt_user_msgs_from_client{user="hello"} 4156445
telemt_user_msgs_to_client{user="hello"} 10445333
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 126836.0 (35h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119061
telemt_connections_bad_total 1026
telemt_handshake_timeouts_total 1353
telemt_upstream_connect_attempt_total 110877
telemt_upstream_connect_success_total 110633
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 110877
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 97977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12331
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 62
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 263
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 110621
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 3056795627 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 80630978636 (75.09 GB)
telemt_user_msgs_from_client{user="hello"} 2832564
telemt_user_msgs_to_client{user="hello"} 18474766
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 126841.2 (35h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180634
telemt_connections_bad_total 27758
telemt_handshake_timeouts_total 4481
telemt_upstream_connect_attempt_total 140756
telemt_upstream_connect_success_total 139891
telemt_upstream_connect_fail_total 865
telemt_upstream_connect_attempts_per_request{bucket="1"} 140756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 120850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18847
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 865
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 139877
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 2070431598 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 108517810876 (101.07 GB)
telemt_user_msgs_from_client{user="hello"} 2898117
telemt_user_msgs_to_client{user="hello"} 14746358
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 26
```