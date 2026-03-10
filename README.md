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

# Server Metrics 2026-03-10 22:01:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 27323.2 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92648
telemt_connections_bad_total 3289
telemt_handshake_timeouts_total 2179
telemt_upstream_connect_attempt_total 83051
telemt_upstream_connect_success_total 83019
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 83051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 83015
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 2528048736 (2.35 GB)
telemt_user_octets_to_client{user="hello"} 65793432228 (61.27 GB)
telemt_user_msgs_from_client{user="hello"} 2410073
telemt_user_msgs_to_client{user="hello"} 4342708
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 27322.6 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35212
telemt_connections_bad_total 319
telemt_handshake_timeouts_total 691
telemt_upstream_connect_attempt_total 32088
telemt_upstream_connect_success_total 32079
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 32088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32075
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 1660714498 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 32936362500 (30.67 GB)
telemt_user_msgs_from_client{user="hello"} 1326601
telemt_user_msgs_to_client{user="hello"} 8411310
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 27322.2 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57253
telemt_connections_bad_total 423
telemt_handshake_timeouts_total 3965
telemt_upstream_connect_attempt_total 49632
telemt_upstream_connect_success_total 49630
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 49632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4730
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49626
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 763922895 (728.53 MB)
telemt_user_octets_to_client{user="hello"} 46224958538 (43.05 GB)
telemt_user_msgs_from_client{user="hello"} 1059484
telemt_user_msgs_to_client{user="hello"} 6967464
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 27321.3 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52527
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 322
telemt_upstream_connect_attempt_total 50434
telemt_upstream_connect_success_total 50292
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 50434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5920
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50288
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 814367520 (776.64 MB)
telemt_user_octets_to_client{user="hello"} 36889869381 (34.36 GB)
telemt_user_msgs_from_client{user="hello"} 1098271
telemt_user_msgs_to_client{user="hello"} 7014449
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 27322.5 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75745
telemt_connections_bad_total 6855
telemt_handshake_timeouts_total 1408
telemt_upstream_connect_attempt_total 64467
telemt_upstream_connect_success_total 64223
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 64467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8469
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 64219
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 2009655724 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 49051780143 (45.68 GB)
telemt_user_msgs_from_client{user="hello"} 1820524
telemt_user_msgs_to_client{user="hello"} 7038498
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 6291.9 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```