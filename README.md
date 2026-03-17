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

# Server Metrics 2026-03-17 18:18:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 84817.5 (23h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1031242
telemt_connections_bad_total 7242
telemt_handshake_timeouts_total 28106
telemt_upstream_connect_attempt_total 19862
telemt_upstream_connect_success_total 19381
telemt_upstream_connect_fail_total 481
telemt_upstream_connect_attempts_per_request{bucket="1"} 19862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9096
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 481
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 29935
telemt_me_reconnect_success_total 12816
telemt_me_reader_eof_total 13961
telemt_me_idle_close_by_peer_total 13960
telemt_me_route_drop_no_conn_total 470259
telemt_me_route_drop_channel_closed_total 135
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 944157
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6243
telemt_desync_full_logged_total 1777
telemt_desync_suppressed_total 4466
telemt_desync_frames_bucket_total{bucket="1_2"} 1718
telemt_desync_frames_bucket_total{bucket="3_10"} 2405
telemt_desync_frames_bucket_total{bucket="gt_10"} 2120
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 13534
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12794
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 718
telemt_user_connections_total{user="hello"} 938397
telemt_user_connections_current{user="hello"} 1036
telemt_user_octets_from_client{user="hello"} 14314179095 (13.33 GB)
telemt_user_octets_to_client{user="hello"} 327194396455 (304.72 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 355
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 85069.4 (23h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 954465
telemt_connections_bad_total 54457
telemt_handshake_timeouts_total 33262
telemt_upstream_connect_attempt_total 410960
telemt_upstream_connect_success_total 410123
telemt_upstream_connect_fail_total 832
telemt_upstream_connect_attempts_per_request{bucket="1"} 410955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 342134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27958
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40029
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 832
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 55338
telemt_me_reconnect_success_total 13565
telemt_me_reader_eof_total 15422
telemt_me_idle_close_by_peer_total 15422
telemt_me_route_drop_no_conn_total 240974
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 425802
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1580
telemt_desync_full_logged_total 504
telemt_desync_suppressed_total 1076
telemt_desync_frames_bucket_total{bucket="1_2"} 360
telemt_desync_frames_bucket_total{bucket="3_10"} 689
telemt_desync_frames_bucket_total{bucket="gt_10"} 531
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 15033
telemt_me_refill_failed_total 1301
telemt_me_writer_restored_same_endpoint_total 13549
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1468
telemt_user_connections_total{user="hello"} 817987
telemt_user_connections_current{user="hello"} 1684
telemt_user_octets_from_client{user="hello"} 10991376964 (10.24 GB)
telemt_user_octets_to_client{user="hello"} 216898653326 (202.00 GB)
telemt_user_msgs_from_client{user="hello"} 6647446
telemt_user_msgs_to_client{user="hello"} 27901792
telemt_user_unique_ips_current{user="hello"} 406
telemt_user_unique_ips_recent_window{user="hello"} 205
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 84845.4 (23h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 492556
telemt_connections_bad_total 18357
telemt_handshake_timeouts_total 21072
telemt_upstream_connect_attempt_total 21041
telemt_upstream_connect_success_total 20923
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 21041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11317
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 37271
telemt_me_reconnect_success_total 16603
telemt_me_reader_eof_total 18160
telemt_me_idle_close_by_peer_total 18153
telemt_me_route_drop_no_conn_total 227089
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 428833
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1206
telemt_desync_full_logged_total 362
telemt_desync_suppressed_total 844
telemt_desync_frames_bucket_total{bucket="1_2"} 388
telemt_desync_frames_bucket_total{bucket="3_10"} 510
telemt_desync_frames_bucket_total{bucket="gt_10"} 308
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 17473
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16591
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 870
telemt_user_connections_total{user="hello"} 427046
telemt_user_connections_current{user="hello"} 1155
telemt_user_octets_from_client{user="hello"} 26266552272 (24.46 GB)
telemt_user_octets_to_client{user="hello"} 156296725480 (145.56 GB)
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 84904.2 (23h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 973186
telemt_connections_bad_total 23617
telemt_handshake_timeouts_total 19011
telemt_upstream_connect_attempt_total 80765
telemt_upstream_connect_success_total 80364
telemt_upstream_connect_fail_total 401
telemt_upstream_connect_attempts_per_request{bucket="1"} 80765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11060
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 401
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33020
telemt_me_reconnect_success_total 12718
telemt_me_reader_eof_total 14044
telemt_me_idle_close_by_peer_total 14043
telemt_me_route_drop_no_conn_total 408341
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 781921
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2501
telemt_desync_full_logged_total 805
telemt_desync_suppressed_total 1696
telemt_desync_frames_bucket_total{bucket="1_2"} 606
telemt_desync_frames_bucket_total{bucket="3_10"} 1103
telemt_desync_frames_bucket_total{bucket="gt_10"} 792
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 13583
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12709
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 865
telemt_user_connections_total{user="hello"} 844996
telemt_user_connections_current{user="hello"} 1531
telemt_user_octets_from_client{user="hello"} 10579661571 (9.85 GB)
telemt_user_octets_to_client{user="hello"} 297522448649 (277.09 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 429
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 84876.1 (23h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 546628
telemt_connections_bad_total 75173
telemt_handshake_timeouts_total 4983
telemt_upstream_connect_attempt_total 39278
telemt_upstream_connect_success_total 38759
telemt_upstream_connect_fail_total 519
telemt_upstream_connect_attempts_per_request{bucket="1"} 39278
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13041
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 371
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 519
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50474
telemt_me_reconnect_success_total 17993
telemt_me_reader_eof_total 19626
telemt_me_idle_close_by_peer_total 19624
telemt_me_route_drop_no_conn_total 162409
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 418052
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1886
telemt_desync_full_logged_total 478
telemt_desync_suppressed_total 1408
telemt_desync_frames_bucket_total{bucket="1_2"} 725
telemt_desync_frames_bucket_total{bucket="3_10"} 737
telemt_desync_frames_bucket_total{bucket="gt_10"} 424
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19311
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 17985
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1318
telemt_user_connections_total{user="hello"} 434730
telemt_user_connections_current{user="hello"} 1451
telemt_user_octets_from_client{user="hello"} 7842637508 (7.30 GB)
telemt_user_octets_to_client{user="hello"} 198413920824 (184.79 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 427
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 85037.5 (23h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 868683
telemt_connections_bad_total 60855
telemt_handshake_timeouts_total 8390
telemt_upstream_connect_attempt_total 17025
telemt_upstream_connect_success_total 16930
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 17025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8764
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 128
telemt_me_reconnect_attempts_total 23928
telemt_me_reconnect_success_total 12657
telemt_me_reader_eof_total 13773
telemt_me_idle_close_by_peer_total 13771
telemt_me_route_drop_no_conn_total 637479
telemt_me_route_drop_channel_closed_total 81
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 888860
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1642
telemt_desync_full_logged_total 561
telemt_desync_suppressed_total 1081
telemt_desync_frames_bucket_total{bucket="1_2"} 405
telemt_desync_frames_bucket_total{bucket="3_10"} 635
telemt_desync_frames_bucket_total{bucket="gt_10"} 602
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13225
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12643
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 568
telemt_user_connections_total{user="hello"} 751916
telemt_user_connections_current{user="hello"} 787
telemt_user_octets_from_client{user="hello"} 11411573200 (10.63 GB)
telemt_user_octets_to_client{user="hello"} 327033767072 (304.57 GB)
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 32804.3 (9h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175528
telemt_connections_bad_total 19489
telemt_handshake_timeouts_total 5369
telemt_upstream_connect_attempt_total 14973
telemt_upstream_connect_success_total 14844
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 14973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6785
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 24594
telemt_me_reconnect_success_total 13015
telemt_me_reader_eof_total 13773
telemt_me_idle_close_by_peer_total 13773
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 42355
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139657
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 316
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 226
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 102
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 13529
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12991
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 514
telemt_user_connections_total{user="hello"} 139607
telemt_user_connections_current{user="hello"} 946
telemt_user_octets_from_client{user="hello"} 11426225461 (10.64 GB)
telemt_user_octets_to_client{user="hello"} 128702289158 (119.86 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 98
```