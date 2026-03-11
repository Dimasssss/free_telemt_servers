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

# Server Metrics 2026-03-11 07:37:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 61863.6 (17h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170103
telemt_connections_bad_total 3538
telemt_handshake_timeouts_total 4018
telemt_upstream_connect_attempt_total 154147
telemt_upstream_connect_success_total 154100
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 154147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 140616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13427
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 154092
telemt_user_connections_current{user="hello"} 348
telemt_user_octets_from_client{user="hello"} 3588884452 (3.34 GB)
telemt_user_octets_to_client{user="hello"} 99983091375 (93.12 GB)
telemt_user_msgs_from_client{user="hello"} 3830019
telemt_user_msgs_to_client{user="hello"} 7191497
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 61862.7 (17h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66643
telemt_connections_bad_total 477
telemt_handshake_timeouts_total 3072
telemt_upstream_connect_attempt_total 59842
telemt_upstream_connect_success_total 59828
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 59842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8378
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 59822
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 4673646655 (4.35 GB)
telemt_user_octets_to_client{user="hello"} 51055195772 (47.55 GB)
telemt_user_msgs_from_client{user="hello"} 2907483
telemt_user_msgs_to_client{user="hello"} 12483496
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 61862.8 (17h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92409
telemt_connections_bad_total 869
telemt_handshake_timeouts_total 5146
telemt_upstream_connect_attempt_total 80890
telemt_upstream_connect_success_total 80887
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 80890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71872
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8954
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 80881
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 11893060840 (11.08 GB)
telemt_user_octets_to_client{user="hello"} 74704060188 (69.57 GB)
telemt_user_msgs_from_client{user="hello"} 5372882
telemt_user_msgs_to_client{user="hello"} 14398434
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 61861.5 (17h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98677
telemt_connections_bad_total 218
telemt_handshake_timeouts_total 669
telemt_upstream_connect_attempt_total 94577
telemt_upstream_connect_success_total 94363
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 94571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12477
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 265
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 94355
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 2885459828 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 64201519528 (59.79 GB)
telemt_user_msgs_from_client{user="hello"} 2393963
telemt_user_msgs_to_client{user="hello"} 15881495
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 61862.7 (17h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165640
telemt_connections_bad_total 13748
telemt_handshake_timeouts_total 1884
telemt_upstream_connect_attempt_total 131946
telemt_upstream_connect_success_total 131696
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 131946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 113034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18419
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 243
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 131690
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 2588943176 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 127360326209 (118.61 GB)
telemt_user_msgs_from_client{user="hello"} 3017083
telemt_user_msgs_to_client{user="hello"} 16209717
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 40832.0 (11h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222
telemt_connections_bad_total 202
telemt_handshake_timeouts_total 9
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