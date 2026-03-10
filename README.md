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

# Server Metrics 2026-03-10 14:13:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 140046.4 (38h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 322942
telemt_connections_bad_total 3701
telemt_handshake_timeouts_total 3379
telemt_upstream_connect_attempt_total 302317
telemt_upstream_connect_success_total 302155
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 302317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 279315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22739
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 302141
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 6892501272 (6.42 GB)
telemt_user_octets_to_client{user="hello"} 198827999261 (185.17 GB)
telemt_user_msgs_from_client{user="hello"} 7207740
telemt_user_msgs_to_client{user="hello"} 11857037
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 140045.2 (38h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99893
telemt_connections_bad_total 3275
telemt_handshake_timeouts_total 1310
telemt_upstream_connect_attempt_total 90186
telemt_upstream_connect_success_total 90140
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 90186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 90126
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 2899854272 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 38493601619 (35.85 GB)
telemt_user_msgs_from_client{user="hello"} 2364977
telemt_user_msgs_to_client{user="hello"} 11140884
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 140045.6 (38h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143581
telemt_connections_bad_total 1241
telemt_handshake_timeouts_total 7005
telemt_upstream_connect_attempt_total 107940
telemt_upstream_connect_success_total 107937
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 107940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 95485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12411
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 107923
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 6720194241 (6.26 GB)
telemt_user_octets_to_client{user="hello"} 69607896508 (64.83 GB)
telemt_user_msgs_from_client{user="hello"} 4605542
telemt_user_msgs_to_client{user="hello"} 11854233
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 140040.5 (38h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147193
telemt_connections_bad_total 1065
telemt_handshake_timeouts_total 3067
telemt_upstream_connect_attempt_total 136107
telemt_upstream_connect_success_total 135798
telemt_upstream_connect_fail_total 309
telemt_upstream_connect_attempts_per_request{bucket="1"} 136107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 120677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14685
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 309
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 135784
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 5080890108 (4.73 GB)
telemt_user_octets_to_client{user="hello"} 95414496000 (88.86 GB)
telemt_user_msgs_from_client{user="hello"} 3929392
telemt_user_msgs_to_client{user="hello"} 21597087
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 140045.8 (38h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217704
telemt_connections_bad_total 31296
telemt_handshake_timeouts_total 6258
telemt_upstream_connect_attempt_total 171132
telemt_upstream_connect_success_total 170170
telemt_upstream_connect_fail_total 962
telemt_upstream_connect_attempts_per_request{bucket="1"} 171132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 147184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22760
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 962
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 170156
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 3656973375 (3.41 GB)
telemt_user_octets_to_client{user="hello"} 120618085528 (112.33 GB)
telemt_user_msgs_from_client{user="hello"} 3883632
telemt_user_msgs_to_client{user="hello"} 16625776
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 29
```