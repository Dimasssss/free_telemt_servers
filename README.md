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

# Server Metrics 2026-03-11 08:23:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 64619.2 (17h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181974
telemt_connections_bad_total 3547
telemt_handshake_timeouts_total 4103
telemt_upstream_connect_attempt_total 165639
telemt_upstream_connect_success_total 165588
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 165639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 151231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 165580
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 3737478684 (3.48 GB)
telemt_user_octets_to_client{user="hello"} 104866249235 (97.66 GB)
telemt_user_msgs_from_client{user="hello"} 4026092
telemt_user_msgs_to_client{user="hello"} 7554703
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 64618.7 (17h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70610
telemt_connections_bad_total 586
telemt_handshake_timeouts_total 3107
telemt_upstream_connect_attempt_total 63553
telemt_upstream_connect_success_total 63539
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 63553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63533
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 4858367703 (4.52 GB)
telemt_user_octets_to_client{user="hello"} 52961881283 (49.32 GB)
telemt_user_msgs_from_client{user="hello"} 3023819
telemt_user_msgs_to_client{user="hello"} 13376122
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 64618.3 (17h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98183
telemt_connections_bad_total 916
telemt_handshake_timeouts_total 5178
telemt_upstream_connect_attempt_total 86331
telemt_upstream_connect_success_total 86328
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 86331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9569
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 86322
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 11923379257 (11.10 GB)
telemt_user_octets_to_client{user="hello"} 75310658153 (70.14 GB)
telemt_user_msgs_from_client{user="hello"} 5452571
telemt_user_msgs_to_client{user="hello"} 14662410
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 64617.1 (17h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107069
telemt_connections_bad_total 223
telemt_handshake_timeouts_total 734
telemt_upstream_connect_attempt_total 102171
telemt_upstream_connect_success_total 101938
telemt_upstream_connect_fail_total 233
telemt_upstream_connect_attempts_per_request{bucket="1"} 102171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88008
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13603
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 275
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 233
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 101930
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 4469082317 (4.16 GB)
telemt_user_octets_to_client{user="hello"} 70697478066 (65.84 GB)
telemt_user_msgs_from_client{user="hello"} 3056274
telemt_user_msgs_to_client{user="hello"} 17956209
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 64618.5 (17h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175712
telemt_connections_bad_total 14257
telemt_handshake_timeouts_total 2467
telemt_upstream_connect_attempt_total 139885
telemt_upstream_connect_success_total 139635
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 139885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 119657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19727
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 251
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 139629
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 2800297062 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 131085673339 (122.08 GB)
telemt_user_msgs_from_client{user="hello"} 3180919
telemt_user_msgs_to_client{user="hello"} 16899980
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 43587.8 (12h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 358
telemt_connections_bad_total 336
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 17
telemt_upstream_connect_success_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```