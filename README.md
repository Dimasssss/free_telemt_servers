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

# Server Metrics 2026-03-11 08:43:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 65843.7 (18h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187287
telemt_connections_bad_total 3550
telemt_handshake_timeouts_total 4147
telemt_upstream_connect_attempt_total 170754
telemt_upstream_connect_success_total 170702
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 170754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14801
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 170694
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 3812400889 (3.55 GB)
telemt_user_octets_to_client{user="hello"} 106286637047 (98.99 GB)
telemt_user_msgs_from_client{user="hello"} 4119354
telemt_user_msgs_to_client{user="hello"} 7718317
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 65843.0 (18h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72609
telemt_connections_bad_total 589
telemt_handshake_timeouts_total 3132
telemt_upstream_connect_attempt_total 65464
telemt_upstream_connect_success_total 65450
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 65464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8963
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 238
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 65444
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 4896447816 (4.56 GB)
telemt_user_octets_to_client{user="hello"} 53311322238 (49.65 GB)
telemt_user_msgs_from_client{user="hello"} 3059106
telemt_user_msgs_to_client{user="hello"} 13565768
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 65842.7 (18h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100708
telemt_connections_bad_total 916
telemt_handshake_timeouts_total 5189
telemt_upstream_connect_attempt_total 88754
telemt_upstream_connect_success_total 88751
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 88754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9852
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 88743
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 11936200554 (11.12 GB)
telemt_user_octets_to_client{user="hello"} 76038580356 (70.82 GB)
telemt_user_msgs_from_client{user="hello"} 5492003
telemt_user_msgs_to_client{user="hello"} 14866243
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 65841.7 (18h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111410
telemt_connections_bad_total 224
telemt_handshake_timeouts_total 947
telemt_upstream_connect_attempt_total 106022
telemt_upstream_connect_success_total 105782
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 106022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 91265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14177
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 105774
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 4529293549 (4.22 GB)
telemt_user_octets_to_client{user="hello"} 72917684476 (67.91 GB)
telemt_user_msgs_from_client{user="hello"} 3129666
telemt_user_msgs_to_client{user="hello"} 18494862
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 65843.1 (18h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180099
telemt_connections_bad_total 14486
telemt_handshake_timeouts_total 3076
telemt_upstream_connect_attempt_total 143308
telemt_upstream_connect_success_total 142907
telemt_upstream_connect_fail_total 401
telemt_upstream_connect_attempts_per_request{bucket="1"} 143308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 122465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 273
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 401
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 142901
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 2861875726 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 131937327866 (122.88 GB)
telemt_user_msgs_from_client{user="hello"} 3234085
telemt_user_msgs_to_client{user="hello"} 17036303
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 44812.4 (12h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 411
telemt_connections_bad_total 389
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