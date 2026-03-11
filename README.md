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

# Server Metrics 2026-03-11 02:51:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 44743.8 (12h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117606
telemt_connections_bad_total 3356
telemt_handshake_timeouts_total 2570
telemt_upstream_connect_attempt_total 106336
telemt_upstream_connect_success_total 106298
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 106336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9432
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 106292
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 2909315071 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 81815043863 (76.20 GB)
telemt_user_msgs_from_client{user="hello"} 2952419
telemt_user_msgs_to_client{user="hello"} 5651061
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 44743.7 (12h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48816
telemt_connections_bad_total 367
telemt_handshake_timeouts_total 2910
telemt_upstream_connect_attempt_total 42899
telemt_upstream_connect_success_total 42890
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 42899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6524
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42886
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 2271097258 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 41554111387 (38.70 GB)
telemt_user_msgs_from_client{user="hello"} 1751408
telemt_user_msgs_to_client{user="hello"} 10089079
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 44743.5 (12h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69487
telemt_connections_bad_total 656
telemt_handshake_timeouts_total 4207
telemt_upstream_connect_attempt_total 60734
telemt_upstream_connect_success_total 60732
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 60734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6722
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60726
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 11742604930 (10.94 GB)
telemt_user_octets_to_client{user="hello"} 70034613225 (65.22 GB)
telemt_user_msgs_from_client{user="hello"} 5129272
telemt_user_msgs_to_client{user="hello"} 13139440
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 44742.4 (12h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68490
telemt_connections_bad_total 147
telemt_handshake_timeouts_total 544
telemt_upstream_connect_attempt_total 65513
telemt_upstream_connect_success_total 65355
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 65512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8213
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 65349
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 1762364604 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 42668805352 (39.74 GB)
telemt_user_msgs_from_client{user="hello"} 1593439
telemt_user_msgs_to_client{user="hello"} 8370382
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 44743.9 (12h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104013
telemt_connections_bad_total 10306
telemt_handshake_timeouts_total 1526
telemt_upstream_connect_attempt_total 88308
telemt_upstream_connect_success_total 88060
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 88308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11272
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 88056
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 2198853940 (2.05 GB)
telemt_user_octets_to_client{user="hello"} 76721545657 (71.45 GB)
telemt_user_msgs_from_client{user="hello"} 2250021
telemt_user_msgs_to_client{user="hello"} 10494899
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 23713.1 (6h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83
telemt_connections_bad_total 79
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```