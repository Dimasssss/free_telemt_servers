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

# Server Metrics 2026-03-12 02:34:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 17335.8 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34410
telemt_connections_bad_total 1908
telemt_handshake_timeouts_total 278
telemt_upstream_connect_attempt_total 30692
telemt_upstream_connect_success_total 30685
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 30692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3271
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30683
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 292258164 (278.72 MB)
telemt_user_octets_to_client{user="hello"} 9730283487 (9.06 GB)
telemt_user_msgs_from_client{user="hello"} 503417
telemt_user_msgs_to_client{user="hello"} 1225352
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 17323.9 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14309
telemt_connections_bad_total 89
telemt_handshake_timeouts_total 69
telemt_upstream_connect_attempt_total 13698
telemt_upstream_connect_success_total 13698
telemt_upstream_connect_attempts_per_request{bucket="1"} 13698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13696
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 96871831 (92.38 MB)
telemt_user_octets_to_client{user="hello"} 6218600880 (5.79 GB)
telemt_user_msgs_from_client{user="hello"} 235981
telemt_user_msgs_to_client{user="hello"} 1770973
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 17297.5 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23801
telemt_connections_bad_total 350
telemt_handshake_timeouts_total 892
telemt_upstream_connect_attempt_total 20508
telemt_upstream_connect_success_total 20508
telemt_upstream_connect_attempts_per_request{bucket="1"} 20508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3037
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20504
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 5202389045 (4.85 GB)
telemt_user_octets_to_client{user="hello"} 12567968638 (11.70 GB)
telemt_user_msgs_from_client{user="hello"} 2163956
telemt_user_msgs_to_client{user="hello"} 2562725
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 17322.8 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26360
telemt_connections_bad_total 8448
telemt_handshake_timeouts_total 700
telemt_upstream_connect_attempt_total 16470
telemt_upstream_connect_success_total 15791
telemt_upstream_connect_fail_total 656
telemt_upstream_connect_attempts_per_request{bucket="1"} 16447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2225
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 656
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15787
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 131214440 (125.14 MB)
telemt_user_octets_to_client{user="hello"} 8952763141 (8.34 GB)
telemt_user_msgs_from_client{user="hello"} 267543
telemt_user_msgs_to_client{user="hello"} 3427962
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 17323.6 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18861
telemt_connections_bad_total 139
telemt_handshake_timeouts_total 130
telemt_upstream_connect_attempt_total 17329
telemt_upstream_connect_success_total 17329
telemt_upstream_connect_attempts_per_request{bucket="1"} 17329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2650
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17327
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 425322009 (405.62 MB)
telemt_user_octets_to_client{user="hello"} 22674718867 (21.12 GB)
telemt_user_msgs_from_client{user="hello"} 545549
telemt_user_msgs_to_client{user="hello"} 2620088
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 12
```