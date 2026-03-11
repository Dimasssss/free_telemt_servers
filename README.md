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

# Server Metrics 2026-03-11 08:18:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 64313.1 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180634
telemt_connections_bad_total 3542
telemt_handshake_timeouts_total 4080
telemt_upstream_connect_attempt_total 164378
telemt_upstream_connect_success_total 164327
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 164378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 150085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 164319
telemt_user_connections_current{user="hello"} 357
telemt_user_octets_from_client{user="hello"} 3729246255 (3.47 GB)
telemt_user_octets_to_client{user="hello"} 104519623003 (97.34 GB)
telemt_user_msgs_from_client{user="hello"} 4008806
telemt_user_msgs_to_client{user="hello"} 7518698
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 64312.3 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70104
telemt_connections_bad_total 585
telemt_handshake_timeouts_total 3104
telemt_upstream_connect_attempt_total 63063
telemt_upstream_connect_success_total 63049
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 63063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8682
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63043
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 4855457906 (4.52 GB)
telemt_user_octets_to_client{user="hello"} 52854234746 (49.22 GB)
telemt_user_msgs_from_client{user="hello"} 3017411
telemt_user_msgs_to_client{user="hello"} 13319937
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 64312.2 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97533
telemt_connections_bad_total 909
telemt_handshake_timeouts_total 5176
telemt_upstream_connect_attempt_total 85727
telemt_upstream_connect_success_total 85724
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 85727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9494
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 85718
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 11920805153 (11.10 GB)
telemt_user_octets_to_client{user="hello"} 75235556800 (70.07 GB)
telemt_user_msgs_from_client{user="hello"} 5444961
telemt_user_msgs_to_client{user="hello"} 14631033
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 64311.0 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106126
telemt_connections_bad_total 223
telemt_handshake_timeouts_total 726
telemt_upstream_connect_attempt_total 101293
telemt_upstream_connect_success_total 101064
telemt_upstream_connect_fail_total 228
telemt_upstream_connect_attempts_per_request{bucket="1"} 101292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 87341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 273
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 228
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 101056
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 4463426990 (4.16 GB)
telemt_user_octets_to_client{user="hello"} 70460565466 (65.62 GB)
telemt_user_msgs_from_client{user="hello"} 3045425
telemt_user_msgs_to_client{user="hello"} 17879699
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 64312.4 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 174695
telemt_connections_bad_total 14199
telemt_handshake_timeouts_total 2467
telemt_upstream_connect_attempt_total 138948
telemt_upstream_connect_success_total 138698
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 138948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 118905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19547
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 138692
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 2790114675 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 130244038271 (121.30 GB)
telemt_user_msgs_from_client{user="hello"} 3162987
telemt_user_msgs_to_client{user="hello"} 16765169
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 43281.8 (12h 1m)
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