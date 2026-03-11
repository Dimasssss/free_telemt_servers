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

# Server Metrics 2026-03-11 08:12:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 64006.8 (17h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179413
telemt_connections_bad_total 3542
telemt_handshake_timeouts_total 4066
telemt_upstream_connect_attempt_total 163196
telemt_upstream_connect_success_total 163145
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 163196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 149002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14086
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 163137
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 3711587939 (3.46 GB)
telemt_user_octets_to_client{user="hello"} 104159835492 (97.01 GB)
telemt_user_msgs_from_client{user="hello"} 3985261
telemt_user_msgs_to_client{user="hello"} 7475609
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 64006.2 (17h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69684
telemt_connections_bad_total 585
telemt_handshake_timeouts_total 3094
telemt_upstream_connect_attempt_total 62661
telemt_upstream_connect_success_total 62647
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 62661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8654
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 62641
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 4852662697 (4.52 GB)
telemt_user_octets_to_client{user="hello"} 52619759421 (49.01 GB)
telemt_user_msgs_from_client{user="hello"} 3010772
telemt_user_msgs_to_client{user="hello"} 13201404
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 64006.0 (17h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97041
telemt_connections_bad_total 909
telemt_handshake_timeouts_total 5174
telemt_upstream_connect_attempt_total 85255
telemt_upstream_connect_success_total 85252
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 85255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9434
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 85246
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 11918863965 (11.10 GB)
telemt_user_octets_to_client{user="hello"} 75193706416 (70.03 GB)
telemt_user_msgs_from_client{user="hello"} 5438347
telemt_user_msgs_to_client{user="hello"} 14611168
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 64004.8 (17h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105202
telemt_connections_bad_total 223
telemt_handshake_timeouts_total 716
telemt_upstream_connect_attempt_total 100505
telemt_upstream_connect_success_total 100280
telemt_upstream_connect_fail_total 225
telemt_upstream_connect_attempts_per_request{bucket="1"} 100505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13282
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 273
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 225
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 100272
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 4452227504 (4.15 GB)
telemt_user_octets_to_client{user="hello"} 69186766145 (64.44 GB)
telemt_user_msgs_from_client{user="hello"} 3025845
telemt_user_msgs_to_client{user="hello"} 17432698
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 64006.1 (17h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173343
telemt_connections_bad_total 14145
telemt_handshake_timeouts_total 2140
telemt_upstream_connect_attempt_total 138008
telemt_upstream_connect_success_total 137756
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 138006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 118165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 137750
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 2707975741 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 129439795341 (120.55 GB)
telemt_user_msgs_from_client{user="hello"} 3120482
telemt_user_msgs_to_client{user="hello"} 16624834
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 42975.5 (11h 56m)
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