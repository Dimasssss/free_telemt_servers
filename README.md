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

# Server Metrics 2026-03-17 16:06:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 76857.1 (21h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 865589
telemt_connections_bad_total 6351
telemt_handshake_timeouts_total 25224
telemt_upstream_connect_attempt_total 18366
telemt_upstream_connect_success_total 17894
telemt_upstream_connect_fail_total 472
telemt_upstream_connect_attempts_per_request{bucket="1"} 18366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 472
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 27621
telemt_me_reconnect_success_total 11725
telemt_me_reader_eof_total 12774
telemt_me_idle_close_by_peer_total 12773
telemt_me_route_drop_no_conn_total 381130
telemt_me_route_drop_channel_closed_total 85
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 793246
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5431
telemt_desync_full_logged_total 1502
telemt_desync_suppressed_total 3929
telemt_desync_frames_bucket_total{bucket="1_2"} 1573
telemt_desync_frames_bucket_total{bucket="3_10"} 2109
telemt_desync_frames_bucket_total{bucket="gt_10"} 1749
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 12380
telemt_me_refill_failed_total 491
telemt_me_writer_restored_same_endpoint_total 11703
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 655
telemt_user_connections_total{user="hello"} 788637
telemt_user_connections_current{user="hello"} 1009
telemt_user_octets_from_client{user="hello"} 12394213843 (11.54 GB)
telemt_user_octets_to_client{user="hello"} 259766986699 (241.93 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 77109.7 (21h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 582470
telemt_connections_bad_total 32322
telemt_handshake_timeouts_total 28528
telemt_upstream_connect_attempt_total 137848
telemt_upstream_connect_success_total 137276
telemt_upstream_connect_fail_total 571
telemt_upstream_connect_attempts_per_request{bucket="1"} 137847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14627
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 571
telemt_me_keepalive_timeout_total 332
telemt_me_reconnect_attempts_total 42903
telemt_me_reconnect_success_total 13516
telemt_me_reader_eof_total 14987
telemt_me_idle_close_by_peer_total 14987
telemt_me_route_drop_no_conn_total 196818
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375662
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1494
telemt_desync_full_logged_total 469
telemt_desync_suppressed_total 1025
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 651
telemt_desync_frames_bucket_total{bucket="gt_10"} 507
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14597
telemt_me_refill_failed_total 914
telemt_me_writer_restored_same_endpoint_total 13500
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1081
telemt_user_connections_total{user="hello"} 495457
telemt_user_connections_current{user="hello"} 913
telemt_user_octets_from_client{user="hello"} 5446561315 (5.07 GB)
telemt_user_octets_to_client{user="hello"} 138189779752 (128.70 GB)
telemt_user_msgs_from_client{user="hello"} 1754786
telemt_user_msgs_to_client{user="hello"} 6570250
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 76885.4 (21h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 291300
telemt_connections_bad_total 7876
telemt_handshake_timeouts_total 18939
telemt_upstream_connect_attempt_total 19836
telemt_upstream_connect_success_total 19732
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 19836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10735
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 33697
telemt_me_reconnect_success_total 15810
telemt_me_reader_eof_total 17228
telemt_me_idle_close_by_peer_total 17225
telemt_me_route_drop_no_conn_total 138838
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 249715
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 828
telemt_desync_full_logged_total 241
telemt_desync_suppressed_total 587
telemt_desync_frames_bucket_total{bucket="1_2"} 300
telemt_desync_frames_bucket_total{bucket="3_10"} 371
telemt_desync_frames_bucket_total{bucket="gt_10"} 157
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 16578
telemt_me_refill_failed_total 556
telemt_me_writer_restored_same_endpoint_total 15799
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 768
telemt_user_connections_total{user="hello"} 249565
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 19493524940 (18.15 GB)
telemt_user_octets_to_client{user="hello"} 59974043196 (55.86 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 76944.8 (21h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 695428
telemt_connections_bad_total 10511
telemt_handshake_timeouts_total 14613
telemt_upstream_connect_attempt_total 69771
telemt_upstream_connect_success_total 69422
telemt_upstream_connect_fail_total 349
telemt_upstream_connect_attempts_per_request{bucket="1"} 69771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10065
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 270
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 349
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 32279
telemt_me_reconnect_success_total 11988
telemt_me_reader_eof_total 13264
telemt_me_idle_close_by_peer_total 13263
telemt_me_route_drop_no_conn_total 259828
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 547961
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1872
telemt_desync_full_logged_total 635
telemt_desync_suppressed_total 1237
telemt_desync_frames_bucket_total{bucket="1_2"} 474
telemt_desync_frames_bucket_total{bucket="3_10"} 841
telemt_desync_frames_bucket_total{bucket="gt_10"} 557
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12831
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 11979
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 843
telemt_user_connections_total{user="hello"} 601294
telemt_user_connections_current{user="hello"} 956
telemt_user_octets_from_client{user="hello"} 7110492033 (6.62 GB)
telemt_user_octets_to_client{user="hello"} 179750488488 (167.41 GB)
telemt_user_msgs_from_client{user="hello"} 608736
telemt_user_msgs_to_client{user="hello"} 4510075
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 76916.6 (21h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 308912
telemt_connections_bad_total 57982
telemt_handshake_timeouts_total 3764
telemt_upstream_connect_attempt_total 21777
telemt_upstream_connect_success_total 21299
telemt_upstream_connect_fail_total 478
telemt_upstream_connect_attempts_per_request{bucket="1"} 21777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11458
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 296
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 478
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 47004
telemt_me_reconnect_success_total 17028
telemt_me_reader_eof_total 18552
telemt_me_idle_close_by_peer_total 18550
telemt_me_route_drop_no_conn_total 89897
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234200
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1146
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 898
telemt_desync_frames_bucket_total{bucket="1_2"} 573
telemt_desync_frames_bucket_total{bucket="3_10"} 443
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 18244
telemt_me_refill_failed_total 932
telemt_me_writer_restored_same_endpoint_total 17020
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1216
telemt_user_connections_total{user="hello"} 234773
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 2866098763 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 85903577271 (80.00 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 77082.4 (21h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 755748
telemt_connections_bad_total 60022
telemt_handshake_timeouts_total 7168
telemt_upstream_connect_attempt_total 15519
telemt_upstream_connect_success_total 15436
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 15519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7921
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 21861
telemt_me_reconnect_success_total 11560
telemt_me_reader_eof_total 12576
telemt_me_idle_close_by_peer_total 12575
telemt_me_route_drop_no_conn_total 558473
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 772767
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1172
telemt_desync_full_logged_total 422
telemt_desync_suppressed_total 750
telemt_desync_frames_bucket_total{bucket="1_2"} 282
telemt_desync_frames_bucket_total{bucket="3_10"} 460
telemt_desync_frames_bucket_total{bucket="gt_10"} 430
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12068
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 11546
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 508
telemt_user_connections_total{user="hello"} 650788
telemt_user_connections_current{user="hello"} 999
telemt_user_octets_from_client{user="hello"} 9453772580 (8.80 GB)
telemt_user_octets_to_client{user="hello"} 291603208108 (271.58 GB)
telemt_user_unique_ips_current{user="hello"} 340
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 24844.8 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19285
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 314
telemt_upstream_connect_attempt_total 13324
telemt_upstream_connect_success_total 13213
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 13324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6013
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 23351
telemt_me_reconnect_success_total 11781
telemt_me_reader_eof_total 12474
telemt_me_idle_close_by_peer_total 12474
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 9687
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18432
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 12272
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 11761
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 491
telemt_user_connections_total{user="hello"} 18486
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 583947977 (556.90 MB)
telemt_user_octets_to_client{user="hello"} 24926222074 (23.21 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 9
```