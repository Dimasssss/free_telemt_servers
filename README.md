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

# Server Metrics 2026-03-11 14:01:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 84890.8 (23h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 278039
telemt_connections_bad_total 3676
telemt_handshake_timeouts_total 4765
telemt_upstream_connect_attempt_total 257143
telemt_upstream_connect_success_total 257064
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 257141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 235301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21704
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 257054
telemt_user_connections_current{user="hello"} 362
telemt_user_octets_from_client{user="hello"} 4955865641 (4.62 GB)
telemt_user_octets_to_client{user="hello"} 132267002710 (123.18 GB)
telemt_user_msgs_from_client{user="hello"} 5709306
telemt_user_msgs_to_client{user="hello"} 10436308
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 84890.3 (23h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108909
telemt_connections_bad_total 914
telemt_handshake_timeouts_total 3346
telemt_upstream_connect_attempt_total 99873
telemt_upstream_connect_success_total 99854
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 99873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86459
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12985
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 410
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 99846
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 5378326101 (5.01 GB)
telemt_user_octets_to_client{user="hello"} 66354216417 (61.80 GB)
telemt_user_msgs_from_client{user="hello"} 3659608
telemt_user_msgs_to_client{user="hello"} 18864774
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 84890.0 (23h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152306
telemt_connections_bad_total 1250
telemt_handshake_timeouts_total 6875
telemt_upstream_connect_attempt_total 135702
telemt_upstream_connect_success_total 135688
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 135702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 120660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14927
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 135680
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 12636502227 (11.77 GB)
telemt_user_octets_to_client{user="hello"} 122542453704 (114.13 GB)
telemt_user_msgs_from_client{user="hello"} 6603280
telemt_user_msgs_to_client{user="hello"} 27024946
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 84888.8 (23h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168384
telemt_connections_bad_total 5539
telemt_handshake_timeouts_total 1924
telemt_upstream_connect_attempt_total 154078
telemt_upstream_connect_success_total 153705
telemt_upstream_connect_fail_total 373
telemt_upstream_connect_attempts_per_request{bucket="1"} 154078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 133610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19589
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 88
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 418
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 373
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 153695
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 9260464248 (8.62 GB)
telemt_user_octets_to_client{user="hello"} 109717466240 (102.18 GB)
telemt_user_msgs_from_client{user="hello"} 5506901
telemt_user_msgs_to_client{user="hello"} 32454354
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 84890.1 (23h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244061
telemt_connections_bad_total 18805
telemt_handshake_timeouts_total 6158
telemt_upstream_connect_attempt_total 197519
telemt_upstream_connect_success_total 197016
telemt_upstream_connect_fail_total 503
telemt_upstream_connect_attempts_per_request{bucket="1"} 197519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 170448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 346
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 503
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 197008
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 4859036923 (4.53 GB)
telemt_user_octets_to_client{user="hello"} 156604674979 (145.85 GB)
telemt_user_msgs_from_client{user="hello"} 4636398
telemt_user_msgs_to_client{user="hello"} 21681869
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 63859.5 (17h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 441
telemt_connections_bad_total 419
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 17
telemt_upstream_connect_success_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```