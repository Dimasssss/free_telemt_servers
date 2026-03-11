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

# Server Metrics 2026-03-11 06:30:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 57887.7 (16h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155231
telemt_connections_bad_total 3497
telemt_handshake_timeouts_total 3926
telemt_upstream_connect_attempt_total 139922
telemt_upstream_connect_success_total 139878
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 139922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 127598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 139872
telemt_user_connections_current{user="hello"} 356
telemt_user_octets_from_client{user="hello"} 3390948161 (3.16 GB)
telemt_user_octets_to_client{user="hello"} 93537428837 (87.11 GB)
telemt_user_msgs_from_client{user="hello"} 3555499
telemt_user_msgs_to_client{user="hello"} 6639147
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 57887.4 (16h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60966
telemt_connections_bad_total 447
telemt_handshake_timeouts_total 3031
telemt_upstream_connect_attempt_total 54417
telemt_upstream_connect_success_total 54405
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 54417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7866
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 54399
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 4609182915 (4.29 GB)
telemt_user_octets_to_client{user="hello"} 48356028259 (45.04 GB)
telemt_user_msgs_from_client{user="hello"} 2812839
telemt_user_msgs_to_client{user="hello"} 11515676
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 57886.7 (16h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82829
telemt_connections_bad_total 737
telemt_handshake_timeouts_total 4376
telemt_upstream_connect_attempt_total 73088
telemt_upstream_connect_success_total 73085
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 73088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8207
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 73079
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 11820889193 (11.01 GB)
telemt_user_octets_to_client{user="hello"} 72700589776 (67.71 GB)
telemt_user_msgs_from_client{user="hello"} 5265740
telemt_user_msgs_to_client{user="hello"} 13768720
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 57885.7 (16h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88826
telemt_connections_bad_total 195
telemt_handshake_timeouts_total 638
telemt_upstream_connect_attempt_total 85041
telemt_upstream_connect_success_total 84852
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 85041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11157
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 236
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 84846
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 1930265853 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 56878301264 (52.97 GB)
telemt_user_msgs_from_client{user="hello"} 1916402
telemt_user_msgs_to_client{user="hello"} 13634620
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 57887.1 (16h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151314
telemt_connections_bad_total 12829
telemt_handshake_timeouts_total 1795
telemt_upstream_connect_attempt_total 119160
telemt_upstream_connect_success_total 118911
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 119160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 101746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16930
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 235
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 118905
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 2488943469 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 113846033022 (106.03 GB)
telemt_user_msgs_from_client{user="hello"} 2813246
telemt_user_msgs_to_client{user="hello"} 14928598
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 36856.4 (10h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166
telemt_connections_bad_total 146
telemt_handshake_timeouts_total 8
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