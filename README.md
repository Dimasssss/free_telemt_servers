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

# Server Metrics 2026-03-11 13:30:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 83043.8 (23h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 269590
telemt_connections_bad_total 3657
telemt_handshake_timeouts_total 4725
telemt_upstream_connect_attempt_total 249199
telemt_upstream_connect_success_total 249123
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 249199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 228089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20975
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 249115
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 4881079228 (4.55 GB)
telemt_user_octets_to_client{user="hello"} 129140362208 (120.27 GB)
telemt_user_msgs_from_client{user="hello"} 5565402
telemt_user_msgs_to_client{user="hello"} 10187077
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 83042.9 (23h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104807
telemt_connections_bad_total 906
telemt_handshake_timeouts_total 3332
telemt_upstream_connect_attempt_total 96002
telemt_upstream_connect_success_total 95983
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 96002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 83219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12417
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 347
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 95975
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 5235037986 (4.88 GB)
telemt_user_octets_to_client{user="hello"} 64581743498 (60.15 GB)
telemt_user_msgs_from_client{user="hello"} 3558860
telemt_user_msgs_to_client{user="hello"} 18250135
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 83042.5 (23h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146174
telemt_connections_bad_total 1183
telemt_handshake_timeouts_total 6797
telemt_upstream_connect_attempt_total 130040
telemt_upstream_connect_success_total 130026
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 130040
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 115428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14500
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 130018
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 12560400067 (11.70 GB)
telemt_user_octets_to_client{user="hello"} 111868318335 (104.19 GB)
telemt_user_msgs_from_client{user="hello"} 6457605
telemt_user_msgs_to_client{user="hello"} 23947167
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 83041.5 (23h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161123
telemt_connections_bad_total 3591
telemt_handshake_timeouts_total 1907
telemt_upstream_connect_attempt_total 149148
telemt_upstream_connect_success_total 148796
telemt_upstream_connect_fail_total 352
telemt_upstream_connect_attempts_per_request{bucket="1"} 149148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 129289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19022
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 399
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 352
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 148788
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 8778776888 (8.18 GB)
telemt_user_octets_to_client{user="hello"} 108972654758 (101.49 GB)
telemt_user_msgs_from_client{user="hello"} 5281624
telemt_user_msgs_to_client{user="hello"} 32123683
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 83042.7 (23h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 237918
telemt_connections_bad_total 18457
telemt_handshake_timeouts_total 6129
telemt_upstream_connect_attempt_total 191902
telemt_upstream_connect_success_total 191400
telemt_upstream_connect_fail_total 502
telemt_upstream_connect_attempts_per_request{bucket="1"} 191902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 165559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25500
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 502
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 191392
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 4779573040 (4.45 GB)
telemt_user_octets_to_client{user="hello"} 155081990473 (144.43 GB)
telemt_user_msgs_from_client{user="hello"} 4540835
telemt_user_msgs_to_client{user="hello"} 21440542
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 62012.1 (17h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 440
telemt_connections_bad_total 418
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