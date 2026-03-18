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

# Server Metrics 2026-03-18 23:24:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 5773.6 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68418
telemt_connections_bad_total 6759
telemt_connections_current 616
telemt_connections_me_current 616
telemt_handshake_timeouts_total 742
telemt_upstream_connect_attempt_total 1066
telemt_upstream_connect_success_total 1051
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 1066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 550
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 731
telemt_me_reconnect_success_total 729
telemt_me_reader_eof_total 741
telemt_me_idle_close_by_peer_total 741
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 23887
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59876
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 308
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 202
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 131
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 726
telemt_me_writer_restored_same_endpoint_total 718
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 57120
telemt_user_connections_current{user="hello"} 616
telemt_user_octets_from_client{user="hello"} 590729100 (563.36 MB)
telemt_user_octets_to_client{user="hello"} 24634227976 (22.94 GB)
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 5776.8 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160763
telemt_connections_bad_total 12882
telemt_connections_current 1652
telemt_connections_me_current 1652
telemt_handshake_timeouts_total 1291
telemt_upstream_connect_attempt_total 1117
telemt_upstream_connect_success_total 1088
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 1117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 554
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 761
telemt_me_reconnect_success_total 760
telemt_me_reader_eof_total 786
telemt_me_idle_close_by_peer_total 786
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 50295
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137922
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 537
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 353
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 193
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 774
telemt_me_writer_restored_same_endpoint_total 749
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 138004
telemt_user_connections_current{user="hello"} 1652
telemt_user_octets_from_client{user="hello"} 10040493224 (9.35 GB)
telemt_user_octets_to_client{user="hello"} 53180806092 (49.53 GB)
telemt_user_unique_ips_current{user="hello"} 649
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 5774.1 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126292
telemt_connections_bad_total 18609
telemt_connections_current 1117
telemt_connections_me_current 1117
telemt_handshake_timeouts_total 3640
telemt_upstream_connect_attempt_total 1133
telemt_upstream_connect_success_total 1133
telemt_upstream_connect_attempts_per_request{bucket="1"} 1133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 547
telemt_me_reconnect_attempts_total 807
telemt_me_reconnect_success_total 806
telemt_me_reader_eof_total 829
telemt_me_idle_close_by_peer_total 829
telemt_me_route_drop_no_conn_total 43423
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100583
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 434
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 262
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 181
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 815
telemt_me_writer_restored_same_endpoint_total 790
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 100585
telemt_user_connections_current{user="hello"} 1117
telemt_user_octets_from_client{user="hello"} 1366518984 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 63792691056 (59.41 GB)
telemt_user_unique_ips_current{user="hello"} 501
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 5827.4 (1h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139027
telemt_connections_bad_total 23584
telemt_connections_current 1023
telemt_connections_me_current 1023
telemt_handshake_timeouts_total 2982
telemt_upstream_connect_attempt_total 1043
telemt_upstream_connect_success_total 1043
telemt_upstream_connect_attempts_per_request{bucket="1"} 1043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 720
telemt_me_reconnect_success_total 717
telemt_me_reader_eof_total 734
telemt_me_idle_close_by_peer_total 734
telemt_me_route_drop_no_conn_total 56171
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106236
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 266
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 169
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 108
telemt_desync_frames_bucket_total{bucket="gt_10"} 105
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 728
telemt_me_writer_restored_same_endpoint_total 693
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 106165
telemt_user_connections_current{user="hello"} 1023
telemt_user_octets_from_client{user="hello"} 1094560320 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 39482396288 (36.77 GB)
telemt_user_unique_ips_current{user="hello"} 424
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 5770.9 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137799
telemt_connections_bad_total 6237
telemt_connections_current 1314
telemt_connections_me_current 1314
telemt_handshake_timeouts_total 4338
telemt_upstream_connect_attempt_total 1069
telemt_upstream_connect_success_total 1062
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1069
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 524
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 735
telemt_me_reconnect_success_total 732
telemt_me_reader_eof_total 746
telemt_me_idle_close_by_peer_total 746
telemt_me_route_drop_no_conn_total 41317
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109004
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 482
telemt_desync_full_logged_total 191
telemt_desync_suppressed_total 291
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 187
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 734
telemt_me_writer_restored_same_endpoint_total 708
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 108962
telemt_user_connections_current{user="hello"} 1314
telemt_user_octets_from_client{user="hello"} 1411880668 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 66035013808 (61.50 GB)
telemt_user_unique_ips_current{user="hello"} 564
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 5782.3 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31902
telemt_connections_bad_total 6205
telemt_connections_current 344
telemt_connections_me_current 344
telemt_handshake_timeouts_total 86
telemt_upstream_connect_attempt_total 1822
telemt_upstream_connect_success_total 1767
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 1822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 814
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 3270
telemt_me_reconnect_success_total 1444
telemt_me_reader_eof_total 1472
telemt_me_idle_close_by_peer_total 1472
telemt_me_route_drop_no_conn_total 10884
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24878
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1475
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 1414
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 24879
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 309540496 (295.20 MB)
telemt_user_octets_to_client{user="hello"} 19757854728 (18.40 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 5773.2 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102566
telemt_connections_bad_total 13657
telemt_connections_current 1167
telemt_connections_me_current 1167
telemt_handshake_timeouts_total 3416
telemt_upstream_connect_attempt_total 1095
telemt_upstream_connect_success_total 1095
telemt_upstream_connect_attempts_per_request{bucket="1"} 1095
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 520
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 768
telemt_me_reconnect_success_total 766
telemt_me_reader_eof_total 787
telemt_me_idle_close_by_peer_total 787
telemt_me_route_drop_no_conn_total 31053
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83304
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 611
telemt_desync_full_logged_total 234
telemt_desync_suppressed_total 377
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 776
telemt_me_writer_restored_same_endpoint_total 751
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 83330
telemt_user_connections_current{user="hello"} 1167
telemt_user_octets_from_client{user="hello"} 885299104 (844.29 MB)
telemt_user_octets_to_client{user="hello"} 47372762704 (44.12 GB)
telemt_user_unique_ips_current{user="hello"} 482
telemt_user_unique_ips_recent_window{user="hello"} 105
```