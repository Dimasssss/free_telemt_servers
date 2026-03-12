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

# Server Metrics 2026-03-12 04:54:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 25765.6 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59723
telemt_connections_bad_total 2102
telemt_handshake_timeouts_total 1293
telemt_upstream_connect_attempt_total 53657
telemt_upstream_connect_success_total 53642
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 53657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7633
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53638
telemt_user_connections_current{user="hello"} 262
telemt_user_octets_from_client{user="hello"} 576338522 (549.64 MB)
telemt_user_octets_to_client{user="hello"} 18785702634 (17.50 GB)
telemt_user_msgs_from_client{user="hello"} 857065
telemt_user_msgs_to_client{user="hello"} 2102638
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 25753.8 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22740
telemt_connections_bad_total 157
telemt_handshake_timeouts_total 134
telemt_upstream_connect_attempt_total 21596
telemt_upstream_connect_success_total 21592
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 21596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2698
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21588
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 193063947 (184.12 MB)
telemt_user_octets_to_client{user="hello"} 12055082234 (11.23 GB)
telemt_user_msgs_from_client{user="hello"} 411076
telemt_user_msgs_to_client{user="hello"} 3432884
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 25727.3 (7h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37803
telemt_connections_bad_total 539
telemt_handshake_timeouts_total 976
telemt_upstream_connect_attempt_total 33612
telemt_upstream_connect_success_total 33611
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 33612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5648
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33607
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 5309848511 (4.95 GB)
telemt_user_octets_to_client{user="hello"} 21323329777 (19.86 GB)
telemt_user_msgs_from_client{user="hello"} 2444748
telemt_user_msgs_to_client{user="hello"} 3863094
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 25753.0 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39464
telemt_connections_bad_total 9435
telemt_handshake_timeouts_total 762
telemt_upstream_connect_attempt_total 27946
telemt_upstream_connect_success_total 26246
telemt_upstream_connect_fail_total 1700
telemt_upstream_connect_attempts_per_request{bucket="1"} 27946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4292
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1700
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26242
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 248978973 (237.44 MB)
telemt_user_octets_to_client{user="hello"} 20765304724 (19.34 GB)
telemt_user_msgs_from_client{user="hello"} 494824
telemt_user_msgs_to_client{user="hello"} 8627908
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 25753.7 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34977
telemt_connections_bad_total 193
telemt_handshake_timeouts_total 180
telemt_upstream_connect_attempt_total 32665
telemt_upstream_connect_success_total 32663
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 32664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5410
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32659
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 653894004 (623.60 MB)
telemt_user_octets_to_client{user="hello"} 33830363044 (31.51 GB)
telemt_user_msgs_from_client{user="hello"} 907047
telemt_user_msgs_to_client{user="hello"} 4536897
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 15
```