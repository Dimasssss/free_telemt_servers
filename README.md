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

# Server Metrics 2026-03-19 05:07:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 26322.7 (7h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 377522
telemt_connections_bad_total 38568
telemt_connections_current 1062
telemt_connections_me_current 1062
telemt_handshake_timeouts_total 20424
telemt_upstream_connect_attempt_total 5130
telemt_upstream_connect_success_total 5045
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 5130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2574
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3731
telemt_me_reconnect_success_total 3714
telemt_me_reader_eof_total 3918
telemt_me_idle_close_by_peer_total 3917
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 97021
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 274711
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1881
telemt_desync_full_logged_total 520
telemt_desync_suppressed_total 1361
telemt_desync_frames_bucket_total{bucket="1_2"} 690
telemt_desync_frames_bucket_total{bucket="3_10"} 750
telemt_desync_frames_bucket_total{bucket="gt_10"} 441
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 3744
telemt_me_writer_restored_same_endpoint_total 3697
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 271960
telemt_user_connections_current{user="hello"} 1062
telemt_user_octets_from_client{user="hello"} 3340249004 (3.11 GB)
telemt_user_octets_to_client{user="hello"} 88291908920 (82.23 GB)
telemt_user_unique_ips_current{user="hello"} 398
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 26327.5 (7h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 721725
telemt_connections_bad_total 44201
telemt_connections_current 2898
telemt_connections_me_current 2898
telemt_handshake_timeouts_total 22350
telemt_upstream_connect_attempt_total 4962
telemt_upstream_connect_success_total 4869
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 4962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2503
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_reconnect_attempts_total 3544
telemt_me_reconnect_success_total 3526
telemt_me_reader_eof_total 3724
telemt_me_idle_close_by_peer_total 3724
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 218793
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 597957
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2403
telemt_desync_full_logged_total 812
telemt_desync_suppressed_total 1591
telemt_desync_frames_bucket_total{bucket="1_2"} 469
telemt_desync_frames_bucket_total{bucket="3_10"} 891
telemt_desync_frames_bucket_total{bucket="gt_10"} 1043
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 3587
telemt_me_writer_restored_same_endpoint_total 3507
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 597869
telemt_user_connections_current{user="hello"} 2898
telemt_user_octets_from_client{user="hello"} 15533560276 (14.47 GB)
telemt_user_octets_to_client{user="hello"} 261826584944 (243.85 GB)
telemt_user_unique_ips_current{user="hello"} 1061
telemt_user_unique_ips_recent_window{user="hello"} 384
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 26324.7 (7h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 611123
telemt_connections_bad_total 113437
telemt_connections_current 2268
telemt_connections_me_current 2268
telemt_handshake_timeouts_total 21832
telemt_upstream_connect_attempt_total 4866
telemt_upstream_connect_success_total 4866
telemt_upstream_connect_attempts_per_request{bucket="1"} 4866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2374
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3536
telemt_me_reconnect_success_total 3522
telemt_me_reader_eof_total 3729
telemt_me_idle_close_by_peer_total 3729
telemt_me_route_drop_no_conn_total 180927
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 440816
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2307
telemt_desync_full_logged_total 753
telemt_desync_suppressed_total 1554
telemt_desync_frames_bucket_total{bucket="1_2"} 347
telemt_desync_frames_bucket_total{bucket="3_10"} 816
telemt_desync_frames_bucket_total{bucket="gt_10"} 1144
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 3582
telemt_me_writer_restored_same_endpoint_total 3506
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 440795
telemt_user_connections_current{user="hello"} 2268
telemt_user_octets_from_client{user="hello"} 9389913584 (8.75 GB)
telemt_user_octets_to_client{user="hello"} 274899980324 (256.02 GB)
telemt_user_unique_ips_current{user="hello"} 851
telemt_user_unique_ips_recent_window{user="hello"} 300
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 26377.9 (7h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 703675
telemt_connections_bad_total 85441
telemt_connections_current 1999
telemt_connections_me_current 1999
telemt_handshake_timeouts_total 15860
telemt_upstream_connect_attempt_total 4703
telemt_upstream_connect_success_total 4703
telemt_upstream_connect_attempts_per_request{bucket="1"} 4703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2309
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 3380
telemt_me_reconnect_success_total 3364
telemt_me_reader_eof_total 3553
telemt_me_idle_close_by_peer_total 3552
telemt_me_route_drop_no_conn_total 198551
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 434865
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1350
telemt_desync_full_logged_total 490
telemt_desync_suppressed_total 860
telemt_desync_frames_bucket_total{bucket="1_2"} 254
telemt_desync_frames_bucket_total{bucket="3_10"} 569
telemt_desync_frames_bucket_total{bucket="gt_10"} 527
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 3406
telemt_me_writer_restored_same_endpoint_total 3340
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 433834
telemt_user_connections_current{user="hello"} 1999
telemt_user_octets_from_client{user="hello"} 6643470160 (6.19 GB)
telemt_user_octets_to_client{user="hello"} 166803058956 (155.35 GB)
telemt_user_unique_ips_current{user="hello"} 759
telemt_user_unique_ips_recent_window{user="hello"} 299
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 26321.3 (7h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 803088
telemt_connections_bad_total 224856
telemt_connections_current 2206
telemt_connections_me_current 2206
telemt_handshake_timeouts_total 21917
telemt_upstream_connect_attempt_total 4819
telemt_upstream_connect_success_total 4789
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 4819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2367
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 3467
telemt_me_reconnect_success_total 3447
telemt_me_reader_eof_total 3646
telemt_me_idle_close_by_peer_total 3646
telemt_me_route_drop_no_conn_total 196304
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 470671
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2142
telemt_desync_full_logged_total 808
telemt_desync_suppressed_total 1334
telemt_desync_frames_bucket_total{bucket="1_2"} 482
telemt_desync_frames_bucket_total{bucket="3_10"} 915
telemt_desync_frames_bucket_total{bucket="gt_10"} 745
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 3481
telemt_me_writer_restored_same_endpoint_total 3423
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 470589
telemt_user_connections_current{user="hello"} 2206
telemt_user_octets_from_client{user="hello"} 14024743796 (13.06 GB)
telemt_user_octets_to_client{user="hello"} 270900932616 (252.30 GB)
telemt_user_unique_ips_current{user="hello"} 835
telemt_user_unique_ips_recent_window{user="hello"} 302
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 26332.8 (7h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140157
telemt_connections_bad_total 10408
telemt_connections_current 601
telemt_connections_me_current 601
telemt_handshake_timeouts_total 776
telemt_upstream_connect_attempt_total 7278
telemt_upstream_connect_success_total 7080
telemt_upstream_connect_fail_total 198
telemt_upstream_connect_attempts_per_request{bucket="1"} 7278
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3692
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 198
telemt_me_reconnect_attempts_total 7585
telemt_me_reconnect_success_total 5741
telemt_me_reader_eof_total 6020
telemt_me_idle_close_by_peer_total 6020
telemt_me_route_drop_no_conn_total 56616
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122990
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 152
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 95
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 67
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 5815
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 5711
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 122983
telemt_user_connections_current{user="hello"} 601
telemt_user_octets_from_client{user="hello"} 2155339164 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 75490785608 (70.31 GB)
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 26323.8 (7h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 464937
telemt_connections_bad_total 48607
telemt_connections_current 2154
telemt_connections_me_current 2154
telemt_handshake_timeouts_total 23819
telemt_upstream_connect_attempt_total 5417
telemt_upstream_connect_success_total 5417
telemt_upstream_connect_attempts_per_request{bucket="1"} 5417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2536
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4094
telemt_me_reconnect_success_total 4082
telemt_me_reader_eof_total 4307
telemt_me_idle_close_by_peer_total 4307
telemt_me_route_drop_no_conn_total 131355
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 378456
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2131
telemt_desync_full_logged_total 783
telemt_desync_suppressed_total 1348
telemt_desync_frames_bucket_total{bucket="1_2"} 443
telemt_desync_frames_bucket_total{bucket="3_10"} 814
telemt_desync_frames_bucket_total{bucket="gt_10"} 874
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4129
telemt_me_writer_restored_same_endpoint_total 4067
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 378466
telemt_user_connections_current{user="hello"} 2154
telemt_user_octets_from_client{user="hello"} 4855236888 (4.52 GB)
telemt_user_octets_to_client{user="hello"} 223103831020 (207.78 GB)
telemt_user_unique_ips_current{user="hello"} 735
telemt_user_unique_ips_recent_window{user="hello"} 260
```