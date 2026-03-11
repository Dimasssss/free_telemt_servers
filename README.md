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

# Server Metrics 2026-03-11 16:56:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 2481.1 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12518
telemt_connections_bad_total 677
telemt_handshake_timeouts_total 483
telemt_upstream_connect_attempt_total 10637
telemt_upstream_connect_success_total 10631
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 10637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 890
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10629
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 98138686 (93.59 MB)
telemt_user_octets_to_client{user="hello"} 4904718834 (4.57 GB)
telemt_user_msgs_from_client{user="hello"} 167660
telemt_user_msgs_to_client{user="hello"} 429696
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

Не удалось получить метрики для этого сервера.

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 95371.6 (26h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178276
telemt_connections_bad_total 1676
telemt_handshake_timeouts_total 7900
telemt_upstream_connect_attempt_total 159096
telemt_upstream_connect_success_total 159082
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 159096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 141130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17839
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 159072
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 12810951246 (11.93 GB)
telemt_user_octets_to_client{user="hello"} 136493871141 (127.12 GB)
telemt_user_msgs_from_client{user="hello"} 7059963
telemt_user_msgs_to_client{user="hello"} 31067387
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 95370.5 (26h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202586
telemt_connections_bad_total 10808
telemt_handshake_timeouts_total 3630
telemt_upstream_connect_attempt_total 180123
telemt_upstream_connect_success_total 179686
telemt_upstream_connect_fail_total 437
telemt_upstream_connect_attempts_per_request{bucket="1"} 180123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22168
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 104
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 497
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 437
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 179676
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 10518329651 (9.80 GB)
telemt_user_octets_to_client{user="hello"} 124988204856 (116.40 GB)
telemt_user_msgs_from_client{user="hello"} 6302558
telemt_user_msgs_to_client{user="hello"} 37169039
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 74341.1 (20h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 490
telemt_connections_bad_total 466
telemt_handshake_timeouts_total 13
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