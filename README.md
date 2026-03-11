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

# Server Metrics 2026-03-11 18:07:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 4042.9 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16670
telemt_connections_bad_total 892
telemt_handshake_timeouts_total 83
telemt_upstream_connect_attempt_total 14900
telemt_upstream_connect_success_total 14897
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 14900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1406
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14895
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 425720096 (406.00 MB)
telemt_user_octets_to_client{user="hello"} 9462049931 (8.81 GB)
telemt_user_msgs_from_client{user="hello"} 370172
telemt_user_msgs_to_client{user="hello"} 669975
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 4031.1 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8725
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 153
telemt_upstream_connect_attempt_total 7935
telemt_upstream_connect_success_total 7934
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7935
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 961
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7932
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 121277028 (115.66 MB)
telemt_user_octets_to_client{user="hello"} 4981188289 (4.64 GB)
telemt_user_msgs_from_client{user="hello"} 186478
telemt_user_msgs_to_client{user="hello"} 1923382
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 4050.4 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9694
telemt_connections_bad_total 19
telemt_handshake_timeouts_total 101
telemt_upstream_connect_attempt_total 9051
telemt_upstream_connect_success_total 9050
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 859
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9048
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 75121096 (71.64 MB)
telemt_user_octets_to_client{user="hello"} 3986361842 (3.71 GB)
telemt_user_msgs_from_client{user="hello"} 188689
telemt_user_msgs_to_client{user="hello"} 1138799
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 4046.3 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9113
telemt_connections_bad_total 395
telemt_handshake_timeouts_total 185
telemt_upstream_connect_attempt_total 8220
telemt_upstream_connect_success_total 8201
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 8220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 845
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8199
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 435170930 (415.01 MB)
telemt_user_octets_to_client{user="hello"} 3773174831 (3.51 GB)
telemt_user_msgs_from_client{user="hello"} 256836
telemt_user_msgs_to_client{user="hello"} 911716
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 4054.4 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10416
telemt_connections_bad_total 843
telemt_handshake_timeouts_total 68
telemt_upstream_connect_attempt_total 9208
telemt_upstream_connect_success_total 9208
telemt_upstream_connect_attempts_per_request{bucket="1"} 9208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9206
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 59914134 (57.14 MB)
telemt_user_octets_to_client{user="hello"} 1307406773 (1.22 GB)
telemt_user_msgs_from_client{user="hello"} 126779
telemt_user_msgs_to_client{user="hello"} 417821
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 78660.8 (21h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 495
telemt_connections_bad_total 471
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 19
telemt_upstream_connect_success_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```