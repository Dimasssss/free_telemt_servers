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

# Server Metrics 2026-03-12 04:32:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 24469.3 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54044
telemt_connections_bad_total 2084
telemt_handshake_timeouts_total 709
telemt_upstream_connect_attempt_total 48862
telemt_upstream_connect_success_total 48848
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 48862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6425
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 48844
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 529386073 (504.86 MB)
telemt_user_octets_to_client{user="hello"} 15291758378 (14.24 GB)
telemt_user_msgs_from_client{user="hello"} 772852
telemt_user_msgs_to_client{user="hello"} 1853444
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 24457.4 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21017
telemt_connections_bad_total 138
telemt_handshake_timeouts_total 109
telemt_upstream_connect_attempt_total 19985
telemt_upstream_connect_success_total 19982
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 19985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2481
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19978
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 179490912 (171.18 MB)
telemt_user_octets_to_client{user="hello"} 11489987264 (10.70 GB)
telemt_user_msgs_from_client{user="hello"} 378209
telemt_user_msgs_to_client{user="hello"} 3157270
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 24431.0 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35660
telemt_connections_bad_total 447
telemt_handshake_timeouts_total 952
telemt_upstream_connect_attempt_total 31702
telemt_upstream_connect_success_total 31702
telemt_upstream_connect_attempts_per_request{bucket="1"} 31702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31698
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 5285755476 (4.92 GB)
telemt_user_octets_to_client{user="hello"} 20757697596 (19.33 GB)
telemt_user_msgs_from_client{user="hello"} 2407471
telemt_user_msgs_to_client{user="hello"} 3767572
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 24456.5 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36336
telemt_connections_bad_total 8656
telemt_handshake_timeouts_total 748
telemt_upstream_connect_attempt_total 25800
telemt_upstream_connect_success_total 24100
telemt_upstream_connect_fail_total 1700
telemt_upstream_connect_attempts_per_request{bucket="1"} 25800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3785
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1700
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24096
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 232033270 (221.28 MB)
telemt_user_octets_to_client{user="hello"} 19652740979 (18.30 GB)
telemt_user_msgs_from_client{user="hello"} 460243
telemt_user_msgs_to_client{user="hello"} 8209399
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 24457.3 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31907
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 173
telemt_upstream_connect_attempt_total 29744
telemt_upstream_connect_success_total 29743
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 29744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4894
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29741
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 634757671 (605.35 MB)
telemt_user_octets_to_client{user="hello"} 32714672698 (30.47 GB)
telemt_user_msgs_from_client{user="hello"} 863798
telemt_user_msgs_to_client{user="hello"} 4280776
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 19
```