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

# Server Metrics 2026-03-11 08:38:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 65537.5 (18h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185980
telemt_connections_bad_total 3549
telemt_handshake_timeouts_total 4129
telemt_upstream_connect_attempt_total 169499
telemt_upstream_connect_success_total 169447
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 169499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 169439
telemt_user_connections_current{user="hello"} 398
telemt_user_octets_from_client{user="hello"} 3797049019 (3.54 GB)
telemt_user_octets_to_client{user="hello"} 105914428249 (98.64 GB)
telemt_user_msgs_from_client{user="hello"} 4098019
telemt_user_msgs_to_client{user="hello"} 7673491
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 65536.7 (18h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72060
telemt_connections_bad_total 589
telemt_handshake_timeouts_total 3109
telemt_upstream_connect_attempt_total 64964
telemt_upstream_connect_success_total 64950
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 64964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8888
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 238
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 64944
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 4889781220 (4.55 GB)
telemt_user_octets_to_client{user="hello"} 53230367331 (49.57 GB)
telemt_user_msgs_from_client{user="hello"} 3052387
telemt_user_msgs_to_client{user="hello"} 13520009
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 65536.4 (18h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100135
telemt_connections_bad_total 916
telemt_handshake_timeouts_total 5187
telemt_upstream_connect_attempt_total 88202
telemt_upstream_connect_success_total 88199
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 88202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9809
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 88191
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 11933193925 (11.11 GB)
telemt_user_octets_to_client{user="hello"} 75805330607 (70.60 GB)
telemt_user_msgs_from_client{user="hello"} 5482545
telemt_user_msgs_to_client{user="hello"} 14809879
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 65535.6 (18h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110555
telemt_connections_bad_total 223
telemt_handshake_timeouts_total 937
telemt_upstream_connect_attempt_total 105220
telemt_upstream_connect_success_total 104982
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 105219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14088
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 282
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 104974
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 4514008395 (4.20 GB)
telemt_user_octets_to_client{user="hello"} 72586897194 (67.60 GB)
telemt_user_msgs_from_client{user="hello"} 3114351
telemt_user_msgs_to_client{user="hello"} 18403026
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 65536.8 (18h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179047
telemt_connections_bad_total 14432
telemt_handshake_timeouts_total 3068
telemt_upstream_connect_attempt_total 142361
telemt_upstream_connect_success_total 142111
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 142361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20051
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 255
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 142105
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 2858295738 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 131858116985 (122.80 GB)
telemt_user_msgs_from_client{user="hello"} 3226851
telemt_user_msgs_to_client{user="hello"} 17015168
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 44506.1 (12h 21m)
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