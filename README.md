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

# Server Metrics 2026-03-19 03:45:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 21416.5 (5h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274764
telemt_connections_bad_total 31481
telemt_connections_current 770
telemt_connections_me_current 770
telemt_handshake_timeouts_total 18023
telemt_upstream_connect_attempt_total 4217
telemt_upstream_connect_success_total 4152
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 4217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3099
telemt_me_reconnect_success_total 3084
telemt_me_reader_eof_total 3235
telemt_me_idle_close_by_peer_total 3235
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 72141
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 207970
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1488
telemt_desync_full_logged_total 400
telemt_desync_suppressed_total 1088
telemt_desync_frames_bucket_total{bucket="1_2"} 552
telemt_desync_frames_bucket_total{bucket="3_10"} 618
telemt_desync_frames_bucket_total{bucket="gt_10"} 318
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3103
telemt_me_writer_restored_same_endpoint_total 3067
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 205195
telemt_user_connections_current{user="hello"} 770
telemt_user_octets_from_client{user="hello"} 2215026304 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 61573361444 (57.34 GB)
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 21420.2 (5h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 503909
telemt_connections_bad_total 38287
telemt_connections_current 2190
telemt_connections_me_current 2190
telemt_handshake_timeouts_total 13778
telemt_upstream_connect_attempt_total 4056
telemt_upstream_connect_success_total 3985
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 4056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2091
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_reconnect_attempts_total 2921
telemt_me_reconnect_success_total 2907
telemt_me_reader_eof_total 3063
telemt_me_idle_close_by_peer_total 3063
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 148920
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 414115
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1559
telemt_desync_full_logged_total 534
telemt_desync_suppressed_total 1025
telemt_desync_frames_bucket_total{bucket="1_2"} 342
telemt_desync_frames_bucket_total{bucket="3_10"} 584
telemt_desync_frames_bucket_total{bucket="gt_10"} 633
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2951
telemt_me_writer_restored_same_endpoint_total 2890
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 414084
telemt_user_connections_current{user="hello"} 2190
telemt_user_octets_from_client{user="hello"} 12861249664 (11.98 GB)
telemt_user_octets_to_client{user="hello"} 173867835640 (161.93 GB)
telemt_user_unique_ips_current{user="hello"} 793
telemt_user_unique_ips_recent_window{user="hello"} 248
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 21417.4 (5h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 410388
telemt_connections_bad_total 87353
telemt_connections_current 1609
telemt_connections_me_current 1609
telemt_handshake_timeouts_total 10134
telemt_upstream_connect_attempt_total 4019
telemt_upstream_connect_success_total 4019
telemt_upstream_connect_attempts_per_request{bucket="1"} 4019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1992
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 2956
telemt_me_reconnect_success_total 2946
telemt_me_reader_eof_total 3116
telemt_me_idle_close_by_peer_total 3116
telemt_me_route_drop_no_conn_total 120690
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 300045
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1443
telemt_desync_full_logged_total 546
telemt_desync_suppressed_total 897
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 590
telemt_desync_frames_bucket_total{bucket="gt_10"} 601
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 2993
telemt_me_writer_restored_same_endpoint_total 2930
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 300042
telemt_user_connections_current{user="hello"} 1609
telemt_user_octets_from_client{user="hello"} 6289640320 (5.86 GB)
telemt_user_octets_to_client{user="hello"} 186530136724 (173.72 GB)
telemt_user_unique_ips_current{user="hello"} 636
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 21470.7 (5h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 496592
telemt_connections_bad_total 56759
telemt_connections_current 1473
telemt_connections_me_current 1473
telemt_handshake_timeouts_total 9748
telemt_upstream_connect_attempt_total 3895
telemt_upstream_connect_success_total 3895
telemt_upstream_connect_attempts_per_request{bucket="1"} 3895
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1920
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2835
telemt_me_reconnect_success_total 2824
telemt_me_reader_eof_total 2974
telemt_me_idle_close_by_peer_total 2973
telemt_me_route_drop_no_conn_total 125119
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 300237
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 834
telemt_desync_full_logged_total 300
telemt_desync_suppressed_total 534
telemt_desync_frames_bucket_total{bucket="1_2"} 179
telemt_desync_frames_bucket_total{bucket="3_10"} 363
telemt_desync_frames_bucket_total{bucket="gt_10"} 292
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 2856
telemt_me_writer_restored_same_endpoint_total 2800
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 299969
telemt_user_connections_current{user="hello"} 1473
telemt_user_octets_from_client{user="hello"} 3397694524 (3.16 GB)
telemt_user_octets_to_client{user="hello"} 108633269296 (101.17 GB)
telemt_user_unique_ips_current{user="hello"} 561
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 21413.9 (5h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 485314
telemt_connections_bad_total 79912
telemt_connections_current 1579
telemt_connections_me_current 1579
telemt_handshake_timeouts_total 16284
telemt_upstream_connect_attempt_total 4035
telemt_upstream_connect_success_total 4009
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 4035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2005
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 2949
telemt_me_reconnect_success_total 2931
telemt_me_reader_eof_total 3093
telemt_me_idle_close_by_peer_total 3093
telemt_me_route_drop_no_conn_total 138848
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 327861
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1457
telemt_desync_full_logged_total 561
telemt_desync_suppressed_total 896
telemt_desync_frames_bucket_total{bucket="1_2"} 372
telemt_desync_frames_bucket_total{bucket="3_10"} 584
telemt_desync_frames_bucket_total{bucket="gt_10"} 501
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 2956
telemt_me_writer_restored_same_endpoint_total 2907
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 327781
telemt_user_connections_current{user="hello"} 1579
telemt_user_octets_from_client{user="hello"} 10568742080 (9.84 GB)
telemt_user_octets_to_client{user="hello"} 189528143588 (176.51 GB)
telemt_user_unique_ips_current{user="hello"} 664
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 21425.6 (5h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101864
telemt_connections_bad_total 10101
telemt_connections_current 374
telemt_connections_me_current 374
telemt_handshake_timeouts_total 454
telemt_upstream_connect_attempt_total 5983
telemt_upstream_connect_success_total 5817
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 5983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3055
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_reconnect_attempts_total 6585
telemt_me_reconnect_success_total 4747
telemt_me_reader_eof_total 4991
telemt_me_idle_close_by_peer_total 4991
telemt_me_route_drop_no_conn_total 42399
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87919
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 42
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 4813
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 4717
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 87911
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 1687497772 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 58258125820 (54.26 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 21416.5 (5h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 308301
telemt_connections_bad_total 30307
telemt_connections_current 1530
telemt_connections_me_current 1530
telemt_handshake_timeouts_total 16524
telemt_upstream_connect_attempt_total 4520
telemt_upstream_connect_success_total 4520
telemt_upstream_connect_attempts_per_request{bucket="1"} 4520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3459
telemt_me_reconnect_success_total 3450
telemt_me_reader_eof_total 3635
telemt_me_idle_close_by_peer_total 3635
telemt_me_route_drop_no_conn_total 87577
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 253602
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1276
telemt_desync_full_logged_total 488
telemt_desync_suppressed_total 788
telemt_desync_frames_bucket_total{bucket="1_2"} 238
telemt_desync_frames_bucket_total{bucket="3_10"} 504
telemt_desync_frames_bucket_total{bucket="gt_10"} 534
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3488
telemt_me_writer_restored_same_endpoint_total 3435
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 253624
telemt_user_connections_current{user="hello"} 1530
telemt_user_octets_from_client{user="hello"} 2721582412 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 138719131640 (129.19 GB)
telemt_user_unique_ips_current{user="hello"} 571
telemt_user_unique_ips_recent_window{user="hello"} 166
```