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

# Server Metrics 2026-03-18 00:00:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 105314.3 (29h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1248275
telemt_connections_bad_total 9413
telemt_handshake_timeouts_total 32369
telemt_upstream_connect_attempt_total 23601
telemt_upstream_connect_success_total 23105
telemt_upstream_connect_fail_total 496
telemt_upstream_connect_attempts_per_request{bucket="1"} 23601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10983
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 496
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 32711
telemt_me_reconnect_success_total 15576
telemt_me_reader_eof_total 16918
telemt_me_idle_close_by_peer_total 16917
telemt_me_route_drop_no_conn_total 551768
telemt_me_route_drop_channel_closed_total 157
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1146665
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7484
telemt_desync_full_logged_total 2187
telemt_desync_suppressed_total 5297
telemt_desync_frames_bucket_total{bucket="1_2"} 2001
telemt_desync_frames_bucket_total{bucket="3_10"} 2838
telemt_desync_frames_bucket_total{bucket="gt_10"} 2645
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 16341
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 15554
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 765
telemt_user_connections_total{user="hello"} 1140887
telemt_user_connections_current{user="hello"} 575
telemt_user_octets_from_client{user="hello"} 22640106623 (21.09 GB)
telemt_user_octets_to_client{user="hello"} 410392429827 (382.21 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 105565.8 (29h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1321529
telemt_connections_bad_total 61398
telemt_handshake_timeouts_total 45632
telemt_upstream_connect_attempt_total 459397
telemt_upstream_connect_success_total 458475
telemt_upstream_connect_fail_total 922
telemt_upstream_connect_attempts_per_request{bucket="1"} 459397
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 383552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31627
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43294
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 922
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 59356
telemt_me_reconnect_success_total 16198
telemt_me_reader_eof_total 18247
telemt_me_idle_close_by_peer_total 18247
telemt_me_route_drop_no_conn_total 343789
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 711134
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3254
telemt_desync_full_logged_total 1073
telemt_desync_suppressed_total 2181
telemt_desync_frames_bucket_total{bucket="1_2"} 631
telemt_desync_frames_bucket_total{bucket="3_10"} 1336
telemt_desync_frames_bucket_total{bucket="gt_10"} 1287
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 17744
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 16182
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1546
telemt_user_connections_total{user="hello"} 1147558
telemt_user_connections_current{user="hello"} 704
telemt_user_octets_from_client{user="hello"} 15705355918 (14.63 GB)
telemt_user_octets_to_client{user="hello"} 394257373778 (367.18 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 105342.2 (29h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 781748
telemt_connections_bad_total 50038
telemt_handshake_timeouts_total 23782
telemt_upstream_connect_attempt_total 24743
telemt_upstream_connect_success_total 24599
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 24743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13219
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 39985
telemt_me_reconnect_success_total 19304
telemt_me_reader_eof_total 21033
telemt_me_idle_close_by_peer_total 21026
telemt_me_route_drop_no_conn_total 317671
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 664567
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2136
telemt_desync_full_logged_total 696
telemt_desync_suppressed_total 1440
telemt_desync_frames_bucket_total{bucket="1_2"} 607
telemt_desync_frames_bucket_total{bucket="3_10"} 826
telemt_desync_frames_bucket_total{bucket="gt_10"} 703
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 20213
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 19292
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 909
telemt_user_connections_total{user="hello"} 662785
telemt_user_connections_current{user="hello"} 541
telemt_user_octets_from_client{user="hello"} 32016782332 (29.82 GB)
telemt_user_octets_to_client{user="hello"} 293262174288 (273.12 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 105401.2 (29h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1267701
telemt_connections_bad_total 50545
telemt_handshake_timeouts_total 21690
telemt_upstream_connect_attempt_total 84370
telemt_upstream_connect_success_total 83930
telemt_upstream_connect_fail_total 440
telemt_upstream_connect_attempts_per_request{bucket="1"} 84370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12916
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 440
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 35605
telemt_me_reconnect_success_total 15276
telemt_me_reader_eof_total 16815
telemt_me_idle_close_by_peer_total 16813
telemt_me_route_drop_no_conn_total 521068
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1033937
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3893
telemt_desync_full_logged_total 1287
telemt_desync_suppressed_total 2606
telemt_desync_frames_bucket_total{bucket="1_2"} 950
telemt_desync_frames_bucket_total{bucket="3_10"} 1636
telemt_desync_frames_bucket_total{bucket="gt_10"} 1307
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 16195
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 15267
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 919
telemt_user_connections_total{user="hello"} 1096420
telemt_user_connections_current{user="hello"} 557
telemt_user_octets_from_client{user="hello"} 17240732879 (16.06 GB)
telemt_user_octets_to_client{user="hello"} 505221681297 (470.52 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 105373.1 (29h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 825955
telemt_connections_bad_total 97320
telemt_handshake_timeouts_total 6659
telemt_upstream_connect_attempt_total 43747
telemt_upstream_connect_success_total 43149
telemt_upstream_connect_fail_total 598
telemt_upstream_connect_attempts_per_request{bucket="1"} 43747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 409
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 598
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 56355
telemt_me_reconnect_success_total 21399
telemt_me_reader_eof_total 23265
telemt_me_idle_close_by_peer_total 23263
telemt_me_route_drop_no_conn_total 262065
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 663968
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3146
telemt_desync_full_logged_total 930
telemt_desync_suppressed_total 2216
telemt_desync_frames_bucket_total{bucket="1_2"} 998
telemt_desync_frames_bucket_total{bucket="3_10"} 1255
telemt_desync_frames_bucket_total{bucket="gt_10"} 893
telemt_pool_swap_total 52
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22844
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 21391
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1445
telemt_user_connections_total{user="hello"} 680576
telemt_user_connections_current{user="hello"} 530
telemt_user_octets_from_client{user="hello"} 13446823992 (12.52 GB)
telemt_user_octets_to_client{user="hello"} 339730120212 (316.40 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 105534.1 (29h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1061509
telemt_connections_bad_total 97933
telemt_handshake_timeouts_total 9573
telemt_upstream_connect_attempt_total 20956
telemt_upstream_connect_success_total 20840
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 20956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9957
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10766
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 26844
telemt_me_reconnect_success_total 15562
telemt_me_reader_eof_total 16897
telemt_me_idle_close_by_peer_total 16895
telemt_me_route_drop_no_conn_total 709421
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1025344
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 92
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 16165
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 15548
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 603
telemt_user_connections_total{user="hello"} 886366
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 14292292348 (13.31 GB)
telemt_user_octets_to_client{user="hello"} 374549919248 (348.83 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 53301.3 (14h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 383748
telemt_connections_bad_total 44665
telemt_handshake_timeouts_total 10778
telemt_upstream_connect_attempt_total 20169
telemt_upstream_connect_success_total 19985
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 20169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9195
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 28744
telemt_me_reconnect_success_total 17145
telemt_me_reader_eof_total 18140
telemt_me_idle_close_by_peer_total 18140
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 95924
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 285350
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1058
telemt_desync_full_logged_total 334
telemt_desync_suppressed_total 724
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 448
telemt_desync_frames_bucket_total{bucket="gt_10"} 396
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 17705
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 17115
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 560
telemt_user_connections_total{user="hello"} 285291
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 22058429833 (20.54 GB)
telemt_user_octets_to_client{user="hello"} 234346327878 (218.25 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 35
```