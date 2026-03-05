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

# Server Metrics 2026-03-05 04:00:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 59590.5 (16h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77745
telemt_connections_bad_total 293
telemt_handshake_timeouts_total 1649
telemt_upstream_connect_attempt_total 70325
telemt_upstream_connect_success_total 70308
telemt_upstream_connect_attempts_per_request{bucket="1"} 70291
telemt_upstream_connect_attempts_per_request{bucket="2"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4791
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 70302
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 2475282602 (2.31 GB)
telemt_user_octets_to_client{user="hello"} 56550684400 (52.67 GB)
telemt_user_msgs_from_client{user="hello"} 2269449
telemt_user_msgs_to_client{user="hello"} 9189687
telemt_user_unique_ips_current{user="hello"} 13
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 59593.5 (16h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16744
telemt_connections_bad_total 331
telemt_handshake_timeouts_total 42
telemt_upstream_connect_attempt_total 12129
telemt_upstream_connect_success_total 12127
telemt_upstream_connect_attempts_per_request{bucket="1"} 12125
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 857
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12121
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 1067180217 (1017.74 MB)
telemt_user_octets_to_client{user="hello"} 11308408224 (10.53 GB)
telemt_user_msgs_from_client{user="hello"} 665439
telemt_user_msgs_to_client{user="hello"} 3805117
telemt_user_unique_ips_current{user="hello"} 3
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 59591.8 (16h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11848
telemt_connections_bad_total 214
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 7909
telemt_upstream_connect_success_total 7909
telemt_upstream_connect_attempts_per_request{bucket="1"} 7909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7903
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 357500787 (340.94 MB)
telemt_user_octets_to_client{user="hello"} 5697150044 (5.31 GB)
telemt_user_msgs_from_client{user="hello"} 300053
telemt_user_msgs_to_client{user="hello"} 1241281
telemt_user_unique_ips_current{user="hello"} 1
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 59589.5 (16h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19389
telemt_connections_bad_total 801
telemt_handshake_timeouts_total 100
telemt_upstream_connect_attempt_total 16827
telemt_upstream_connect_success_total 16821
telemt_upstream_connect_attempts_per_request{bucket="1"} 16815
telemt_upstream_connect_attempts_per_request{bucket="2"} 6
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1357
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16815
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 410518469 (391.50 MB)
telemt_user_octets_to_client{user="hello"} 6055968437 (5.64 GB)
telemt_user_msgs_from_client{user="hello"} 333148
telemt_user_msgs_to_client{user="hello"} 1546166
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 59591.3 (16h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21702
telemt_connections_bad_total 10726
telemt_handshake_timeouts_total 37
telemt_upstream_connect_attempt_total 10580
telemt_upstream_connect_success_total 10576
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10574
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1674
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10570
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 528420795 (503.94 MB)
telemt_user_octets_to_client{user="hello"} 22828644531 (21.26 GB)
telemt_user_msgs_from_client{user="hello"} 581626
telemt_user_msgs_to_client{user="hello"} 4347118
telemt_user_unique_ips_current{user="hello"} 3
```