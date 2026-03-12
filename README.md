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

# Server Metrics 2026-03-12 03:22:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 20253.8 (5h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41167
telemt_connections_bad_total 1933
telemt_handshake_timeouts_total 330
telemt_upstream_connect_attempt_total 37071
telemt_upstream_connect_success_total 37064
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 37071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4392
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37062
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 344161422 (328.22 MB)
telemt_user_octets_to_client{user="hello"} 11106716190 (10.34 GB)
telemt_user_msgs_from_client{user="hello"} 583131
telemt_user_msgs_to_client{user="hello"} 1400476
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 20242.2 (5h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16498
telemt_connections_bad_total 106
telemt_handshake_timeouts_total 71
telemt_upstream_connect_attempt_total 15758
telemt_upstream_connect_success_total 15757
telemt_upstream_connect_attempts_per_request{bucket="1"} 15757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15755
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 137825364 (131.44 MB)
telemt_user_octets_to_client{user="hello"} 9042667463 (8.42 GB)
telemt_user_msgs_from_client{user="hello"} 297913
telemt_user_msgs_to_client{user="hello"} 2423911
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 20215.6 (5h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28535
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 912
telemt_upstream_connect_attempt_total 25024
telemt_upstream_connect_success_total 25024
telemt_upstream_connect_attempts_per_request{bucket="1"} 25024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3978
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25020
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 5237636614 (4.88 GB)
telemt_user_octets_to_client{user="hello"} 16153169162 (15.04 GB)
telemt_user_msgs_from_client{user="hello"} 2272706
telemt_user_msgs_to_client{user="hello"} 3237954
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 20241.1 (5h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30389
telemt_connections_bad_total 8513
telemt_handshake_timeouts_total 711
telemt_upstream_connect_attempt_total 20280
telemt_upstream_connect_success_total 18582
telemt_upstream_connect_fail_total 1698
telemt_upstream_connect_attempts_per_request{bucket="1"} 20280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2752
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1698
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18578
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 170725085 (162.82 MB)
telemt_user_octets_to_client{user="hello"} 13391476506 (12.47 GB)
telemt_user_msgs_from_client{user="hello"} 341111
telemt_user_msgs_to_client{user="hello"} 5467171
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 20241.8 (5h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23056
telemt_connections_bad_total 144
telemt_handshake_timeouts_total 142
telemt_upstream_connect_attempt_total 21330
telemt_upstream_connect_success_total 21329
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 21330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17929
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3396
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21327
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 520361923 (496.26 MB)
telemt_user_octets_to_client{user="hello"} 29740249054 (27.70 GB)
telemt_user_msgs_from_client{user="hello"} 704509
telemt_user_msgs_to_client{user="hello"} 3721895
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 15
```