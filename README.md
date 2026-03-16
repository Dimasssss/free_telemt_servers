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

# Server Metrics 2026-03-16 20:55:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 7815.8 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54147
telemt_connections_bad_total 527
telemt_handshake_timeouts_total 2780
telemt_upstream_connect_attempt_total 1449
telemt_upstream_connect_success_total 1437
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 793
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 1024
telemt_me_reconnect_success_total 1020
telemt_me_reader_eof_total 1049
telemt_me_idle_close_by_peer_total 1049
telemt_me_route_drop_no_conn_total 18399
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48644
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 236
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 181
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1017
telemt_me_writer_restored_same_endpoint_total 999
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_user_connections_total{user="hello"} 48602
telemt_user_connections_current{user="hello"} 574
telemt_user_octets_from_client{user="hello"} 924946588 (882.10 MB)
telemt_user_octets_to_client{user="hello"} 31895897332 (29.71 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 8067.2 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43645
telemt_connections_bad_total 25
telemt_handshake_timeouts_total 2074
telemt_upstream_connect_attempt_total 1706
telemt_upstream_connect_success_total 1682
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 1706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 1271
telemt_me_reconnect_success_total 1268
telemt_me_reader_eof_total 1311
telemt_me_idle_close_by_peer_total 1311
telemt_me_route_drop_no_conn_total 16823
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39545
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 91
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 66
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1289
telemt_me_writer_restored_same_endpoint_total 1252
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 39530
telemt_user_connections_current{user="hello"} 279
telemt_user_octets_from_client{user="hello"} 587816608 (560.59 MB)
telemt_user_octets_to_client{user="hello"} 15266572412 (14.22 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 7843.3 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23054
telemt_connections_bad_total 352
telemt_handshake_timeouts_total 155
telemt_upstream_connect_attempt_total 1750
telemt_upstream_connect_success_total 1738
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 995
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 1334
telemt_me_reconnect_success_total 1317
telemt_me_reader_eof_total 1376
telemt_me_idle_close_by_peer_total 1376
telemt_me_route_drop_no_conn_total 7770
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21975
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1331
telemt_me_writer_restored_same_endpoint_total 1306
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 21971
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 556253332 (530.48 MB)
telemt_user_octets_to_client{user="hello"} 8371544492 (7.80 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 7902.7 (2h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46169
telemt_connections_bad_total 2928
telemt_handshake_timeouts_total 365
telemt_upstream_connect_attempt_total 1590
telemt_upstream_connect_success_total 1570
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 1590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 794
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 1159
telemt_me_reconnect_success_total 1145
telemt_me_reader_eof_total 1183
telemt_me_idle_close_by_peer_total 1183
telemt_me_route_drop_no_conn_total 14294
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41540
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 121
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1159
telemt_me_writer_restored_same_endpoint_total 1138
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 41533
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 626013768 (597.01 MB)
telemt_user_octets_to_client{user="hello"} 15262658508 (14.21 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 7874.7 (2h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30017
telemt_connections_bad_total 8959
telemt_handshake_timeouts_total 169
telemt_upstream_connect_attempt_total 1975
telemt_upstream_connect_success_total 1949
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 1975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1001
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 2628
telemt_me_reconnect_success_total 1532
telemt_me_reader_eof_total 1579
telemt_me_idle_close_by_peer_total 1579
telemt_me_route_drop_no_conn_total 7966
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19822
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1570
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 1524
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 19820
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 199613684 (190.37 MB)
telemt_user_octets_to_client{user="hello"} 6635952716 (6.18 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 8035.8 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67813
telemt_connections_bad_total 925
telemt_handshake_timeouts_total 690
telemt_upstream_connect_attempt_total 1468
telemt_upstream_connect_success_total 1458
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 738
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 1047
telemt_me_reconnect_success_total 1045
telemt_me_reader_eof_total 1088
telemt_me_idle_close_by_peer_total 1088
telemt_me_route_drop_no_conn_total 28472
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63806
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1062
telemt_me_writer_restored_same_endpoint_total 1035
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 63799
telemt_user_connections_current{user="hello"} 505
telemt_user_octets_from_client{user="hello"} 1394365808 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 33592695792 (31.29 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 57
```