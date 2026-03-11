# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

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

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-11 07:42:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 62169.7 (17h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171341
telemt_connections_bad_total 3538
telemt_handshake_timeouts_total 4032
telemt_upstream_connect_attempt_total 155341
telemt_upstream_connect_success_total 155293
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 155341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 141742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13494
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 155285
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 3597583792 (3.35 GB)
telemt_user_octets_to_client{user="hello"} 100261790655 (93.38 GB)
telemt_user_msgs_from_client{user="hello"} 3845443
telemt_user_msgs_to_client{user="hello"} 7217008
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 62169.1 (17h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67092
telemt_connections_bad_total 577
telemt_handshake_timeouts_total 3076
telemt_upstream_connect_attempt_total 60180
telemt_upstream_connect_success_total 60166
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 60180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8399
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 234
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60160
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 4702028410 (4.38 GB)
telemt_user_octets_to_client{user="hello"} 51103608499 (47.59 GB)
telemt_user_msgs_from_client{user="hello"} 2921029
telemt_user_msgs_to_client{user="hello"} 12508751
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 62168.8 (17h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93049
telemt_connections_bad_total 871
telemt_handshake_timeouts_total 5148
telemt_upstream_connect_attempt_total 81489
telemt_upstream_connect_success_total 81486
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 81489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9060
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 81480
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 11895961134 (11.08 GB)
telemt_user_octets_to_client{user="hello"} 74773651098 (69.64 GB)
telemt_user_msgs_from_client{user="hello"} 5380934
telemt_user_msgs_to_client{user="hello"} 14427342
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 62167.6 (17h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99694
telemt_connections_bad_total 219
telemt_handshake_timeouts_total 672
telemt_upstream_connect_attempt_total 95478
telemt_upstream_connect_success_total 95269
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 95478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 82331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12620
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 266
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 95261
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 3189231157 (2.97 GB)
telemt_user_octets_to_client{user="hello"} 64522773056 (60.09 GB)
telemt_user_msgs_from_client{user="hello"} 2510254
telemt_user_msgs_to_client{user="hello"} 15970060
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 62169.0 (17h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166608
telemt_connections_bad_total 13812
telemt_handshake_timeouts_total 1886
telemt_upstream_connect_attempt_total 132779
telemt_upstream_connect_success_total 132529
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 132779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 113792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 132523
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 2593182494 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 127549978481 (118.79 GB)
telemt_user_msgs_from_client{user="hello"} 3027352
telemt_user_msgs_to_client{user="hello"} 16242867
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 41138.3 (11h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222
telemt_connections_bad_total 202
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 15
telemt_upstream_connect_success_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```