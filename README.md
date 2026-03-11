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

# Server Metrics 2026-03-11 11:47:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 76897.8 (21h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236533
telemt_connections_bad_total 3631
telemt_handshake_timeouts_total 4514
telemt_upstream_connect_attempt_total 217802
telemt_upstream_connect_success_total 217733
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 217802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 199267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18409
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 217725
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 4521981479 (4.21 GB)
telemt_user_octets_to_client{user="hello"} 121729425178 (113.37 GB)
telemt_user_msgs_from_client{user="hello"} 5063671
telemt_user_msgs_to_client{user="hello"} 9340892
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 76896.7 (21h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92500
telemt_connections_bad_total 849
telemt_handshake_timeouts_total 3266
telemt_upstream_connect_attempt_total 84207
telemt_upstream_connect_success_total 84191
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 84207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 267
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 84183
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 5134532270 (4.78 GB)
telemt_user_octets_to_client{user="hello"} 57936582406 (53.96 GB)
telemt_user_msgs_from_client{user="hello"} 3360037
telemt_user_msgs_to_client{user="hello"} 15456287
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 76896.7 (21h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129380
telemt_connections_bad_total 1094
telemt_handshake_timeouts_total 6651
telemt_upstream_connect_attempt_total 114355
telemt_upstream_connect_success_total 114341
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 114355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 101461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12785
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 114333
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 12361616487 (11.51 GB)
telemt_user_octets_to_client{user="hello"} 88227080543 (82.17 GB)
telemt_user_msgs_from_client{user="hello"} 6050145
telemt_user_msgs_to_client{user="hello"} 17581940
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 76895.4 (21h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139982
telemt_connections_bad_total 335
telemt_handshake_timeouts_total 1366
telemt_upstream_connect_attempt_total 132737
telemt_upstream_connect_success_total 132430
telemt_upstream_connect_fail_total 307
telemt_upstream_connect_attempts_per_request{bucket="1"} 132737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 114874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17127
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 71
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 358
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 307
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 132422
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 5738702286 (5.34 GB)
telemt_user_octets_to_client{user="hello"} 100494757026 (93.59 GB)
telemt_user_msgs_from_client{user="hello"} 3977208
telemt_user_msgs_to_client{user="hello"} 28808429
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 76896.8 (21h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214688
telemt_connections_bad_total 16797
telemt_handshake_timeouts_total 3787
telemt_upstream_connect_attempt_total 173267
telemt_upstream_connect_success_total 172864
telemt_upstream_connect_fail_total 403
telemt_upstream_connect_attempts_per_request{bucket="1"} 173267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 149034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 316
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 403
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 172856
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 4182981454 (3.90 GB)
telemt_user_octets_to_client{user="hello"} 146045435813 (136.02 GB)
telemt_user_msgs_from_client{user="hello"} 4086299
telemt_user_msgs_to_client{user="hello"} 19845736
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 55866.2 (15h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 426
telemt_connections_bad_total 404
telemt_handshake_timeouts_total 10
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