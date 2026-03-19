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

# Server Metrics 2026-03-19 07:55:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 36439.2 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 656522
telemt_connections_bad_total 68382
telemt_connections_current 1603
telemt_connections_me_current 1603
telemt_handshake_timeouts_total 24370
telemt_upstream_connect_attempt_total 6956
telemt_upstream_connect_success_total 6829
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 6956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3513
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 6151
telemt_me_reconnect_success_total 5001
telemt_me_reader_eof_total 5312
telemt_me_idle_close_by_peer_total 5311
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 186200
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 498079
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3340
telemt_desync_full_logged_total 946
telemt_desync_suppressed_total 2394
telemt_desync_frames_bucket_total{bucket="1_2"} 1181
telemt_desync_frames_bucket_total{bucket="3_10"} 1248
telemt_desync_frames_bucket_total{bucket="gt_10"} 911
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5095
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 4984
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 495165
telemt_user_connections_current{user="hello"} 1603
telemt_user_octets_from_client{user="hello"} 6511505600 (6.06 GB)
telemt_user_octets_to_client{user="hello"} 165337419312 (153.98 GB)
telemt_user_unique_ips_current{user="hello"} 523
telemt_user_unique_ips_recent_window{user="hello"} 278
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 36443.1 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1568761
telemt_connections_bad_total 89568
telemt_connections_current 3943
telemt_connections_me_current 3943
telemt_handshake_timeouts_total 37594
telemt_upstream_connect_attempt_total 6891
telemt_upstream_connect_success_total 6761
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 6891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 6073
telemt_me_reconnect_success_total 4918
telemt_me_reader_eof_total 5209
telemt_me_idle_close_by_peer_total 5209
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 650855
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1290256
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5869
telemt_desync_full_logged_total 1956
telemt_desync_suppressed_total 3913
telemt_desync_frames_bucket_total{bucket="1_2"} 1038
telemt_desync_frames_bucket_total{bucket="3_10"} 2232
telemt_desync_frames_bucket_total{bucket="gt_10"} 2599
telemt_pool_swap_total 29
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5044
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 4897
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 1290098
telemt_user_connections_current{user="hello"} 3943
telemt_user_octets_from_client{user="hello"} 23178410596 (21.59 GB)
telemt_user_octets_to_client{user="hello"} 506423399132 (471.64 GB)
telemt_user_unique_ips_current{user="hello"} 1364
telemt_user_unique_ips_recent_window{user="hello"} 648
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 36440.6 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1334476
telemt_connections_bad_total 185715
telemt_connections_current 2972
telemt_connections_me_current 2972
telemt_handshake_timeouts_total 35308
telemt_upstream_connect_attempt_total 6503
telemt_upstream_connect_success_total 6503
telemt_upstream_connect_attempts_per_request{bucket="1"} 6503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3134
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 4690
telemt_me_reconnect_success_total 4665
telemt_me_reader_eof_total 4944
telemt_me_idle_close_by_peer_total 4944
telemt_me_route_drop_no_conn_total 559450
telemt_me_route_drop_channel_closed_total 46
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1008055
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4776
telemt_desync_full_logged_total 1473
telemt_desync_suppressed_total 3303
telemt_desync_frames_bucket_total{bucket="1_2"} 1018
telemt_desync_frames_bucket_total{bucket="3_10"} 1721
telemt_desync_frames_bucket_total{bucket="gt_10"} 2037
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 4752
telemt_me_writer_restored_same_endpoint_total 4649
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 1007657
telemt_user_connections_current{user="hello"} 2972
telemt_user_octets_from_client{user="hello"} 17797245960 (16.57 GB)
telemt_user_octets_to_client{user="hello"} 509458926448 (474.47 GB)
telemt_user_unique_ips_current{user="hello"} 1026
telemt_user_unique_ips_recent_window{user="hello"} 441
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 36493.7 (10h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1368124
telemt_connections_bad_total 91190
telemt_connections_current 2922
telemt_connections_me_current 2922
telemt_handshake_timeouts_total 33675
telemt_upstream_connect_attempt_total 6471
telemt_upstream_connect_success_total 6471
telemt_upstream_connect_attempts_per_request{bucket="1"} 6471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3179
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5679
telemt_me_reconnect_success_total 4616
telemt_me_reader_eof_total 4892
telemt_me_idle_close_by_peer_total 4891
telemt_me_route_drop_no_conn_total 518829
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 951130
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3594
telemt_desync_full_logged_total 1239
telemt_desync_suppressed_total 2355
telemt_desync_frames_bucket_total{bucket="1_2"} 703
telemt_desync_frames_bucket_total{bucket="3_10"} 1410
telemt_desync_frames_bucket_total{bucket="gt_10"} 1481
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 4714
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4592
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 949901
telemt_user_connections_current{user="hello"} 2922
telemt_user_octets_from_client{user="hello"} 13178252056 (12.27 GB)
telemt_user_octets_to_client{user="hello"} 328295279176 (305.75 GB)
telemt_user_unique_ips_current{user="hello"} 1002
telemt_user_unique_ips_recent_window{user="hello"} 439
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 36436.8 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1656125
telemt_connections_bad_total 439139
telemt_connections_current 3192
telemt_connections_me_current 3192
telemt_handshake_timeouts_total 35286
telemt_upstream_connect_attempt_total 6352
telemt_upstream_connect_success_total 6311
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 6352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3093
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_reconnect_attempts_total 4510
telemt_me_reconnect_success_total 4477
telemt_me_reader_eof_total 4748
telemt_me_idle_close_by_peer_total 4748
telemt_me_route_drop_no_conn_total 418005
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1007565
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4868
telemt_desync_full_logged_total 1510
telemt_desync_suppressed_total 3358
telemt_desync_frames_bucket_total{bucket="1_2"} 1044
telemt_desync_frames_bucket_total{bucket="3_10"} 2211
telemt_desync_frames_bucket_total{bucket="gt_10"} 1613
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 4537
telemt_me_writer_restored_same_endpoint_total 4453
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1007223
telemt_user_connections_current{user="hello"} 3192
telemt_user_octets_from_client{user="hello"} 20939517260 (19.50 GB)
telemt_user_octets_to_client{user="hello"} 484314268336 (451.05 GB)
telemt_user_unique_ips_current{user="hello"} 1139
telemt_user_unique_ips_recent_window{user="hello"} 548
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 36448.7 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280365
telemt_connections_bad_total 13931
telemt_connections_current 890
telemt_connections_me_current 890
telemt_handshake_timeouts_total 2666
telemt_upstream_connect_attempt_total 9480
telemt_upstream_connect_success_total 9234
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 9480
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4695
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 12773
telemt_me_reconnect_success_total 7397
telemt_me_reader_eof_total 7858
telemt_me_idle_close_by_peer_total 7858
telemt_me_route_drop_no_conn_total 131097
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 249472
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 373
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 248
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 156
telemt_desync_frames_bucket_total{bucket="gt_10"} 107
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 7614
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 7367
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 217
telemt_user_connections_total{user="hello"} 249439
telemt_user_connections_current{user="hello"} 890
telemt_user_octets_from_client{user="hello"} 3740684576 (3.48 GB)
telemt_user_octets_to_client{user="hello"} 118636387356 (110.49 GB)
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 36439.4 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1057965
telemt_connections_bad_total 94832
telemt_connections_current 2870
telemt_connections_me_current 2870
telemt_handshake_timeouts_total 47610
telemt_upstream_connect_attempt_total 7354
telemt_upstream_connect_success_total 7354
telemt_upstream_connect_attempts_per_request{bucket="1"} 7354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3432
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 6855
telemt_me_reconnect_success_total 5518
telemt_me_reader_eof_total 5860
telemt_me_idle_close_by_peer_total 5860
telemt_me_route_drop_no_conn_total 418459
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 875326
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5217
telemt_desync_full_logged_total 1726
telemt_desync_suppressed_total 3491
telemt_desync_frames_bucket_total{bucket="1_2"} 1032
telemt_desync_frames_bucket_total{bucket="3_10"} 2001
telemt_desync_frames_bucket_total{bucket="gt_10"} 2184
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 5621
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 5503
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 874363
telemt_user_connections_current{user="hello"} 2870
telemt_user_octets_from_client{user="hello"} 12873413272 (11.99 GB)
telemt_user_octets_to_client{user="hello"} 467751797020 (435.63 GB)
telemt_user_unique_ips_current{user="hello"} 958
telemt_user_unique_ips_recent_window{user="hello"} 418
```