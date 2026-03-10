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

# Server Metrics 2026-03-10 22:27:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 28852.9 (8h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94519
telemt_connections_bad_total 3291
telemt_handshake_timeouts_total 2199
telemt_upstream_connect_attempt_total 84835
telemt_upstream_connect_success_total 84803
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 84835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7433
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 84799
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 2549125922 (2.37 GB)
telemt_user_octets_to_client{user="hello"} 67366475157 (62.74 GB)
telemt_user_msgs_from_client{user="hello"} 2456635
telemt_user_msgs_to_client{user="hello"} 4434265
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 28852.3 (8h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36058
telemt_connections_bad_total 322
telemt_handshake_timeouts_total 728
telemt_upstream_connect_attempt_total 32853
telemt_upstream_connect_success_total 32844
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 32853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4830
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32840
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 1674965467 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 34302793865 (31.95 GB)
telemt_user_msgs_from_client{user="hello"} 1353484
telemt_user_msgs_to_client{user="hello"} 8629744
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 28852.2 (8h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58561
telemt_connections_bad_total 444
telemt_handshake_timeouts_total 3985
telemt_upstream_connect_attempt_total 50804
telemt_upstream_connect_success_total 50802
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 50804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4922
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50798
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 770155604 (734.48 MB)
telemt_user_octets_to_client{user="hello"} 47027264533 (43.80 GB)
telemt_user_msgs_from_client{user="hello"} 1074978
telemt_user_msgs_to_client{user="hello"} 7088053
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 28851.0 (8h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53666
telemt_connections_bad_total 87
telemt_handshake_timeouts_total 329
telemt_upstream_connect_attempt_total 51523
telemt_upstream_connect_success_total 51380
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 51523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6066
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51376
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 821335094 (783.29 MB)
telemt_user_octets_to_client{user="hello"} 37141069525 (34.59 GB)
telemt_user_msgs_from_client{user="hello"} 1112251
telemt_user_msgs_to_client{user="hello"} 7094014
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 28852.3 (8h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78345
telemt_connections_bad_total 7168
telemt_handshake_timeouts_total 1456
telemt_upstream_connect_attempt_total 66651
telemt_upstream_connect_success_total 66403
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 66651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8815
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 66399
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 2041694268 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 51219833746 (47.70 GB)
telemt_user_msgs_from_client{user="hello"} 1874152
telemt_user_msgs_to_client{user="hello"} 7534546
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 7821.7 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```