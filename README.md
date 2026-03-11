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

# Server Metrics 2026-03-11 15:53:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 91649.5 (25h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 312970
telemt_connections_bad_total 5504
telemt_handshake_timeouts_total 5438
telemt_upstream_connect_attempt_total 288098
telemt_upstream_connect_success_total 288018
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 288098
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 263261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 288008
telemt_user_connections_current{user="hello"} 318
telemt_user_octets_from_client{user="hello"} 5360687145 (4.99 GB)
telemt_user_octets_to_client{user="hello"} 140031849642 (130.41 GB)
telemt_user_msgs_from_client{user="hello"} 6205570
telemt_user_msgs_to_client{user="hello"} 11321403
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 91648.7 (25h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123772
telemt_connections_bad_total 973
telemt_handshake_timeouts_total 3419
telemt_upstream_connect_attempt_total 114136
telemt_upstream_connect_success_total 114113
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 114136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 99312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 535
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 114103
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 6074638855 (5.66 GB)
telemt_user_octets_to_client{user="hello"} 70300460834 (65.47 GB)
telemt_user_msgs_from_client{user="hello"} 4093946
telemt_user_msgs_to_client{user="hello"} 20489198
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 91648.4 (25h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169354
telemt_connections_bad_total 1438
telemt_handshake_timeouts_total 7267
telemt_upstream_connect_attempt_total 151323
telemt_upstream_connect_success_total 151309
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 151323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 134306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16897
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 151299
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 12756911357 (11.88 GB)
telemt_user_octets_to_client{user="hello"} 132287631667 (123.20 GB)
telemt_user_msgs_from_client{user="hello"} 6905259
telemt_user_msgs_to_client{user="hello"} 29804560
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 91647.4 (25h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190667
telemt_connections_bad_total 9405
telemt_handshake_timeouts_total 2668
telemt_upstream_connect_attempt_total 170974
telemt_upstream_connect_success_total 170561
telemt_upstream_connect_fail_total 413
telemt_upstream_connect_attempts_per_request{bucket="1"} 170974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 148746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21259
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 95
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 461
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 413
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 170551
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 9968968528 (9.28 GB)
telemt_user_octets_to_client{user="hello"} 116562152732 (108.56 GB)
telemt_user_msgs_from_client{user="hello"} 5972726
telemt_user_msgs_to_client{user="hello"} 34885851
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 91648.8 (25h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 267102
telemt_connections_bad_total 20094
telemt_handshake_timeouts_total 6364
telemt_upstream_connect_attempt_total 218363
telemt_upstream_connect_success_total 217858
telemt_upstream_connect_fail_total 505
telemt_upstream_connect_attempts_per_request{bucket="1"} 218363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 188790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28700
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 505
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 217850
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 5143308872 (4.79 GB)
telemt_user_octets_to_client{user="hello"} 174809200560 (162.80 GB)
telemt_user_msgs_from_client{user="hello"} 5108202
telemt_user_msgs_to_client{user="hello"} 24473060
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 70618.2 (19h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 472
telemt_connections_bad_total 449
telemt_handshake_timeouts_total 12
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