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

# Server Metrics 2026-03-19 06:08:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 30001.0 (8h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 459356
telemt_connections_bad_total 45175
telemt_connections_current 1226
telemt_connections_me_current 1226
telemt_handshake_timeouts_total 21898
telemt_upstream_connect_attempt_total 5856
telemt_upstream_connect_success_total 5752
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 5856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2941
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5381
telemt_me_reconnect_success_total 4239
telemt_me_reader_eof_total 4493
telemt_me_idle_close_by_peer_total 4492
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 121603
telemt_me_route_drop_channel_closed_total 30
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 342276
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2195
telemt_desync_full_logged_total 626
telemt_desync_suppressed_total 1569
telemt_desync_frames_bucket_total{bucket="1_2"} 760
telemt_desync_frames_bucket_total{bucket="3_10"} 863
telemt_desync_frames_bucket_total{bucket="gt_10"} 572
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4313
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 4222
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 339527
telemt_user_connections_current{user="hello"} 1226
telemt_user_octets_from_client{user="hello"} 4213902676 (3.92 GB)
telemt_user_octets_to_client{user="hello"} 116470042884 (108.47 GB)
telemt_user_unique_ips_current{user="hello"} 463
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 30005.0 (8h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 961299
telemt_connections_bad_total 55907
telemt_connections_current 3435
telemt_connections_me_current 3435
telemt_handshake_timeouts_total 27314
telemt_upstream_connect_attempt_total 5684
telemt_upstream_connect_success_total 5577
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 5684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2818
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_reconnect_attempts_total 5194
telemt_me_reconnect_success_total 4049
telemt_me_reader_eof_total 4296
telemt_me_idle_close_by_peer_total 4296
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 302529
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 790855
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3300
telemt_desync_full_logged_total 1126
telemt_desync_suppressed_total 2174
telemt_desync_frames_bucket_total{bucket="1_2"} 610
telemt_desync_frames_bucket_total{bucket="3_10"} 1242
telemt_desync_frames_bucket_total{bucket="gt_10"} 1448
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 4158
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 4029
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 790758
telemt_user_connections_current{user="hello"} 3435
telemt_user_octets_from_client{user="hello"} 17878152104 (16.65 GB)
telemt_user_octets_to_client{user="hello"} 350122388756 (326.08 GB)
telemt_user_unique_ips_current{user="hello"} 1228
telemt_user_unique_ips_recent_window{user="hello"} 468
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 30002.3 (8h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 818644
telemt_connections_bad_total 135281
telemt_connections_current 2925
telemt_connections_me_current 2925
telemt_handshake_timeouts_total 26479
telemt_upstream_connect_attempt_total 5494
telemt_upstream_connect_success_total 5494
telemt_upstream_connect_attempts_per_request{bucket="1"} 5494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2676
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3989
telemt_me_reconnect_success_total 3970
telemt_me_reader_eof_total 4199
telemt_me_idle_close_by_peer_total 4199
telemt_me_route_drop_no_conn_total 253650
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 595883
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3088
telemt_desync_full_logged_total 1001
telemt_desync_suppressed_total 2087
telemt_desync_frames_bucket_total{bucket="1_2"} 561
telemt_desync_frames_bucket_total{bucket="3_10"} 1095
telemt_desync_frames_bucket_total{bucket="gt_10"} 1432
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 4044
telemt_me_writer_restored_same_endpoint_total 3954
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 595655
telemt_user_connections_current{user="hello"} 2925
telemt_user_octets_from_client{user="hello"} 11280831332 (10.51 GB)
telemt_user_octets_to_client{user="hello"} 348297166712 (324.38 GB)
telemt_user_unique_ips_current{user="hello"} 956
telemt_user_unique_ips_recent_window{user="hello"} 441
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 30055.8 (8h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 895082
telemt_connections_bad_total 87795
telemt_connections_current 2434
telemt_connections_me_current 2434
telemt_handshake_timeouts_total 21708
telemt_upstream_connect_attempt_total 5326
telemt_upstream_connect_success_total 5326
telemt_upstream_connect_attempts_per_request{bucket="1"} 5326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2618
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 4847
telemt_me_reconnect_success_total 3797
telemt_me_reader_eof_total 4032
telemt_me_idle_close_by_peer_total 4031
telemt_me_route_drop_no_conn_total 270694
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 589311
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2186
telemt_desync_full_logged_total 795
telemt_desync_suppressed_total 1391
telemt_desync_frames_bucket_total{bucket="1_2"} 391
telemt_desync_frames_bucket_total{bucket="3_10"} 882
telemt_desync_frames_bucket_total{bucket="gt_10"} 913
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 3883
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 3773
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 588223
telemt_user_connections_current{user="hello"} 2434
telemt_user_octets_from_client{user="hello"} 9332124264 (8.69 GB)
telemt_user_octets_to_client{user="hello"} 225497128412 (210.01 GB)
telemt_user_unique_ips_current{user="hello"} 865
telemt_user_unique_ips_recent_window{user="hello"} 384
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 29998.8 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1071201
telemt_connections_bad_total 300712
telemt_connections_current 2760
telemt_connections_me_current 2760
telemt_handshake_timeouts_total 27414
telemt_upstream_connect_attempt_total 5374
telemt_upstream_connect_success_total 5340
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 5374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2634
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 3844
telemt_me_reconnect_success_total 3819
telemt_me_reader_eof_total 4038
telemt_me_idle_close_by_peer_total 4038
telemt_me_route_drop_no_conn_total 260468
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 632036
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3122
telemt_desync_full_logged_total 1046
telemt_desync_suppressed_total 2076
telemt_desync_frames_bucket_total{bucket="1_2"} 741
telemt_desync_frames_bucket_total{bucket="3_10"} 1347
telemt_desync_frames_bucket_total{bucket="gt_10"} 1034
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 3860
telemt_me_writer_restored_same_endpoint_total 3795
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 631956
telemt_user_connections_current{user="hello"} 2760
telemt_user_octets_from_client{user="hello"} 16143116800 (15.03 GB)
telemt_user_octets_to_client{user="hello"} 339913468700 (316.57 GB)
telemt_user_unique_ips_current{user="hello"} 985
telemt_user_unique_ips_recent_window{user="hello"} 425
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 30010.3 (8h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181403
telemt_connections_bad_total 11631
telemt_connections_current 679
telemt_connections_me_current 679
telemt_handshake_timeouts_total 1454
telemt_upstream_connect_attempt_total 8163
telemt_upstream_connect_success_total 7952
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 8163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_reconnect_attempts_total 10872
telemt_me_reconnect_success_total 6434
telemt_me_reader_eof_total 6810
telemt_me_idle_close_by_peer_total 6810
telemt_me_route_drop_no_conn_total 72409
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 157935
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 196
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 6595
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6404
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 157931
telemt_user_connections_current{user="hello"} 679
telemt_user_octets_from_client{user="hello"} 2629735620 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 87378649196 (81.38 GB)
telemt_user_unique_ips_current{user="hello"} 274
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 30001.3 (8h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 654733
telemt_connections_bad_total 82521
telemt_connections_current 2558
telemt_connections_me_current 2558
telemt_handshake_timeouts_total 28463
telemt_upstream_connect_attempt_total 6079
telemt_upstream_connect_success_total 6079
telemt_upstream_connect_attempts_per_request{bucket="1"} 6079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2854
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4580
telemt_me_reconnect_success_total 4566
telemt_me_reader_eof_total 4831
telemt_me_idle_close_by_peer_total 4831
telemt_me_route_drop_no_conn_total 231450
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 522059
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2957
telemt_desync_full_logged_total 1055
telemt_desync_suppressed_total 1902
telemt_desync_frames_bucket_total{bucket="1_2"} 593
telemt_desync_frames_bucket_total{bucket="3_10"} 1130
telemt_desync_frames_bucket_total{bucket="gt_10"} 1234
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 4619
telemt_me_writer_restored_same_endpoint_total 4551
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 521867
telemt_user_connections_current{user="hello"} 2558
telemt_user_octets_from_client{user="hello"} 6844564364 (6.37 GB)
telemt_user_octets_to_client{user="hello"} 299580235960 (279.01 GB)
telemt_user_unique_ips_current{user="hello"} 890
telemt_user_unique_ips_recent_window{user="hello"} 313
```