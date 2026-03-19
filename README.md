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

# Server Metrics 2026-03-19 19:03:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 6345.8 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207400
telemt_connections_bad_total 7739
telemt_connections_current 1366
telemt_connections_me_current 1366
telemt_handshake_timeouts_total 2172
telemt_upstream_connect_attempt_total 912
telemt_upstream_connect_success_total 899
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 912
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 453
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 564
telemt_me_reconnect_success_total 560
telemt_me_reader_eof_total 576
telemt_me_idle_close_by_peer_total 576
telemt_me_route_drop_no_conn_total 63542
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161141
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 720
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 482
telemt_desync_frames_bucket_total{bucket="1_2"} 161
telemt_desync_frames_bucket_total{bucket="3_10"} 215
telemt_desync_frames_bucket_total{bucket="gt_10"} 344
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 579
telemt_me_writer_restored_same_endpoint_total 547
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 161355
telemt_user_connections_current{user="hello"} 1366
telemt_user_octets_from_client{user="hello"} 2484796608 (2.31 GB)
telemt_user_octets_to_client{user="hello"} 53924246872 (50.22 GB)
telemt_user_unique_ips_current{user="hello"} 429
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 22801.4 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2207830
telemt_connections_bad_total 101714
telemt_connections_current 3873
telemt_connections_me_current 3873
telemt_handshake_timeouts_total 41691
telemt_upstream_connect_attempt_total 5083
telemt_upstream_connect_success_total 5017
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 5083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3279
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1702
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6832
telemt_me_reconnect_success_total 2607
telemt_me_reader_eof_total 2813
telemt_me_idle_close_by_peer_total 2813
telemt_me_route_drop_no_conn_total 1229362
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1852954
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7596
telemt_desync_full_logged_total 2431
telemt_desync_suppressed_total 5165
telemt_desync_frames_bucket_total{bucket="1_2"} 1424
telemt_desync_frames_bucket_total{bucket="3_10"} 3008
telemt_desync_frames_bucket_total{bucket="gt_10"} 3164
telemt_pool_swap_total 16
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 2754
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2552
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 1852902
telemt_user_connections_current{user="hello"} 3873
telemt_user_octets_from_client{user="hello"} 27077808130 (25.22 GB)
telemt_user_octets_to_client{user="hello"} 614828791734 (572.60 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1320
telemt_user_unique_ips_recent_window{user="hello"} 544
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 22779.7 (6h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2011007
telemt_connections_bad_total 241375
telemt_connections_current 2787
telemt_connections_me_current 2787
telemt_handshake_timeouts_total 23346
telemt_upstream_connect_attempt_total 3590
telemt_upstream_connect_success_total 3565
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 3590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1669
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3301
telemt_me_reconnect_success_total 2383
telemt_me_reader_eof_total 2443
telemt_me_idle_close_by_peer_total 2442
telemt_me_route_drop_no_conn_total 1720058
telemt_me_route_drop_channel_closed_total 148
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1529152
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5243
telemt_desync_full_logged_total 1562
telemt_desync_suppressed_total 3681
telemt_desync_frames_bucket_total{bucket="1_2"} 1340
telemt_desync_frames_bucket_total{bucket="3_10"} 1970
telemt_desync_frames_bucket_total{bucket="gt_10"} 1933
telemt_pool_swap_total 19
telemt_me_writer_close_signal_drop_total 50
telemt_me_writer_removed_unexpected_total 2381
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2382
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1525513
telemt_user_connections_current{user="hello"} 2787
telemt_user_octets_from_client{user="hello"} 20277163632 (18.88 GB)
telemt_user_octets_to_client{user="hello"} 502864344072 (468.33 GB)
telemt_user_unique_ips_current{user="hello"} 934
telemt_user_unique_ips_recent_window{user="hello"} 355
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 22767.5 (6h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1878575
telemt_connections_bad_total 62535
telemt_connections_current 2863
telemt_connections_me_current 2863
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 24624
telemt_upstream_connect_attempt_total 25628
telemt_upstream_connect_success_total 24431
telemt_upstream_connect_fail_total 1197
telemt_upstream_connect_attempts_per_request{bucket="1"} 25628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4166
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 354
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1197
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5207
telemt_me_reconnect_success_total 2823
telemt_me_reader_eof_total 2927
telemt_me_idle_close_by_peer_total 2926
telemt_me_route_drop_no_conn_total 1623789
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1621294
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6419
telemt_desync_full_logged_total 1994
telemt_desync_suppressed_total 4425
telemt_desync_frames_bucket_total{bucket="1_2"} 1650
telemt_desync_frames_bucket_total{bucket="3_10"} 2356
telemt_desync_frames_bucket_total{bucket="gt_10"} 2413
telemt_pool_swap_total 10
telemt_me_writer_close_signal_drop_total 200
telemt_me_writer_removed_unexpected_total 3238
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2819
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 415
telemt_user_connections_total{user="hello"} 1640626
telemt_user_connections_current{user="hello"} 2863
telemt_user_octets_from_client{user="hello"} 27991508209 (26.07 GB)
telemt_user_octets_to_client{user="hello"} 367352770321 (342.12 GB)
telemt_user_msgs_from_client{user="hello"} 49930
telemt_user_msgs_to_client{user="hello"} 93819
telemt_user_unique_ips_current{user="hello"} 965
telemt_user_unique_ips_recent_window{user="hello"} 404
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 76490.6 (21h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5571132
telemt_connections_bad_total 1009569
telemt_connections_current 3066
telemt_connections_me_current 3066
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 101559
telemt_upstream_connect_attempt_total 65135
telemt_upstream_connect_success_total 62641
telemt_upstream_connect_fail_total 2494
telemt_upstream_connect_attempts_per_request{bucket="1"} 65135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8524
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1050
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2494
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75059
telemt_me_reconnect_success_total 9649
telemt_me_reader_eof_total 10170
telemt_me_idle_close_by_peer_total 10167
telemt_me_route_drop_no_conn_total 2555393
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3882799
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
telemt_desync_total 17098
telemt_desync_full_logged_total 5244
telemt_desync_suppressed_total 11854
telemt_desync_frames_bucket_total{bucket="1_2"} 2847
telemt_desync_frames_bucket_total{bucket="3_10"} 7094
telemt_desync_frames_bucket_total{bucket="gt_10"} 7157
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 9896
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9625
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 3930921
telemt_user_connections_current{user="hello"} 3066
telemt_user_octets_from_client{user="hello"} 61508624359 (57.28 GB)
telemt_user_octets_to_client{user="hello"} 1451262572564 (1.32 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1094
telemt_user_unique_ips_recent_window{user="hello"} 448
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 22731.8 (6h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 520523
telemt_connections_bad_total 37554
telemt_connections_current 711
telemt_connections_me_current 711
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 10550
telemt_upstream_connect_attempt_total 7386
telemt_upstream_connect_success_total 7189
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 7386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4152
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 549
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 424
telemt_me_reconnect_attempts_total 3073
telemt_me_reconnect_success_total 3016
telemt_me_reader_eof_total 3103
telemt_me_idle_close_by_peer_total 3102
telemt_me_route_drop_no_conn_total 364723
telemt_me_route_drop_channel_closed_total 129
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 412138
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
telemt_desync_total 1094
telemt_desync_full_logged_total 348
telemt_desync_suppressed_total 746
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 444
telemt_desync_frames_bucket_total{bucket="gt_10"} 475
telemt_pool_swap_total 15
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 134
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 3038
telemt_me_writer_restored_same_endpoint_total 3007
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 430784
telemt_user_connections_current{user="hello"} 711
telemt_user_octets_from_client{user="hello"} 4886429268 (4.55 GB)
telemt_user_octets_to_client{user="hello"} 90299250710 (84.10 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 22732.0 (6h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1473177
telemt_connections_bad_total 89748
telemt_connections_current 3248
telemt_connections_me_current 3248
telemt_handshake_timeouts_total 25183
telemt_upstream_connect_attempt_total 3758
telemt_upstream_connect_success_total 3730
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 3758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 2569
telemt_me_reconnect_success_total 2542
telemt_me_reader_eof_total 2669
telemt_me_idle_close_by_peer_total 2669
telemt_me_route_drop_no_conn_total 566625
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1277716
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6760
telemt_desync_full_logged_total 2090
telemt_desync_suppressed_total 4670
telemt_desync_frames_bucket_total{bucket="1_2"} 1278
telemt_desync_frames_bucket_total{bucket="3_10"} 2366
telemt_desync_frames_bucket_total{bucket="gt_10"} 3116
telemt_pool_swap_total 20
telemt_me_writer_close_signal_drop_total 33
telemt_me_writer_removed_unexpected_total 2594
telemt_me_writer_restored_same_endpoint_total 2525
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 1276965
telemt_user_connections_current{user="hello"} 3248
telemt_user_octets_from_client{user="hello"} 20366644356 (18.97 GB)
telemt_user_octets_to_client{user="hello"} 570723639944 (531.53 GB)
telemt_user_unique_ips_current{user="hello"} 978
telemt_user_unique_ips_recent_window{user="hello"} 397
```