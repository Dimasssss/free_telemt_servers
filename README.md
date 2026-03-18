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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-18 13:15:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 16443.2 (4h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 612749
telemt_connections_bad_total 24730
telemt_handshake_timeouts_total 16541
telemt_upstream_connect_attempt_total 66201
telemt_upstream_connect_success_total 65246
telemt_upstream_connect_fail_total 955
telemt_upstream_connect_attempts_per_request{bucket="1"} 66201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4096
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 955
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 514061
telemt_me_reconnect_success_total 2412
telemt_me_reader_eof_total 2572
telemt_me_idle_close_by_peer_total 2570
telemt_me_route_drop_no_conn_total 364061
telemt_me_route_drop_channel_closed_total 128
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 470627
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2134
telemt_desync_full_logged_total 713
telemt_desync_suppressed_total 1421
telemt_desync_frames_bucket_total{bucket="1_2"} 599
telemt_desync_frames_bucket_total{bucket="3_10"} 755
telemt_desync_frames_bucket_total{bucket="gt_10"} 780
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2580
telemt_me_refill_failed_total 16672
telemt_me_writer_restored_same_endpoint_total 2307
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 528833
telemt_user_connections_current{user="hello"} 1753
telemt_user_octets_from_client{user="hello"} 7096968316 (6.61 GB)
telemt_user_octets_to_client{user="hello"} 134608270445 (125.36 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 560
telemt_user_unique_ips_recent_window{user="hello"} 254
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 16475.2 (4h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1630683
telemt_connections_bad_total 115213
telemt_handshake_timeouts_total 36310
telemt_upstream_connect_attempt_total 2946
telemt_upstream_connect_success_total 2934
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1349
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3159
telemt_me_reconnect_success_total 2017
telemt_me_reader_eof_total 2092
telemt_me_idle_close_by_peer_total 2091
telemt_me_route_drop_no_conn_total 1358057
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1401287
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4331
telemt_desync_full_logged_total 1344
telemt_desync_suppressed_total 2987
telemt_desync_frames_bucket_total{bucket="1_2"} 888
telemt_desync_frames_bucket_total{bucket="3_10"} 1758
telemt_desync_frames_bucket_total{bucket="gt_10"} 1685
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2063
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 2016
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 1400263
telemt_user_connections_current{user="hello"} 4405
telemt_user_octets_from_client{user="hello"} 34913087948 (32.52 GB)
telemt_user_octets_to_client{user="hello"} 421341381620 (392.40 GB)
telemt_user_unique_ips_current{user="hello"} 1293
telemt_user_unique_ips_recent_window{user="hello"} 598
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 16390.2 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1164607
telemt_connections_bad_total 87003
telemt_handshake_timeouts_total 27323
telemt_upstream_connect_attempt_total 11434
telemt_upstream_connect_success_total 11434
telemt_upstream_connect_attempts_per_request{bucket="1"} 11434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2817
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 609052
telemt_me_reconnect_success_total 2328
telemt_me_reader_eof_total 2388
telemt_me_idle_close_by_peer_total 2387
telemt_me_route_drop_no_conn_total 504394
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 896871
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2814
telemt_desync_full_logged_total 938
telemt_desync_suppressed_total 1876
telemt_desync_frames_bucket_total{bucket="1_2"} 800
telemt_desync_frames_bucket_total{bucket="3_10"} 1020
telemt_desync_frames_bucket_total{bucket="gt_10"} 994
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2374
telemt_me_refill_failed_total 19704
telemt_me_writer_restored_same_endpoint_total 2293
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 904366
telemt_user_connections_current{user="hello"} 3203
telemt_user_octets_from_client{user="hello"} 11661213627 (10.86 GB)
telemt_user_octets_to_client{user="hello"} 382777417624 (356.49 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 987
telemt_user_unique_ips_recent_window{user="hello"} 460
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 16420.1 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1931697
telemt_connections_bad_total 30230
telemt_handshake_timeouts_total 172371
telemt_upstream_connect_attempt_total 12551
telemt_upstream_connect_success_total 12348
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 12551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1330
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2832370
telemt_me_reconnect_success_total 1180
telemt_me_reader_eof_total 1798
telemt_me_idle_close_by_peer_total 1798
telemt_me_route_drop_no_conn_total 2942020
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1577590
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3334
telemt_desync_full_logged_total 1009
telemt_desync_suppressed_total 2325
telemt_desync_frames_bucket_total{bucket="1_2"} 857
telemt_desync_frames_bucket_total{bucket="3_10"} 1406
telemt_desync_frames_bucket_total{bucket="gt_10"} 1071
telemt_me_writer_removed_unexpected_total 1847
telemt_me_refill_failed_total 100212
telemt_me_writer_restored_same_endpoint_total 1085
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 667
telemt_user_connections_total{user="hello"} 1596123
telemt_user_connections_current{user="hello"} 3225
telemt_user_octets_from_client{user="hello"} 28875716422 (26.89 GB)
telemt_user_octets_to_client{user="hello"} 235399699157 (219.23 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 865
telemt_user_unique_ips_recent_window{user="hello"} 502
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 16315.0 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1280699
telemt_connections_bad_total 77902
telemt_handshake_timeouts_total 21554
telemt_upstream_connect_attempt_total 12356
telemt_upstream_connect_success_total 12355
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1588
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2986402
telemt_me_reconnect_success_total 1970
telemt_me_reader_eof_total 2050
telemt_me_idle_close_by_peer_total 2050
telemt_me_route_drop_no_conn_total 1213932
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1076950
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3300
telemt_desync_full_logged_total 1110
telemt_desync_suppressed_total 2190
telemt_desync_frames_bucket_total{bucket="1_2"} 488
telemt_desync_frames_bucket_total{bucket="3_10"} 1291
telemt_desync_frames_bucket_total{bucket="gt_10"} 1521
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2028
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 1855
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 1077025
telemt_user_connections_current{user="hello"} 3046
telemt_user_octets_from_client{user="hello"} 16233371089 (15.12 GB)
telemt_user_octets_to_client{user="hello"} 388335330397 (361.67 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1009
telemt_user_unique_ips_recent_window{user="hello"} 490
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 16200.1 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355586
telemt_connections_bad_total 33132
telemt_handshake_timeouts_total 2615
telemt_upstream_connect_attempt_total 2963
telemt_upstream_connect_success_total 2963
telemt_upstream_connect_attempts_per_request{bucket="1"} 2963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1598
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 8541
telemt_me_reconnect_success_total 2089
telemt_me_reader_eof_total 2325
telemt_me_idle_close_by_peer_total 2324
telemt_me_route_drop_no_conn_total 206266
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 304328
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 791
telemt_desync_full_logged_total 279
telemt_desync_suppressed_total 512
telemt_desync_frames_bucket_total{bucket="1_2"} 157
telemt_desync_frames_bucket_total{bucket="3_10"} 295
telemt_desync_frames_bucket_total{bucket="gt_10"} 339
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2308
telemt_me_refill_failed_total 200
telemt_me_writer_restored_same_endpoint_total 2080
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 219
telemt_user_connections_total{user="hello"} 294606
telemt_user_connections_current{user="hello"} 980
telemt_user_octets_from_client{user="hello"} 4679416324 (4.36 GB)
telemt_user_octets_to_client{user="hello"} 59917677284 (55.80 GB)
telemt_user_unique_ips_current{user="hello"} 327
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 16271.1 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1036138
telemt_connections_bad_total 117680
telemt_handshake_timeouts_total 21169
telemt_upstream_connect_attempt_total 2956
telemt_upstream_connect_success_total 2929
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 2956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1293
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 2087
telemt_me_reconnect_success_total 2041
telemt_me_reader_eof_total 2095
telemt_me_idle_close_by_peer_total 2095
telemt_me_route_drop_no_conn_total 609003
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 817887
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2807
telemt_desync_full_logged_total 938
telemt_desync_suppressed_total 1869
telemt_desync_frames_bucket_total{bucket="1_2"} 515
telemt_desync_frames_bucket_total{bucket="3_10"} 959
telemt_desync_frames_bucket_total{bucket="gt_10"} 1333
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2059
telemt_me_writer_restored_same_endpoint_total 2031
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 817335
telemt_user_connections_current{user="hello"} 2795
telemt_user_octets_from_client{user="hello"} 16321121384 (15.20 GB)
telemt_user_octets_to_client{user="hello"} 375043167236 (349.29 GB)
telemt_user_unique_ips_current{user="hello"} 859
telemt_user_unique_ips_recent_window{user="hello"} 427
```