# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

-----

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

# Server Metrics 2026-03-09 16:54:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 63295.1 (17h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117146
telemt_connections_bad_total 1656
telemt_handshake_timeouts_total 984
telemt_upstream_connect_attempt_total 109707
telemt_upstream_connect_success_total 109667
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 109707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 101298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8310
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 109661
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 2957034676 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 58724817137 (54.69 GB)
telemt_user_msgs_from_client{user="hello"} 2741676
telemt_user_msgs_to_client{user="hello"} 3850193
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 63293.7 (17h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31410
telemt_connections_bad_total 222
telemt_handshake_timeouts_total 356
telemt_upstream_connect_attempt_total 29618
telemt_upstream_connect_success_total 29600
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 29618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2551
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 238
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29594
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 1006401541 (959.78 MB)
telemt_user_octets_to_client{user="hello"} 15880209135 (14.79 GB)
telemt_user_msgs_from_client{user="hello"} 855617
telemt_user_msgs_to_client{user="hello"} 4400597
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 63294.4 (17h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39989
telemt_connections_bad_total 657
telemt_handshake_timeouts_total 1766
telemt_upstream_connect_attempt_total 30536
telemt_upstream_connect_success_total 30536
telemt_upstream_connect_attempts_per_request{bucket="1"} 30536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3343
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30530
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 4467715701 (4.16 GB)
telemt_user_octets_to_client{user="hello"} 18614810011 (17.34 GB)
telemt_user_msgs_from_client{user="hello"} 1997322
telemt_user_msgs_to_client{user="hello"} 2484787
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 63289.0 (17h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45745
telemt_connections_bad_total 198
telemt_handshake_timeouts_total 881
telemt_upstream_connect_attempt_total 41851
telemt_upstream_connect_success_total 41750
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 41851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5863
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41742
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 1957812179 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 31368086364 (29.21 GB)
telemt_user_msgs_from_client{user="hello"} 1294189
telemt_user_msgs_to_client{user="hello"} 7928807
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 63294.6 (17h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74287
telemt_connections_bad_total 15310
telemt_handshake_timeouts_total 1681
telemt_upstream_connect_attempt_total 53889
telemt_upstream_connect_success_total 53887
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 53889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8191
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53879
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 917621217 (875.11 MB)
telemt_user_octets_to_client{user="hello"} 55523409742 (51.71 GB)
telemt_user_msgs_from_client{user="hello"} 1245538
telemt_user_msgs_to_client{user="hello"} 6813397
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 16
```