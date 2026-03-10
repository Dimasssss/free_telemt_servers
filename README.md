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

# Server Metrics 2026-03-10 21:05:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 23956.2 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87200
telemt_connections_bad_total 3270
telemt_handshake_timeouts_total 2147
telemt_upstream_connect_attempt_total 77859
telemt_upstream_connect_success_total 77828
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 77859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6755
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 77824
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 2461893688 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 60214622404 (56.08 GB)
telemt_user_msgs_from_client{user="hello"} 2287311
telemt_user_msgs_to_client{user="hello"} 4104521
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 23955.6 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33342
telemt_connections_bad_total 313
telemt_handshake_timeouts_total 607
telemt_upstream_connect_attempt_total 30410
telemt_upstream_connect_success_total 30402
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 30410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4511
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30398
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 1568554577 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 26236647849 (24.43 GB)
telemt_user_msgs_from_client{user="hello"} 1213749
telemt_user_msgs_to_client{user="hello"} 7518968
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 23955.4 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53329
telemt_connections_bad_total 298
telemt_handshake_timeouts_total 3728
telemt_upstream_connect_attempt_total 46259
telemt_upstream_connect_success_total 46257
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 46259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4378
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46253
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 733156405 (699.19 MB)
telemt_user_octets_to_client{user="hello"} 42217656034 (39.32 GB)
telemt_user_msgs_from_client{user="hello"} 989158
telemt_user_msgs_to_client{user="hello"} 6339852
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 23954.3 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47639
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 315
telemt_upstream_connect_attempt_total 45732
telemt_upstream_connect_success_total 45600
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 45732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5319
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45596
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 767477242 (731.92 MB)
telemt_user_octets_to_client{user="hello"} 34642718502 (32.26 GB)
telemt_user_msgs_from_client{user="hello"} 1013468
telemt_user_msgs_to_client{user="hello"} 6608851
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 23955.6 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67641
telemt_connections_bad_total 6182
telemt_handshake_timeouts_total 1393
telemt_upstream_connect_attempt_total 57278
telemt_upstream_connect_success_total 57034
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 57278
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6968
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 57030
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 1833827342 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 44963301515 (41.88 GB)
telemt_user_msgs_from_client{user="hello"} 1649741
telemt_user_msgs_to_client{user="hello"} 6181446
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 2924.9 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16
telemt_connections_bad_total 16
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```