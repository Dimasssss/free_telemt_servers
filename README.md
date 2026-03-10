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

# Server Metrics 2026-03-10 11:50:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 131445.1 (36h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 287637
telemt_connections_bad_total 3463
telemt_handshake_timeouts_total 3053
telemt_upstream_connect_attempt_total 268964
telemt_upstream_connect_success_total 268816
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 268964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 248409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20320
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 268804
telemt_user_connections_current{user="hello"} 309
telemt_user_octets_from_client{user="hello"} 6413631665 (5.97 GB)
telemt_user_octets_to_client{user="hello"} 171080864879 (159.33 GB)
telemt_user_msgs_from_client{user="hello"} 6487796
telemt_user_msgs_to_client{user="hello"} 10449314
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 131443.5 (36h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87772
telemt_connections_bad_total 3270
telemt_handshake_timeouts_total 1242
telemt_upstream_connect_attempt_total 78687
telemt_upstream_connect_success_total 78643
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 78687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7393
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 78629
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 2753263630 (2.56 GB)
telemt_user_octets_to_client{user="hello"} 34407700500 (32.04 GB)
telemt_user_msgs_from_client{user="hello"} 2155996
telemt_user_msgs_to_client{user="hello"} 9910870
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 131444.0 (36h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124672
telemt_connections_bad_total 1202
telemt_handshake_timeouts_total 6264
telemt_upstream_connect_attempt_total 90843
telemt_upstream_connect_success_total 90841
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 90843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10420
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 90829
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 6479452485 (6.03 GB)
telemt_user_octets_to_client{user="hello"} 65148246869 (60.67 GB)
telemt_user_msgs_from_client{user="hello"} 4277110
telemt_user_msgs_to_client{user="hello"} 10780583
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 131438.7 (36h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129683
telemt_connections_bad_total 1036
telemt_handshake_timeouts_total 2896
telemt_upstream_connect_attempt_total 119380
telemt_upstream_connect_success_total 119127
telemt_upstream_connect_fail_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 119380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13046
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 73
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 295
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 253
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 119115
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 3158960995 (2.94 GB)
telemt_user_octets_to_client{user="hello"} 82875060877 (77.18 GB)
telemt_user_msgs_from_client{user="hello"} 2971430
telemt_user_msgs_to_client{user="hello"} 18999129
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 131444.2 (36h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193339
telemt_connections_bad_total 28588
telemt_handshake_timeouts_total 5112
telemt_upstream_connect_attempt_total 151452
telemt_upstream_connect_success_total 150491
telemt_upstream_connect_fail_total 961
telemt_upstream_connect_attempts_per_request{bucket="1"} 151452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 961
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 150477
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 3361842210 (3.13 GB)
telemt_user_octets_to_client{user="hello"} 112451141950 (104.73 GB)
telemt_user_msgs_from_client{user="hello"} 3489738
telemt_user_msgs_to_client{user="hello"} 15297358
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 26
```