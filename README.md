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

# Server Metrics 2026-03-11 14:52:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 87963.2 (24h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 292883
telemt_connections_bad_total 3714
telemt_handshake_timeouts_total 4846
telemt_upstream_connect_attempt_total 271196
telemt_upstream_connect_success_total 271118
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 271196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 248037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23020
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 271108
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 5086459256 (4.74 GB)
telemt_user_octets_to_client{user="hello"} 136216410405 (126.86 GB)
telemt_user_msgs_from_client{user="hello"} 5924435
telemt_user_msgs_to_client{user="hello"} 10862001
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 87962.4 (24h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116122
telemt_connections_bad_total 965
telemt_handshake_timeouts_total 3373
telemt_upstream_connect_attempt_total 106742
telemt_upstream_connect_success_total 106721
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 106742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13632
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 471
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 106711
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 5978609055 (5.57 GB)
telemt_user_octets_to_client{user="hello"} 68842334840 (64.11 GB)
telemt_user_msgs_from_client{user="hello"} 3960944
telemt_user_msgs_to_client{user="hello"} 19836686
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 87962.3 (24h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160983
telemt_connections_bad_total 1251
telemt_handshake_timeouts_total 7010
telemt_upstream_connect_attempt_total 143722
telemt_upstream_connect_success_total 143708
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 143722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 127675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15930
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 143698
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 12702058663 (11.83 GB)
telemt_user_octets_to_client{user="hello"} 128567057029 (119.74 GB)
telemt_user_msgs_from_client{user="hello"} 6761739
telemt_user_msgs_to_client{user="hello"} 28756201
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 87961.3 (24h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178665
telemt_connections_bad_total 7454
telemt_handshake_timeouts_total 2044
telemt_upstream_connect_attempt_total 162032
telemt_upstream_connect_success_total 161638
telemt_upstream_connect_fail_total 394
telemt_upstream_connect_attempts_per_request{bucket="1"} 162032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 140585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20521
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 441
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 394
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 161628
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 9654547382 (8.99 GB)
telemt_user_octets_to_client{user="hello"} 112813405975 (105.07 GB)
telemt_user_msgs_from_client{user="hello"} 5746198
telemt_user_msgs_to_client{user="hello"} 33594948
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 87962.4 (24h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 255075
telemt_connections_bad_total 19420
telemt_handshake_timeouts_total 6319
telemt_upstream_connect_attempt_total 207418
telemt_upstream_connect_success_total 206914
telemt_upstream_connect_fail_total 504
telemt_upstream_connect_attempts_per_request{bucket="1"} 207418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 179144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27414
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 504
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 206906
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 5045050943 (4.70 GB)
telemt_user_octets_to_client{user="hello"} 168904353652 (157.30 GB)
telemt_user_msgs_from_client{user="hello"} 4896531
telemt_user_msgs_to_client{user="hello"} 23365918
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 66931.9 (18h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 462
telemt_connections_bad_total 440
telemt_handshake_timeouts_total 10
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