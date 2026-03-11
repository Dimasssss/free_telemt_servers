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

# Server Metrics 2026-03-11 12:18:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 78743.3 (21h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 246043
telemt_connections_bad_total 3635
telemt_handshake_timeouts_total 4605
telemt_upstream_connect_attempt_total 226794
telemt_upstream_connect_success_total 226722
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 226794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 207474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19191
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 226714
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 4618623564 (4.30 GB)
telemt_user_octets_to_client{user="hello"} 124030753757 (115.51 GB)
telemt_user_msgs_from_client{user="hello"} 5198676
telemt_user_msgs_to_client{user="hello"} 9595927
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 78742.5 (21h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95994
telemt_connections_bad_total 896
telemt_handshake_timeouts_total 3310
telemt_upstream_connect_attempt_total 87498
telemt_upstream_connect_success_total 87482
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 87498
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11409
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 276
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 87474
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 5165442179 (4.81 GB)
telemt_user_octets_to_client{user="hello"} 59024345238 (54.97 GB)
telemt_user_msgs_from_client{user="hello"} 3410768
telemt_user_msgs_to_client{user="hello"} 16000778
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 78742.2 (21h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133921
telemt_connections_bad_total 1099
telemt_handshake_timeouts_total 6696
telemt_upstream_connect_attempt_total 118599
telemt_upstream_connect_success_total 118585
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 118599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13299
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 118577
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 12425401200 (11.57 GB)
telemt_user_octets_to_client{user="hello"} 88975812978 (82.87 GB)
telemt_user_msgs_from_client{user="hello"} 6137998
telemt_user_msgs_to_client{user="hello"} 17827612
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 78741.3 (21h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145764
telemt_connections_bad_total 341
telemt_handshake_timeouts_total 1862
telemt_upstream_connect_attempt_total 137595
telemt_upstream_connect_success_total 137274
telemt_upstream_connect_fail_total 321
telemt_upstream_connect_attempts_per_request{bucket="1"} 137595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 119139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17699
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 71
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 321
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 137266
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 6554561014 (6.10 GB)
telemt_user_octets_to_client{user="hello"} 102723312502 (95.67 GB)
telemt_user_msgs_from_client{user="hello"} 4329752
telemt_user_msgs_to_client{user="hello"} 29673436
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 78742.4 (21h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221458
telemt_connections_bad_total 17352
telemt_handshake_timeouts_total 3850
telemt_upstream_connect_attempt_total 179226
telemt_upstream_connect_success_total 178822
telemt_upstream_connect_fail_total 404
telemt_upstream_connect_attempts_per_request{bucket="1"} 179226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 319
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 404
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 178814
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 4669700937 (4.35 GB)
telemt_user_octets_to_client{user="hello"} 148922960353 (138.70 GB)
telemt_user_msgs_from_client{user="hello"} 4336688
telemt_user_msgs_to_client{user="hello"} 20396673
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 57712.0 (16h 1m)
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