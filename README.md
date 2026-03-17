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

# Server Metrics 2026-03-17 23:35:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 103787.4 (28h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1237363
telemt_connections_bad_total 9043
telemt_handshake_timeouts_total 32287
telemt_upstream_connect_attempt_total 23351
telemt_upstream_connect_success_total 22856
telemt_upstream_connect_fail_total 495
telemt_upstream_connect_attempts_per_request{bucket="1"} 23351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10870
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 495
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 32505
telemt_me_reconnect_success_total 15371
telemt_me_reader_eof_total 16696
telemt_me_idle_close_by_peer_total 16695
telemt_me_route_drop_no_conn_total 548376
telemt_me_route_drop_channel_closed_total 156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1136471
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7473
telemt_desync_full_logged_total 2176
telemt_desync_suppressed_total 5297
telemt_desync_frames_bucket_total{bucket="1_2"} 1998
telemt_desync_frames_bucket_total{bucket="3_10"} 2832
telemt_desync_frames_bucket_total{bucket="gt_10"} 2643
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 16130
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 15349
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 759
telemt_user_connections_total{user="hello"} 1130693
telemt_user_connections_current{user="hello"} 536
telemt_user_octets_from_client{user="hello"} 22194466283 (20.67 GB)
telemt_user_octets_to_client{user="hello"} 408602938655 (380.54 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 104039.1 (28h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1310321
telemt_connections_bad_total 61031
telemt_handshake_timeouts_total 45343
telemt_upstream_connect_attempt_total 458896
telemt_upstream_connect_success_total 457984
telemt_upstream_connect_fail_total 912
telemt_upstream_connect_attempts_per_request{bucket="1"} 458896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 383373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31317
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43292
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 912
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 58951
telemt_me_reconnect_success_total 15793
telemt_me_reader_eof_total 17838
telemt_me_idle_close_by_peer_total 17838
telemt_me_route_drop_no_conn_total 341100
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 700928
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3211
telemt_desync_full_logged_total 1053
telemt_desync_suppressed_total 2158
telemt_desync_frames_bucket_total{bucket="1_2"} 627
telemt_desync_frames_bucket_total{bucket="3_10"} 1315
telemt_desync_frames_bucket_total{bucket="gt_10"} 1269
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 17335
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 15777
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1542
telemt_user_connections_total{user="hello"} 1137356
telemt_user_connections_current{user="hello"} 699
telemt_user_octets_from_client{user="hello"} 15625779174 (14.55 GB)
telemt_user_octets_to_client{user="hello"} 390082353938 (363.29 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 266
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 103815.2 (28h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 771795
telemt_connections_bad_total 48855
telemt_handshake_timeouts_total 23729
telemt_upstream_connect_attempt_total 24487
telemt_upstream_connect_success_total 24344
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 24487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13072
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 39785
telemt_me_reconnect_success_total 19104
telemt_me_reader_eof_total 20823
telemt_me_idle_close_by_peer_total 20816
telemt_me_route_drop_no_conn_total 315062
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 656159
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2134
telemt_desync_full_logged_total 694
telemt_desync_suppressed_total 1440
telemt_desync_frames_bucket_total{bucket="1_2"} 606
telemt_desync_frames_bucket_total{bucket="3_10"} 826
telemt_desync_frames_bucket_total{bucket="gt_10"} 702
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 20011
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 19092
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 907
telemt_user_connections_total{user="hello"} 654408
telemt_user_connections_current{user="hello"} 530
telemt_user_octets_from_client{user="hello"} 31817671540 (29.63 GB)
telemt_user_octets_to_client{user="hello"} 289839615960 (269.93 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 103874.6 (28h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1260575
telemt_connections_bad_total 48953
telemt_handshake_timeouts_total 21661
telemt_upstream_connect_attempt_total 84084
telemt_upstream_connect_success_total 83647
telemt_upstream_connect_fail_total 437
telemt_upstream_connect_attempts_per_request{bucket="1"} 84084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12769
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 351
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 437
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 35408
telemt_me_reconnect_success_total 15080
telemt_me_reader_eof_total 16608
telemt_me_idle_close_by_peer_total 16606
telemt_me_route_drop_no_conn_total 518579
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1028752
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3878
telemt_desync_full_logged_total 1278
telemt_desync_suppressed_total 2600
telemt_desync_frames_bucket_total{bucket="1_2"} 947
telemt_desync_frames_bucket_total{bucket="3_10"} 1629
telemt_desync_frames_bucket_total{bucket="gt_10"} 1302
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 15995
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 15071
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 915
telemt_user_connections_total{user="hello"} 1091235
telemt_user_connections_current{user="hello"} 576
telemt_user_octets_from_client{user="hello"} 17171863639 (15.99 GB)
telemt_user_octets_to_client{user="hello"} 498272431821 (464.05 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 103846.4 (28h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 816776
telemt_connections_bad_total 96172
telemt_handshake_timeouts_total 6632
telemt_upstream_connect_attempt_total 43303
telemt_upstream_connect_success_total 42713
telemt_upstream_connect_fail_total 590
telemt_upstream_connect_attempts_per_request{bucket="1"} 43303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 405
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 590
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 55988
telemt_me_reconnect_success_total 21034
telemt_me_reader_eof_total 22900
telemt_me_idle_close_by_peer_total 22898
telemt_me_route_drop_no_conn_total 259442
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 656184
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3097
telemt_desync_full_logged_total 912
telemt_desync_suppressed_total 2185
telemt_desync_frames_bucket_total{bucket="1_2"} 986
telemt_desync_frames_bucket_total{bucket="3_10"} 1237
telemt_desync_frames_bucket_total{bucket="gt_10"} 874
telemt_pool_swap_total 52
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22479
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 21026
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1445
telemt_user_connections_total{user="hello"} 672794
telemt_user_connections_current{user="hello"} 512
telemt_user_octets_from_client{user="hello"} 13327269032 (12.41 GB)
telemt_user_octets_to_client{user="hello"} 333168910496 (310.29 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 104007.6 (28h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1050728
telemt_connections_bad_total 93865
telemt_handshake_timeouts_total 9548
telemt_upstream_connect_attempt_total 20604
telemt_upstream_connect_success_total 20489
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 20604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10588
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 26580
telemt_me_reconnect_success_total 15299
telemt_me_reader_eof_total 16611
telemt_me_idle_close_by_peer_total 16609
telemt_me_route_drop_no_conn_total 702377
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1017677
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
telemt_pool_swap_total 90
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 15902
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 15285
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 603
telemt_user_connections_total{user="hello"} 880703
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 14244242928 (13.27 GB)
telemt_user_octets_to_client{user="hello"} 371435486884 (345.93 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 51774.6 (14h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 376208
telemt_connections_bad_total 44617
telemt_handshake_timeouts_total 10735
telemt_upstream_connect_attempt_total 19669
telemt_upstream_connect_success_total 19490
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 19669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8969
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 28335
telemt_me_reconnect_success_total 16738
telemt_me_reader_eof_total 17697
telemt_me_idle_close_by_peer_total 17697
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 94768
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 282166
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1029
telemt_desync_full_logged_total 324
telemt_desync_suppressed_total 705
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 433
telemt_desync_frames_bucket_total{bucket="gt_10"} 382
telemt_pool_swap_total 31
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 17296
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 16709
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 558
telemt_user_connections_total{user="hello"} 282104
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 22004623765 (20.49 GB)
telemt_user_octets_to_client{user="hello"} 231677314106 (215.77 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 22
```