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

# Server Metrics 2026-03-19 05:02:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 26017.0 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371364
telemt_connections_bad_total 38192
telemt_connections_current 1111
telemt_connections_me_current 1111
telemt_handshake_timeouts_total 20341
telemt_upstream_connect_attempt_total 5046
telemt_upstream_connect_success_total 4963
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 5046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2536
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3692
telemt_me_reconnect_success_total 3675
telemt_me_reader_eof_total 3873
telemt_me_idle_close_by_peer_total 3872
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 94936
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 269172
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1854
telemt_desync_full_logged_total 511
telemt_desync_suppressed_total 1343
telemt_desync_frames_bucket_total{bucket="1_2"} 685
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 426
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3705
telemt_me_writer_restored_same_endpoint_total 3658
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 266425
telemt_user_connections_current{user="hello"} 1111
telemt_user_octets_from_client{user="hello"} 3192711240 (2.97 GB)
telemt_user_octets_to_client{user="hello"} 85222196440 (79.37 GB)
telemt_user_unique_ips_current{user="hello"} 404
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 26020.7 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 704056
telemt_connections_bad_total 43232
telemt_connections_current 2908
telemt_connections_me_current 2908
telemt_handshake_timeouts_total 21884
telemt_upstream_connect_attempt_total 4870
telemt_upstream_connect_success_total 4780
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 4870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2467
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_reconnect_attempts_total 3501
telemt_me_reconnect_success_total 3483
telemt_me_reader_eof_total 3675
telemt_me_idle_close_by_peer_total 3675
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 212589
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 582781
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2361
telemt_desync_full_logged_total 793
telemt_desync_suppressed_total 1568
telemt_desync_frames_bucket_total{bucket="1_2"} 466
telemt_desync_frames_bucket_total{bucket="3_10"} 874
telemt_desync_frames_bucket_total{bucket="gt_10"} 1021
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 3543
telemt_me_writer_restored_same_endpoint_total 3465
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 582697
telemt_user_connections_current{user="hello"} 2908
telemt_user_octets_from_client{user="hello"} 15386992828 (14.33 GB)
telemt_user_octets_to_client{user="hello"} 255397621456 (237.86 GB)
telemt_user_unique_ips_current{user="hello"} 1080
telemt_user_unique_ips_recent_window{user="hello"} 402
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 26018.1 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 594800
telemt_connections_bad_total 111689
telemt_connections_current 2376
telemt_connections_me_current 2376
telemt_handshake_timeouts_total 21083
telemt_upstream_connect_attempt_total 4779
telemt_upstream_connect_success_total 4779
telemt_upstream_connect_attempts_per_request{bucket="1"} 4779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2338
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3492
telemt_me_reconnect_success_total 3481
telemt_me_reader_eof_total 3681
telemt_me_idle_close_by_peer_total 3681
telemt_me_route_drop_no_conn_total 176034
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 428718
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2264
telemt_desync_full_logged_total 739
telemt_desync_suppressed_total 1525
telemt_desync_frames_bucket_total{bucket="1_2"} 338
telemt_desync_frames_bucket_total{bucket="3_10"} 800
telemt_desync_frames_bucket_total{bucket="gt_10"} 1126
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 3540
telemt_me_writer_restored_same_endpoint_total 3465
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 428702
telemt_user_connections_current{user="hello"} 2376
telemt_user_octets_from_client{user="hello"} 9219917544 (8.59 GB)
telemt_user_octets_to_client{user="hello"} 268755049944 (250.30 GB)
telemt_user_unique_ips_current{user="hello"} 828
telemt_user_unique_ips_recent_window{user="hello"} 327
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 26071.2 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 690595
telemt_connections_bad_total 85302
telemt_connections_current 2033
telemt_connections_me_current 2033
telemt_handshake_timeouts_total 15557
telemt_upstream_connect_attempt_total 4616
telemt_upstream_connect_success_total 4616
telemt_upstream_connect_attempts_per_request{bucket="1"} 4616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2270
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 3337
telemt_me_reconnect_success_total 3322
telemt_me_reader_eof_total 3506
telemt_me_idle_close_by_peer_total 3505
telemt_me_route_drop_no_conn_total 173980
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 422325
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1325
telemt_desync_full_logged_total 483
telemt_desync_suppressed_total 842
telemt_desync_frames_bucket_total{bucket="1_2"} 245
telemt_desync_frames_bucket_total{bucket="3_10"} 565
telemt_desync_frames_bucket_total{bucket="gt_10"} 515
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 3363
telemt_me_writer_restored_same_endpoint_total 3298
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 422091
telemt_user_connections_current{user="hello"} 2033
telemt_user_octets_from_client{user="hello"} 6543709816 (6.09 GB)
telemt_user_octets_to_client{user="hello"} 162036758308 (150.91 GB)
telemt_user_unique_ips_current{user="hello"} 760
telemt_user_unique_ips_recent_window{user="hello"} 334
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 26014.5 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 773319
telemt_connections_bad_total 211011
telemt_connections_current 2306
telemt_connections_me_current 2306
telemt_handshake_timeouts_total 21137
telemt_upstream_connect_attempt_total 4737
telemt_upstream_connect_success_total 4708
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 4737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 3429
telemt_me_reconnect_success_total 3409
telemt_me_reader_eof_total 3602
telemt_me_idle_close_by_peer_total 3602
telemt_me_route_drop_no_conn_total 190571
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 457768
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2078
telemt_desync_full_logged_total 783
telemt_desync_suppressed_total 1295
telemt_desync_frames_bucket_total{bucket="1_2"} 474
telemt_desync_frames_bucket_total{bucket="3_10"} 878
telemt_desync_frames_bucket_total{bucket="gt_10"} 726
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 3442
telemt_me_writer_restored_same_endpoint_total 3385
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 457690
telemt_user_connections_current{user="hello"} 2306
telemt_user_octets_from_client{user="hello"} 13842320932 (12.89 GB)
telemt_user_octets_to_client{user="hello"} 263662581212 (245.55 GB)
telemt_user_unique_ips_current{user="hello"} 884
telemt_user_unique_ips_recent_window{user="hello"} 364
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 26025.9 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136866
telemt_connections_bad_total 10408
telemt_connections_current 576
telemt_connections_me_current 576
telemt_handshake_timeouts_total 617
telemt_upstream_connect_attempt_total 7119
telemt_upstream_connect_success_total 6930
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 7119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3304
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3626
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_reconnect_attempts_total 7479
telemt_me_reconnect_success_total 5635
telemt_me_reader_eof_total 5914
telemt_me_idle_close_by_peer_total 5914
telemt_me_route_drop_no_conn_total 55279
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120182
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 147
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 5709
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 5605
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 120174
telemt_user_connections_current{user="hello"} 576
telemt_user_octets_from_client{user="hello"} 2131000288 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 74469327332 (69.35 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 26016.9 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 453048
telemt_connections_bad_total 48107
telemt_connections_current 2165
telemt_connections_me_current 2165
telemt_handshake_timeouts_total 23480
telemt_upstream_connect_attempt_total 5304
telemt_upstream_connect_success_total 5304
telemt_upstream_connect_attempts_per_request{bucket="1"} 5304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2482
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4026
telemt_me_reconnect_success_total 4014
telemt_me_reader_eof_total 4237
telemt_me_idle_close_by_peer_total 4237
telemt_me_route_drop_no_conn_total 127175
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 367602
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2024
telemt_desync_full_logged_total 752
telemt_desync_suppressed_total 1272
telemt_desync_frames_bucket_total{bucket="1_2"} 416
telemt_desync_frames_bucket_total{bucket="3_10"} 777
telemt_desync_frames_bucket_total{bucket="gt_10"} 831
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4059
telemt_me_writer_restored_same_endpoint_total 3999
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 367614
telemt_user_connections_current{user="hello"} 2165
telemt_user_octets_from_client{user="hello"} 4613001324 (4.30 GB)
telemt_user_octets_to_client{user="hello"} 216382278444 (201.52 GB)
telemt_user_unique_ips_current{user="hello"} 742
telemt_user_unique_ips_recent_window{user="hello"} 287
```