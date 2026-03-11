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

# Server Metrics 2026-03-11 07:52:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 62782.7 (17h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173964
telemt_connections_bad_total 3538
telemt_handshake_timeouts_total 4058
telemt_upstream_connect_attempt_total 157894
telemt_upstream_connect_success_total 157845
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 157894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 144120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13668
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 157837
telemt_user_connections_current{user="hello"} 318
telemt_user_octets_from_client{user="hello"} 3634789387 (3.39 GB)
telemt_user_octets_to_client{user="hello"} 101325701057 (94.37 GB)
telemt_user_msgs_from_client{user="hello"} 3887611
telemt_user_msgs_to_client{user="hello"} 7304479
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 62781.8 (17h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67931
telemt_connections_bad_total 581
telemt_handshake_timeouts_total 3078
telemt_upstream_connect_attempt_total 60988
telemt_upstream_connect_success_total 60974
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 60988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8455
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 234
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60968
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 4772121802 (4.44 GB)
telemt_user_octets_to_client{user="hello"} 51394708539 (47.87 GB)
telemt_user_msgs_from_client{user="hello"} 2953924
telemt_user_msgs_to_client{user="hello"} 12649578
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 62781.6 (17h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94189
telemt_connections_bad_total 881
telemt_handshake_timeouts_total 5153
telemt_upstream_connect_attempt_total 82576
telemt_upstream_connect_success_total 82573
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 82576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73346
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9166
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 82567
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 11904325791 (11.09 GB)
telemt_user_octets_to_client{user="hello"} 74957598789 (69.81 GB)
telemt_user_msgs_from_client{user="hello"} 5401673
telemt_user_msgs_to_client{user="hello"} 14506948
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 62780.5 (17h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101556
telemt_connections_bad_total 219
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 97173
telemt_upstream_connect_success_total 96958
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 97173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 83834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12806
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 266
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 96950
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 3581217588 (3.34 GB)
telemt_user_octets_to_client{user="hello"} 65799421351 (61.28 GB)
telemt_user_msgs_from_client{user="hello"} 2667219
telemt_user_msgs_to_client{user="hello"} 16291504
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 62781.9 (17h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168533
telemt_connections_bad_total 13921
telemt_handshake_timeouts_total 1913
telemt_upstream_connect_attempt_total 134491
telemt_upstream_connect_success_total 134241
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 134491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 115335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18662
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 134235
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 2609189457 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 127980717259 (119.19 GB)
telemt_user_msgs_from_client{user="hello"} 3048319
telemt_user_msgs_to_client{user="hello"} 16321394
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 41751.2 (11h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231
telemt_connections_bad_total 211
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 15
telemt_upstream_connect_success_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```