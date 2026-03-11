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

# Server Metrics 2026-03-11 01:55:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 41382.8 (11h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111184
telemt_connections_bad_total 3353
telemt_handshake_timeouts_total 2541
telemt_upstream_connect_attempt_total 100227
telemt_upstream_connect_success_total 100191
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 100227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 91175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8962
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 100187
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 2771166729 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 80007020182 (74.51 GB)
telemt_user_msgs_from_client{user="hello"} 2844532
telemt_user_msgs_to_client{user="hello"} 5518302
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 41382.2 (11h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45922
telemt_connections_bad_total 361
telemt_handshake_timeouts_total 2131
telemt_upstream_connect_attempt_total 40860
telemt_upstream_connect_success_total 40851
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 40860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6072
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 40847
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 2134613470 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 38868400116 (36.20 GB)
telemt_user_msgs_from_client{user="hello"} 1665972
telemt_user_msgs_to_client{user="hello"} 9666423
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 41382.0 (11h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67181
telemt_connections_bad_total 639
telemt_handshake_timeouts_total 4137
telemt_upstream_connect_attempt_total 58617
telemt_upstream_connect_success_total 58615
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 58617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52304
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6262
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 58609
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 11623230100 (10.82 GB)
telemt_user_octets_to_client{user="hello"} 68844942793 (64.12 GB)
telemt_user_msgs_from_client{user="hello"} 5064358
telemt_user_msgs_to_client{user="hello"} 12775413
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 41380.8 (11h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65900
telemt_connections_bad_total 126
telemt_handshake_timeouts_total 539
telemt_upstream_connect_attempt_total 63056
telemt_upstream_connect_success_total 62901
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 63056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54873
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7833
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 62895
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 1748622524 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 42536914579 (39.62 GB)
telemt_user_msgs_from_client{user="hello"} 1571120
telemt_user_msgs_to_client{user="hello"} 8318727
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 41382.2 (11h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95329
telemt_connections_bad_total 9662
telemt_handshake_timeouts_total 1512
telemt_upstream_connect_attempt_total 80628
telemt_upstream_connect_success_total 80380
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 80628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 80376
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 2148284624 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 65913353004 (61.39 GB)
telemt_user_msgs_from_client{user="hello"} 2141022
telemt_user_msgs_to_client{user="hello"} 9499471
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 20351.5 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```