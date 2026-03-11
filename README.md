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

# Server Metrics 2026-03-11 12:13:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 78436.0 (21h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244475
telemt_connections_bad_total 3635
telemt_handshake_timeouts_total 4584
telemt_upstream_connect_attempt_total 225287
telemt_upstream_connect_success_total 225216
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 225287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 206110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19049
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 225208
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 4602626218 (4.29 GB)
telemt_user_octets_to_client{user="hello"} 123743069822 (115.24 GB)
telemt_user_msgs_from_client{user="hello"} 5176518
telemt_user_msgs_to_client{user="hello"} 9560424
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 78435.3 (21h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95364
telemt_connections_bad_total 895
telemt_handshake_timeouts_total 3306
telemt_upstream_connect_attempt_total 86887
telemt_upstream_connect_success_total 86871
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 86887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 274
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 86863
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 5162305394 (4.81 GB)
telemt_user_octets_to_client{user="hello"} 58898099520 (54.85 GB)
telemt_user_msgs_from_client{user="hello"} 3402886
telemt_user_msgs_to_client{user="hello"} 15948438
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 78434.8 (21h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133227
telemt_connections_bad_total 1098
telemt_handshake_timeouts_total 6696
telemt_upstream_connect_attempt_total 117926
telemt_upstream_connect_success_total 117912
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 117926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 104605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13212
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 117904
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 12419600545 (11.57 GB)
telemt_user_octets_to_client{user="hello"} 88616599599 (82.53 GB)
telemt_user_msgs_from_client{user="hello"} 6121417
telemt_user_msgs_to_client{user="hello"} 17749138
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 78434.0 (21h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144790
telemt_connections_bad_total 339
telemt_handshake_timeouts_total 1857
telemt_upstream_connect_attempt_total 136698
telemt_upstream_connect_success_total 136381
telemt_upstream_connect_fail_total 317
telemt_upstream_connect_attempts_per_request{bucket="1"} 136698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 118334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17611
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 71
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 317
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 136373
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 6168168134 (5.74 GB)
telemt_user_octets_to_client{user="hello"} 101751141147 (94.76 GB)
telemt_user_msgs_from_client{user="hello"} 4180233
telemt_user_msgs_to_client{user="hello"} 29280612
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 78435.3 (21h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220220
telemt_connections_bad_total 17129
telemt_handshake_timeouts_total 3841
telemt_upstream_connect_attempt_total 178280
telemt_upstream_connect_success_total 177876
telemt_upstream_connect_fail_total 404
telemt_upstream_connect_attempts_per_request{bucket="1"} 178280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 153450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 319
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 404
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 177868
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 4662557015 (4.34 GB)
telemt_user_octets_to_client{user="hello"} 148274628225 (138.09 GB)
telemt_user_msgs_from_client{user="hello"} 4319647
telemt_user_msgs_to_client{user="hello"} 20273573
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 57404.7 (15h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 428
telemt_connections_bad_total 406
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