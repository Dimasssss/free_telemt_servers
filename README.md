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

# Server Metrics 2026-03-11 21:17:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 15403.2 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51662
telemt_connections_bad_total 2544
telemt_handshake_timeouts_total 237
telemt_upstream_connect_attempt_total 46789
telemt_upstream_connect_success_total 46777
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 46789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4496
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46775
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 1484170633 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 27490963661 (25.60 GB)
telemt_user_msgs_from_client{user="hello"} 1285692
telemt_user_msgs_to_client{user="hello"} 2642779
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 15391.3 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23920
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 262
telemt_upstream_connect_attempt_total 22142
telemt_upstream_connect_success_total 22103
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 22142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2653
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22101
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 263703555 (251.49 MB)
telemt_user_octets_to_client{user="hello"} 11396110693 (10.61 GB)
telemt_user_msgs_from_client{user="hello"} 459738
telemt_user_msgs_to_client{user="hello"} 4680890
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 15411.4 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29288
telemt_connections_bad_total 49
telemt_handshake_timeouts_total 254
telemt_upstream_connect_attempt_total 27445
telemt_upstream_connect_success_total 27443
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 27445
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2521
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27441
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 319246376 (304.46 MB)
telemt_user_octets_to_client{user="hello"} 10293160497 (9.59 GB)
telemt_user_msgs_from_client{user="hello"} 528807
telemt_user_msgs_to_client{user="hello"} 2607794
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 15407.1 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31378
telemt_connections_bad_total 1803
telemt_handshake_timeouts_total 472
telemt_upstream_connect_attempt_total 27730
telemt_upstream_connect_success_total 27648
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 27730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24871
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2688
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27646
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 719957016 (686.60 MB)
telemt_user_octets_to_client{user="hello"} 17485850322 (16.28 GB)
telemt_user_msgs_from_client{user="hello"} 660342
telemt_user_msgs_to_client{user="hello"} 5592796
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 15414.9 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34551
telemt_connections_bad_total 2966
telemt_handshake_timeouts_total 183
telemt_upstream_connect_attempt_total 30392
telemt_upstream_connect_success_total 30389
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 30392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3538
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30387
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 538246002 (513.31 MB)
telemt_user_octets_to_client{user="hello"} 11317564705 (10.54 GB)
telemt_user_msgs_from_client{user="hello"} 682295
telemt_user_msgs_to_client{user="hello"} 4115614
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 90021.2 (25h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2894
telemt_connections_bad_total 494
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 2320
telemt_upstream_connect_success_total 2320
telemt_upstream_connect_attempts_per_request{bucket="1"} 2320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 359
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2310
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 27350158 (26.08 MB)
telemt_user_octets_to_client{user="hello"} 2494506456 (2.32 GB)
telemt_user_msgs_from_client{user="hello"} 72998
telemt_user_msgs_to_client{user="hello"} 299851
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 9
```