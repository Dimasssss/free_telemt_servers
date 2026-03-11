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

# Server Metrics 2026-03-11 15:02:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 88577.1 (24h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 296286
telemt_connections_bad_total 4098
telemt_handshake_timeouts_total 4869
telemt_upstream_connect_attempt_total 274025
telemt_upstream_connect_success_total 273945
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 274025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 250570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23314
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 273935
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 5104004396 (4.75 GB)
telemt_user_octets_to_client{user="hello"} 136860828193 (127.46 GB)
telemt_user_msgs_from_client{user="hello"} 5963213
telemt_user_msgs_to_client{user="hello"} 10944272
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 88576.4 (24h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117490
telemt_connections_bad_total 966
telemt_handshake_timeouts_total 3396
telemt_upstream_connect_attempt_total 108049
telemt_upstream_connect_success_total 108028
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 108049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13744
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 478
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 108018
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 5986486066 (5.58 GB)
telemt_user_octets_to_client{user="hello"} 69074742152 (64.33 GB)
telemt_user_msgs_from_client{user="hello"} 3979496
telemt_user_msgs_to_client{user="hello"} 19956656
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 88576.1 (24h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162170
telemt_connections_bad_total 1251
telemt_handshake_timeouts_total 7025
telemt_upstream_connect_attempt_total 144842
telemt_upstream_connect_success_total 144828
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 144842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 128658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16067
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 144818
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 12708386681 (11.84 GB)
telemt_user_octets_to_client{user="hello"} 128718438783 (119.88 GB)
telemt_user_msgs_from_client{user="hello"} 6777877
telemt_user_msgs_to_client{user="hello"} 28812091
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 88575.2 (24h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180410
telemt_connections_bad_total 7532
telemt_handshake_timeouts_total 2092
telemt_upstream_connect_attempt_total 163595
telemt_upstream_connect_success_total 163192
telemt_upstream_connect_fail_total 403
telemt_upstream_connect_attempts_per_request{bucket="1"} 163595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 142013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20641
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 447
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 403
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 163182
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 9735342694 (9.07 GB)
telemt_user_octets_to_client{user="hello"} 113583956840 (105.78 GB)
telemt_user_msgs_from_client{user="hello"} 5796389
telemt_user_msgs_to_client{user="hello"} 33888194
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 88576.2 (24h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257060
telemt_connections_bad_total 19536
telemt_handshake_timeouts_total 6323
telemt_upstream_connect_attempt_total 209229
telemt_upstream_connect_success_total 208725
telemt_upstream_connect_fail_total 504
telemt_upstream_connect_attempts_per_request{bucket="1"} 209229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 180743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27626
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 504
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 208717
telemt_user_connections_current{user="hello"} 346
telemt_user_octets_from_client{user="hello"} 5062760726 (4.72 GB)
telemt_user_octets_to_client{user="hello"} 171762879024 (159.97 GB)
telemt_user_msgs_from_client{user="hello"} 4944814
telemt_user_msgs_to_client{user="hello"} 23782835
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 67545.6 (18h 45m)
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