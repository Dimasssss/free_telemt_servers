# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

# Server Metrics 2026-03-20 05:28:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 43860.4 (12h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 840956
telemt_connections_bad_total 55469
telemt_connections_current 1381
telemt_connections_me_current 1381
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 19741
telemt_upstream_connect_attempt_total 8593
telemt_upstream_connect_success_total 8494
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 8593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3754
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5249
telemt_me_reconnect_success_total 5206
telemt_me_reader_eof_total 5514
telemt_me_idle_close_by_peer_total 5513
telemt_me_route_drop_no_conn_total 234156
telemt_me_route_drop_channel_closed_total 74
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 675734
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3588
telemt_desync_full_logged_total 1293
telemt_desync_suppressed_total 2295
telemt_desync_frames_bucket_total{bucket="1_2"} 689
telemt_desync_frames_bucket_total{bucket="3_10"} 1403
telemt_desync_frames_bucket_total{bucket="gt_10"} 1496
telemt_pool_swap_total 48
telemt_me_writer_close_signal_drop_total 44
telemt_me_writer_removed_unexpected_total 5257
telemt_me_writer_restored_same_endpoint_total 5193
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 677265
telemt_user_connections_current{user="hello"} 1381
telemt_user_octets_from_client{user="hello"} 32829339496 (30.57 GB)
telemt_user_octets_to_client{user="hello"} 230723202733 (214.88 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 500
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 60316.2 (16h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3758472
telemt_connections_bad_total 336668
telemt_connections_current 3703
telemt_connections_me_current 3703
telemt_handshake_timeouts_total 87847
telemt_upstream_connect_attempt_total 11364
telemt_upstream_connect_success_total 11157
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 11364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4794
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 11206
telemt_me_reconnect_success_total 6955
telemt_me_reader_eof_total 7440
telemt_me_idle_close_by_peer_total 7440
telemt_me_route_drop_no_conn_total 1680119
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3077206
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12632
telemt_desync_full_logged_total 4223
telemt_desync_suppressed_total 8409
telemt_desync_frames_bucket_total{bucket="1_2"} 2408
telemt_desync_frames_bucket_total{bucket="3_10"} 4884
telemt_desync_frames_bucket_total{bucket="gt_10"} 5340
telemt_pool_swap_total 54
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 57
telemt_me_writer_removed_unexpected_total 7172
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6900
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 217
telemt_user_connections_total{user="hello"} 3076921
telemt_user_connections_current{user="hello"} 3703
telemt_user_octets_from_client{user="hello"} 46548166434 (43.35 GB)
telemt_user_octets_to_client{user="hello"} 1168899547894 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1305
telemt_user_unique_ips_recent_window{user="hello"} 484
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 60294.5 (16h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3405795
telemt_connections_bad_total 496166
telemt_connections_current 3008
telemt_connections_me_current 3008
telemt_handshake_timeouts_total 53154
telemt_upstream_connect_attempt_total 9747
telemt_upstream_connect_success_total 9679
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 9747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7647
telemt_me_reconnect_success_total 6704
telemt_me_reader_eof_total 7062
telemt_me_idle_close_by_peer_total 7061
telemt_me_route_drop_no_conn_total 2054373
telemt_me_route_drop_channel_closed_total 183
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2394248
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8783
telemt_desync_full_logged_total 2713
telemt_desync_suppressed_total 6070
telemt_desync_frames_bucket_total{bucket="1_2"} 2184
telemt_desync_frames_bucket_total{bucket="3_10"} 3334
telemt_desync_frames_bucket_total{bucket="gt_10"} 3265
telemt_pool_swap_total 60
telemt_me_writer_close_signal_drop_total 76
telemt_me_writer_removed_unexpected_total 6776
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6703
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 2389287
telemt_user_connections_current{user="hello"} 3008
telemt_user_octets_from_client{user="hello"} 36191767128 (33.71 GB)
telemt_user_octets_to_client{user="hello"} 973358932376 (906.51 GB)
telemt_user_unique_ips_current{user="hello"} 1067
telemt_user_unique_ips_recent_window{user="hello"} 400
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 60281.9 (16h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3125226
telemt_connections_bad_total 230421
telemt_connections_current 2791
telemt_connections_me_current 2791
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 45556
telemt_upstream_connect_attempt_total 67121
telemt_upstream_connect_success_total 62423
telemt_upstream_connect_fail_total 4698
telemt_upstream_connect_attempts_per_request{bucket="1"} 67121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9438
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 711
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4698
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 10005
telemt_me_reconnect_success_total 7041
telemt_me_reader_eof_total 7338
telemt_me_idle_close_by_peer_total 7337
telemt_me_route_drop_no_conn_total 2164474
telemt_me_route_drop_channel_closed_total 69
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2541397
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9590
telemt_desync_full_logged_total 3052
telemt_desync_suppressed_total 6538
telemt_desync_frames_bucket_total{bucket="1_2"} 2274
telemt_desync_frames_bucket_total{bucket="3_10"} 3547
telemt_desync_frames_bucket_total{bucket="gt_10"} 3769
telemt_pool_swap_total 47
telemt_me_writer_close_signal_drop_total 674
telemt_me_writer_removed_unexpected_total 7752
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7037
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 711
telemt_user_connections_total{user="hello"} 2591787
telemt_user_connections_current{user="hello"} 2791
telemt_user_octets_from_client{user="hello"} 39878178912 (37.14 GB)
telemt_user_octets_to_client{user="hello"} 770351369575 (717.45 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 991
telemt_user_unique_ips_recent_window{user="hello"} 358
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 114005.2 (31h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6856258
telemt_connections_bad_total 1196589
telemt_connections_current 3448
telemt_connections_me_current 3448
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 121153
telemt_upstream_connect_attempt_total 129731
telemt_upstream_connect_success_total 96429
telemt_upstream_connect_fail_total 33302
telemt_upstream_connect_attempts_per_request{bucket="1"} 129731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13560
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33302
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 80128
telemt_me_reconnect_success_total 14448
telemt_me_reader_eof_total 15546
telemt_me_idle_close_by_peer_total 15532
telemt_me_route_drop_no_conn_total 2943822
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4843186
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 21003
telemt_desync_full_logged_total 6687
telemt_desync_suppressed_total 14316
telemt_desync_frames_bucket_total{bucket="1_2"} 3734
telemt_desync_frames_bucket_total{bucket="3_10"} 8685
telemt_desync_frames_bucket_total{bucket="gt_10"} 8584
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 14779
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 14423
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 331
telemt_user_connections_total{user="hello"} 4918199
telemt_user_connections_current{user="hello"} 3448
telemt_user_octets_from_client{user="hello"} 78027852744 (72.67 GB)
telemt_user_octets_to_client{user="hello"} 1947390877032 (1.77 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 1172
telemt_user_unique_ips_recent_window{user="hello"} 437
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 60245.2 (16h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1595430
telemt_connections_bad_total 103949
telemt_connections_current 645
telemt_connections_me_current 645
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 14470
telemt_upstream_connect_attempt_total 13771
telemt_upstream_connect_success_total 13441
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 58
telemt_me_keepalive_timeout_total 546
telemt_me_reconnect_attempts_total 6736
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7008
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 473648
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585597
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1548
telemt_desync_full_logged_total 578
telemt_desync_suppressed_total 970
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 695
telemt_desync_frames_bucket_total{bucket="gt_10"} 617
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6689
telemt_me_writer_restored_same_endpoint_total 6618
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 1415804
telemt_user_connections_current{user="hello"} 645
telemt_user_octets_from_client{user="hello"} 9155210347 (8.53 GB)
telemt_user_octets_to_client{user="hello"} 146633294638 (136.56 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 205
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 60246.6 (16h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2455628
telemt_connections_bad_total 154623
telemt_connections_current 3034
telemt_connections_me_current 3034
telemt_handshake_timeouts_total 44714
telemt_upstream_connect_attempt_total 10761
telemt_upstream_connect_success_total 10694
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 10761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7762
telemt_me_reconnect_success_total 7712
telemt_me_reader_eof_total 8152
telemt_me_idle_close_by_peer_total 8152
telemt_me_route_drop_no_conn_total 859874
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2061547
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10497
telemt_desync_full_logged_total 3409
telemt_desync_suppressed_total 7088
telemt_desync_frames_bucket_total{bucket="1_2"} 2037
telemt_desync_frames_bucket_total{bucket="3_10"} 3701
telemt_desync_frames_bucket_total{bucket="gt_10"} 4759
telemt_pool_swap_total 61
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 7820
telemt_me_writer_restored_same_endpoint_total 7695
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 2060244
telemt_user_connections_current{user="hello"} 3034
telemt_user_octets_from_client{user="hello"} 43960710600 (40.94 GB)
telemt_user_octets_to_client{user="hello"} 1089655102148 (1014.82 GB)
telemt_user_unique_ips_current{user="hello"} 1001
telemt_user_unique_ips_recent_window{user="hello"} 348
```