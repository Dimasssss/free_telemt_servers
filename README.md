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

# Server Metrics 2026-03-11 07:27:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 61251.3 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167366
telemt_connections_bad_total 3537
telemt_handshake_timeouts_total 4009
telemt_upstream_connect_attempt_total 151478
telemt_upstream_connect_success_total 151431
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 151478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 138133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13242
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 151423
telemt_user_connections_current{user="hello"} 321
telemt_user_octets_from_client{user="hello"} 3567234244 (3.32 GB)
telemt_user_octets_to_client{user="hello"} 99239632271 (92.42 GB)
telemt_user_msgs_from_client{user="hello"} 3795389
telemt_user_msgs_to_client{user="hello"} 7124281
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 61250.9 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65943
telemt_connections_bad_total 461
telemt_handshake_timeouts_total 3070
telemt_upstream_connect_attempt_total 59196
telemt_upstream_connect_success_total 59182
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 59196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8312
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 59176
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 4669316217 (4.35 GB)
telemt_user_octets_to_client{user="hello"} 50915641658 (47.42 GB)
telemt_user_msgs_from_client{user="hello"} 2896638
telemt_user_msgs_to_client{user="hello"} 12413501
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 61250.7 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90442
telemt_connections_bad_total 776
telemt_handshake_timeouts_total 5076
telemt_upstream_connect_attempt_total 79254
telemt_upstream_connect_success_total 79250
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 79253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 79244
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 11872351620 (11.06 GB)
telemt_user_octets_to_client{user="hello"} 74575499188 (69.45 GB)
telemt_user_msgs_from_client{user="hello"} 5354472
telemt_user_msgs_to_client{user="hello"} 14341923
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 61249.6 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97171
telemt_connections_bad_total 217
telemt_handshake_timeouts_total 667
telemt_upstream_connect_attempt_total 93118
telemt_upstream_connect_success_total 92909
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 93117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12235
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 50
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 262
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 92901
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 2276617662 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 62896099163 (58.58 GB)
telemt_user_msgs_from_client{user="hello"} 2163190
telemt_user_msgs_to_client{user="hello"} 15594813
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 61250.9 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163156
telemt_connections_bad_total 13498
telemt_handshake_timeouts_total 1863
telemt_upstream_connect_attempt_total 129788
telemt_upstream_connect_success_total 129538
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 129788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18118
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 129532
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 2577634868 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 126309055161 (117.63 GB)
telemt_user_msgs_from_client{user="hello"} 2989068
telemt_user_msgs_to_client{user="hello"} 16086250
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 40220.2 (11h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220
telemt_connections_bad_total 200
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 15
telemt_upstream_connect_success_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```