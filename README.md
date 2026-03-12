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

# Server Metrics 2026-03-12 02:44:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 17984.8 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35986
telemt_connections_bad_total 1921
telemt_handshake_timeouts_total 300
telemt_upstream_connect_attempt_total 32193
telemt_upstream_connect_success_total 32186
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 32193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32184
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 301320443 (287.36 MB)
telemt_user_octets_to_client{user="hello"} 9953486139 (9.27 GB)
telemt_user_msgs_from_client{user="hello"} 518385
telemt_user_msgs_to_client{user="hello"} 1267168
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 17972.9 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14790
telemt_connections_bad_total 103
telemt_handshake_timeouts_total 69
telemt_upstream_connect_attempt_total 14149
telemt_upstream_connect_success_total 14149
telemt_upstream_connect_attempts_per_request{bucket="1"} 14149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1610
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14147
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 101716308 (97.00 MB)
telemt_user_octets_to_client{user="hello"} 6756348036 (6.29 GB)
telemt_user_msgs_from_client{user="hello"} 246569
telemt_user_msgs_to_client{user="hello"} 1883453
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 17946.6 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24967
telemt_connections_bad_total 365
telemt_handshake_timeouts_total 904
telemt_upstream_connect_attempt_total 21585
telemt_upstream_connect_success_total 21585
telemt_upstream_connect_attempts_per_request{bucket="1"} 21585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18294
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21581
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 5207922600 (4.85 GB)
telemt_user_octets_to_client{user="hello"} 12694450983 (11.82 GB)
telemt_user_msgs_from_client{user="hello"} 2181059
telemt_user_msgs_to_client{user="hello"} 2618584
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 17972.1 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28051
telemt_connections_bad_total 8467
telemt_handshake_timeouts_total 702
telemt_upstream_connect_attempt_total 18097
telemt_upstream_connect_success_total 16399
telemt_upstream_connect_fail_total 1698
telemt_upstream_connect_attempts_per_request{bucket="1"} 18097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2375
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1698
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16395
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 140354779 (133.85 MB)
telemt_user_octets_to_client{user="hello"} 11025334898 (10.27 GB)
telemt_user_msgs_from_client{user="hello"} 292716
telemt_user_msgs_to_client{user="hello"} 4382797
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 17972.7 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19629
telemt_connections_bad_total 139
telemt_handshake_timeouts_total 133
telemt_upstream_connect_attempt_total 18059
telemt_upstream_connect_success_total 18059
telemt_upstream_connect_attempts_per_request{bucket="1"} 18059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2813
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18057
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 440737062 (420.32 MB)
telemt_user_octets_to_client{user="hello"} 24008658901 (22.36 GB)
telemt_user_msgs_from_client{user="hello"} 573086
telemt_user_msgs_to_client{user="hello"} 2847182
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 13
```