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

# Server Metrics 2026-03-19 19:33:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 8183.2 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254130
telemt_connections_bad_total 10907
telemt_connections_current 1323
telemt_connections_me_current 1323
telemt_handshake_timeouts_total 2588
telemt_upstream_connect_attempt_total 1238
telemt_upstream_connect_success_total 1223
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 1238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 633
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 780
telemt_me_reconnect_success_total 774
telemt_me_reader_eof_total 802
telemt_me_idle_close_by_peer_total 802
telemt_me_route_drop_no_conn_total 75914
telemt_me_route_drop_channel_closed_total 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 197564
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 946
telemt_desync_full_logged_total 314
telemt_desync_suppressed_total 632
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 278
telemt_desync_frames_bucket_total{bucket="gt_10"} 470
telemt_pool_swap_total 8
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 796
telemt_me_writer_restored_same_endpoint_total 761
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 197816
telemt_user_connections_current{user="hello"} 1323
telemt_user_octets_from_client{user="hello"} 7342239404 (6.84 GB)
telemt_user_octets_to_client{user="hello"} 69729000108 (64.94 GB)
telemt_user_unique_ips_current{user="hello"} 410
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 24638.6 (6h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2335614
telemt_connections_bad_total 103851
telemt_connections_current 3548
telemt_connections_me_current 3548
telemt_handshake_timeouts_total 44557
telemt_upstream_connect_attempt_total 5328
telemt_upstream_connect_success_total 5256
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 5328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1804
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6985
telemt_me_reconnect_success_total 2758
telemt_me_reader_eof_total 2979
telemt_me_idle_close_by_peer_total 2979
telemt_me_route_drop_no_conn_total 1278655
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1969197
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8227
telemt_desync_full_logged_total 2668
telemt_desync_suppressed_total 5559
telemt_desync_frames_bucket_total{bucket="1_2"} 1515
telemt_desync_frames_bucket_total{bucket="3_10"} 3248
telemt_desync_frames_bucket_total{bucket="gt_10"} 3464
telemt_pool_swap_total 18
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 2912
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2703
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 1969191
telemt_user_connections_current{user="hello"} 3548
telemt_user_octets_from_client{user="hello"} 28801435902 (26.82 GB)
telemt_user_octets_to_client{user="hello"} 666073885386 (620.33 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1261
telemt_user_unique_ips_recent_window{user="hello"} 453
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 24616.5 (6h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2116122
telemt_connections_bad_total 251745
telemt_connections_current 2703
telemt_connections_me_current 2703
telemt_handshake_timeouts_total 24745
telemt_upstream_connect_attempt_total 3849
telemt_upstream_connect_success_total 3823
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3472
telemt_me_reconnect_success_total 2553
telemt_me_reader_eof_total 2626
telemt_me_idle_close_by_peer_total 2625
telemt_me_route_drop_no_conn_total 1751396
telemt_me_route_drop_channel_closed_total 154
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1609355
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5700
telemt_desync_full_logged_total 1700
telemt_desync_suppressed_total 4000
telemt_desync_frames_bucket_total{bucket="1_2"} 1449
telemt_desync_frames_bucket_total{bucket="3_10"} 2157
telemt_desync_frames_bucket_total{bucket="gt_10"} 2094
telemt_pool_swap_total 21
telemt_me_writer_close_signal_drop_total 54
telemt_me_writer_removed_unexpected_total 2554
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2552
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 1605711
telemt_user_connections_current{user="hello"} 2703
telemt_user_octets_from_client{user="hello"} 22740990928 (21.18 GB)
telemt_user_octets_to_client{user="hello"} 544291469936 (506.91 GB)
telemt_user_unique_ips_current{user="hello"} 893
telemt_user_unique_ips_recent_window{user="hello"} 327
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 24604.0 (6h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1989267
telemt_connections_bad_total 65752
telemt_connections_current 2469
telemt_connections_me_current 2469
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 25350
telemt_upstream_connect_attempt_total 25906
telemt_upstream_connect_success_total 24691
telemt_upstream_connect_fail_total 1215
telemt_upstream_connect_attempts_per_request{bucket="1"} 25906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4296
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1215
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5390
telemt_me_reconnect_success_total 2996
telemt_me_reader_eof_total 3113
telemt_me_idle_close_by_peer_total 3112
telemt_me_route_drop_no_conn_total 1697115
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1716271
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6952
telemt_desync_full_logged_total 2178
telemt_desync_suppressed_total 4774
telemt_desync_frames_bucket_total{bucket="1_2"} 1725
telemt_desync_frames_bucket_total{bucket="3_10"} 2548
telemt_desync_frames_bucket_total{bucket="gt_10"} 2679
telemt_pool_swap_total 12
telemt_me_writer_close_signal_drop_total 201
telemt_me_writer_removed_unexpected_total 3415
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2992
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 419
telemt_user_connections_total{user="hello"} 1735593
telemt_user_connections_current{user="hello"} 2469
telemt_user_octets_from_client{user="hello"} 29940069117 (27.88 GB)
telemt_user_octets_to_client{user="hello"} 395603384857 (368.43 GB)
telemt_user_msgs_from_client{user="hello"} 49930
telemt_user_msgs_to_client{user="hello"} 93819
telemt_user_unique_ips_current{user="hello"} 909
telemt_user_unique_ips_recent_window{user="hello"} 348
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 78327.2 (21h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5673772
telemt_connections_bad_total 1015841
telemt_connections_current 2735
telemt_connections_me_current 2735
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 103785
telemt_upstream_connect_attempt_total 65381
telemt_upstream_connect_success_total 62884
telemt_upstream_connect_fail_total 2497
telemt_upstream_connect_attempts_per_request{bucket="1"} 65381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8645
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1051
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2497
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75210
telemt_me_reconnect_success_total 9799
telemt_me_reader_eof_total 10335
telemt_me_idle_close_by_peer_total 10332
telemt_me_route_drop_no_conn_total 2605032
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3969427
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
telemt_desync_total 17476
telemt_desync_full_logged_total 5383
telemt_desync_suppressed_total 12093
telemt_desync_frames_bucket_total{bucket="1_2"} 2916
telemt_desync_frames_bucket_total{bucket="3_10"} 7266
telemt_desync_frames_bucket_total{bucket="gt_10"} 7294
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 10052
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9775
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 4017520
telemt_user_connections_current{user="hello"} 2735
telemt_user_octets_from_client{user="hello"} 62631505679 (58.33 GB)
telemt_user_octets_to_client{user="hello"} 1497948078572 (1.36 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1010
telemt_user_unique_ips_recent_window{user="hello"} 363
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 24568.4 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 548420
telemt_connections_bad_total 42568
telemt_connections_current 560
telemt_connections_me_current 560
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 10784
telemt_upstream_connect_attempt_total 7666
telemt_upstream_connect_success_total 7469
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 7666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4313
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 175
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 549
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 424
telemt_me_reconnect_attempts_total 3266
telemt_me_reconnect_success_total 3208
telemt_me_reader_eof_total 3309
telemt_me_idle_close_by_peer_total 3308
telemt_me_route_drop_no_conn_total 374245
telemt_me_route_drop_channel_closed_total 132
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 433871
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
telemt_desync_total 1122
telemt_desync_full_logged_total 355
telemt_desync_suppressed_total 767
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 455
telemt_desync_frames_bucket_total{bucket="gt_10"} 491
telemt_pool_swap_total 17
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 135
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 3233
telemt_me_writer_restored_same_endpoint_total 3199
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 452512
telemt_user_connections_current{user="hello"} 560
telemt_user_octets_from_client{user="hello"} 5170450048 (4.82 GB)
telemt_user_octets_to_client{user="hello"} 95534342574 (88.97 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 24568.7 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1568297
telemt_connections_bad_total 95334
telemt_connections_current 2662
telemt_connections_me_current 2662
telemt_handshake_timeouts_total 25704
telemt_upstream_connect_attempt_total 4076
telemt_upstream_connect_success_total 4046
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 4076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 2799
telemt_me_reconnect_success_total 2770
telemt_me_reader_eof_total 2909
telemt_me_idle_close_by_peer_total 2909
telemt_me_route_drop_no_conn_total 597691
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1361253
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7148
telemt_desync_full_logged_total 2207
telemt_desync_suppressed_total 4941
telemt_desync_frames_bucket_total{bucket="1_2"} 1351
telemt_desync_frames_bucket_total{bucket="3_10"} 2483
telemt_desync_frames_bucket_total{bucket="gt_10"} 3314
telemt_pool_swap_total 22
telemt_me_writer_close_signal_drop_total 34
telemt_me_writer_removed_unexpected_total 2827
telemt_me_writer_restored_same_endpoint_total 2753
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 1360507
telemt_user_connections_current{user="hello"} 2662
telemt_user_octets_from_client{user="hello"} 22008172508 (20.50 GB)
telemt_user_octets_to_client{user="hello"} 626077709712 (583.08 GB)
telemt_user_unique_ips_current{user="hello"} 903
telemt_user_unique_ips_recent_window{user="hello"} 318
```