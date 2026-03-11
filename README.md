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

# Server Metrics 2026-03-11 09:19:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 67992.2 (18h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197100
telemt_connections_bad_total 3564
telemt_handshake_timeouts_total 4216
telemt_upstream_connect_attempt_total 180144
telemt_upstream_connect_success_total 180088
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 180144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 164377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15654
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 180080
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 3972021594 (3.70 GB)
telemt_user_octets_to_client{user="hello"} 108490500454 (101.04 GB)
telemt_user_msgs_from_client{user="hello"} 4292372
telemt_user_msgs_to_client{user="hello"} 8031926
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 67991.5 (18h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76458
telemt_connections_bad_total 689
telemt_handshake_timeouts_total 3138
telemt_upstream_connect_attempt_total 69073
telemt_upstream_connect_success_total 69058
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 69073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9423
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 249
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 69050
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 4932299042 (4.59 GB)
telemt_user_octets_to_client{user="hello"} 54081893480 (50.37 GB)
telemt_user_msgs_from_client{user="hello"} 3111570
telemt_user_msgs_to_client{user="hello"} 13920408
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 67991.8 (18h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106134
telemt_connections_bad_total 932
telemt_handshake_timeouts_total 5210
telemt_upstream_connect_attempt_total 93926
telemt_upstream_connect_success_total 93922
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 93926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 83303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10556
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 93914
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 11972988281 (11.15 GB)
telemt_user_octets_to_client{user="hello"} 78939105560 (73.52 GB)
telemt_user_msgs_from_client{user="hello"} 5582838
telemt_user_msgs_to_client{user="hello"} 15380883
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 67990.3 (18h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117191
telemt_connections_bad_total 227
telemt_handshake_timeouts_total 1055
telemt_upstream_connect_attempt_total 111327
telemt_upstream_connect_success_total 111077
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 111327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 95797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14919
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 57
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 304
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 111069
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 4799201811 (4.47 GB)
telemt_user_octets_to_client{user="hello"} 80253383577 (74.74 GB)
telemt_user_msgs_from_client{user="hello"} 3312196
telemt_user_msgs_to_client{user="hello"} 20612655
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 67991.4 (18h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186253
telemt_connections_bad_total 14875
telemt_handshake_timeouts_total 3104
telemt_upstream_connect_attempt_total 148858
telemt_upstream_connect_success_total 148456
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 148858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 127253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20924
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 279
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 148450
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 2900565904 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 134047926483 (124.84 GB)
telemt_user_msgs_from_client{user="hello"} 3321044
telemt_user_msgs_to_client{user="hello"} 17454179
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 46960.8 (13h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420
telemt_connections_bad_total 398
telemt_handshake_timeouts_total 9
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