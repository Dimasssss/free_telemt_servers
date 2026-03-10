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

# Server Metrics 2026-03-10 23:07:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 31301.2 (8h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97386
telemt_connections_bad_total 3305
telemt_handshake_timeouts_total 2212
telemt_upstream_connect_attempt_total 87585
telemt_upstream_connect_success_total 87553
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 87585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7760
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 87549
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 2586153615 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 71771143409 (66.84 GB)
telemt_user_msgs_from_client{user="hello"} 2556219
telemt_user_msgs_to_client{user="hello"} 4915820
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 31300.5 (8h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37620
telemt_connections_bad_total 332
telemt_handshake_timeouts_total 841
telemt_upstream_connect_attempt_total 34194
telemt_upstream_connect_success_total 34185
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 34194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5096
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34181
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 1707036443 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 36234570025 (33.75 GB)
telemt_user_msgs_from_client{user="hello"} 1417956
telemt_user_msgs_to_client{user="hello"} 9051613
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 31300.4 (8h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60175
telemt_connections_bad_total 447
telemt_handshake_timeouts_total 4075
telemt_upstream_connect_attempt_total 52172
telemt_upstream_connect_success_total 52170
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 52172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5136
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 52166
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 793222900 (756.48 MB)
telemt_user_octets_to_client{user="hello"} 50243277831 (46.79 GB)
telemt_user_msgs_from_client{user="hello"} 1113223
telemt_user_msgs_to_client{user="hello"} 7469767
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 31299.3 (8h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55714
telemt_connections_bad_total 87
telemt_handshake_timeouts_total 331
telemt_upstream_connect_attempt_total 53487
telemt_upstream_connect_success_total 53336
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 53487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6311
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53332
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 828890665 (790.49 MB)
telemt_user_octets_to_client{user="hello"} 37433847601 (34.86 GB)
telemt_user_msgs_from_client{user="hello"} 1132075
telemt_user_msgs_to_client{user="hello"} 7173569
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 31300.6 (8h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81825
telemt_connections_bad_total 7655
telemt_handshake_timeouts_total 1467
telemt_upstream_connect_attempt_total 69547
telemt_upstream_connect_success_total 69299
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 69547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59929
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9158
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 69295
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 2071502223 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 55629630080 (51.81 GB)
telemt_user_msgs_from_client{user="hello"} 1950247
telemt_user_msgs_to_client{user="hello"} 8159190
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 10270.0 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```