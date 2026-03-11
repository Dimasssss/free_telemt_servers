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

# Server Metrics 2026-03-11 13:19:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 82429.0 (22h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266501
telemt_connections_bad_total 3646
telemt_handshake_timeouts_total 4704
telemt_upstream_connect_attempt_total 246321
telemt_upstream_connect_success_total 246246
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 246321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 225451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20736
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 246238
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 4859315629 (4.53 GB)
telemt_user_octets_to_client{user="hello"} 128586775562 (119.76 GB)
telemt_user_msgs_from_client{user="hello"} 5517144
telemt_user_msgs_to_client{user="hello"} 10116554
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 82428.3 (22h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103723
telemt_connections_bad_total 906
telemt_handshake_timeouts_total 3331
telemt_upstream_connect_attempt_total 94951
telemt_upstream_connect_success_total 94932
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 94951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 82312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12288
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 332
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 94924
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 5225756919 (4.87 GB)
telemt_user_octets_to_client{user="hello"} 63756509558 (59.38 GB)
telemt_user_msgs_from_client{user="hello"} 3538788
telemt_user_msgs_to_client{user="hello"} 17965634
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 82428.1 (22h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144342
telemt_connections_bad_total 1160
telemt_handshake_timeouts_total 6791
telemt_upstream_connect_attempt_total 128487
telemt_upstream_connect_success_total 128473
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 128487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 113976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14402
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 128465
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 12543319340 (11.68 GB)
telemt_user_octets_to_client{user="hello"} 108377891214 (100.93 GB)
telemt_user_msgs_from_client{user="hello"} 6413646
telemt_user_msgs_to_client{user="hello"} 22957894
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 82426.9 (22h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158848
telemt_connections_bad_total 2864
telemt_handshake_timeouts_total 1901
telemt_upstream_connect_attempt_total 147651
telemt_upstream_connect_success_total 147306
telemt_upstream_connect_fail_total 345
telemt_upstream_connect_attempts_per_request{bucket="1"} 147651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 127995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18836
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 84
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 391
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 345
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 147298
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 8656697184 (8.06 GB)
telemt_user_octets_to_client{user="hello"} 108783759867 (101.31 GB)
telemt_user_msgs_from_client{user="hello"} 5220512
telemt_user_msgs_to_client{user="hello"} 32051565
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 82428.3 (22h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 235644
telemt_connections_bad_total 18336
telemt_handshake_timeouts_total 5932
telemt_upstream_connect_attempt_total 190006
telemt_upstream_connect_success_total 189504
telemt_upstream_connect_fail_total 502
telemt_upstream_connect_attempts_per_request{bucket="1"} 190006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 163838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 338
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 502
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 189496
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 4764789081 (4.44 GB)
telemt_user_octets_to_client{user="hello"} 154834804127 (144.20 GB)
telemt_user_msgs_from_client{user="hello"} 4515714
telemt_user_msgs_to_client{user="hello"} 21386390
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 61397.6 (17h 3m)
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