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

# Server Metrics 2026-03-11 00:14:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 35273.1 (9h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102305
telemt_connections_bad_total 3338
telemt_handshake_timeouts_total 2488
telemt_upstream_connect_attempt_total 91951
telemt_upstream_connect_success_total 91919
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 91951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 83594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8272
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 91915
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 2674636073 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 75197161454 (70.03 GB)
telemt_user_msgs_from_client{user="hello"} 2673955
telemt_user_msgs_to_client{user="hello"} 5131244
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 35272.6 (9h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40237
telemt_connections_bad_total 340
telemt_handshake_timeouts_total 964
telemt_upstream_connect_attempt_total 36577
telemt_upstream_connect_success_total 36568
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 36577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5471
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36564
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 2005632639 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 38340346746 (35.71 GB)
telemt_user_msgs_from_client{user="hello"} 1574222
telemt_user_msgs_to_client{user="hello"} 9456708
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 35272.4 (9h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63102
telemt_connections_bad_total 455
telemt_handshake_timeouts_total 4088
telemt_upstream_connect_attempt_total 54969
telemt_upstream_connect_success_total 54967
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 54969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5557
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 54963
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 3629545865 (3.38 GB)
telemt_user_octets_to_client{user="hello"} 56985906854 (53.07 GB)
telemt_user_msgs_from_client{user="hello"} 2164259
telemt_user_msgs_to_client{user="hello"} 8400869
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 35271.2 (9h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59892
telemt_connections_bad_total 97
telemt_handshake_timeouts_total 526
telemt_upstream_connect_attempt_total 57311
telemt_upstream_connect_success_total 57158
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 57311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6959
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 57154
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 843309320 (804.24 MB)
telemt_user_octets_to_client{user="hello"} 37926924033 (35.32 GB)
telemt_user_msgs_from_client{user="hello"} 1167806
telemt_user_msgs_to_client{user="hello"} 7326067
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 35272.6 (9h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86934
telemt_connections_bad_total 8402
telemt_handshake_timeouts_total 1471
telemt_upstream_connect_attempt_total 73796
telemt_upstream_connect_success_total 73545
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 73793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9726
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 73541
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 2098366630 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 58164700232 (54.17 GB)
telemt_user_msgs_from_client{user="hello"} 2017416
telemt_user_msgs_to_client{user="hello"} 8432945
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 14242.0 (3h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42
telemt_connections_bad_total 39
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```