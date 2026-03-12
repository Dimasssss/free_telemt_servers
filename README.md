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

# Server Metrics 2026-03-12 05:21:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 27387.0 (7h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66760
telemt_connections_bad_total 2104
telemt_handshake_timeouts_total 1806
telemt_upstream_connect_attempt_total 59937
telemt_upstream_connect_success_total 59919
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 59937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9044
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 59915
telemt_user_connections_current{user="hello"} 262
telemt_user_octets_from_client{user="hello"} 615982593 (587.45 MB)
telemt_user_octets_to_client{user="hello"} 19918967881 (18.55 GB)
telemt_user_msgs_from_client{user="hello"} 923740
telemt_user_msgs_to_client{user="hello"} 2243014
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 27375.2 (7h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25987
telemt_connections_bad_total 208
telemt_handshake_timeouts_total 143
telemt_upstream_connect_attempt_total 24704
telemt_upstream_connect_success_total 24698
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 24704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3117
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24694
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 223775823 (213.41 MB)
telemt_user_octets_to_client{user="hello"} 13381870573 (12.46 GB)
telemt_user_msgs_from_client{user="hello"} 459357
telemt_user_msgs_to_client{user="hello"} 3836028
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 27348.6 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41350
telemt_connections_bad_total 558
telemt_handshake_timeouts_total 1023
telemt_upstream_connect_attempt_total 36982
telemt_upstream_connect_success_total 36975
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 36976
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6159
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36971
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 5330813097 (4.96 GB)
telemt_user_octets_to_client{user="hello"} 22736578893 (21.18 GB)
telemt_user_msgs_from_client{user="hello"} 2499923
telemt_user_msgs_to_client{user="hello"} 4097285
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 27374.0 (7h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45847
telemt_connections_bad_total 11338
telemt_handshake_timeouts_total 819
telemt_upstream_connect_attempt_total 32005
telemt_upstream_connect_success_total 30305
telemt_upstream_connect_fail_total 1700
telemt_upstream_connect_attempts_per_request{bucket="1"} 32005
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4920
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1700
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30301
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 279473045 (266.53 MB)
telemt_user_octets_to_client{user="hello"} 21968435132 (20.46 GB)
telemt_user_msgs_from_client{user="hello"} 554177
telemt_user_msgs_to_client{user="hello"} 9095907
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 27374.9 (7h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39300
telemt_connections_bad_total 760
telemt_handshake_timeouts_total 195
telemt_upstream_connect_attempt_total 36277
telemt_upstream_connect_success_total 36276
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 36277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6092
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36272
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 685935952 (654.16 MB)
telemt_user_octets_to_client{user="hello"} 35333373948 (32.91 GB)
telemt_user_msgs_from_client{user="hello"} 962862
telemt_user_msgs_to_client{user="hello"} 4770208
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 28
```