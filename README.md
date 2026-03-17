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

# Server Metrics 2026-03-17 11:25:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 60007.1 (16h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 533479
telemt_connections_bad_total 4495
telemt_handshake_timeouts_total 15985
telemt_upstream_connect_attempt_total 14812
telemt_upstream_connect_success_total 14371
telemt_upstream_connect_fail_total 441
telemt_upstream_connect_attempts_per_request{bucket="1"} 14812
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6623
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 441
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 10624
telemt_me_reconnect_success_total 9089
telemt_me_reader_eof_total 9663
telemt_me_idle_close_by_peer_total 9662
telemt_me_route_drop_no_conn_total 174734
telemt_me_route_drop_channel_closed_total 49
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 482230
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3846
telemt_desync_full_logged_total 1008
telemt_desync_suppressed_total 2838
telemt_desync_frames_bucket_total{bucket="1_2"} 1114
telemt_desync_frames_bucket_total{bucket="3_10"} 1603
telemt_desync_frames_bucket_total{bucket="gt_10"} 1129
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 9272
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 9067
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 484167
telemt_user_connections_current{user="hello"} 978
telemt_user_octets_from_client{user="hello"} 6654241151 (6.20 GB)
telemt_user_octets_to_client{user="hello"} 178111216699 (165.88 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 349
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 60259.1 (16h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 297835
telemt_connections_bad_total 10992
telemt_handshake_timeouts_total 17332
telemt_upstream_connect_attempt_total 15244
telemt_upstream_connect_success_total 15026
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 15244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 24383
telemt_me_reconnect_success_total 12050
telemt_me_reader_eof_total 13014
telemt_me_idle_close_by_peer_total 13014
telemt_me_route_drop_no_conn_total 111358
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 254873
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 751
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 477
telemt_desync_frames_bucket_total{bucket="1_2"} 211
telemt_desync_frames_bucket_total{bucket="3_10"} 326
telemt_desync_frames_bucket_total{bucket="gt_10"} 214
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 12566
telemt_me_refill_failed_total 384
telemt_me_writer_restored_same_endpoint_total 12034
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 516
telemt_user_connections_total{user="hello"} 254861
telemt_user_connections_current{user="hello"} 520
telemt_user_octets_from_client{user="hello"} 3016377556 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 92733521536 (86.36 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 60035.0 (16h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175626
telemt_connections_bad_total 7641
telemt_handshake_timeouts_total 14145
telemt_upstream_connect_attempt_total 15778
telemt_upstream_connect_success_total 15696
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 15778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8695
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 14548
telemt_me_reconnect_success_total 12678
telemt_me_reader_eof_total 13552
telemt_me_idle_close_by_peer_total 13552
telemt_me_route_drop_no_conn_total 52420
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143610
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 521
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 385
telemt_desync_frames_bucket_total{bucket="1_2"} 224
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 12910
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 12667
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 143514
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 13525089484 (12.60 GB)
telemt_user_octets_to_client{user="hello"} 41719196100 (38.85 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 60094.0 (16h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 396555
telemt_connections_bad_total 6700
telemt_handshake_timeouts_total 11994
telemt_upstream_connect_attempt_total 13673
telemt_upstream_connect_success_total 13545
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 13673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7085
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 11591
telemt_me_reconnect_success_total 10485
telemt_me_reader_eof_total 11142
telemt_me_idle_close_by_peer_total 11142
telemt_me_route_drop_no_conn_total 111350
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 328721
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 946
telemt_desync_full_logged_total 342
telemt_desync_suppressed_total 604
telemt_desync_frames_bucket_total{bucket="1_2"} 229
telemt_desync_frames_bucket_total{bucket="3_10"} 408
telemt_desync_frames_bucket_total{bucket="gt_10"} 309
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 10693
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 10477
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 328662
telemt_user_connections_current{user="hello"} 731
telemt_user_octets_from_client{user="hello"} 4295136026 (4.00 GB)
telemt_user_octets_to_client{user="hello"} 120892772729 (112.59 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 60065.8 (16h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209284
telemt_connections_bad_total 51914
telemt_handshake_timeouts_total 3021
telemt_upstream_connect_attempt_total 17775
telemt_upstream_connect_success_total 17542
telemt_upstream_connect_fail_total 233
telemt_upstream_connect_attempts_per_request{bucket="1"} 17775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9464
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 233
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 28076
telemt_me_reconnect_success_total 14424
telemt_me_reader_eof_total 15449
telemt_me_idle_close_by_peer_total 15449
telemt_me_route_drop_no_conn_total 55151
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147617
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 883
telemt_desync_full_logged_total 169
telemt_desync_suppressed_total 714
telemt_desync_frames_bucket_total{bucket="1_2"} 470
telemt_desync_frames_bucket_total{bucket="3_10"} 318
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 15028
telemt_me_refill_failed_total 424
telemt_me_writer_restored_same_endpoint_total 14416
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 604
telemt_user_connections_total{user="hello"} 147633
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 2072086127 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 63296500710 (58.95 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 60227.2 (16h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 492090
telemt_connections_bad_total 51649
telemt_handshake_timeouts_total 4693
telemt_upstream_connect_attempt_total 12200
telemt_upstream_connect_success_total 12134
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 12200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6121
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 13037
telemt_me_reconnect_success_total 9145
telemt_me_reader_eof_total 9858
telemt_me_idle_close_by_peer_total 9858
telemt_me_route_drop_no_conn_total 332025
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 486661
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 728
telemt_desync_full_logged_total 272
telemt_desync_suppressed_total 456
telemt_desync_frames_bucket_total{bucket="1_2"} 195
telemt_desync_frames_bucket_total{bucket="3_10"} 282
telemt_desync_frames_bucket_total{bucket="gt_10"} 251
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 9407
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 9131
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 408355
telemt_user_connections_current{user="hello"} 875
telemt_user_octets_from_client{user="hello"} 6015148588 (5.60 GB)
telemt_user_octets_to_client{user="hello"} 206764556672 (192.56 GB)
telemt_user_unique_ips_current{user="hello"} 301
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 7994.0 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5860
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 4381
telemt_upstream_connect_success_total 4340
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 4381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 4688
telemt_me_reconnect_success_total 3787
telemt_me_reader_eof_total 3912
telemt_me_idle_close_by_peer_total 3912
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 2298
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5551
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 3854
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 3778
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 5657
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 144631757 (137.93 MB)
telemt_user_octets_to_client{user="hello"} 18891838946 (17.59 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 6
```