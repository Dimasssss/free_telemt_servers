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

# Server Metrics 2026-03-12 06:40:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 32115.1 (8h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88242
telemt_connections_bad_total 2118
telemt_handshake_timeouts_total 2320
telemt_upstream_connect_attempt_total 79969
telemt_upstream_connect_success_total 79857
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 79969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12079
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 79853
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 819771594 (781.80 MB)
telemt_user_octets_to_client{user="hello"} 23712329096 (22.08 GB)
telemt_user_msgs_from_client{user="hello"} 1200995
telemt_user_msgs_to_client{user="hello"} 2726705
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 32103.2 (8h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35932
telemt_connections_bad_total 211
telemt_handshake_timeouts_total 537
telemt_upstream_connect_attempt_total 33915
telemt_upstream_connect_success_total 33890
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 33915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4608
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33886
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 306713028 (292.50 MB)
telemt_user_octets_to_client{user="hello"} 15905550316 (14.81 GB)
telemt_user_msgs_from_client{user="hello"} 605461
telemt_user_msgs_to_client{user="hello"} 5040803
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 32076.7 (8h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53511
telemt_connections_bad_total 676
telemt_handshake_timeouts_total 1117
telemt_upstream_connect_attempt_total 48305
telemt_upstream_connect_success_total 48278
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 48305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 48274
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 5448241681 (5.07 GB)
telemt_user_octets_to_client{user="hello"} 28913531977 (26.93 GB)
telemt_user_msgs_from_client{user="hello"} 2710744
telemt_user_msgs_to_client{user="hello"} 5147942
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 32102.2 (8h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58787
telemt_connections_bad_total 13010
telemt_handshake_timeouts_total 887
telemt_upstream_connect_attempt_total 42507
telemt_upstream_connect_success_total 40764
telemt_upstream_connect_fail_total 1742
telemt_upstream_connect_attempts_per_request{bucket="1"} 42506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6934
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1742
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 40760
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 1394600635 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 30433344172 (28.34 GB)
telemt_user_msgs_from_client{user="hello"} 1117935
telemt_user_msgs_to_client{user="hello"} 12434829
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 2294.5 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3346
telemt_connections_bad_total 410
telemt_handshake_timeouts_total 79
telemt_upstream_connect_attempt_total 2743
telemt_upstream_connect_success_total 2721
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 2743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 292
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2719
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 116159969 (110.78 MB)
telemt_user_octets_to_client{user="hello"} 3062550657 (2.85 GB)
telemt_user_msgs_from_client{user="hello"} 89396
telemt_user_msgs_to_client{user="hello"} 372452
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 32103.0 (8h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55310
telemt_connections_bad_total 889
telemt_handshake_timeouts_total 324
telemt_upstream_connect_attempt_total 51591
telemt_upstream_connect_success_total 51537
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 51591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8513
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51533
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 939935865 (896.39 MB)
telemt_user_octets_to_client{user="hello"} 48324738882 (45.01 GB)
telemt_user_msgs_from_client{user="hello"} 1324550
telemt_user_msgs_to_client{user="hello"} 6184848
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 29
```