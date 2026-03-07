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

# Server Metrics 2026-03-07 01:05:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 25053.4 (6h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32286
telemt_connections_bad_total 189
telemt_handshake_timeouts_total 487
telemt_upstream_connect_attempt_total 30121
telemt_upstream_connect_success_total 30114
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 30121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1851
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30110
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 2076002960 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 33007856087 (30.74 GB)
telemt_user_msgs_from_client{user="hello"} 1372151
telemt_user_msgs_to_client{user="hello"} 5197479
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 25051.9 (6h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6697
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 104
telemt_upstream_connect_attempt_total 6267
telemt_upstream_connect_success_total 6264
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6260
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 215271230 (205.30 MB)
telemt_user_octets_to_client{user="hello"} 3894569207 (3.63 GB)
telemt_user_msgs_from_client{user="hello"} 201825
telemt_user_msgs_to_client{user="hello"} 1088966
telemt_user_unique_ips_current{user="hello"} 4
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 25051.9 (6h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3186
telemt_connections_bad_total 166
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 2900
telemt_upstream_connect_success_total 2900
telemt_upstream_connect_attempts_per_request{bucket="1"} 2900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 250
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2896
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 65237095 (62.21 MB)
telemt_user_octets_to_client{user="hello"} 1870295411 (1.74 GB)
telemt_user_msgs_from_client{user="hello"} 64484
telemt_user_msgs_to_client{user="hello"} 396851
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 25051.9 (6h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4383
telemt_connections_bad_total 105
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 4206
telemt_upstream_connect_success_total 4199
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 384
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4195
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 100746704 (96.08 MB)
telemt_user_octets_to_client{user="hello"} 1365089399 (1.27 GB)
telemt_user_msgs_from_client{user="hello"} 85941
telemt_user_msgs_to_client{user="hello"} 351597
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 25052.4 (6h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12276
telemt_connections_bad_total 5456
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 6673
telemt_upstream_connect_success_total 6672
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1032
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6668
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 227957400 (217.40 MB)
telemt_user_octets_to_client{user="hello"} 7430978293 (6.92 GB)
telemt_user_msgs_from_client{user="hello"} 214916
telemt_user_msgs_to_client{user="hello"} 1528994
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 2
```