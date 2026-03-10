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

# Server Metrics 2026-03-10 21:51:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 26710.4 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91860
telemt_connections_bad_total 3277
telemt_handshake_timeouts_total 2179
telemt_upstream_connect_attempt_total 82301
telemt_upstream_connect_success_total 82269
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 82301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 82265
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 2510602989 (2.34 GB)
telemt_user_octets_to_client{user="hello"} 64979450164 (60.52 GB)
telemt_user_msgs_from_client{user="hello"} 2390256
telemt_user_msgs_to_client{user="hello"} 4298652
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 26709.5 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34945
telemt_connections_bad_total 319
telemt_handshake_timeouts_total 675
telemt_upstream_connect_attempt_total 31853
telemt_upstream_connect_success_total 31844
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 31853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4669
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31840
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 1652733450 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 30851487887 (28.73 GB)
telemt_user_msgs_from_client{user="hello"} 1305055
telemt_user_msgs_to_client{user="hello"} 8170238
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 26709.2 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56741
telemt_connections_bad_total 410
telemt_handshake_timeouts_total 3965
telemt_upstream_connect_attempt_total 49167
telemt_upstream_connect_success_total 49165
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 49167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4685
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49161
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 753615493 (718.70 MB)
telemt_user_octets_to_client{user="hello"} 43525271196 (40.54 GB)
telemt_user_msgs_from_client{user="hello"} 1029789
telemt_user_msgs_to_client{user="hello"} 6586918
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 26708.1 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51741
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 322
telemt_upstream_connect_attempt_total 49680
telemt_upstream_connect_success_total 49540
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 49680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5779
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49536
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 805999523 (768.66 MB)
telemt_user_octets_to_client{user="hello"} 36813513142 (34.29 GB)
telemt_user_msgs_from_client{user="hello"} 1088051
telemt_user_msgs_to_client{user="hello"} 6990477
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 26709.5 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74774
telemt_connections_bad_total 6702
telemt_handshake_timeouts_total 1407
telemt_upstream_connect_attempt_total 63678
telemt_upstream_connect_success_total 63434
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 63678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63430
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 1992464409 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 47651243700 (44.38 GB)
telemt_user_msgs_from_client{user="hello"} 1792652
telemt_user_msgs_to_client{user="hello"} 6821219
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 5678.9 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19
telemt_connections_bad_total 19
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```