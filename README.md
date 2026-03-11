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

# Server Metrics 2026-03-11 16:24:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 623.2 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3034
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 31
telemt_upstream_connect_attempt_total 2615
telemt_upstream_connect_success_total 2614
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2612
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 25583483 (24.40 MB)
telemt_user_octets_to_client{user="hello"} 678709037 (647.27 MB)
telemt_user_msgs_from_client{user="hello"} 39969
telemt_user_msgs_to_client{user="hello"} 69113
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 93514.3 (25h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128054
telemt_connections_bad_total 974
telemt_handshake_timeouts_total 3457
telemt_upstream_connect_attempt_total 118206
telemt_upstream_connect_success_total 118183
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 118206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 102971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14627
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 585
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 118173
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 6108137795 (5.69 GB)
telemt_user_octets_to_client{user="hello"} 72689701269 (67.70 GB)
telemt_user_msgs_from_client{user="hello"} 4166624
telemt_user_msgs_to_client{user="hello"} 21326648
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 93514.0 (25h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173851
telemt_connections_bad_total 1446
telemt_handshake_timeouts_total 7846
telemt_upstream_connect_attempt_total 155114
telemt_upstream_connect_success_total 155100
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 155114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 137598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17394
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 155090
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 12782775119 (11.90 GB)
telemt_user_octets_to_client{user="hello"} 133847429131 (124.66 GB)
telemt_user_msgs_from_client{user="hello"} 6981177
telemt_user_msgs_to_client{user="hello"} 30374593
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 93513.0 (25h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196345
telemt_connections_bad_total 9516
telemt_handshake_timeouts_total 3130
telemt_upstream_connect_attempt_total 175840
telemt_upstream_connect_success_total 175413
telemt_upstream_connect_fail_total 427
telemt_upstream_connect_attempts_per_request{bucket="1"} 175840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 153061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21778
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 96
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 478
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 427
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 175403
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 10379440160 (9.67 GB)
telemt_user_octets_to_client{user="hello"} 120769411568 (112.48 GB)
telemt_user_msgs_from_client{user="hello"} 6192302
telemt_user_msgs_to_client{user="hello"} 36109929
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 72483.6 (20h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 473
telemt_connections_bad_total 450
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 19
telemt_upstream_connect_success_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```