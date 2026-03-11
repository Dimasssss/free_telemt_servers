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

# Server Metrics 2026-03-11 05:29:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 54219.2 (15h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139395
telemt_connections_bad_total 3410
telemt_handshake_timeouts_total 3014
telemt_upstream_connect_attempt_total 126709
telemt_upstream_connect_success_total 126665
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 126709
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 115548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11062
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 126659
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 3119093124 (2.90 GB)
telemt_user_octets_to_client{user="hello"} 88588219949 (82.50 GB)
telemt_user_msgs_from_client{user="hello"} 3281579
telemt_user_msgs_to_client{user="hello"} 6232802
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 54218.8 (15h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56700
telemt_connections_bad_total 438
telemt_handshake_timeouts_total 2975
telemt_upstream_connect_attempt_total 50379
telemt_upstream_connect_success_total 50367
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 50379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7510
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50361
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 4508412716 (4.20 GB)
telemt_user_octets_to_client{user="hello"} 47231510683 (43.99 GB)
telemt_user_msgs_from_client{user="hello"} 2702177
telemt_user_msgs_to_client{user="hello"} 11125036
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 54218.5 (15h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77327
telemt_connections_bad_total 719
telemt_handshake_timeouts_total 4324
telemt_upstream_connect_attempt_total 67899
telemt_upstream_connect_success_total 67896
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 67899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7636
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 67890
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 11792430535 (10.98 GB)
telemt_user_octets_to_client{user="hello"} 71347298780 (66.45 GB)
telemt_user_msgs_from_client{user="hello"} 5204909
telemt_user_msgs_to_client{user="hello"} 13436786
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 54217.3 (15h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81203
telemt_connections_bad_total 163
telemt_handshake_timeouts_total 599
telemt_upstream_connect_attempt_total 77736
telemt_upstream_connect_success_total 77567
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 77736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10164
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 77561
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 1841556196 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 49634345621 (46.23 GB)
telemt_user_msgs_from_client{user="hello"} 1763263
telemt_user_msgs_to_client{user="hello"} 10900738
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 54218.7 (15h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131303
telemt_connections_bad_total 12174
telemt_handshake_timeouts_total 1737
telemt_upstream_connect_attempt_total 109795
telemt_upstream_connect_success_total 109546
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 109795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 95084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14229
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 109540
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 2421567110 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 105346031306 (98.11 GB)
telemt_user_msgs_from_client{user="hello"} 2663071
telemt_user_msgs_to_client{user="hello"} 13589225
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 33188.0 (9h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```