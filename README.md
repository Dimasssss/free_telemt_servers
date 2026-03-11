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

# Server Metrics 2026-03-11 08:28:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 64924.7 (18h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183233
telemt_connections_bad_total 3547
telemt_handshake_timeouts_total 4113
telemt_upstream_connect_attempt_total 166836
telemt_upstream_connect_success_total 166785
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 166836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 152310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 166777
telemt_user_connections_current{user="hello"} 311
telemt_user_octets_from_client{user="hello"} 3748792869 (3.49 GB)
telemt_user_octets_to_client{user="hello"} 105202851695 (97.98 GB)
telemt_user_msgs_from_client{user="hello"} 4043947
telemt_user_msgs_to_client{user="hello"} 7589673
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 64924.2 (18h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71171
telemt_connections_bad_total 587
telemt_handshake_timeouts_total 3108
telemt_upstream_connect_attempt_total 64100
telemt_upstream_connect_success_total 64086
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 64100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8806
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 64080
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 4885498191 (4.55 GB)
telemt_user_octets_to_client{user="hello"} 53143283830 (49.49 GB)
telemt_user_msgs_from_client{user="hello"} 3041267
telemt_user_msgs_to_client{user="hello"} 13471356
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 64924.0 (18h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98751
telemt_connections_bad_total 916
telemt_handshake_timeouts_total 5184
telemt_upstream_connect_attempt_total 86863
telemt_upstream_connect_success_total 86860
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 86863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9655
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 86852
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 11926922425 (11.11 GB)
telemt_user_octets_to_client{user="hello"} 75431411794 (70.25 GB)
telemt_user_msgs_from_client{user="hello"} 5463081
telemt_user_msgs_to_client{user="hello"} 14711710
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 64922.8 (18h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107930
telemt_connections_bad_total 223
telemt_handshake_timeouts_total 735
telemt_upstream_connect_attempt_total 102965
telemt_upstream_connect_success_total 102732
telemt_upstream_connect_fail_total 233
telemt_upstream_connect_attempts_per_request{bucket="1"} 102965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13718
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 53
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 280
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 233
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 102724
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 4474984072 (4.17 GB)
telemt_user_octets_to_client{user="hello"} 71187480315 (66.30 GB)
telemt_user_msgs_from_client{user="hello"} 3069416
telemt_user_msgs_to_client{user="hello"} 18084770
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 64924.1 (18h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176770
telemt_connections_bad_total 14315
telemt_handshake_timeouts_total 2552
telemt_upstream_connect_attempt_total 140647
telemt_upstream_connect_success_total 140397
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 140647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 120315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19828
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 254
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 140391
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 2838376910 (2.64 GB)
telemt_user_octets_to_client{user="hello"} 131630020396 (122.59 GB)
telemt_user_msgs_from_client{user="hello"} 3204472
telemt_user_msgs_to_client{user="hello"} 16963572
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 43893.5 (12h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 410
telemt_connections_bad_total 388
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