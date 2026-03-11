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

# Server Metrics 2026-03-11 04:13:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 49633.7 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126458
telemt_connections_bad_total 3382
telemt_handshake_timeouts_total 2655
telemt_upstream_connect_attempt_total 114738
telemt_upstream_connect_success_total 114697
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 114738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 104593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10049
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 114691
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 2997386251 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 84063846396 (78.29 GB)
telemt_user_msgs_from_client{user="hello"} 3069365
telemt_user_msgs_to_client{user="hello"} 5844318
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 49633.3 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51996
telemt_connections_bad_total 401
telemt_handshake_timeouts_total 2941
telemt_upstream_connect_attempt_total 45914
telemt_upstream_connect_success_total 45904
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 45914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6959
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45898
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 2331530362 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 44176250413 (41.14 GB)
telemt_user_msgs_from_client{user="hello"} 1827779
telemt_user_msgs_to_client{user="hello"} 10518057
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 49633.0 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72860
telemt_connections_bad_total 672
telemt_handshake_timeouts_total 4239
telemt_upstream_connect_attempt_total 63912
telemt_upstream_connect_success_total 63909
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 63912
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7236
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63903
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 11765191506 (10.96 GB)
telemt_user_octets_to_client{user="hello"} 70813984201 (65.95 GB)
telemt_user_msgs_from_client{user="hello"} 5161442
telemt_user_msgs_to_client{user="hello"} 13283230
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 49631.9 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74484
telemt_connections_bad_total 152
telemt_handshake_timeouts_total 566
telemt_upstream_connect_attempt_total 71304
telemt_upstream_connect_success_total 71142
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 71303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9138
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 184
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 71136
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 1788448837 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 43327305524 (40.35 GB)
telemt_user_msgs_from_client{user="hello"} 1645622
telemt_user_msgs_to_client{user="hello"} 8537248
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 49633.2 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117830
telemt_connections_bad_total 11232
telemt_handshake_timeouts_total 1656
telemt_upstream_connect_attempt_total 100431
telemt_upstream_connect_success_total 100183
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 100431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 87746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 100177
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 2295524111 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 93078653595 (86.69 GB)
telemt_user_msgs_from_client{user="hello"} 2447386
telemt_user_msgs_to_client{user="hello"} 11950501
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 28602.6 (7h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```