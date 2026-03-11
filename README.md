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

# Server Metrics 2026-03-11 21:11:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 15095.9 (4h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51083
telemt_connections_bad_total 2544
telemt_handshake_timeouts_total 235
telemt_upstream_connect_attempt_total 46224
telemt_upstream_connect_success_total 46213
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 46224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4424
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46211
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 1479103826 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 27161765463 (25.30 GB)
telemt_user_msgs_from_client{user="hello"} 1273048
telemt_user_msgs_to_client{user="hello"} 2568201
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 15084.1 (4h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23565
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 261
telemt_upstream_connect_attempt_total 21800
telemt_upstream_connect_success_total 21761
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 21800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2601
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21759
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 252917646 (241.20 MB)
telemt_user_octets_to_client{user="hello"} 11170431455 (10.40 GB)
telemt_user_msgs_from_client{user="hello"} 448039
telemt_user_msgs_to_client{user="hello"} 4581127
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 15104.2 (4h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28928
telemt_connections_bad_total 49
telemt_handshake_timeouts_total 253
telemt_upstream_connect_attempt_total 27095
telemt_upstream_connect_success_total 27093
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 27095
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2498
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27091
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 314339434 (299.78 MB)
telemt_user_octets_to_client{user="hello"} 10249312496 (9.55 GB)
telemt_user_msgs_from_client{user="hello"} 521770
telemt_user_msgs_to_client{user="hello"} 2593138
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 15099.5 (4h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30953
telemt_connections_bad_total 1803
telemt_handshake_timeouts_total 460
telemt_upstream_connect_attempt_total 27333
telemt_upstream_connect_success_total 27252
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 27333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2646
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27250
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 715751729 (682.59 MB)
telemt_user_octets_to_client{user="hello"} 16958991824 (15.79 GB)
telemt_user_msgs_from_client{user="hello"} 649156
telemt_user_msgs_to_client{user="hello"} 5376736
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 15107.6 (4h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34238
telemt_connections_bad_total 2911
telemt_handshake_timeouts_total 181
telemt_upstream_connect_attempt_total 30144
telemt_upstream_connect_success_total 30141
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 30144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3520
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30139
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 537367509 (512.47 MB)
telemt_user_octets_to_client{user="hello"} 11300246115 (10.52 GB)
telemt_user_msgs_from_client{user="hello"} 679891
telemt_user_msgs_to_client{user="hello"} 4110829
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 89714.0 (24h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2668
telemt_connections_bad_total 494
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 2096
telemt_upstream_connect_success_total 2096
telemt_upstream_connect_attempts_per_request{bucket="1"} 2096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 315
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2086
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 25020747 (23.86 MB)
telemt_user_octets_to_client{user="hello"} 2371607821 (2.21 GB)
telemt_user_msgs_from_client{user="hello"} 66959
telemt_user_msgs_to_client{user="hello"} 280159
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 4
```