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

# Server Metrics 2026-03-19 19:54:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 9406.0 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280649
telemt_connections_bad_total 12955
telemt_connections_current 1119
telemt_connections_me_current 1119
telemt_handshake_timeouts_total 2824
telemt_upstream_connect_attempt_total 1452
telemt_upstream_connect_success_total 1437
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 1452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 745
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 939
telemt_me_reconnect_success_total 932
telemt_me_reader_eof_total 972
telemt_me_idle_close_by_peer_total 972
telemt_me_route_drop_no_conn_total 83615
telemt_me_route_drop_channel_closed_total 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 220367
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1109
telemt_desync_full_logged_total 367
telemt_desync_suppressed_total 742
telemt_desync_frames_bucket_total{bucket="1_2"} 226
telemt_desync_frames_bucket_total{bucket="3_10"} 323
telemt_desync_frames_bucket_total{bucket="gt_10"} 560
telemt_pool_swap_total 10
telemt_me_writer_close_signal_drop_total 29
telemt_me_writer_removed_unexpected_total 954
telemt_me_writer_restored_same_endpoint_total 919
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 220614
telemt_user_connections_current{user="hello"} 1119
telemt_user_octets_from_client{user="hello"} 9773801024 (9.10 GB)
telemt_user_octets_to_client{user="hello"} 78450945252 (73.06 GB)
telemt_user_unique_ips_current{user="hello"} 375
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 25861.5 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2410259
telemt_connections_bad_total 105644
telemt_connections_current 3175
telemt_connections_me_current 3175
telemt_handshake_timeouts_total 45948
telemt_upstream_connect_attempt_total 5485
telemt_upstream_connect_success_total 5410
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 5485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1893
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7096
telemt_me_reconnect_success_total 2869
telemt_me_reader_eof_total 3097
telemt_me_idle_close_by_peer_total 3097
telemt_me_route_drop_no_conn_total 1309560
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2038363
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8693
telemt_desync_full_logged_total 2827
telemt_desync_suppressed_total 5866
telemt_desync_frames_bucket_total{bucket="1_2"} 1594
telemt_desync_frames_bucket_total{bucket="3_10"} 3436
telemt_desync_frames_bucket_total{bucket="gt_10"} 3663
telemt_pool_swap_total 19
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 3026
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2814
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 2038346
telemt_user_connections_current{user="hello"} 3175
telemt_user_octets_from_client{user="hello"} 30400432754 (28.31 GB)
telemt_user_octets_to_client{user="hello"} 698890096290 (650.89 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1135
telemt_user_unique_ips_recent_window{user="hello"} 365
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 25840.1 (7h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2181510
telemt_connections_bad_total 254677
telemt_connections_current 2533
telemt_connections_me_current 2533
telemt_handshake_timeouts_total 25864
telemt_upstream_connect_attempt_total 3984
telemt_upstream_connect_success_total 3957
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 3984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1862
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3563
telemt_me_reconnect_success_total 2644
telemt_me_reader_eof_total 2725
telemt_me_idle_close_by_peer_total 2724
telemt_me_route_drop_no_conn_total 1769025
telemt_me_route_drop_channel_closed_total 158
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1660711
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5966
telemt_desync_full_logged_total 1789
telemt_desync_suppressed_total 4177
telemt_desync_frames_bucket_total{bucket="1_2"} 1512
telemt_desync_frames_bucket_total{bucket="3_10"} 2258
telemt_desync_frames_bucket_total{bucket="gt_10"} 2196
telemt_pool_swap_total 22
telemt_me_writer_close_signal_drop_total 56
telemt_me_writer_removed_unexpected_total 2649
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2643
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1657066
telemt_user_connections_current{user="hello"} 2533
telemt_user_octets_from_client{user="hello"} 23520656608 (21.91 GB)
telemt_user_octets_to_client{user="hello"} 567329815600 (528.37 GB)
telemt_user_unique_ips_current{user="hello"} 842
telemt_user_unique_ips_recent_window{user="hello"} 306
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 25827.4 (7h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2060147
telemt_connections_bad_total 68862
telemt_connections_current 2475
telemt_connections_me_current 2475
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 26129
telemt_upstream_connect_attempt_total 31219
telemt_upstream_connect_success_total 29691
telemt_upstream_connect_fail_total 1528
telemt_upstream_connect_attempts_per_request{bucket="1"} 31219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4666
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1528
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5608
telemt_me_reconnect_success_total 3078
telemt_me_reader_eof_total 3190
telemt_me_idle_close_by_peer_total 3189
telemt_me_route_drop_no_conn_total 1723257
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1769352
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7096
telemt_desync_full_logged_total 2231
telemt_desync_suppressed_total 4865
telemt_desync_frames_bucket_total{bucket="1_2"} 1757
telemt_desync_frames_bucket_total{bucket="3_10"} 2596
telemt_desync_frames_bucket_total{bucket="gt_10"} 2743
telemt_pool_swap_total 13
telemt_me_writer_close_signal_drop_total 288
telemt_me_writer_removed_unexpected_total 3531
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 3074
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 453
telemt_user_connections_total{user="hello"} 1793538
telemt_user_connections_current{user="hello"} 2475
telemt_user_octets_from_client{user="hello"} 30304420436 (28.22 GB)
telemt_user_octets_to_client{user="hello"} 415063130606 (386.56 GB)
telemt_user_msgs_from_client{user="hello"} 63004
telemt_user_msgs_to_client{user="hello"} 130023
telemt_user_unique_ips_current{user="hello"} 816
telemt_user_unique_ips_recent_window{user="hello"} 294
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 79550.7 (22h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5735656
telemt_connections_bad_total 1018839
telemt_connections_current 2855
telemt_connections_me_current 2855
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 105425
telemt_upstream_connect_attempt_total 65600
telemt_upstream_connect_success_total 63102
telemt_upstream_connect_fail_total 2498
telemt_upstream_connect_attempts_per_request{bucket="1"} 65600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1052
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2498
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75348
telemt_me_reconnect_success_total 9935
telemt_me_reader_eof_total 10481
telemt_me_idle_close_by_peer_total 10478
telemt_me_route_drop_no_conn_total 2639259
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4022221
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
telemt_desync_total 17716
telemt_desync_full_logged_total 5476
telemt_desync_suppressed_total 12240
telemt_desync_frames_bucket_total{bucket="1_2"} 2970
telemt_desync_frames_bucket_total{bucket="3_10"} 7347
telemt_desync_frames_bucket_total{bucket="gt_10"} 7399
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 10189
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9911
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 4070287
telemt_user_connections_current{user="hello"} 2855
telemt_user_octets_from_client{user="hello"} 63570026363 (59.20 GB)
telemt_user_octets_to_client{user="hello"} 1530939222736 (1.39 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 994
telemt_user_unique_ips_recent_window{user="hello"} 348
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 25792.0 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 560802
telemt_connections_bad_total 42726
telemt_connections_current 626
telemt_connections_me_current 626
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 10897
telemt_upstream_connect_attempt_total 7853
telemt_upstream_connect_success_total 7656
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 7853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4421
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 175
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 550
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 3410
telemt_me_reconnect_success_total 3350
telemt_me_reader_eof_total 3458
telemt_me_idle_close_by_peer_total 3457
telemt_me_route_drop_no_conn_total 379532
telemt_me_route_drop_channel_closed_total 135
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 445549
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
telemt_desync_total 1131
telemt_desync_full_logged_total 359
telemt_desync_suppressed_total 772
telemt_desync_frames_bucket_total{bucket="1_2"} 177
telemt_desync_frames_bucket_total{bucket="3_10"} 459
telemt_desync_frames_bucket_total{bucket="gt_10"} 495
telemt_pool_swap_total 18
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 136
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 3376
telemt_me_writer_restored_same_endpoint_total 3341
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 464189
telemt_user_connections_current{user="hello"} 626
telemt_user_octets_from_client{user="hello"} 5246439912 (4.89 GB)
telemt_user_octets_to_client{user="hello"} 98256706186 (91.51 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 25791.9 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1621893
telemt_connections_bad_total 97484
telemt_connections_current 2779
telemt_connections_me_current 2779
telemt_handshake_timeouts_total 26334
telemt_upstream_connect_attempt_total 4266
telemt_upstream_connect_success_total 4235
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 4266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1919
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 2943
telemt_me_reconnect_success_total 2913
telemt_me_reader_eof_total 3058
telemt_me_idle_close_by_peer_total 3058
telemt_me_route_drop_no_conn_total 614529
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1408820
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7384
telemt_desync_full_logged_total 2292
telemt_desync_suppressed_total 5092
telemt_desync_frames_bucket_total{bucket="1_2"} 1390
telemt_desync_frames_bucket_total{bucket="3_10"} 2567
telemt_desync_frames_bucket_total{bucket="gt_10"} 3427
telemt_pool_swap_total 23
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 2970
telemt_me_writer_restored_same_endpoint_total 2896
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 1408072
telemt_user_connections_current{user="hello"} 2779
telemt_user_octets_from_client{user="hello"} 22791529168 (21.23 GB)
telemt_user_octets_to_client{user="hello"} 659579592244 (614.28 GB)
telemt_user_unique_ips_current{user="hello"} 889
telemt_user_unique_ips_recent_window{user="hello"} 316
```