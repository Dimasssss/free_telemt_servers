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

# Server Metrics 2026-03-11 12:49:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 80585.3 (22h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256818
telemt_connections_bad_total 3635
telemt_handshake_timeouts_total 4638
telemt_upstream_connect_attempt_total 237128
telemt_upstream_connect_success_total 237055
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 237128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 217045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19953
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 237047
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 4758762602 (4.43 GB)
telemt_user_octets_to_client{user="hello"} 126382627395 (117.70 GB)
telemt_user_msgs_from_client{user="hello"} 5357290
telemt_user_msgs_to_client{user="hello"} 9846622
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 80584.9 (22h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99976
telemt_connections_bad_total 906
telemt_handshake_timeouts_total 3326
telemt_upstream_connect_attempt_total 91319
telemt_upstream_connect_success_total 91302
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 91319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11861
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 289
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 91294
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 5198293265 (4.84 GB)
telemt_user_octets_to_client{user="hello"} 61202361236 (57.00 GB)
telemt_user_msgs_from_client{user="hello"} 3479871
telemt_user_msgs_to_client{user="hello"} 16929367
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 80584.5 (22h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138611
telemt_connections_bad_total 1103
telemt_handshake_timeouts_total 6706
telemt_upstream_connect_attempt_total 123142
telemt_upstream_connect_success_total 123128
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 123142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13801
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 123120
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 12480981921 (11.62 GB)
telemt_user_octets_to_client{user="hello"} 96067312949 (89.47 GB)
telemt_user_msgs_from_client{user="hello"} 6259516
telemt_user_msgs_to_client{user="hello"} 19794451
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 80583.5 (22h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151894
telemt_connections_bad_total 555
telemt_handshake_timeouts_total 1889
telemt_upstream_connect_attempt_total 143191
telemt_upstream_connect_success_total 142854
telemt_upstream_connect_fail_total 337
telemt_upstream_connect_attempts_per_request{bucket="1"} 143191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 123994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18411
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 75
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 374
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 337
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 142846
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 8125306074 (7.57 GB)
telemt_user_octets_to_client{user="hello"} 107616002265 (100.23 GB)
telemt_user_msgs_from_client{user="hello"} 4970871
telemt_user_msgs_to_client{user="hello"} 31647055
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 80584.6 (22h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227827
telemt_connections_bad_total 17820
telemt_handshake_timeouts_total 4539
telemt_upstream_connect_attempt_total 184265
telemt_upstream_connect_success_total 183765
telemt_upstream_connect_fail_total 500
telemt_upstream_connect_attempts_per_request{bucket="1"} 184265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 158774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 500
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 183757
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 4712148789 (4.39 GB)
telemt_user_octets_to_client{user="hello"} 150193386548 (139.88 GB)
telemt_user_msgs_from_client{user="hello"} 4410503
telemt_user_msgs_to_client{user="hello"} 20714958
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 59554.1 (16h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 429
telemt_connections_bad_total 407
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