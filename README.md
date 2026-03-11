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

# Server Metrics 2026-03-11 11:58:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 77513.8 (21h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239361
telemt_connections_bad_total 3633
telemt_handshake_timeouts_total 4526
telemt_upstream_connect_attempt_total 220521
telemt_upstream_connect_success_total 220451
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 220521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 201815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 220443
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 4552635295 (4.24 GB)
telemt_user_octets_to_client{user="hello"} 122434626756 (114.03 GB)
telemt_user_msgs_from_client{user="hello"} 5101665
telemt_user_msgs_to_client{user="hello"} 9414881
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 77513.0 (21h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93791
telemt_connections_bad_total 893
telemt_handshake_timeouts_total 3296
telemt_upstream_connect_attempt_total 85370
telemt_upstream_connect_success_total 85354
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 85370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 267
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 85346
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 5141984248 (4.79 GB)
telemt_user_octets_to_client{user="hello"} 58199076255 (54.20 GB)
telemt_user_msgs_from_client{user="hello"} 3377145
telemt_user_msgs_to_client{user="hello"} 15593948
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 77512.7 (21h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130876
telemt_connections_bad_total 1094
telemt_handshake_timeouts_total 6685
telemt_upstream_connect_attempt_total 115720
telemt_upstream_connect_success_total 115706
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 115720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 102706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12905
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 115698
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 12383780721 (11.53 GB)
telemt_user_octets_to_client{user="hello"} 88332705232 (82.27 GB)
telemt_user_msgs_from_client{user="hello"} 6077261
telemt_user_msgs_to_client{user="hello"} 17630475
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 77511.9 (21h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142135
telemt_connections_bad_total 337
telemt_handshake_timeouts_total 1716
telemt_upstream_connect_attempt_total 134298
telemt_upstream_connect_success_total 133985
telemt_upstream_connect_fail_total 313
telemt_upstream_connect_attempts_per_request{bucket="1"} 134298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 116213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17338
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 71
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 363
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 313
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 133977
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 5828640721 (5.43 GB)
telemt_user_octets_to_client{user="hello"} 100757051786 (93.84 GB)
telemt_user_msgs_from_client{user="hello"} 4030282
telemt_user_msgs_to_client{user="hello"} 28914165
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 77512.9 (21h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216716
telemt_connections_bad_total 16910
telemt_handshake_timeouts_total 3826
telemt_upstream_connect_attempt_total 175073
telemt_upstream_connect_success_total 174669
telemt_upstream_connect_fail_total 404
telemt_upstream_connect_attempts_per_request{bucket="1"} 175073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 150629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23722
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 318
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 404
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 174661
telemt_user_connections_current{user="hello"} 281
telemt_user_octets_from_client{user="hello"} 4499333994 (4.19 GB)
telemt_user_octets_to_client{user="hello"} 146733699566 (136.66 GB)
telemt_user_msgs_from_client{user="hello"} 4221000
telemt_user_msgs_to_client{user="hello"} 20037169
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 56482.3 (15h 41m)
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