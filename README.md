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

# Server Metrics 2026-03-11 19:34:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 9266.6 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35665
telemt_connections_bad_total 1997
telemt_handshake_timeouts_total 139
telemt_upstream_connect_attempt_total 32186
telemt_upstream_connect_success_total 32177
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 32186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3054
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32175
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 819587571 (781.62 MB)
telemt_user_octets_to_client{user="hello"} 19148083864 (17.83 GB)
telemt_user_msgs_from_client{user="hello"} 820442
telemt_user_msgs_to_client{user="hello"} 1576264
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 9254.4 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17046
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 246
telemt_upstream_connect_attempt_total 15616
telemt_upstream_connect_success_total 15606
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 15616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 309
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15604
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 205743286 (196.21 MB)
telemt_user_octets_to_client{user="hello"} 8586406128 (8.00 GB)
telemt_user_msgs_from_client{user="hello"} 336732
telemt_user_msgs_to_client{user="hello"} 3304405
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 9274.3 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19772
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 166
telemt_upstream_connect_attempt_total 18468
telemt_upstream_connect_success_total 18466
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 18468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1600
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18464
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 194019155 (185.03 MB)
telemt_user_octets_to_client{user="hello"} 8595194507 (8.00 GB)
telemt_user_msgs_from_client{user="hello"} 379325
telemt_user_msgs_to_client{user="hello"} 2112770
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 9269.7 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21743
telemt_connections_bad_total 1753
telemt_handshake_timeouts_total 374
telemt_upstream_connect_attempt_total 18689
telemt_upstream_connect_success_total 18632
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 18689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1688
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18630
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 583211303 (556.19 MB)
telemt_user_octets_to_client{user="hello"} 10766578545 (10.03 GB)
telemt_user_msgs_from_client{user="hello"} 464307
telemt_user_msgs_to_client{user="hello"} 2871714
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 9277.9 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22546
telemt_connections_bad_total 1788
telemt_handshake_timeouts_total 158
telemt_upstream_connect_attempt_total 19823
telemt_upstream_connect_success_total 19822
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 19823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2500
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19820
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 343830197 (327.90 MB)
telemt_user_octets_to_client{user="hello"} 7435277892 (6.92 GB)
telemt_user_msgs_from_client{user="hello"} 435320
telemt_user_msgs_to_client{user="hello"} 2499434
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 83884.4 (23h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 565
telemt_connections_bad_total 491
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 59
telemt_upstream_connect_success_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 201572 (196.85 KB)
telemt_user_octets_to_client{user="hello"} 1307210 (1.25 MB)
telemt_user_msgs_from_client{user="hello"} 250
telemt_user_msgs_to_client{user="hello"} 389
```