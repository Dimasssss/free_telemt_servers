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

# Server Metrics 2026-03-19 06:44:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 32145.4 (8h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 521363
telemt_connections_bad_total 56830
telemt_connections_current 1309
telemt_connections_me_current 1309
telemt_handshake_timeouts_total 22535
telemt_upstream_connect_attempt_total 6214
telemt_upstream_connect_success_total 6106
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 6214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3122
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5648
telemt_me_reconnect_success_total 4504
telemt_me_reader_eof_total 4775
telemt_me_idle_close_by_peer_total 4774
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 141777
telemt_me_route_drop_channel_closed_total 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 388963
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2445
telemt_desync_full_logged_total 710
telemt_desync_suppressed_total 1735
telemt_desync_frames_bucket_total{bucket="1_2"} 816
telemt_desync_frames_bucket_total{bucket="3_10"} 954
telemt_desync_frames_bucket_total{bucket="gt_10"} 675
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 4587
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 4487
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 386208
telemt_user_connections_current{user="hello"} 1309
telemt_user_octets_from_client{user="hello"} 5353007704 (4.99 GB)
telemt_user_octets_to_client{user="hello"} 130962345404 (121.97 GB)
telemt_user_unique_ips_current{user="hello"} 479
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 32149.6 (8h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1111775
telemt_connections_bad_total 62641
telemt_connections_current 3815
telemt_connections_me_current 3815
telemt_handshake_timeouts_total 29349
telemt_upstream_connect_attempt_total 5997
telemt_upstream_connect_success_total 5889
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 5997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2960
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_reconnect_attempts_total 5420
telemt_me_reconnect_success_total 4272
telemt_me_reader_eof_total 4539
telemt_me_idle_close_by_peer_total 4539
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 363566
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 921832
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3957
telemt_desync_full_logged_total 1370
telemt_desync_suppressed_total 2587
telemt_desync_frames_bucket_total{bucket="1_2"} 714
telemt_desync_frames_bucket_total{bucket="3_10"} 1499
telemt_desync_frames_bucket_total{bucket="gt_10"} 1744
telemt_pool_swap_total 28
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4386
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 4252
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 921771
telemt_user_connections_current{user="hello"} 3815
telemt_user_octets_from_client{user="hello"} 19574413256 (18.23 GB)
telemt_user_octets_to_client{user="hello"} 406056625468 (378.17 GB)
telemt_user_unique_ips_current{user="hello"} 1320
telemt_user_unique_ips_recent_window{user="hello"} 507
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 32147.2 (8h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 964300
telemt_connections_bad_total 149747
telemt_connections_current 3000
telemt_connections_me_current 3000
telemt_handshake_timeouts_total 28888
telemt_upstream_connect_attempt_total 5837
telemt_upstream_connect_success_total 5837
telemt_upstream_connect_attempts_per_request{bucket="1"} 5837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2847
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 4244
telemt_me_reconnect_success_total 4225
telemt_me_reader_eof_total 4475
telemt_me_idle_close_by_peer_total 4475
telemt_me_route_drop_no_conn_total 304071
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 709937
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3469
telemt_desync_full_logged_total 1107
telemt_desync_suppressed_total 2362
telemt_desync_frames_bucket_total{bucket="1_2"} 641
telemt_desync_frames_bucket_total{bucket="3_10"} 1255
telemt_desync_frames_bucket_total{bucket="gt_10"} 1573
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 4302
telemt_me_writer_restored_same_endpoint_total 4209
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 709613
telemt_user_connections_current{user="hello"} 3000
telemt_user_octets_from_client{user="hello"} 13253092304 (12.34 GB)
telemt_user_octets_to_client{user="hello"} 397818051604 (370.50 GB)
telemt_user_unique_ips_current{user="hello"} 1035
telemt_user_unique_ips_recent_window{user="hello"} 424
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 32200.1 (8h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1021283
telemt_connections_bad_total 88588
telemt_connections_current 2692
telemt_connections_me_current 2692
telemt_handshake_timeouts_total 25067
telemt_upstream_connect_attempt_total 5653
telemt_upstream_connect_success_total 5653
telemt_upstream_connect_attempts_per_request{bucket="1"} 5653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2778
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 5086
telemt_me_reconnect_success_total 4035
telemt_me_reader_eof_total 4290
telemt_me_idle_close_by_peer_total 4289
telemt_me_route_drop_no_conn_total 340506
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 699992
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2659
telemt_desync_full_logged_total 954
telemt_desync_suppressed_total 1705
telemt_desync_frames_bucket_total{bucket="1_2"} 476
telemt_desync_frames_bucket_total{bucket="3_10"} 1060
telemt_desync_frames_bucket_total{bucket="gt_10"} 1123
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 4126
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4011
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 698880
telemt_user_connections_current{user="hello"} 2692
telemt_user_octets_from_client{user="hello"} 10877785956 (10.13 GB)
telemt_user_octets_to_client{user="hello"} 262072011440 (244.07 GB)
telemt_user_unique_ips_current{user="hello"} 923
telemt_user_unique_ips_recent_window{user="hello"} 382
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 32143.3 (8h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1256636
telemt_connections_bad_total 358015
telemt_connections_current 2859
telemt_connections_me_current 2859
telemt_handshake_timeouts_total 29900
telemt_upstream_connect_attempt_total 5692
telemt_upstream_connect_success_total 5657
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 5692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2779
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_reconnect_attempts_total 4075
telemt_me_reconnect_success_total 4046
telemt_me_reader_eof_total 4285
telemt_me_idle_close_by_peer_total 4285
telemt_me_route_drop_no_conn_total 306911
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 744896
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3688
telemt_desync_full_logged_total 1185
telemt_desync_suppressed_total 2503
telemt_desync_frames_bucket_total{bucket="1_2"} 831
telemt_desync_frames_bucket_total{bucket="3_10"} 1636
telemt_desync_frames_bucket_total{bucket="gt_10"} 1221
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 4094
telemt_me_writer_restored_same_endpoint_total 4022
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 744698
telemt_user_connections_current{user="hello"} 2859
telemt_user_octets_from_client{user="hello"} 17534642336 (16.33 GB)
telemt_user_octets_to_client{user="hello"} 388883442488 (362.18 GB)
telemt_user_unique_ips_current{user="hello"} 1026
telemt_user_unique_ips_recent_window{user="hello"} 443
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 32155.4 (8h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208278
telemt_connections_bad_total 12295
telemt_connections_current 759
telemt_connections_me_current 759
telemt_handshake_timeouts_total 1727
telemt_upstream_connect_attempt_total 8559
telemt_upstream_connect_success_total 8342
telemt_upstream_connect_fail_total 217
telemt_upstream_connect_attempts_per_request{bucket="1"} 8559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4270
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 217
telemt_me_reconnect_attempts_total 11174
telemt_me_reconnect_success_total 6734
telemt_me_reader_eof_total 7131
telemt_me_idle_close_by_peer_total 7131
telemt_me_route_drop_no_conn_total 85207
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183015
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 294
telemt_desync_full_logged_total 103
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 132
telemt_desync_frames_bucket_total{bucket="gt_10"} 86
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 6906
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6704
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 183002
telemt_user_connections_current{user="hello"} 759
telemt_user_octets_from_client{user="hello"} 2921446040 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 96858533644 (90.21 GB)
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 32146.0 (8h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 771521
telemt_connections_bad_total 86788
telemt_connections_current 3044
telemt_connections_me_current 3044
telemt_handshake_timeouts_total 33655
telemt_upstream_connect_attempt_total 6437
telemt_upstream_connect_success_total 6437
telemt_upstream_connect_attempts_per_request{bucket="1"} 6437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3422
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3012
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4849
telemt_me_reconnect_success_total 4835
telemt_me_reader_eof_total 5105
telemt_me_idle_close_by_peer_total 5105
telemt_me_route_drop_no_conn_total 267498
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 622765
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3522
telemt_desync_full_logged_total 1245
telemt_desync_suppressed_total 2277
telemt_desync_frames_bucket_total{bucket="1_2"} 675
telemt_desync_frames_bucket_total{bucket="3_10"} 1360
telemt_desync_frames_bucket_total{bucket="gt_10"} 1487
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 4888
telemt_me_writer_restored_same_endpoint_total 4820
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 622561
telemt_user_connections_current{user="hello"} 3044
telemt_user_octets_from_client{user="hello"} 9162127096 (8.53 GB)
telemt_user_octets_to_client{user="hello"} 355503235860 (331.09 GB)
telemt_user_unique_ips_current{user="hello"} 939
telemt_user_unique_ips_recent_window{user="hello"} 362
```