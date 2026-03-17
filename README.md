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

# Server Metrics 2026-03-17 14:49:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 72259.0 (20h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 776830
telemt_connections_bad_total 5835
telemt_handshake_timeouts_total 23145
telemt_upstream_connect_attempt_total 17445
telemt_upstream_connect_success_total 16985
telemt_upstream_connect_fail_total 460
telemt_upstream_connect_attempts_per_request{bucket="1"} 17445
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7920
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 460
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 24376
telemt_me_reconnect_success_total 11051
telemt_me_reader_eof_total 12019
telemt_me_idle_close_by_peer_total 12018
telemt_me_route_drop_no_conn_total 309972
telemt_me_route_drop_channel_closed_total 78
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 704302
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4925
telemt_desync_full_logged_total 1371
telemt_desync_suppressed_total 3554
telemt_desync_frames_bucket_total{bucket="1_2"} 1417
telemt_desync_frames_bucket_total{bucket="3_10"} 1971
telemt_desync_frames_bucket_total{bucket="gt_10"} 1537
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11620
telemt_me_refill_failed_total 411
telemt_me_writer_restored_same_endpoint_total 11029
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 569
telemt_user_connections_total{user="hello"} 706163
telemt_user_connections_current{user="hello"} 988
telemt_user_octets_from_client{user="hello"} 11714101911 (10.91 GB)
telemt_user_octets_to_client{user="hello"} 235312393727 (219.15 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 72510.4 (20h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 496111
telemt_connections_bad_total 31641
telemt_handshake_timeouts_total 25082
telemt_upstream_connect_attempt_total 68750
telemt_upstream_connect_success_total 68246
telemt_upstream_connect_fail_total 497
telemt_upstream_connect_attempts_per_request{bucket="1"} 68743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11539
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5098
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 497
telemt_me_keepalive_timeout_total 326
telemt_me_reconnect_attempts_total 35907
telemt_me_reconnect_success_total 13405
telemt_me_reader_eof_total 14666
telemt_me_idle_close_by_peer_total 14666
telemt_me_route_drop_no_conn_total 190696
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 364579
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1467
telemt_desync_full_logged_total 461
telemt_desync_suppressed_total 1006
telemt_desync_frames_bucket_total{bucket="1_2"} 329
telemt_desync_frames_bucket_total{bucket="3_10"} 644
telemt_desync_frames_bucket_total{bucket="gt_10"} 494
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14271
telemt_me_refill_failed_total 699
telemt_me_writer_restored_same_endpoint_total 13389
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 866
telemt_user_connections_total{user="hello"} 415684
telemt_user_connections_current{user="hello"} 745
telemt_user_octets_from_client{user="hello"} 4537230730 (4.23 GB)
telemt_user_octets_to_client{user="hello"} 124907356707 (116.33 GB)
telemt_user_msgs_from_client{user="hello"} 725842
telemt_user_msgs_to_client{user="hello"} 2354696
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 72286.4 (20h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257814
telemt_connections_bad_total 7828
telemt_handshake_timeouts_total 17143
telemt_upstream_connect_attempt_total 19042
telemt_upstream_connect_success_total 18945
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 19042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10362
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 26330
telemt_me_reconnect_success_total 15263
telemt_me_reader_eof_total 16474
telemt_me_idle_close_by_peer_total 16471
telemt_me_route_drop_no_conn_total 118158
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 219436
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 790
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 563
telemt_desync_frames_bucket_total{bucket="1_2"} 288
telemt_desync_frames_bucket_total{bucket="3_10"} 356
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 15816
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 15252
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 553
telemt_user_connections_total{user="hello"} 219302
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 17681552452 (16.47 GB)
telemt_user_octets_to_client{user="hello"} 54763789152 (51.00 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 72345.7 (20h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 594784
telemt_connections_bad_total 8428
telemt_handshake_timeouts_total 13328
telemt_upstream_connect_attempt_total 16737
telemt_upstream_connect_success_total 16579
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 16737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8143
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 25328
telemt_me_reconnect_success_total 11889
telemt_me_reader_eof_total 12960
telemt_me_idle_close_by_peer_total 12959
telemt_me_route_drop_no_conn_total 221210
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 510575
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1757
telemt_desync_full_logged_total 599
telemt_desync_suppressed_total 1158
telemt_desync_frames_bucket_total{bucket="1_2"} 444
telemt_desync_frames_bucket_total{bucket="3_10"} 781
telemt_desync_frames_bucket_total{bucket="gt_10"} 532
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12516
telemt_me_refill_failed_total 415
telemt_me_writer_restored_same_endpoint_total 11880
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 627
telemt_user_connections_total{user="hello"} 511402
telemt_user_connections_current{user="hello"} 759
telemt_user_octets_from_client{user="hello"} 6376088570 (5.94 GB)
telemt_user_octets_to_client{user="hello"} 163613085115 (152.38 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 72317.7 (20h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 282684
telemt_connections_bad_total 57093
telemt_handshake_timeouts_total 3608
telemt_upstream_connect_attempt_total 21090
telemt_upstream_connect_success_total 20620
telemt_upstream_connect_fail_total 470
telemt_upstream_connect_attempts_per_request{bucket="1"} 21090
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11050
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 287
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 470
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 39732
telemt_me_reconnect_success_total 16574
telemt_me_reader_eof_total 17887
telemt_me_idle_close_by_peer_total 17885
telemt_me_route_drop_no_conn_total 79468
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 210088
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1120
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 882
telemt_desync_frames_bucket_total{bucket="1_2"} 560
telemt_desync_frames_bucket_total{bucket="3_10"} 431
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 17575
telemt_me_refill_failed_total 719
telemt_me_writer_restored_same_endpoint_total 16566
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1001
telemt_user_connections_total{user="hello"} 210585
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 2661001639 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 75322610747 (70.15 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 72479.4 (20h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 680447
telemt_connections_bad_total 54133
telemt_handshake_timeouts_total 6755
telemt_upstream_connect_attempt_total 14522
telemt_upstream_connect_success_total 14442
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 14522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7302
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 21087
telemt_me_reconnect_success_total 10798
telemt_me_reader_eof_total 11765
telemt_me_idle_close_by_peer_total 11765
telemt_me_route_drop_no_conn_total 483244
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 684857
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 949
telemt_desync_full_logged_total 351
telemt_desync_suppressed_total 598
telemt_desync_frames_bucket_total{bucket="1_2"} 235
telemt_desync_frames_bucket_total{bucket="3_10"} 377
telemt_desync_frames_bucket_total{bucket="gt_10"} 337
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 11285
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 10784
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 487
telemt_user_connections_total{user="hello"} 584873
telemt_user_connections_current{user="hello"} 928
telemt_user_octets_from_client{user="hello"} 8646763456 (8.05 GB)
telemt_user_octets_to_client{user="hello"} 261531481884 (243.57 GB)
telemt_user_unique_ips_current{user="hello"} 326
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 20245.8 (5h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16081
telemt_connections_bad_total 69
telemt_handshake_timeouts_total 308
telemt_upstream_connect_attempt_total 11082
telemt_upstream_connect_success_total 10995
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 11082
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4945
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 21345
telemt_me_reconnect_success_total 9794
telemt_me_reader_eof_total 10388
telemt_me_idle_close_by_peer_total 10388
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 5895
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15299
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 10253
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 9779
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 459
telemt_user_connections_total{user="hello"} 15397
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 462295405 (440.88 MB)
telemt_user_octets_to_client{user="hello"} 23158190842 (21.57 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 6
```