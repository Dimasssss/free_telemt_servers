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

# Server Metrics 2026-03-19 05:32:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 27855.1 (7h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 407684
telemt_connections_bad_total 40588
telemt_connections_current 1068
telemt_connections_me_current 1068
telemt_handshake_timeouts_total 21233
telemt_upstream_connect_attempt_total 5327
telemt_upstream_connect_success_total 5238
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 5327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2675
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3881
telemt_me_reconnect_success_total 3863
telemt_me_reader_eof_total 4076
telemt_me_idle_close_by_peer_total 4075
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 107282
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 300080
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1999
telemt_desync_full_logged_total 557
telemt_desync_suppressed_total 1442
telemt_desync_frames_bucket_total{bucket="1_2"} 723
telemt_desync_frames_bucket_total{bucket="3_10"} 786
telemt_desync_frames_bucket_total{bucket="gt_10"} 490
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 3896
telemt_me_writer_restored_same_endpoint_total 3846
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 297333
telemt_user_connections_current{user="hello"} 1068
telemt_user_octets_from_client{user="hello"} 3788843752 (3.53 GB)
telemt_user_octets_to_client{user="hello"} 100006650212 (93.14 GB)
telemt_user_unique_ips_current{user="hello"} 415
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 27859.3 (7h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 813176
telemt_connections_bad_total 47849
telemt_connections_current 3175
telemt_connections_me_current 3175
telemt_handshake_timeouts_total 23912
telemt_upstream_connect_attempt_total 5137
telemt_upstream_connect_success_total 5043
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 5137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2581
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_reconnect_attempts_total 3675
telemt_me_reconnect_success_total 3655
telemt_me_reader_eof_total 3861
telemt_me_idle_close_by_peer_total 3861
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 248777
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 674153
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2712
telemt_desync_full_logged_total 926
telemt_desync_suppressed_total 1786
telemt_desync_frames_bucket_total{bucket="1_2"} 513
telemt_desync_frames_bucket_total{bucket="3_10"} 1020
telemt_desync_frames_bucket_total{bucket="gt_10"} 1179
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3720
telemt_me_writer_restored_same_endpoint_total 3636
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 674043
telemt_user_connections_current{user="hello"} 3175
telemt_user_octets_from_client{user="hello"} 16301861328 (15.18 GB)
telemt_user_octets_to_client{user="hello"} 294442070648 (274.22 GB)
telemt_user_unique_ips_current{user="hello"} 1145
telemt_user_unique_ips_recent_window{user="hello"} 459
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 27856.6 (7h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 692535
telemt_connections_bad_total 119429
telemt_connections_current 2277
telemt_connections_me_current 2277
telemt_handshake_timeouts_total 24044
telemt_upstream_connect_attempt_total 5032
telemt_upstream_connect_success_total 5032
telemt_upstream_connect_attempts_per_request{bucket="1"} 5032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2446
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3659
telemt_me_reconnect_success_total 3645
telemt_me_reader_eof_total 3862
telemt_me_idle_close_by_peer_total 3862
telemt_me_route_drop_no_conn_total 208589
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 500240
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2625
telemt_desync_full_logged_total 852
telemt_desync_suppressed_total 1773
telemt_desync_frames_bucket_total{bucket="1_2"} 423
telemt_desync_frames_bucket_total{bucket="3_10"} 934
telemt_desync_frames_bucket_total{bucket="gt_10"} 1268
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 3710
telemt_me_writer_restored_same_endpoint_total 3629
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 500227
telemt_user_connections_current{user="hello"} 2277
telemt_user_octets_from_client{user="hello"} 10107642252 (9.41 GB)
telemt_user_octets_to_client{user="hello"} 304986531720 (284.04 GB)
telemt_user_unique_ips_current{user="hello"} 888
telemt_user_unique_ips_recent_window{user="hello"} 335
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 27909.4 (7h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 774957
telemt_connections_bad_total 86771
telemt_connections_current 2216
telemt_connections_me_current 2216
telemt_handshake_timeouts_total 18631
telemt_upstream_connect_attempt_total 4857
telemt_upstream_connect_success_total 4857
telemt_upstream_connect_attempts_per_request{bucket="1"} 4857
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2388
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 3491
telemt_me_reconnect_success_total 3473
telemt_me_reader_eof_total 3669
telemt_me_idle_close_by_peer_total 3668
telemt_me_route_drop_no_conn_total 224018
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 495941
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1586
telemt_desync_full_logged_total 575
telemt_desync_suppressed_total 1011
telemt_desync_frames_bucket_total{bucket="1_2"} 290
telemt_desync_frames_bucket_total{bucket="3_10"} 653
telemt_desync_frames_bucket_total{bucket="gt_10"} 643
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 3519
telemt_me_writer_restored_same_endpoint_total 3449
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 494859
telemt_user_connections_current{user="hello"} 2216
telemt_user_octets_from_client{user="hello"} 7433625136 (6.92 GB)
telemt_user_octets_to_client{user="hello"} 189441067812 (176.43 GB)
telemt_user_unique_ips_current{user="hello"} 794
telemt_user_unique_ips_recent_window{user="hello"} 342
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 27852.9 (7h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 903771
telemt_connections_bad_total 252051
telemt_connections_current 2515
telemt_connections_me_current 2515
telemt_handshake_timeouts_total 25125
telemt_upstream_connect_attempt_total 4995
telemt_upstream_connect_success_total 4965
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 4995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2454
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 3600
telemt_me_reconnect_success_total 3579
telemt_me_reader_eof_total 3785
telemt_me_idle_close_by_peer_total 3785
telemt_me_route_drop_no_conn_total 218734
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 532527
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2568
telemt_desync_full_logged_total 906
telemt_desync_suppressed_total 1662
telemt_desync_frames_bucket_total{bucket="1_2"} 627
telemt_desync_frames_bucket_total{bucket="3_10"} 1096
telemt_desync_frames_bucket_total{bucket="gt_10"} 845
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 3616
telemt_me_writer_restored_same_endpoint_total 3555
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 532436
telemt_user_connections_current{user="hello"} 2515
telemt_user_octets_from_client{user="hello"} 14767590400 (13.75 GB)
telemt_user_octets_to_client{user="hello"} 298987679660 (278.45 GB)
telemt_user_unique_ips_current{user="hello"} 923
telemt_user_unique_ips_recent_window{user="hello"} 376
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 27864.7 (7h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155677
telemt_connections_bad_total 10574
telemt_connections_current 602
telemt_connections_me_current 602
telemt_handshake_timeouts_total 1206
telemt_upstream_connect_attempt_total 7704
telemt_upstream_connect_success_total 7497
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 7704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3880
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_reconnect_attempts_total 9238
telemt_me_reconnect_success_total 6113
telemt_me_reader_eof_total 6436
telemt_me_idle_close_by_peer_total 6436
telemt_me_route_drop_no_conn_total 62745
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 136187
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 186
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 115
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 6231
telemt_me_refill_failed_total 97
telemt_me_writer_restored_same_endpoint_total 6083
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 136180
telemt_user_connections_current{user="hello"} 602
telemt_user_octets_from_client{user="hello"} 2334333152 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 80271206988 (74.76 GB)
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 27855.3 (7h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 530373
telemt_connections_bad_total 52352
telemt_connections_current 2400
telemt_connections_me_current 2400
telemt_handshake_timeouts_total 25296
telemt_upstream_connect_attempt_total 5682
telemt_upstream_connect_success_total 5682
telemt_upstream_connect_attempts_per_request{bucket="1"} 5682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2665
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4316
telemt_me_reconnect_success_total 4304
telemt_me_reader_eof_total 4542
telemt_me_idle_close_by_peer_total 4542
telemt_me_route_drop_no_conn_total 151134
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 435821
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2444
telemt_desync_full_logged_total 885
telemt_desync_suppressed_total 1559
telemt_desync_frames_bucket_total{bucket="1_2"} 505
telemt_desync_frames_bucket_total{bucket="3_10"} 939
telemt_desync_frames_bucket_total{bucket="gt_10"} 1000
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 4353
telemt_me_writer_restored_same_endpoint_total 4289
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 435853
telemt_user_connections_current{user="hello"} 2400
telemt_user_octets_from_client{user="hello"} 5573455408 (5.19 GB)
telemt_user_octets_to_client{user="hello"} 257100771968 (239.44 GB)
telemt_user_unique_ips_current{user="hello"} 823
telemt_user_unique_ips_recent_window{user="hello"} 311
```