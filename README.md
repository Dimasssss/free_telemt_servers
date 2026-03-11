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

# Server Metrics 2026-03-11 03:42:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 47800.7 (13h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122141
telemt_connections_bad_total 3374
telemt_handshake_timeouts_total 2597
telemt_upstream_connect_attempt_total 110629
telemt_upstream_connect_success_total 110590
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 110629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 100742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9794
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 110584
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 2960151915 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 82943866239 (77.25 GB)
telemt_user_msgs_from_client{user="hello"} 3010863
telemt_user_msgs_to_client{user="hello"} 5753019
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 47799.9 (13h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50884
telemt_connections_bad_total 399
telemt_handshake_timeouts_total 2925
telemt_upstream_connect_attempt_total 44858
telemt_upstream_connect_success_total 44848
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 44858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6846
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44842
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 2318417292 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 44084964370 (41.06 GB)
telemt_user_msgs_from_client{user="hello"} 1806991
telemt_user_msgs_to_client{user="hello"} 10479082
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 47799.7 (13h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71412
telemt_connections_bad_total 667
telemt_handshake_timeouts_total 4231
telemt_upstream_connect_attempt_total 62533
telemt_upstream_connect_success_total 62531
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 62533
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55422
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7059
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 62525
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 11748527047 (10.94 GB)
telemt_user_octets_to_client{user="hello"} 70616504181 (65.77 GB)
telemt_user_msgs_from_client{user="hello"} 5142338
telemt_user_msgs_to_client{user="hello"} 13226662
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 47798.6 (13h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72021
telemt_connections_bad_total 152
telemt_handshake_timeouts_total 559
telemt_upstream_connect_attempt_total 68911
telemt_upstream_connect_success_total 68752
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 68911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8759
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 182
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 68746
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 1778539487 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 42912582210 (39.97 GB)
telemt_user_msgs_from_client{user="hello"} 1623186
telemt_user_msgs_to_client{user="hello"} 8444777
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 47799.8 (13h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113511
telemt_connections_bad_total 10888
telemt_handshake_timeouts_total 1648
telemt_upstream_connect_attempt_total 96597
telemt_upstream_connect_success_total 96349
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 96597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 96343
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 2268727703 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 89302975523 (83.17 GB)
telemt_user_msgs_from_client{user="hello"} 2393396
telemt_user_msgs_to_client{user="hello"} 11651958
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 26769.1 (7h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113
telemt_connections_bad_total 107
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```