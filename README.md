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

# Server Metrics 2026-03-11 22:59:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 4471.3 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7290
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 58
telemt_upstream_connect_attempt_total 6961
telemt_upstream_connect_success_total 6957
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 6961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 833
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6955
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 87182782 (83.14 MB)
telemt_user_octets_to_client{user="hello"} 3093725800 (2.88 GB)
telemt_user_msgs_from_client{user="hello"} 157755
telemt_user_msgs_to_client{user="hello"} 463514
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 4459.9 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3272
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 3141
telemt_upstream_connect_success_total 3141
telemt_upstream_connect_attempts_per_request{bucket="1"} 3141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 365
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3139
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 15369627 (14.66 MB)
telemt_user_octets_to_client{user="hello"} 394054284 (375.80 MB)
telemt_user_msgs_from_client{user="hello"} 38176
telemt_user_msgs_to_client{user="hello"} 179615
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 4433.3 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5777
telemt_connections_bad_total 245
telemt_handshake_timeouts_total 117
telemt_upstream_connect_attempt_total 4713
telemt_upstream_connect_success_total 4713
telemt_upstream_connect_attempts_per_request{bucket="1"} 4713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 599
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4711
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 27489756 (26.22 MB)
telemt_user_octets_to_client{user="hello"} 2413828396 (2.25 GB)
telemt_user_msgs_from_client{user="hello"} 89295
telemt_user_msgs_to_client{user="hello"} 648515
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 4458.7 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4324
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 52
telemt_upstream_connect_attempt_total 4136
telemt_upstream_connect_success_total 4132
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 575
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4130
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 35628298 (33.98 MB)
telemt_user_octets_to_client{user="hello"} 1370723829 (1.28 GB)
telemt_user_msgs_from_client{user="hello"} 65684
telemt_user_msgs_to_client{user="hello"} 517942
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 4460.0 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4409
telemt_connections_bad_total 889
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 3451
telemt_upstream_connect_success_total 3451
telemt_upstream_connect_attempts_per_request{bucket="1"} 3451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 308
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3449
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 41743175 (39.81 MB)
telemt_user_octets_to_client{user="hello"} 1395971930 (1.30 GB)
telemt_user_msgs_from_client{user="hello"} 50446
telemt_user_msgs_to_client{user="hello"} 254081
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 4459.5 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4667
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 89
telemt_upstream_connect_attempt_total 3959
telemt_upstream_connect_success_total 3959
telemt_upstream_connect_attempts_per_request{bucket="1"} 3959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 645
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3957
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 76931738 (73.37 MB)
telemt_user_octets_to_client{user="hello"} 10926160520 (10.18 GB)
telemt_user_msgs_from_client{user="hello"} 135768
telemt_user_msgs_to_client{user="hello"} 760126
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 7
```