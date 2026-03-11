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

# Server Metrics 2026-03-11 09:34:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 68911.2 (19h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201441
telemt_connections_bad_total 3592
telemt_handshake_timeouts_total 4267
telemt_upstream_connect_attempt_total 184266
telemt_upstream_connect_success_total 184207
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 184266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 168220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15930
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 184199
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 4052432197 (3.77 GB)
telemt_user_octets_to_client{user="hello"} 110222514277 (102.65 GB)
telemt_user_msgs_from_client{user="hello"} 4385705
telemt_user_msgs_to_client{user="hello"} 8183611
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 68910.6 (19h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78298
telemt_connections_bad_total 778
telemt_handshake_timeouts_total 3141
telemt_upstream_connect_attempt_total 70718
telemt_upstream_connect_success_total 70702
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 70718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60840
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9613
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 249
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 70694
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 4944236150 (4.60 GB)
telemt_user_octets_to_client{user="hello"} 55226570610 (51.43 GB)
telemt_user_msgs_from_client{user="hello"} 3136434
telemt_user_msgs_to_client{user="hello"} 14152247
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 68910.7 (19h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108246
telemt_connections_bad_total 943
telemt_handshake_timeouts_total 5221
telemt_upstream_connect_attempt_total 95923
telemt_upstream_connect_success_total 95919
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 95923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 85008
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10848
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 95911
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 11988135345 (11.16 GB)
telemt_user_octets_to_client{user="hello"} 80217695003 (74.71 GB)
telemt_user_msgs_from_client{user="hello"} 5626742
telemt_user_msgs_to_client{user="hello"} 15580192
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 68909.3 (19h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119717
telemt_connections_bad_total 251
telemt_handshake_timeouts_total 1108
telemt_upstream_connect_attempt_total 113698
telemt_upstream_connect_success_total 113439
telemt_upstream_connect_fail_total 259
telemt_upstream_connect_attempts_per_request{bucket="1"} 113698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 97852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15218
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 58
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 311
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 259
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 113431
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 5273173052 (4.91 GB)
telemt_user_octets_to_client{user="hello"} 81451703207 (75.86 GB)
telemt_user_msgs_from_client{user="hello"} 3508011
telemt_user_msgs_to_client{user="hello"} 20940593
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 68910.5 (19h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189198
telemt_connections_bad_total 15041
telemt_handshake_timeouts_total 3313
telemt_upstream_connect_attempt_total 151242
telemt_upstream_connect_success_total 150840
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 151242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 129314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 280
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 150834
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 2928866745 (2.73 GB)
telemt_user_octets_to_client{user="hello"} 134479891679 (125.24 GB)
telemt_user_msgs_from_client{user="hello"} 3361483
telemt_user_msgs_to_client{user="hello"} 17585025
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 47879.9 (13h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420
telemt_connections_bad_total 398
telemt_handshake_timeouts_total 9
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