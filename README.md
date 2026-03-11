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

# Server Metrics 2026-03-11 02:31:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 43522.2 (12h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114888
telemt_connections_bad_total 3353
telemt_handshake_timeouts_total 2558
telemt_upstream_connect_attempt_total 103752
telemt_upstream_connect_success_total 103716
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 103752
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 94432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 103710
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 2888650939 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 80853149965 (75.30 GB)
telemt_user_msgs_from_client{user="hello"} 2922884
telemt_user_msgs_to_client{user="hello"} 5604177
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 43521.6 (12h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47365
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 2316
telemt_upstream_connect_attempt_total 42069
telemt_upstream_connect_success_total 42060
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 42069
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6364
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42056
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 2267358551 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 41417472603 (38.57 GB)
telemt_user_msgs_from_client{user="hello"} 1744079
telemt_user_msgs_to_client{user="hello"} 10056958
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 43521.1 (12h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68533
telemt_connections_bad_total 653
telemt_handshake_timeouts_total 4165
telemt_upstream_connect_attempt_total 59845
telemt_upstream_connect_success_total 59843
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 59845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6463
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 59837
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 11737147834 (10.93 GB)
telemt_user_octets_to_client{user="hello"} 69971869895 (65.17 GB)
telemt_user_msgs_from_client{user="hello"} 5121634
telemt_user_msgs_to_client{user="hello"} 13115463
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 43520.2 (12h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67243
telemt_connections_bad_total 147
telemt_handshake_timeouts_total 542
telemt_upstream_connect_attempt_total 64320
telemt_upstream_connect_success_total 64164
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 64320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8002
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 64158
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 1756880647 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 42588991116 (39.66 GB)
telemt_user_msgs_from_client{user="hello"} 1583330
telemt_user_msgs_to_client{user="hello"} 8340720
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 43521.6 (12h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100540
telemt_connections_bad_total 10058
telemt_handshake_timeouts_total 1523
telemt_upstream_connect_attempt_total 85194
telemt_upstream_connect_success_total 84946
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 85194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11080
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 84942
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 2179844604 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 72490378860 (67.51 GB)
telemt_user_msgs_from_client{user="hello"} 2202908
telemt_user_msgs_to_client{user="hello"} 10188997
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 22490.8 (6h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68
telemt_connections_bad_total 64
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```