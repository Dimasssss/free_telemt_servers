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

# Server Metrics 2026-03-18 10:11:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 5438.3 (1h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208366
telemt_connections_bad_total 1495
telemt_handshake_timeouts_total 4241
telemt_upstream_connect_attempt_total 64033
telemt_upstream_connect_success_total 63112
telemt_upstream_connect_fail_total 921
telemt_upstream_connect_attempts_per_request{bucket="1"} 64033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59488
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3041
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 921
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 507506
telemt_me_reconnect_success_total 866
telemt_me_reader_eof_total 812
telemt_me_idle_close_by_peer_total 810
telemt_me_route_drop_no_conn_total 69994
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119355
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 601
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 411
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 204
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 853
telemt_me_refill_failed_total 16516
telemt_me_writer_restored_same_endpoint_total 761
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_user_connections_total{user="hello"} 181223
telemt_user_connections_current{user="hello"} 1693
telemt_user_octets_from_client{user="hello"} 2162240980 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 42043103345 (39.16 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 505
telemt_user_unique_ips_recent_window{user="hello"} 262
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 5470.2 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 488561
telemt_connections_bad_total 57704
telemt_handshake_timeouts_total 11937
telemt_upstream_connect_attempt_total 928
telemt_upstream_connect_success_total 927
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 379
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 610
telemt_me_reconnect_success_total 597
telemt_me_reader_eof_total 569
telemt_me_idle_close_by_peer_total 569
telemt_me_route_drop_no_conn_total 207676
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 391053
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1929
telemt_desync_full_logged_total 526
telemt_desync_suppressed_total 1403
telemt_desync_frames_bucket_total{bucket="1_2"} 378
telemt_desync_frames_bucket_total{bucket="3_10"} 752
telemt_desync_frames_bucket_total{bucket="gt_10"} 799
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 579
telemt_me_writer_restored_same_endpoint_total 596
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 390193
telemt_user_connections_current{user="hello"} 3667
telemt_user_octets_from_client{user="hello"} 8674341728 (8.08 GB)
telemt_user_octets_to_client{user="hello"} 144672894904 (134.74 GB)
telemt_user_unique_ips_current{user="hello"} 1133
telemt_user_unique_ips_recent_window{user="hello"} 546
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 5385.0 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 384059
telemt_connections_bad_total 22038
telemt_handshake_timeouts_total 9676
telemt_upstream_connect_attempt_total 9324
telemt_upstream_connect_success_total 9324
telemt_upstream_connect_attempts_per_request{bucket="1"} 9324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1752
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 606496
telemt_me_reconnect_success_total 824
telemt_me_reader_eof_total 792
telemt_me_idle_close_by_peer_total 791
telemt_me_route_drop_no_conn_total 187007
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 283734
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 672
telemt_desync_full_logged_total 232
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 151
telemt_desync_frames_bucket_total{bucket="3_10"} 291
telemt_desync_frames_bucket_total{bucket="gt_10"} 230
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 819
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 789
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 291734
telemt_user_connections_current{user="hello"} 2606
telemt_user_octets_from_client{user="hello"} 2908063975 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 109327627136 (101.82 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 745
telemt_user_unique_ips_recent_window{user="hello"} 378
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 5415.3 (1h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 736512
telemt_connections_bad_total 8340
telemt_handshake_timeouts_total 82373
telemt_upstream_connect_attempt_total 11630
telemt_upstream_connect_success_total 11521
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 11630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1069
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2814648
telemt_me_reconnect_success_total 947
telemt_me_reader_eof_total 1035
telemt_me_idle_close_by_peer_total 1035
telemt_me_route_drop_no_conn_total 1378969
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 574422
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 804
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 562
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 327
telemt_desync_frames_bucket_total{bucket="gt_10"} 279
telemt_me_writer_removed_unexpected_total 1062
telemt_me_refill_failed_total 99666
telemt_me_writer_restored_same_endpoint_total 852
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 593373
telemt_user_connections_current{user="hello"} 2722
telemt_user_octets_from_client{user="hello"} 4166613578 (3.88 GB)
telemt_user_octets_to_client{user="hello"} 72099149621 (67.15 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 800
telemt_user_unique_ips_recent_window{user="hello"} 406
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 5310.2 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 374522
telemt_connections_bad_total 10673
telemt_handshake_timeouts_total 5912
telemt_upstream_connect_attempt_total 10581
telemt_upstream_connect_success_total 10580
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10581
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 837
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2982735
telemt_me_reconnect_success_total 785
telemt_me_reader_eof_total 730
telemt_me_idle_close_by_peer_total 730
telemt_me_route_drop_no_conn_total 165080
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 307241
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1008
telemt_desync_full_logged_total 352
telemt_desync_suppressed_total 656
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 381
telemt_desync_frames_bucket_total{bucket="gt_10"} 465
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 738
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 670
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 315657
telemt_user_connections_current{user="hello"} 3228
telemt_user_octets_from_client{user="hello"} 5431154805 (5.06 GB)
telemt_user_octets_to_client{user="hello"} 123013199133 (114.56 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 963
telemt_user_unique_ips_recent_window{user="hello"} 469
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 5194.7 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110263
telemt_connections_bad_total 13784
telemt_handshake_timeouts_total 633
telemt_upstream_connect_attempt_total 952
telemt_upstream_connect_success_total 952
telemt_upstream_connect_attempts_per_request{bucket="1"} 952
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 435
telemt_me_reconnect_attempts_total 653
telemt_me_reconnect_success_total 646
telemt_me_reader_eof_total 632
telemt_me_idle_close_by_peer_total 632
telemt_me_route_drop_no_conn_total 49832
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89066
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 194
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 119
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 78
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 641
telemt_me_writer_restored_same_endpoint_total 638
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_user_connections_total{user="hello"} 86668
telemt_user_connections_current{user="hello"} 837
telemt_user_octets_from_client{user="hello"} 1471130380 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 18508973200 (17.24 GB)
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 5266.0 (1h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274925
telemt_connections_bad_total 19131
telemt_handshake_timeouts_total 4956
telemt_upstream_connect_attempt_total 992
telemt_upstream_connect_success_total 974
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 399
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 680
telemt_me_reconnect_success_total 668
telemt_me_reader_eof_total 643
telemt_me_idle_close_by_peer_total 643
telemt_me_route_drop_no_conn_total 155298
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231627
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 810
telemt_desync_full_logged_total 277
telemt_desync_suppressed_total 533
telemt_desync_frames_bucket_total{bucket="1_2"} 155
telemt_desync_frames_bucket_total{bucket="3_10"} 307
telemt_desync_frames_bucket_total{bucket="gt_10"} 348
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 660
telemt_me_writer_restored_same_endpoint_total 658
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 231460
telemt_user_connections_current{user="hello"} 2325
telemt_user_octets_from_client{user="hello"} 3406036880 (3.17 GB)
telemt_user_octets_to_client{user="hello"} 111436048412 (103.78 GB)
telemt_user_unique_ips_current{user="hello"} 694
telemt_user_unique_ips_recent_window{user="hello"} 373
```