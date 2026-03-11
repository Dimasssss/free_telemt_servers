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

# Server Metrics 2026-03-11 14:57:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 88269.9 (24h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 294537
telemt_connections_bad_total 3850
telemt_handshake_timeouts_total 4860
telemt_upstream_connect_attempt_total 272594
telemt_upstream_connect_success_total 272514
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 272594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 249282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23171
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 272504
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 5095343760 (4.75 GB)
telemt_user_octets_to_client{user="hello"} 136529724001 (127.15 GB)
telemt_user_msgs_from_client{user="hello"} 5943473
telemt_user_msgs_to_client{user="hello"} 10894642
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 88269.4 (24h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116822
telemt_connections_bad_total 965
telemt_handshake_timeouts_total 3380
telemt_upstream_connect_attempt_total 107421
telemt_upstream_connect_success_total 107400
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 107421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13690
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 474
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 107390
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 5982844846 (5.57 GB)
telemt_user_octets_to_client{user="hello"} 68991488250 (64.25 GB)
telemt_user_msgs_from_client{user="hello"} 3971265
telemt_user_msgs_to_client{user="hello"} 19913971
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 88269.1 (24h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161625
telemt_connections_bad_total 1251
telemt_handshake_timeouts_total 7018
telemt_upstream_connect_attempt_total 144319
telemt_upstream_connect_success_total 144305
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 144319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 128193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16009
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 144295
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 12705525234 (11.83 GB)
telemt_user_octets_to_client{user="hello"} 128643171192 (119.81 GB)
telemt_user_msgs_from_client{user="hello"} 6769687
telemt_user_msgs_to_client{user="hello"} 28784606
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 88268.1 (24h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179454
telemt_connections_bad_total 7454
telemt_handshake_timeouts_total 2075
telemt_upstream_connect_attempt_total 162764
telemt_upstream_connect_success_total 162365
telemt_upstream_connect_fail_total 399
telemt_upstream_connect_attempts_per_request{bucket="1"} 162764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 141260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20572
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 442
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 399
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 162355
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 9686075144 (9.02 GB)
telemt_user_octets_to_client{user="hello"} 113180797878 (105.41 GB)
telemt_user_msgs_from_client{user="hello"} 5767773
telemt_user_msgs_to_client{user="hello"} 33736850
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 88269.4 (24h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 255955
telemt_connections_bad_total 19481
telemt_handshake_timeouts_total 6321
telemt_upstream_connect_attempt_total 208213
telemt_upstream_connect_success_total 207709
telemt_upstream_connect_fail_total 504
telemt_upstream_connect_attempts_per_request{bucket="1"} 208213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 179867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27486
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 504
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 207701
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 5053313456 (4.71 GB)
telemt_user_octets_to_client{user="hello"} 170372441560 (158.67 GB)
telemt_user_msgs_from_client{user="hello"} 4919693
telemt_user_msgs_to_client{user="hello"} 23603982
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 67238.8 (18h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 462
telemt_connections_bad_total 440
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 19
telemt_upstream_connect_success_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```