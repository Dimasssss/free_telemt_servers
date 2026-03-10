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

# Server Metrics 2026-03-10 23:12:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 31606.8 (8h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97636
telemt_connections_bad_total 3305
telemt_handshake_timeouts_total 2212
telemt_upstream_connect_attempt_total 87822
telemt_upstream_connect_success_total 87790
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 87822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7802
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 87786
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 2588411859 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 71902101267 (66.96 GB)
telemt_user_msgs_from_client{user="hello"} 2561683
telemt_user_msgs_to_client{user="hello"} 4926016
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 31606.1 (8h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37822
telemt_connections_bad_total 333
telemt_handshake_timeouts_total 851
telemt_upstream_connect_attempt_total 34369
telemt_upstream_connect_success_total 34360
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 34369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34356
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 1712415568 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 36673694609 (34.16 GB)
telemt_user_msgs_from_client{user="hello"} 1427986
telemt_user_msgs_to_client{user="hello"} 9122370
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 31606.0 (8h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60358
telemt_connections_bad_total 448
telemt_handshake_timeouts_total 4081
telemt_upstream_connect_attempt_total 52336
telemt_upstream_connect_success_total 52334
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 52336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5159
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 52330
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 795281837 (758.44 MB)
telemt_user_octets_to_client{user="hello"} 50833034638 (47.34 GB)
telemt_user_msgs_from_client{user="hello"} 1119154
telemt_user_msgs_to_client{user="hello"} 7553791
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 31604.8 (8h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56068
telemt_connections_bad_total 87
telemt_handshake_timeouts_total 333
telemt_upstream_connect_attempt_total 53832
telemt_upstream_connect_success_total 53681
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 53832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6338
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53677
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 829823604 (791.38 MB)
telemt_user_octets_to_client{user="hello"} 37446984171 (34.88 GB)
telemt_user_msgs_from_client{user="hello"} 1134445
telemt_user_msgs_to_client{user="hello"} 7179366
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 31606.1 (8h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82176
telemt_connections_bad_total 7710
telemt_handshake_timeouts_total 1467
telemt_upstream_connect_attempt_total 69834
telemt_upstream_connect_success_total 69586
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 69834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9210
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 69582
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 2076381850 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 56574927613 (52.69 GB)
telemt_user_msgs_from_client{user="hello"} 1963817
telemt_user_msgs_to_client{user="hello"} 8248037
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 10575.5 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```