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

# Server Metrics 2026-03-19 18:37:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 4812.0 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153652
telemt_connections_bad_total 5045
telemt_connections_current 1501
telemt_connections_me_current 1501
telemt_handshake_timeouts_total 1603
telemt_upstream_connect_attempt_total 735
telemt_upstream_connect_success_total 722
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 353
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 440
telemt_me_reconnect_success_total 438
telemt_me_reader_eof_total 447
telemt_me_idle_close_by_peer_total 447
telemt_me_route_drop_no_conn_total 48518
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 126170
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 576
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 386
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 173
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 453
telemt_me_writer_restored_same_endpoint_total 425
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 126444
telemt_user_connections_current{user="hello"} 1501
telemt_user_octets_from_client{user="hello"} 1980790524 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 42742390816 (39.81 GB)
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 21267.9 (5h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2091079
telemt_connections_bad_total 99113
telemt_connections_current 3837
telemt_connections_me_current 3837
telemt_handshake_timeouts_total 39148
telemt_upstream_connect_attempt_total 4842
telemt_upstream_connect_success_total 4776
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 4842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1589
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6678
telemt_me_reconnect_success_total 2452
telemt_me_reader_eof_total 2648
telemt_me_idle_close_by_peer_total 2648
telemt_me_route_drop_no_conn_total 1183163
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1746567
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7067
telemt_desync_full_logged_total 2246
telemt_desync_suppressed_total 4821
telemt_desync_frames_bucket_total{bucket="1_2"} 1328
telemt_desync_frames_bucket_total{bucket="3_10"} 2812
telemt_desync_frames_bucket_total{bucket="gt_10"} 2927
telemt_pool_swap_total 14
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 2599
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2397
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 1746522
telemt_user_connections_current{user="hello"} 3837
telemt_user_octets_from_client{user="hello"} 25294923926 (23.56 GB)
telemt_user_octets_to_client{user="hello"} 573385449638 (534.01 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1299
telemt_user_unique_ips_recent_window{user="hello"} 534
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 21246.1 (5h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1909973
telemt_connections_bad_total 224072
telemt_connections_current 2932
telemt_connections_me_current 2932
telemt_handshake_timeouts_total 21744
telemt_upstream_connect_attempt_total 3351
telemt_upstream_connect_success_total 3327
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 3351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1547
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3151
telemt_me_reconnect_success_total 2233
telemt_me_reader_eof_total 2281
telemt_me_idle_close_by_peer_total 2280
telemt_me_route_drop_no_conn_total 1675724
telemt_me_route_drop_channel_closed_total 103
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1454719
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4798
telemt_desync_full_logged_total 1436
telemt_desync_suppressed_total 3362
telemt_desync_frames_bucket_total{bucket="1_2"} 1225
telemt_desync_frames_bucket_total{bucket="3_10"} 1810
telemt_desync_frames_bucket_total{bucket="gt_10"} 1763
telemt_pool_swap_total 17
telemt_me_writer_close_signal_drop_total 50
telemt_me_writer_removed_unexpected_total 2228
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2232
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1451457
telemt_user_connections_current{user="hello"} 2932
telemt_user_octets_from_client{user="hello"} 19028652000 (17.72 GB)
telemt_user_octets_to_client{user="hello"} 465755931632 (433.77 GB)
telemt_user_unique_ips_current{user="hello"} 981
telemt_user_unique_ips_recent_window{user="hello"} 362
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 21233.7 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1793205
telemt_connections_bad_total 59938
telemt_connections_current 2923
telemt_connections_me_current 2923
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 23969
telemt_upstream_connect_attempt_total 25330
telemt_upstream_connect_success_total 24149
telemt_upstream_connect_fail_total 1181
telemt_upstream_connect_attempts_per_request{bucket="1"} 25330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4028
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1181
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5001
telemt_me_reconnect_success_total 2627
telemt_me_reader_eof_total 2718
telemt_me_idle_close_by_peer_total 2717
telemt_me_route_drop_no_conn_total 1572962
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1547954
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6055
telemt_desync_full_logged_total 1885
telemt_desync_suppressed_total 4170
telemt_desync_frames_bucket_total{bucket="1_2"} 1596
telemt_desync_frames_bucket_total{bucket="3_10"} 2226
telemt_desync_frames_bucket_total{bucket="gt_10"} 2233
telemt_pool_swap_total 9
telemt_me_writer_close_signal_drop_total 200
telemt_me_writer_removed_unexpected_total 3037
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2623
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 410
telemt_user_connections_total{user="hello"} 1567288
telemt_user_connections_current{user="hello"} 2923
telemt_user_octets_from_client{user="hello"} 27083102245 (25.22 GB)
telemt_user_octets_to_client{user="hello"} 341336066101 (317.89 GB)
telemt_user_msgs_from_client{user="hello"} 49930
telemt_user_msgs_to_client{user="hello"} 93819
telemt_user_unique_ips_current{user="hello"} 953
telemt_user_unique_ips_recent_window{user="hello"} 398
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 74958.4 (20h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5480561
telemt_connections_bad_total 1007051
telemt_connections_current 3292
telemt_connections_me_current 3292
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 100145
telemt_upstream_connect_attempt_total 64964
telemt_upstream_connect_success_total 62471
telemt_upstream_connect_fail_total 2493
telemt_upstream_connect_attempts_per_request{bucket="1"} 64964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8430
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1049
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2493
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 74932
telemt_me_reconnect_success_total 9523
telemt_me_reader_eof_total 10040
telemt_me_idle_close_by_peer_total 10037
telemt_me_route_drop_no_conn_total 2516119
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3803421
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
telemt_desync_total 16627
telemt_desync_full_logged_total 5096
telemt_desync_suppressed_total 11531
telemt_desync_frames_bucket_total{bucket="1_2"} 2760
telemt_desync_frames_bucket_total{bucket="3_10"} 6916
telemt_desync_frames_bucket_total{bucket="gt_10"} 6951
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 9768
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9499
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 3851555
telemt_user_connections_current{user="hello"} 3292
telemt_user_octets_from_client{user="hello"} 60270513291 (56.13 GB)
telemt_user_octets_to_client{user="hello"} 1415495800096 (1.29 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1126
telemt_user_unique_ips_recent_window{user="hello"} 456
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 21197.4 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 499842
telemt_connections_bad_total 35569
telemt_connections_current 646
telemt_connections_me_current 646
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 10204
telemt_upstream_connect_attempt_total 7157
telemt_upstream_connect_success_total 6960
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 7157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3997
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 548
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 424
telemt_me_reconnect_attempts_total 2930
telemt_me_reconnect_success_total 2873
telemt_me_reader_eof_total 2947
telemt_me_idle_close_by_peer_total 2946
telemt_me_route_drop_no_conn_total 356808
telemt_me_route_drop_channel_closed_total 123
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 394531
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
telemt_desync_total 1048
telemt_desync_full_logged_total 334
telemt_desync_suppressed_total 714
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 428
telemt_desync_frames_bucket_total{bucket="gt_10"} 453
telemt_pool_swap_total 13
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 131
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 2891
telemt_me_writer_restored_same_endpoint_total 2864
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 413184
telemt_user_connections_current{user="hello"} 646
telemt_user_octets_from_client{user="hello"} 4747289264 (4.42 GB)
telemt_user_octets_to_client{user="hello"} 86830799810 (80.87 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 21198.1 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1391565
telemt_connections_bad_total 88157
telemt_connections_current 3017
telemt_connections_me_current 3017
telemt_handshake_timeouts_total 24626
telemt_upstream_connect_attempt_total 3507
telemt_upstream_connect_success_total 3481
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1610
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 2406
telemt_me_reconnect_success_total 2380
telemt_me_reader_eof_total 2496
telemt_me_idle_close_by_peer_total 2496
telemt_me_route_drop_no_conn_total 535771
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1203410
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6407
telemt_desync_full_logged_total 1963
telemt_desync_suppressed_total 4444
telemt_desync_frames_bucket_total{bucket="1_2"} 1238
telemt_desync_frames_bucket_total{bucket="3_10"} 2238
telemt_desync_frames_bucket_total{bucket="gt_10"} 2931
telemt_pool_swap_total 18
telemt_me_writer_close_signal_drop_total 31
telemt_me_writer_removed_unexpected_total 2429
telemt_me_writer_restored_same_endpoint_total 2363
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 1202704
telemt_user_connections_current{user="hello"} 3017
telemt_user_octets_from_client{user="hello"} 18847837512 (17.55 GB)
telemt_user_octets_to_client{user="hello"} 531148652376 (494.67 GB)
telemt_user_unique_ips_current{user="hello"} 982
telemt_user_unique_ips_recent_window{user="hello"} 382
```