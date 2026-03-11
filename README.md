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

# Server Metrics 2026-03-11 06:20:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 57277.0 (15h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152817
telemt_connections_bad_total 3497
telemt_handshake_timeouts_total 3882
telemt_upstream_connect_attempt_total 137704
telemt_upstream_connect_success_total 137660
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 137704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 125570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12034
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 137654
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 3355880135 (3.13 GB)
telemt_user_octets_to_client{user="hello"} 92479911619 (86.13 GB)
telemt_user_msgs_from_client{user="hello"} 3507109
telemt_user_msgs_to_client{user="hello"} 6537773
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 57276.4 (15h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60270
telemt_connections_bad_total 447
telemt_handshake_timeouts_total 3026
telemt_upstream_connect_attempt_total 53748
telemt_upstream_connect_success_total 53736
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 53748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53730
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 4597664943 (4.28 GB)
telemt_user_octets_to_client{user="hello"} 48079411301 (44.78 GB)
telemt_user_msgs_from_client{user="hello"} 2794389
telemt_user_msgs_to_client{user="hello"} 11422573
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 57276.1 (15h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81816
telemt_connections_bad_total 737
telemt_handshake_timeouts_total 4364
telemt_upstream_connect_attempt_total 72131
telemt_upstream_connect_success_total 72128
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 72131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63972
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8101
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 72122
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 11812074081 (11.00 GB)
telemt_user_octets_to_client{user="hello"} 72316979174 (67.35 GB)
telemt_user_msgs_from_client{user="hello"} 5250691
telemt_user_msgs_to_client{user="hello"} 13673006
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 57275.1 (15h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87539
telemt_connections_bad_total 194
telemt_handshake_timeouts_total 637
telemt_upstream_connect_attempt_total 83787
telemt_upstream_connect_success_total 83603
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 83787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11007
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 83597
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 1904901686 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 55836229622 (52.00 GB)
telemt_user_msgs_from_client{user="hello"} 1887936
telemt_user_msgs_to_client{user="hello"} 13214480
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 57276.4 (15h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149600
telemt_connections_bad_total 12720
telemt_handshake_timeouts_total 1788
telemt_upstream_connect_attempt_total 117646
telemt_upstream_connect_success_total 117397
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 117646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 100445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 235
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 117391
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 2475599369 (2.31 GB)
telemt_user_octets_to_client{user="hello"} 111686415004 (104.02 GB)
telemt_user_msgs_from_client{user="hello"} 2785128
telemt_user_msgs_to_client{user="hello"} 14738793
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 36245.8 (10h 4m)
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