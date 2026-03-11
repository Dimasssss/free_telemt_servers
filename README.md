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

# Server Metrics 2026-03-11 01:35:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 40159.9 (11h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108900
telemt_connections_bad_total 3353
telemt_handshake_timeouts_total 2528
telemt_upstream_connect_attempt_total 98230
telemt_upstream_connect_success_total 98195
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 98230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 89305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8836
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 98191
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 2753863346 (2.56 GB)
telemt_user_octets_to_client{user="hello"} 78839029489 (73.42 GB)
telemt_user_msgs_from_client{user="hello"} 2808665
telemt_user_msgs_to_client{user="hello"} 5420683
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 40159.3 (11h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44673
telemt_connections_bad_total 356
telemt_handshake_timeouts_total 1806
telemt_upstream_connect_attempt_total 39965
telemt_upstream_connect_success_total 39956
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 39965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5901
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39952
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 2023473639 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 38764994130 (36.10 GB)
telemt_user_msgs_from_client{user="hello"} 1618644
telemt_user_msgs_to_client{user="hello"} 9620057
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 40159.0 (11h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66327
telemt_connections_bad_total 584
telemt_handshake_timeouts_total 4128
telemt_upstream_connect_attempt_total 57858
telemt_upstream_connect_success_total 57856
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 57858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6126
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 57852
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 9887461670 (9.21 GB)
telemt_user_octets_to_client{user="hello"} 66466316924 (61.90 GB)
telemt_user_msgs_from_client{user="hello"} 4437310
telemt_user_msgs_to_client{user="hello"} 11939175
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 40158.0 (11h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64722
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 532
telemt_upstream_connect_attempt_total 61933
telemt_upstream_connect_success_total 61778
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 61933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7623
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 61774
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 1744558832 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 42497842418 (39.58 GB)
telemt_user_msgs_from_client{user="hello"} 1560304
telemt_user_msgs_to_client{user="hello"} 8299932
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 40159.2 (11h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93477
telemt_connections_bad_total 9391
telemt_handshake_timeouts_total 1495
telemt_upstream_connect_attempt_total 79176
telemt_upstream_connect_success_total 78928
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 79176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10215
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 78924
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 2133058756 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 62285604029 (58.01 GB)
telemt_user_msgs_from_client{user="hello"} 2101829
telemt_user_msgs_to_client{user="hello"} 9079034
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 19128.7 (5h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56
telemt_connections_bad_total 52
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```