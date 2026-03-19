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

# Server Metrics 2026-03-19 04:41:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 24790.3 (6h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 343930
telemt_connections_bad_total 36150
telemt_connections_current 920
telemt_connections_me_current 920
telemt_handshake_timeouts_total 19924
telemt_upstream_connect_attempt_total 4866
telemt_upstream_connect_success_total 4786
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 4866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2446
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3558
telemt_me_reconnect_success_total 3541
telemt_me_reader_eof_total 3730
telemt_me_idle_close_by_peer_total 3729
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 87983
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 251359
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1771
telemt_desync_full_logged_total 480
telemt_desync_suppressed_total 1291
telemt_desync_frames_bucket_total{bucket="1_2"} 659
telemt_desync_frames_bucket_total{bucket="3_10"} 717
telemt_desync_frames_bucket_total{bucket="gt_10"} 395
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 3569
telemt_me_writer_restored_same_endpoint_total 3524
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 248610
telemt_user_connections_current{user="hello"} 920
telemt_user_octets_from_client{user="hello"} 2805227996 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 75245634004 (70.08 GB)
telemt_user_unique_ips_current{user="hello"} 362
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 24794.5 (6h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 640717
telemt_connections_bad_total 39696
telemt_connections_current 2556
telemt_connections_me_current 2556
telemt_handshake_timeouts_total 19002
telemt_upstream_connect_attempt_total 4682
telemt_upstream_connect_success_total 4597
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 4682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2372
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_reconnect_attempts_total 3361
telemt_me_reconnect_success_total 3344
telemt_me_reader_eof_total 3525
telemt_me_idle_close_by_peer_total 3525
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 193108
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 530405
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2050
telemt_desync_full_logged_total 693
telemt_desync_suppressed_total 1357
telemt_desync_frames_bucket_total{bucket="1_2"} 407
telemt_desync_frames_bucket_total{bucket="3_10"} 744
telemt_desync_frames_bucket_total{bucket="gt_10"} 899
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3401
telemt_me_writer_restored_same_endpoint_total 3326
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 530343
telemt_user_connections_current{user="hello"} 2556
telemt_user_octets_from_client{user="hello"} 14833985924 (13.82 GB)
telemt_user_octets_to_client{user="hello"} 232278156040 (216.33 GB)
telemt_user_unique_ips_current{user="hello"} 947
telemt_user_unique_ips_recent_window{user="hello"} 318
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 24791.7 (6h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 542653
telemt_connections_bad_total 106757
telemt_connections_current 2156
telemt_connections_me_current 2156
telemt_handshake_timeouts_total 17928
telemt_upstream_connect_attempt_total 4581
telemt_upstream_connect_success_total 4581
telemt_upstream_connect_attempts_per_request{bucket="1"} 4581
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2250
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3341
telemt_me_reconnect_success_total 3330
telemt_me_reader_eof_total 3526
telemt_me_idle_close_by_peer_total 3526
telemt_me_route_drop_no_conn_total 159978
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 388921
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1980
telemt_desync_full_logged_total 688
telemt_desync_suppressed_total 1292
telemt_desync_frames_bucket_total{bucket="1_2"} 324
telemt_desync_frames_bucket_total{bucket="3_10"} 747
telemt_desync_frames_bucket_total{bucket="gt_10"} 909
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 3385
telemt_me_writer_restored_same_endpoint_total 3314
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 388928
telemt_user_connections_current{user="hello"} 2156
telemt_user_octets_from_client{user="hello"} 8556659268 (7.97 GB)
telemt_user_octets_to_client{user="hello"} 245776580964 (228.90 GB)
telemt_user_unique_ips_current{user="hello"} 766
telemt_user_unique_ips_recent_window{user="hello"} 272
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 24844.7 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 640889
telemt_connections_bad_total 79793
telemt_connections_current 1631
telemt_connections_me_current 1631
telemt_handshake_timeouts_total 13860
telemt_upstream_connect_attempt_total 4443
telemt_upstream_connect_success_total 4443
telemt_upstream_connect_attempts_per_request{bucket="1"} 4443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2192
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 3209
telemt_me_reconnect_success_total 3195
telemt_me_reader_eof_total 3370
telemt_me_idle_close_by_peer_total 3369
telemt_me_route_drop_no_conn_total 160317
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 385128
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1182
telemt_desync_full_logged_total 427
telemt_desync_suppressed_total 755
telemt_desync_frames_bucket_total{bucket="1_2"} 226
telemt_desync_frames_bucket_total{bucket="3_10"} 503
telemt_desync_frames_bucket_total{bucket="gt_10"} 453
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 3233
telemt_me_writer_restored_same_endpoint_total 3171
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 384890
telemt_user_connections_current{user="hello"} 1631
telemt_user_octets_from_client{user="hello"} 4608213380 (4.29 GB)
telemt_user_octets_to_client{user="hello"} 148809979456 (138.59 GB)
telemt_user_unique_ips_current{user="hello"} 620
telemt_user_unique_ips_recent_window{user="hello"} 228
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 24788.3 (6h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 705314
telemt_connections_bad_total 191089
telemt_connections_current 1991
telemt_connections_me_current 1991
telemt_handshake_timeouts_total 19812
telemt_upstream_connect_attempt_total 4591
telemt_upstream_connect_success_total 4562
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 4591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 3326
telemt_me_reconnect_success_total 3306
telemt_me_reader_eof_total 3494
telemt_me_idle_close_by_peer_total 3494
telemt_me_route_drop_no_conn_total 175192
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 418605
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1844
telemt_desync_full_logged_total 706
telemt_desync_suppressed_total 1138
telemt_desync_frames_bucket_total{bucket="1_2"} 434
telemt_desync_frames_bucket_total{bucket="3_10"} 778
telemt_desync_frames_bucket_total{bucket="gt_10"} 632
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3338
telemt_me_writer_restored_same_endpoint_total 3282
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 418519
telemt_user_connections_current{user="hello"} 1991
telemt_user_octets_from_client{user="hello"} 12074862816 (11.25 GB)
telemt_user_octets_to_client{user="hello"} 245494568800 (228.63 GB)
telemt_user_unique_ips_current{user="hello"} 780
telemt_user_unique_ips_recent_window{user="hello"} 269
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 24799.7 (6h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125306
telemt_connections_bad_total 10275
telemt_connections_current 532
telemt_connections_me_current 532
telemt_handshake_timeouts_total 573
telemt_upstream_connect_attempt_total 6857
telemt_upstream_connect_success_total 6674
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 6857
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3519
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_reconnect_attempts_total 7266
telemt_me_reconnect_success_total 5423
telemt_me_reader_eof_total 5702
telemt_me_idle_close_by_peer_total 5702
telemt_me_route_drop_no_conn_total 51397
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109894
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 76
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 5497
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 5393
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 109886
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 1995943948 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 70228896752 (65.41 GB)
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 24790.6 (6h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 412884
telemt_connections_bad_total 46711
telemt_connections_current 1758
telemt_connections_me_current 1758
telemt_handshake_timeouts_total 21364
telemt_upstream_connect_attempt_total 5148
telemt_upstream_connect_success_total 5148
telemt_upstream_connect_attempts_per_request{bucket="1"} 5148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2416
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3913
telemt_me_reconnect_success_total 3902
telemt_me_reader_eof_total 4117
telemt_me_idle_close_by_peer_total 4117
telemt_me_route_drop_no_conn_total 116394
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 332172
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1724
telemt_desync_full_logged_total 658
telemt_desync_suppressed_total 1066
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 669
telemt_desync_frames_bucket_total{bucket="gt_10"} 701
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 3943
telemt_me_writer_restored_same_endpoint_total 3887
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 332187
telemt_user_connections_current{user="hello"} 1758
telemt_user_octets_from_client{user="hello"} 4057227372 (3.78 GB)
telemt_user_octets_to_client{user="hello"} 192998241812 (179.74 GB)
telemt_user_unique_ips_current{user="hello"} 616
telemt_user_unique_ips_recent_window{user="hello"} 163
```