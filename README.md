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

# Server Metrics 2026-03-11 14:31:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 86734.8 (24h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286938
telemt_connections_bad_total 3681
telemt_handshake_timeouts_total 4793
telemt_upstream_connect_attempt_total 265645
telemt_upstream_connect_success_total 265568
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 265645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 242993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 265558
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 5050611501 (4.70 GB)
telemt_user_octets_to_client{user="hello"} 134684765676 (125.43 GB)
telemt_user_msgs_from_client{user="hello"} 5845920
telemt_user_msgs_to_client{user="hello"} 10687560
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 86734.4 (24h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113501
telemt_connections_bad_total 922
telemt_handshake_timeouts_total 3367
telemt_upstream_connect_attempt_total 104238
telemt_upstream_connect_success_total 104217
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 104238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13406
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 453
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 104207
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 5957967174 (5.55 GB)
telemt_user_octets_to_client{user="hello"} 68302789810 (63.61 GB)
telemt_user_msgs_from_client{user="hello"} 3924316
telemt_user_msgs_to_client{user="hello"} 19580824
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 86734.1 (24h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157902
telemt_connections_bad_total 1251
telemt_handshake_timeouts_total 6929
telemt_upstream_connect_attempt_total 140942
telemt_upstream_connect_success_total 140928
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 140942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 125364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15461
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 140918
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 12685014829 (11.81 GB)
telemt_user_octets_to_client{user="hello"} 127944643182 (119.16 GB)
telemt_user_msgs_from_client{user="hello"} 6710862
telemt_user_msgs_to_client{user="hello"} 28546888
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 86732.9 (24h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175519
telemt_connections_bad_total 7453
telemt_handshake_timeouts_total 1967
telemt_upstream_connect_attempt_total 159075
telemt_upstream_connect_success_total 158688
telemt_upstream_connect_fail_total 386
telemt_upstream_connect_attempts_per_request{bucket="1"} 159074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 137923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20242
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 89
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 434
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 386
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 158678
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 9586841433 (8.93 GB)
telemt_user_octets_to_client{user="hello"} 111114813637 (103.48 GB)
telemt_user_msgs_from_client{user="hello"} 5680088
telemt_user_msgs_to_client{user="hello"} 32982094
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 86734.3 (24h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250778
telemt_connections_bad_total 19177
telemt_handshake_timeouts_total 6302
telemt_upstream_connect_attempt_total 203524
telemt_upstream_connect_success_total 203021
telemt_upstream_connect_fail_total 503
telemt_upstream_connect_attempts_per_request{bucket="1"} 203524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 175745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26924
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 352
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 503
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 203013
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 4993549029 (4.65 GB)
telemt_user_octets_to_client{user="hello"} 164412597202 (153.12 GB)
telemt_user_msgs_from_client{user="hello"} 4798711
telemt_user_msgs_to_client{user="hello"} 22612181
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 65703.7 (18h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 454
telemt_connections_bad_total 432
telemt_handshake_timeouts_total 10
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