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

# Server Metrics 2026-03-20 01:39:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 30100.3 (8h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 566660
telemt_connections_bad_total 36598
telemt_connections_current 794
telemt_connections_me_current 794
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 8845
telemt_upstream_connect_attempt_total 6379
telemt_upstream_connect_success_total 6295
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 6379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3624
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2643
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3697
telemt_me_reconnect_success_total 3662
telemt_me_reader_eof_total 3863
telemt_me_idle_close_by_peer_total 3862
telemt_me_route_drop_no_conn_total 163540
telemt_me_route_drop_channel_closed_total 57
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 452633
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2129
telemt_desync_full_logged_total 761
telemt_desync_suppressed_total 1368
telemt_desync_frames_bucket_total{bucket="1_2"} 430
telemt_desync_frames_bucket_total{bucket="3_10"} 730
telemt_desync_frames_bucket_total{bucket="gt_10"} 969
telemt_pool_swap_total 33
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 3687
telemt_me_writer_restored_same_endpoint_total 3649
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 454062
telemt_user_connections_current{user="hello"} 794
telemt_user_octets_from_client{user="hello"} 29764121236 (27.72 GB)
telemt_user_octets_to_client{user="hello"} 161143680325 (150.08 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 324
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 46555.8 (12h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3000857
telemt_connections_bad_total 125881
telemt_connections_current 1434
telemt_connections_me_current 1434
telemt_handshake_timeouts_total 66126
telemt_upstream_connect_attempt_total 9257
telemt_upstream_connect_success_total 9104
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 9257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3761
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 9801
telemt_me_reconnect_success_total 5559
telemt_me_reader_eof_total 5951
telemt_me_idle_close_by_peer_total 5951
telemt_me_route_drop_no_conn_total 1503621
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2571751
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11124
telemt_desync_full_logged_total 3661
telemt_desync_suppressed_total 7463
telemt_desync_frames_bucket_total{bucket="1_2"} 2131
telemt_desync_frames_bucket_total{bucket="3_10"} 4350
telemt_desync_frames_bucket_total{bucket="gt_10"} 4643
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 5755
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5504
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 2571531
telemt_user_connections_current{user="hello"} 1434
telemt_user_octets_from_client{user="hello"} 39319158254 (36.62 GB)
telemt_user_octets_to_client{user="hello"} 940119212850 (875.55 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 636
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 46533.9 (12h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2952011
telemt_connections_bad_total 475288
telemt_connections_current 1118
telemt_connections_me_current 1118
telemt_handshake_timeouts_total 43312
telemt_upstream_connect_attempt_total 7500
telemt_upstream_connect_success_total 7444
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 7500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3632
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6058
telemt_me_reconnect_success_total 5125
telemt_me_reader_eof_total 5375
telemt_me_idle_close_by_peer_total 5374
telemt_me_route_drop_no_conn_total 1920300
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2034887
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7644
telemt_desync_full_logged_total 2320
telemt_desync_suppressed_total 5324
telemt_desync_frames_bucket_total{bucket="1_2"} 1882
telemt_desync_frames_bucket_total{bucket="3_10"} 2913
telemt_desync_frames_bucket_total{bucket="gt_10"} 2849
telemt_pool_swap_total 45
telemt_me_writer_close_signal_drop_total 69
telemt_me_writer_removed_unexpected_total 5175
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5124
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 2030509
telemt_user_connections_current{user="hello"} 1118
telemt_user_octets_from_client{user="hello"} 29967977820 (27.91 GB)
telemt_user_octets_to_client{user="hello"} 775668558360 (722.40 GB)
telemt_user_unique_ips_current{user="hello"} 474
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 46521.8 (12h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2564970
telemt_connections_bad_total 128548
telemt_connections_current 1053
telemt_connections_me_current 1053
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 31138
telemt_upstream_connect_attempt_total 55447
telemt_upstream_connect_success_total 51170
telemt_upstream_connect_fail_total 4277
telemt_upstream_connect_attempts_per_request{bucket="1"} 55447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7503
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 528
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4277
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8445
telemt_me_reconnect_success_total 5605
telemt_me_reader_eof_total 5824
telemt_me_idle_close_by_peer_total 5823
telemt_me_route_drop_no_conn_total 1863809
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2137967
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8346
telemt_desync_full_logged_total 2631
telemt_desync_suppressed_total 5715
telemt_desync_frames_bucket_total{bucket="1_2"} 2060
telemt_desync_frames_bucket_total{bucket="3_10"} 3032
telemt_desync_frames_bucket_total{bucket="gt_10"} 3254
telemt_pool_swap_total 32
telemt_me_writer_close_signal_drop_total 476
telemt_me_writer_removed_unexpected_total 6230
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5601
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 625
telemt_user_connections_total{user="hello"} 2180038
telemt_user_connections_current{user="hello"} 1053
telemt_user_octets_from_client{user="hello"} 35583793689 (33.14 GB)
telemt_user_octets_to_client{user="hello"} 612792776365 (570.71 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 402
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 100245.2 (27h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6271297
telemt_connections_bad_total 1043066
telemt_connections_current 1266
telemt_connections_me_current 1266
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 113500
telemt_upstream_connect_attempt_total 127468
telemt_upstream_connect_success_total 94183
telemt_upstream_connect_fail_total 33285
telemt_upstream_connect_attempts_per_request{bucket="1"} 127468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12457
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33285
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 78528
telemt_me_reconnect_success_total 12858
telemt_me_reader_eof_total 13852
telemt_me_idle_close_by_peer_total 13838
telemt_me_route_drop_no_conn_total 2797387
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4444925
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
telemt_desync_total 19546
telemt_desync_full_logged_total 6192
telemt_desync_suppressed_total 13354
telemt_desync_frames_bucket_total{bucket="1_2"} 3436
telemt_desync_frames_bucket_total{bucket="3_10"} 8047
telemt_desync_frames_bucket_total{bucket="gt_10"} 8063
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 13167
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 12833
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 309
telemt_user_connections_total{user="hello"} 4520139
telemt_user_connections_current{user="hello"} 1266
telemt_user_octets_from_client{user="hello"} 72499099756 (67.52 GB)
telemt_user_octets_to_client{user="hello"} 1740039345964 (1.58 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 535
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 46485.0 (12h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 711257
telemt_connections_bad_total 76184
telemt_connections_current 363
telemt_connections_me_current 363
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13021
telemt_upstream_connect_attempt_total 13658
telemt_upstream_connect_success_total 13328
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6959
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 6667
telemt_me_reconnect_success_total 6560
telemt_me_reader_eof_total 6884
telemt_me_idle_close_by_peer_total 6881
telemt_me_route_drop_no_conn_total 469839
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 583786
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
telemt_desync_total 1397
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 874
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 576
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 150
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6621
telemt_me_writer_restored_same_endpoint_total 6551
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 571932
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 7341072323 (6.84 GB)
telemt_user_octets_to_client{user="hello"} 145627541718 (135.63 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 46486.5 (12h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2018213
telemt_connections_bad_total 120016
telemt_connections_current 1155
telemt_connections_me_current 1155
telemt_handshake_timeouts_total 37592
telemt_upstream_connect_attempt_total 8304
telemt_upstream_connect_success_total 8244
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 8304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3762
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5960
telemt_me_reconnect_success_total 5917
telemt_me_reader_eof_total 6245
telemt_me_idle_close_by_peer_total 6245
telemt_me_route_drop_no_conn_total 743328
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1739947
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9218
telemt_desync_full_logged_total 2960
telemt_desync_suppressed_total 6258
telemt_desync_frames_bucket_total{bucket="1_2"} 1737
telemt_desync_frames_bucket_total{bucket="3_10"} 3230
telemt_desync_frames_bucket_total{bucket="gt_10"} 4251
telemt_pool_swap_total 46
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 6006
telemt_me_writer_restored_same_endpoint_total 5900
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 1739055
telemt_user_connections_current{user="hello"} 1155
telemt_user_octets_from_client{user="hello"} 29703292888 (27.66 GB)
telemt_user_octets_to_client{user="hello"} 881403600028 (820.87 GB)
telemt_user_unique_ips_current{user="hello"} 460
telemt_user_unique_ips_recent_window{user="hello"} 84
```