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

# Server Metrics 2026-03-17 20:00:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 90931.3 (25h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1127554
telemt_connections_bad_total 7990
telemt_handshake_timeouts_total 30239
telemt_upstream_connect_attempt_total 20894
telemt_upstream_connect_success_total 20406
telemt_upstream_connect_fail_total 488
telemt_upstream_connect_attempts_per_request{bucket="1"} 20894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9609
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 205
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 488
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 30692
telemt_me_reconnect_success_total 13564
telemt_me_reader_eof_total 14749
telemt_me_idle_close_by_peer_total 14748
telemt_me_route_drop_no_conn_total 505762
telemt_me_route_drop_channel_closed_total 152
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1032932
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6841
telemt_desync_full_logged_total 1954
telemt_desync_suppressed_total 4887
telemt_desync_frames_bucket_total{bucket="1_2"} 1842
telemt_desync_frames_bucket_total{bucket="3_10"} 2592
telemt_desync_frames_bucket_total{bucket="gt_10"} 2407
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 14298
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13542
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 734
telemt_user_connections_total{user="hello"} 1027170
telemt_user_connections_current{user="hello"} 831
telemt_user_octets_from_client{user="hello"} 15527917883 (14.46 GB)
telemt_user_octets_to_client{user="hello"} 358719213443 (334.08 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 91182.8 (25h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1127611
telemt_connections_bad_total 58609
telemt_handshake_timeouts_total 40172
telemt_upstream_connect_attempt_total 456512
telemt_upstream_connect_success_total 455636
telemt_upstream_connect_fail_total 876
telemt_upstream_connect_attempts_per_request{bucket="1"} 456512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30015
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43289
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 876
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57208
telemt_me_reconnect_success_total 14057
telemt_me_reader_eof_total 15990
telemt_me_idle_close_by_peer_total 15990
telemt_me_route_drop_no_conn_total 280254
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 531482
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2221
telemt_desync_full_logged_total 718
telemt_desync_suppressed_total 1503
telemt_desync_frames_bucket_total{bucket="1_2"} 451
telemt_desync_frames_bucket_total{bucket="3_10"} 939
telemt_desync_frames_bucket_total{bucket="gt_10"} 831
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 15578
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14041
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1521
telemt_user_connections_total{user="hello"} 967918
telemt_user_connections_current{user="hello"} 1595
telemt_user_octets_from_client{user="hello"} 13466136254 (12.54 GB)
telemt_user_octets_to_client{user="hello"} 304453908730 (283.54 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 437
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 90958.7 (25h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 606312
telemt_connections_bad_total 28419
telemt_handshake_timeouts_total 22047
telemt_upstream_connect_attempt_total 22098
telemt_upstream_connect_success_total 21969
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 22098
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11854
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38039
telemt_me_reconnect_success_total 17367
telemt_me_reader_eof_total 18966
telemt_me_idle_close_by_peer_total 18959
telemt_me_route_drop_no_conn_total 266800
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 526887
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1555
telemt_desync_full_logged_total 463
telemt_desync_suppressed_total 1092
telemt_desync_frames_bucket_total{bucket="1_2"} 446
telemt_desync_frames_bucket_total{bucket="3_10"} 617
telemt_desync_frames_bucket_total{bucket="gt_10"} 492
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 18250
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17355
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 883
telemt_user_connections_total{user="hello"} 525173
telemt_user_connections_current{user="hello"} 1121
telemt_user_octets_from_client{user="hello"} 27856890248 (25.94 GB)
telemt_user_octets_to_client{user="hello"} 210537815212 (196.08 GB)
telemt_user_unique_ips_current{user="hello"} 310
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 91018.2 (25h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1105467
telemt_connections_bad_total 29139
telemt_handshake_timeouts_total 20663
telemt_upstream_connect_attempt_total 81696
telemt_upstream_connect_success_total 81289
telemt_upstream_connect_fail_total 407
telemt_upstream_connect_attempts_per_request{bucket="1"} 81696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11539
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 407
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33644
telemt_me_reconnect_success_total 13337
telemt_me_reader_eof_total 14711
telemt_me_idle_close_by_peer_total 14710
telemt_me_route_drop_no_conn_total 456995
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 898624
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3032
telemt_desync_full_logged_total 969
telemt_desync_suppressed_total 2063
telemt_desync_frames_bucket_total{bucket="1_2"} 734
telemt_desync_frames_bucket_total{bucket="3_10"} 1311
telemt_desync_frames_bucket_total{bucket="gt_10"} 987
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 14219
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13328
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 882
telemt_user_connections_total{user="hello"} 961682
telemt_user_connections_current{user="hello"} 1428
telemt_user_octets_from_client{user="hello"} 13769478171 (12.82 GB)
telemt_user_octets_to_client{user="hello"} 377282644269 (351.37 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 387
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 90990.0 (25h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 658650
telemt_connections_bad_total 78600
telemt_handshake_timeouts_total 5567
telemt_upstream_connect_attempt_total 40358
telemt_upstream_connect_success_total 39822
telemt_upstream_connect_fail_total 536
telemt_upstream_connect_attempts_per_request{bucket="1"} 40358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13633
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 385
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 536
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 51241
telemt_me_reconnect_success_total 18757
telemt_me_reader_eof_total 20449
telemt_me_idle_close_by_peer_total 20447
telemt_me_route_drop_no_conn_total 205713
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 521733
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2356
telemt_desync_full_logged_total 656
telemt_desync_suppressed_total 1700
telemt_desync_frames_bucket_total{bucket="1_2"} 824
telemt_desync_frames_bucket_total{bucket="3_10"} 936
telemt_desync_frames_bucket_total{bucket="gt_10"} 596
telemt_pool_swap_total 45
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20092
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18749
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1335
telemt_user_connections_total{user="hello"} 538379
telemt_user_connections_current{user="hello"} 1229
telemt_user_octets_from_client{user="hello"} 10826102176 (10.08 GB)
telemt_user_octets_to_client{user="hello"} 249751132020 (232.60 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 91151.6 (25h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 934344
telemt_connections_bad_total 62033
telemt_handshake_timeouts_total 9029
telemt_upstream_connect_attempt_total 18094
telemt_upstream_connect_success_total 17991
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 18094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8554
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9321
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 24685
telemt_me_reconnect_success_total 13410
telemt_me_reader_eof_total 14577
telemt_me_idle_close_by_peer_total 14575
telemt_me_route_drop_no_conn_total 665930
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 946668
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1876
telemt_desync_full_logged_total 653
telemt_desync_suppressed_total 1223
telemt_desync_frames_bucket_total{bucket="1_2"} 442
telemt_desync_frames_bucket_total{bucket="3_10"} 720
telemt_desync_frames_bucket_total{bucket="gt_10"} 714
telemt_pool_swap_total 76
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13987
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13396
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 577
telemt_user_connections_total{user="hello"} 809704
telemt_user_connections_current{user="hello"} 795
telemt_user_octets_from_client{user="hello"} 12502514452 (11.64 GB)
telemt_user_octets_to_client{user="hello"} 351040445952 (326.93 GB)
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 38918.3 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 264299
telemt_connections_bad_total 35315
telemt_handshake_timeouts_total 6603
telemt_upstream_connect_attempt_total 16622
telemt_upstream_connect_success_total 16469
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 16622
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 25917
telemt_me_reconnect_success_total 14328
telemt_me_reader_eof_total 15141
telemt_me_idle_close_by_peer_total 15141
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 64122
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 203197
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 620
telemt_desync_full_logged_total 165
telemt_desync_suppressed_total 455
telemt_desync_frames_bucket_total{bucket="1_2"} 170
telemt_desync_frames_bucket_total{bucket="3_10"} 236
telemt_desync_frames_bucket_total{bucket="gt_10"} 214
telemt_pool_swap_total 17
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14862
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 14301
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 534
telemt_user_connections_total{user="hello"} 203144
telemt_user_connections_current{user="hello"} 764
telemt_user_octets_from_client{user="hello"} 19754006201 (18.40 GB)
telemt_user_octets_to_client{user="hello"} 169788223322 (158.13 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 97
```