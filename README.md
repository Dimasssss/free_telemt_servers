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

# Server Metrics 2026-03-11 20:10:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 11413.8 (3h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42145
telemt_connections_bad_total 2482
telemt_handshake_timeouts_total 208
telemt_upstream_connect_attempt_total 37626
telemt_upstream_connect_success_total 37617
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 37626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3495
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37615
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 1006679617 (960.04 MB)
telemt_user_octets_to_client{user="hello"} 20934763462 (19.50 GB)
telemt_user_msgs_from_client{user="hello"} 966939
telemt_user_msgs_to_client{user="hello"} 1819977
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 11402.2 (3h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19648
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 255
telemt_upstream_connect_attempt_total 18094
telemt_upstream_connect_success_total 18055
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 18094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 323
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18053
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 218768222 (208.63 MB)
telemt_user_octets_to_client{user="hello"} 9052244394 (8.43 GB)
telemt_user_msgs_from_client{user="hello"} 369914
telemt_user_msgs_to_client{user="hello"} 3545230
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 11422.1 (3h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23509
telemt_connections_bad_total 28
telemt_handshake_timeouts_total 196
telemt_upstream_connect_attempt_total 21966
telemt_upstream_connect_success_total 21964
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 21966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19978
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1968
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21962
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 217733474 (207.65 MB)
telemt_user_octets_to_client{user="hello"} 9102282031 (8.48 GB)
telemt_user_msgs_from_client{user="hello"} 431273
telemt_user_msgs_to_client{user="hello"} 2282304
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 11417.7 (3h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25528
telemt_connections_bad_total 1801
telemt_handshake_timeouts_total 383
telemt_upstream_connect_attempt_total 22328
telemt_upstream_connect_success_total 22261
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 22328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2058
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22259
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 646584100 (616.63 MB)
telemt_user_octets_to_client{user="hello"} 11731326183 (10.93 GB)
telemt_user_msgs_from_client{user="hello"} 536996
telemt_user_msgs_to_client{user="hello"} 3290925
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 11425.6 (3h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28192
telemt_connections_bad_total 2177
telemt_handshake_timeouts_total 166
telemt_upstream_connect_attempt_total 24966
telemt_upstream_connect_success_total 24965
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 24966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3022
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24963
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 462362996 (440.94 MB)
telemt_user_octets_to_client{user="hello"} 9184856622 (8.55 GB)
telemt_user_msgs_from_client{user="hello"} 565758
telemt_user_msgs_to_client{user="hello"} 3328897
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 86032.1 (23h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 686
telemt_connections_bad_total 493
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 172
telemt_upstream_connect_success_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 164
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 1009670 (986.01 KB)
telemt_user_octets_to_client{user="hello"} 56725156 (54.10 MB)
telemt_user_msgs_from_client{user="hello"} 2198
telemt_user_msgs_to_client{user="hello"} 8816
telemt_user_unique_ips_current{user="hello"} 2
```