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

# Server Metrics 2026-03-14 12:02:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 188974.2 (52h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 745533
telemt_connections_bad_total 34944
telemt_handshake_timeouts_total 14410
telemt_upstream_connect_attempt_total 47978
telemt_upstream_connect_success_total 47740
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 47978
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25736
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6329
telemt_me_reconnect_attempts_total 43728
telemt_me_reconnect_success_total 37961
telemt_me_reader_eof_total 40587
telemt_me_idle_close_by_peer_total 40586
telemt_me_route_drop_no_conn_total 245691
telemt_me_route_drop_channel_closed_total 40
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 639805
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2714
telemt_desync_full_logged_total 904
telemt_desync_suppressed_total 1810
telemt_desync_frames_bucket_total{bucket="1_2"} 561
telemt_desync_frames_bucket_total{bucket="3_10"} 1021
telemt_desync_frames_bucket_total{bucket="gt_10"} 1132
telemt_pool_swap_total 171
telemt_me_writer_removed_unexpected_total 38548
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 37941
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 587
telemt_user_connections_total{user="hello"} 639711
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 17763292610 (16.54 GB)
telemt_user_octets_to_client{user="hello"} 307446225584 (286.33 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 188867.9 (52h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 369975
telemt_connections_bad_total 2847
telemt_handshake_timeouts_total 3339
telemt_upstream_connect_attempt_total 157428
telemt_upstream_connect_success_total 156038
telemt_upstream_connect_fail_total 1390
telemt_upstream_connect_attempts_per_request{bucket="1"} 157428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 113435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40089
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2513
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1390
telemt_me_keepalive_timeout_total 5697
telemt_me_reconnect_attempts_total 196483
telemt_me_reconnect_success_total 41854
telemt_me_reader_eof_total 47767
telemt_me_idle_close_by_peer_total 47767
telemt_me_route_drop_no_conn_total 127518
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 244747
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 47085
telemt_me_refill_failed_total 4824
telemt_me_writer_restored_same_endpoint_total 41836
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5231
telemt_user_connections_total{user="hello"} 349315
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 3544825357 (3.30 GB)
telemt_user_octets_to_client{user="hello"} 112671225488 (104.93 GB)
telemt_user_msgs_from_client{user="hello"} 1709928
telemt_user_msgs_to_client{user="hello"} 9557062
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 188831.9 (52h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 427447
telemt_connections_bad_total 3315
telemt_handshake_timeouts_total 36560
telemt_upstream_connect_attempt_total 50356
telemt_upstream_connect_success_total 50347
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 50356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27131
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4287
telemt_me_reconnect_attempts_total 42166
telemt_me_reconnect_success_total 40843
telemt_me_reader_eof_total 43881
telemt_me_idle_close_by_peer_total 43881
telemt_me_route_drop_no_conn_total 156299
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 372251
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 146
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 176
telemt_me_writer_removed_unexpected_total 41334
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 40822
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 491
telemt_user_connections_total{user="hello"} 372009
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 15807161186 (14.72 GB)
telemt_user_octets_to_client{user="hello"} 163075002679 (151.88 GB)
telemt_user_msgs_from_client{user="hello"} 166
telemt_user_msgs_to_client{user="hello"} 712
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 188807.2 (52h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 542872
telemt_connections_bad_total 16775
telemt_handshake_timeouts_total 5300
telemt_upstream_connect_attempt_total 80787
telemt_upstream_connect_success_total 70080
telemt_upstream_connect_fail_total 10706
telemt_upstream_connect_attempts_per_request{bucket="1"} 80786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28946
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 390
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10706
telemt_me_keepalive_timeout_total 5839
telemt_me_reconnect_attempts_total 156287
telemt_me_reconnect_success_total 41644
telemt_me_reader_eof_total 46555
telemt_me_idle_close_by_peer_total 46547
telemt_me_route_drop_no_conn_total 196461
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 465599
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2145
telemt_desync_full_logged_total 628
telemt_desync_suppressed_total 1517
telemt_desync_frames_bucket_total{bucket="1_2"} 500
telemt_desync_frames_bucket_total{bucket="3_10"} 813
telemt_desync_frames_bucket_total{bucket="gt_10"} 832
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 45704
telemt_me_refill_failed_total 3574
telemt_me_writer_restored_same_endpoint_total 41634
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4060
telemt_user_connections_total{user="hello"} 484465
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 10235800719 (9.53 GB)
telemt_user_octets_to_client{user="hello"} 197274375316 (183.73 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 138978.6 (38h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 235649
telemt_connections_bad_total 37810
telemt_handshake_timeouts_total 2148
telemt_upstream_connect_attempt_total 48894
telemt_upstream_connect_success_total 48401
telemt_upstream_connect_fail_total 493
telemt_upstream_connect_attempts_per_request{bucket="1"} 48894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 493
telemt_me_keepalive_timeout_total 3126
telemt_me_reconnect_attempts_total 53497
telemt_me_reconnect_success_total 36584
telemt_me_reader_eof_total 39133
telemt_me_idle_close_by_peer_total 39133
telemt_me_route_drop_no_conn_total 71381
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184519
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 808
telemt_desync_full_logged_total 195
telemt_desync_suppressed_total 613
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 379
telemt_desync_frames_bucket_total{bucket="gt_10"} 296
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 37459
telemt_me_refill_failed_total 524
telemt_me_writer_restored_same_endpoint_total 36566
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 875
telemt_user_connections_total{user="hello"} 189274
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 2755779493 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 86891080759 (80.92 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 188763.2 (52h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1100946
telemt_connections_bad_total 37679
telemt_handshake_timeouts_total 27201
telemt_upstream_connect_attempt_total 39352
telemt_upstream_connect_success_total 39146
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 39352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 5185
telemt_me_reconnect_attempts_total 34509
telemt_me_reconnect_success_total 29815
telemt_me_reader_eof_total 31970
telemt_me_idle_close_by_peer_total 31967
telemt_me_route_drop_no_conn_total 517634
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1021009
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 809
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 541
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 176
telemt_me_writer_removed_unexpected_total 30340
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 29808
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 525
telemt_user_connections_total{user="hello"} 993593
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 21283159636 (19.82 GB)
telemt_user_octets_to_client{user="hello"} 498021006752 (463.82 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 68
```