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

# Server Metrics 2026-03-17 18:08:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 84205.0 (23h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1021756
telemt_connections_bad_total 6679
telemt_handshake_timeouts_total 28054
telemt_upstream_connect_attempt_total 19764
telemt_upstream_connect_success_total 19283
telemt_upstream_connect_fail_total 481
telemt_upstream_connect_attempts_per_request{bucket="1"} 19764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9058
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 184
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 481
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 29880
telemt_me_reconnect_success_total 12761
telemt_me_reader_eof_total 13902
telemt_me_idle_close_by_peer_total 13901
telemt_me_route_drop_no_conn_total 466510
telemt_me_route_drop_channel_closed_total 131
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 935579
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6210
telemt_desync_full_logged_total 1761
telemt_desync_suppressed_total 4449
telemt_desync_frames_bucket_total{bucket="1_2"} 1705
telemt_desync_frames_bucket_total{bucket="3_10"} 2391
telemt_desync_frames_bucket_total{bucket="gt_10"} 2114
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 13479
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12739
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 718
telemt_user_connections_total{user="hello"} 929826
telemt_user_connections_current{user="hello"} 1146
telemt_user_octets_from_client{user="hello"} 14186091631 (13.21 GB)
telemt_user_octets_to_client{user="hello"} 322402029831 (300.26 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 372
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 84457.8 (23h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 926827
telemt_connections_bad_total 53454
telemt_handshake_timeouts_total 32734
telemt_upstream_connect_attempt_total 392797
telemt_upstream_connect_success_total 391979
telemt_upstream_connect_fail_total 812
telemt_upstream_connect_attempts_per_request{bucket="1"} 392791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 326838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27285
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37854
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 812
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 53962
telemt_me_reconnect_success_total 13565
telemt_me_reader_eof_total 15380
telemt_me_idle_close_by_peer_total 15380
telemt_me_route_drop_no_conn_total 239087
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 421672
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1575
telemt_desync_full_logged_total 501
telemt_desync_suppressed_total 1074
telemt_desync_frames_bucket_total{bucket="1_2"} 360
telemt_desync_frames_bucket_total{bucket="3_10"} 687
telemt_desync_frames_bucket_total{bucket="gt_10"} 528
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14990
telemt_me_refill_failed_total 1258
telemt_me_writer_restored_same_endpoint_total 13549
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1425
telemt_user_connections_total{user="hello"} 795757
telemt_user_connections_current{user="hello"} 1775
telemt_user_octets_from_client{user="hello"} 10766262545 (10.03 GB)
telemt_user_octets_to_client{user="hello"} 212539059548 (197.94 GB)
telemt_user_msgs_from_client{user="hello"} 6388626
telemt_user_msgs_to_client{user="hello"} 26825800
telemt_user_unique_ips_current{user="hello"} 433
telemt_user_unique_ips_recent_window{user="hello"} 284
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 84233.4 (23h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 480942
telemt_connections_bad_total 18138
telemt_handshake_timeouts_total 20978
telemt_upstream_connect_attempt_total 20933
telemt_upstream_connect_success_total 20815
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 20933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11268
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 37206
telemt_me_reconnect_success_total 16538
telemt_me_reader_eof_total 18088
telemt_me_idle_close_by_peer_total 18081
telemt_me_route_drop_no_conn_total 223019
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 418089
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1193
telemt_desync_full_logged_total 356
telemt_desync_suppressed_total 837
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 508
telemt_desync_frames_bucket_total{bucket="gt_10"} 301
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 17407
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16526
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 869
telemt_user_connections_total{user="hello"} 416300
telemt_user_connections_current{user="hello"} 1313
telemt_user_octets_from_client{user="hello"} 26116733720 (24.32 GB)
telemt_user_octets_to_client{user="hello"} 150591657184 (140.25 GB)
telemt_user_unique_ips_current{user="hello"} 370
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 84292.6 (23h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 958914
telemt_connections_bad_total 23560
telemt_handshake_timeouts_total 18632
telemt_upstream_connect_attempt_total 80661
telemt_upstream_connect_success_total 80262
telemt_upstream_connect_fail_total 399
telemt_upstream_connect_attempts_per_request{bucket="1"} 80661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11012
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 399
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 32961
telemt_me_reconnect_success_total 12659
telemt_me_reader_eof_total 13981
telemt_me_idle_close_by_peer_total 13980
telemt_me_route_drop_no_conn_total 403178
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 769514
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2462
telemt_desync_full_logged_total 791
telemt_desync_suppressed_total 1671
telemt_desync_frames_bucket_total{bucket="1_2"} 597
telemt_desync_frames_bucket_total{bucket="3_10"} 1095
telemt_desync_frames_bucket_total{bucket="gt_10"} 770
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 13524
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12650
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 865
telemt_user_connections_total{user="hello"} 832606
telemt_user_connections_current{user="hello"} 1661
telemt_user_octets_from_client{user="hello"} 10256829827 (9.55 GB)
telemt_user_octets_to_client{user="hello"} 287384420649 (267.65 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 446
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 84264.6 (23h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 533291
telemt_connections_bad_total 75061
telemt_handshake_timeouts_total 4882
telemt_upstream_connect_attempt_total 39105
telemt_upstream_connect_success_total 38594
telemt_upstream_connect_fail_total 511
telemt_upstream_connect_attempts_per_request{bucket="1"} 39105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12974
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 511
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50352
telemt_me_reconnect_success_total 17872
telemt_me_reader_eof_total 19502
telemt_me_idle_close_by_peer_total 19500
telemt_me_route_drop_no_conn_total 157371
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 405479
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1796
telemt_desync_full_logged_total 460
telemt_desync_suppressed_total 1336
telemt_desync_frames_bucket_total{bucket="1_2"} 710
telemt_desync_frames_bucket_total{bucket="3_10"} 707
telemt_desync_frames_bucket_total{bucket="gt_10"} 379
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19187
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 17864
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1315
telemt_user_connections_total{user="hello"} 422160
telemt_user_connections_current{user="hello"} 1585
telemt_user_octets_from_client{user="hello"} 7588666484 (7.07 GB)
telemt_user_octets_to_client{user="hello"} 192361385256 (179.15 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 453
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 84427.4 (23h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 861756
telemt_connections_bad_total 60840
telemt_handshake_timeouts_total 8291
telemt_upstream_connect_attempt_total 16898
telemt_upstream_connect_success_total 16804
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 16898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8696
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 23845
telemt_me_reconnect_success_total 12574
telemt_me_reader_eof_total 13682
telemt_me_idle_close_by_peer_total 13680
telemt_me_route_drop_no_conn_total 634400
telemt_me_route_drop_channel_closed_total 80
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 882816
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1620
telemt_desync_full_logged_total 555
telemt_desync_suppressed_total 1065
telemt_desync_frames_bucket_total{bucket="1_2"} 395
telemt_desync_frames_bucket_total{bucket="3_10"} 630
telemt_desync_frames_bucket_total{bucket="gt_10"} 595
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 13140
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12560
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 566
telemt_user_connections_total{user="hello"} 745873
telemt_user_connections_current{user="hello"} 854
telemt_user_octets_from_client{user="hello"} 11324248100 (10.55 GB)
telemt_user_octets_to_client{user="hello"} 325109077320 (302.78 GB)
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 32192.8 (8h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165539
telemt_connections_bad_total 18910
telemt_handshake_timeouts_total 5218
telemt_upstream_connect_attempt_total 14798
telemt_upstream_connect_success_total 14669
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 14798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 24462
telemt_me_reconnect_success_total 12883
telemt_me_reader_eof_total 13643
telemt_me_idle_close_by_peer_total 13643
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 39964
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131476
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 288
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 206
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 13398
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12860
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 515
telemt_user_connections_total{user="hello"} 131427
telemt_user_connections_current{user="hello"} 1030
telemt_user_octets_from_client{user="hello"} 11085279513 (10.32 GB)
telemt_user_octets_to_client{user="hello"} 123799423782 (115.30 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 108
```