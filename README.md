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

# Server Metrics 2026-03-12 02:17:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 16362.1 (4h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32117
telemt_connections_bad_total 1907
telemt_handshake_timeouts_total 247
telemt_upstream_connect_attempt_total 28499
telemt_upstream_connect_success_total 28492
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 28499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2972
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28490
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 281095597 (268.07 MB)
telemt_user_octets_to_client{user="hello"} 9434962039 (8.79 GB)
telemt_user_msgs_from_client{user="hello"} 482545
telemt_user_msgs_to_client{user="hello"} 1167591
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 16350.5 (4h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13398
telemt_connections_bad_total 64
telemt_handshake_timeouts_total 50
telemt_upstream_connect_attempt_total 12848
telemt_upstream_connect_success_total 12848
telemt_upstream_connect_attempts_per_request{bucket="1"} 12848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12846
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 88303592 (84.21 MB)
telemt_user_octets_to_client{user="hello"} 5643613889 (5.26 GB)
telemt_user_msgs_from_client{user="hello"} 216786
telemt_user_msgs_to_client{user="hello"} 1610515
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 16324.0 (4h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22244
telemt_connections_bad_total 350
telemt_handshake_timeouts_total 880
telemt_upstream_connect_attempt_total 19005
telemt_upstream_connect_success_total 19005
telemt_upstream_connect_attempts_per_request{bucket="1"} 19005
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2752
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19003
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 3976187362 (3.70 GB)
telemt_user_octets_to_client{user="hello"} 11918231395 (11.10 GB)
telemt_user_msgs_from_client{user="hello"} 1715718
telemt_user_msgs_to_client{user="hello"} 2376346
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 16349.4 (4h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24748
telemt_connections_bad_total 8404
telemt_handshake_timeouts_total 698
telemt_upstream_connect_attempt_total 14945
telemt_upstream_connect_success_total 14906
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 14945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2038
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14902
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 122082283 (116.43 MB)
telemt_user_octets_to_client{user="hello"} 7103918806 (6.62 GB)
telemt_user_msgs_from_client{user="hello"} 242341
telemt_user_msgs_to_client{user="hello"} 2646178
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 16350.2 (4h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17721
telemt_connections_bad_total 137
telemt_handshake_timeouts_total 128
telemt_upstream_connect_attempt_total 16220
telemt_upstream_connect_success_total 16220
telemt_upstream_connect_attempts_per_request{bucket="1"} 16220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2452
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16218
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 413901933 (394.73 MB)
telemt_user_octets_to_client{user="hello"} 21759389613 (20.27 GB)
telemt_user_msgs_from_client{user="hello"} 515444
telemt_user_msgs_to_client{user="hello"} 2396464
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 8
```