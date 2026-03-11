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

# Server Metrics 2026-03-11 13:50:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 84274.7 (23h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 275088
telemt_connections_bad_total 3675
telemt_handshake_timeouts_total 4758
telemt_upstream_connect_attempt_total 254365
telemt_upstream_connect_success_total 254288
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 254365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 232814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21415
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 254278
telemt_user_connections_current{user="hello"} 366
telemt_user_octets_from_client{user="hello"} 4927869715 (4.59 GB)
telemt_user_octets_to_client{user="hello"} 130653344614 (121.68 GB)
telemt_user_msgs_from_client{user="hello"} 5654523
telemt_user_msgs_to_client{user="hello"} 10330074
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 84273.6 (23h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107632
telemt_connections_bad_total 910
telemt_handshake_timeouts_total 3339
telemt_upstream_connect_attempt_total 98679
telemt_upstream_connect_success_total 98660
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 98679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 85493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12779
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 388
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 98652
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 5308866340 (4.94 GB)
telemt_user_octets_to_client{user="hello"} 65555692598 (61.05 GB)
telemt_user_msgs_from_client{user="hello"} 3615141
telemt_user_msgs_to_client{user="hello"} 18583023
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 84273.2 (23h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150119
telemt_connections_bad_total 1250
telemt_handshake_timeouts_total 6865
telemt_upstream_connect_attempt_total 133654
telemt_upstream_connect_success_total 133640
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 133654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 118772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14769
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 133632
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 12619165593 (11.75 GB)
telemt_user_octets_to_client{user="hello"} 118903490783 (110.74 GB)
telemt_user_msgs_from_client{user="hello"} 6557786
telemt_user_msgs_to_client{user="hello"} 25979003
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 84272.3 (23h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166214
telemt_connections_bad_total 5094
telemt_handshake_timeouts_total 1915
telemt_upstream_connect_attempt_total 152410
telemt_upstream_connect_success_total 152042
telemt_upstream_connect_fail_total 368
telemt_upstream_connect_attempts_per_request{bucket="1"} 152410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 132126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19421
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 409
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 368
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 152032
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 9137806750 (8.51 GB)
telemt_user_octets_to_client{user="hello"} 109453660935 (101.94 GB)
telemt_user_msgs_from_client{user="hello"} 5446273
telemt_user_msgs_to_client{user="hello"} 32342023
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 84273.4 (23h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241974
telemt_connections_bad_total 18690
telemt_handshake_timeouts_total 6143
telemt_upstream_connect_attempt_total 195618
telemt_upstream_connect_success_total 195116
telemt_upstream_connect_fail_total 502
telemt_upstream_connect_attempts_per_request{bucket="1"} 195618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 168745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26028
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 502
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 195108
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 4816444848 (4.49 GB)
telemt_user_octets_to_client{user="hello"} 156123832026 (145.40 GB)
telemt_user_msgs_from_client{user="hello"} 4598083
telemt_user_msgs_to_client{user="hello"} 21606017
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 63242.8 (17h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 440
telemt_connections_bad_total 418
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