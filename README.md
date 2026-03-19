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

# Server Metrics 2026-03-19 03:24:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 20190.0 (5h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254796
telemt_connections_bad_total 29641
telemt_connections_current 726
telemt_connections_me_current 726
telemt_handshake_timeouts_total 16954
telemt_upstream_connect_attempt_total 3999
telemt_upstream_connect_success_total 3939
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 3999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2037
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2929
telemt_me_reconnect_success_total 2915
telemt_me_reader_eof_total 3056
telemt_me_idle_close_by_peer_total 3056
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 67231
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194175
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1350
telemt_desync_full_logged_total 357
telemt_desync_suppressed_total 993
telemt_desync_frames_bucket_total{bucket="1_2"} 505
telemt_desync_frames_bucket_total{bucket="3_10"} 569
telemt_desync_frames_bucket_total{bucket="gt_10"} 276
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2933
telemt_me_writer_restored_same_endpoint_total 2898
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 191400
telemt_user_connections_current{user="hello"} 726
telemt_user_octets_from_client{user="hello"} 2032450032 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 58160535172 (54.17 GB)
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 20193.9 (5h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 461161
telemt_connections_bad_total 37629
telemt_connections_current 1850
telemt_connections_me_current 1850
telemt_handshake_timeouts_total 11475
telemt_upstream_connect_attempt_total 3883
telemt_upstream_connect_success_total 3817
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 3883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2011
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_reconnect_attempts_total 2796
telemt_me_reconnect_success_total 2783
telemt_me_reader_eof_total 2933
telemt_me_idle_close_by_peer_total 2933
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 137561
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 383748
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1412
telemt_desync_full_logged_total 487
telemt_desync_suppressed_total 925
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 530
telemt_desync_frames_bucket_total{bucket="gt_10"} 568
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2825
telemt_me_writer_restored_same_endpoint_total 2767
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 383720
telemt_user_connections_current{user="hello"} 1850
telemt_user_octets_from_client{user="hello"} 12443029672 (11.59 GB)
telemt_user_octets_to_client{user="hello"} 156395241036 (145.65 GB)
telemt_user_unique_ips_current{user="hello"} 714
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 20191.0 (5h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 378977
telemt_connections_bad_total 81038
telemt_connections_current 1352
telemt_connections_me_current 1352
telemt_handshake_timeouts_total 9272
telemt_upstream_connect_attempt_total 3837
telemt_upstream_connect_success_total 3837
telemt_upstream_connect_attempts_per_request{bucket="1"} 3837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1886
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 2817
telemt_me_reconnect_success_total 2807
telemt_me_reader_eof_total 2969
telemt_me_idle_close_by_peer_total 2969
telemt_me_route_drop_no_conn_total 113105
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 277395
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1321
telemt_desync_full_logged_total 502
telemt_desync_suppressed_total 819
telemt_desync_frames_bucket_total{bucket="1_2"} 227
telemt_desync_frames_bucket_total{bucket="3_10"} 539
telemt_desync_frames_bucket_total{bucket="gt_10"} 555
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 2850
telemt_me_writer_restored_same_endpoint_total 2791
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 277389
telemt_user_connections_current{user="hello"} 1352
telemt_user_octets_from_client{user="hello"} 5970167572 (5.56 GB)
telemt_user_octets_to_client{user="hello"} 170648921944 (158.93 GB)
telemt_user_unique_ips_current{user="hello"} 572
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 20244.3 (5h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 450332
telemt_connections_bad_total 46805
telemt_connections_current 1222
telemt_connections_me_current 1222
telemt_handshake_timeouts_total 8205
telemt_upstream_connect_attempt_total 3717
telemt_upstream_connect_success_total 3717
telemt_upstream_connect_attempts_per_request{bucket="1"} 3717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2701
telemt_me_reconnect_success_total 2690
telemt_me_reader_eof_total 2832
telemt_me_idle_close_by_peer_total 2831
telemt_me_route_drop_no_conn_total 117828
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 277348
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 739
telemt_desync_full_logged_total 269
telemt_desync_suppressed_total 470
telemt_desync_frames_bucket_total{bucket="1_2"} 154
telemt_desync_frames_bucket_total{bucket="3_10"} 318
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 2720
telemt_me_writer_restored_same_endpoint_total 2666
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 277084
telemt_user_connections_current{user="hello"} 1222
telemt_user_octets_from_client{user="hello"} 2464409652 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 97663073412 (90.96 GB)
telemt_user_unique_ips_current{user="hello"} 498
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 20187.7 (5h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 414592
telemt_connections_bad_total 44290
telemt_connections_current 1579
telemt_connections_me_current 1579
telemt_handshake_timeouts_total 14486
telemt_upstream_connect_attempt_total 3865
telemt_upstream_connect_success_total 3842
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 3865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1928
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 2824
telemt_me_reconnect_success_total 2809
telemt_me_reader_eof_total 2964
telemt_me_idle_close_by_peer_total 2964
telemt_me_route_drop_no_conn_total 118631
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 300223
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1338
telemt_desync_full_logged_total 515
telemt_desync_suppressed_total 823
telemt_desync_frames_bucket_total{bucket="1_2"} 357
telemt_desync_frames_bucket_total{bucket="3_10"} 534
telemt_desync_frames_bucket_total{bucket="gt_10"} 447
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 2831
telemt_me_writer_restored_same_endpoint_total 2785
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 300144
telemt_user_connections_current{user="hello"} 1579
telemt_user_octets_from_client{user="hello"} 10290157352 (9.58 GB)
telemt_user_octets_to_client{user="hello"} 174856955700 (162.85 GB)
telemt_user_unique_ips_current{user="hello"} 623
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 20199.1 (5h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95179
telemt_connections_bad_total 9911
telemt_connections_current 346
telemt_connections_me_current 346
telemt_handshake_timeouts_total 419
telemt_upstream_connect_attempt_total 5740
telemt_upstream_connect_success_total 5577
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 5740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2920
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_reconnect_attempts_total 6389
telemt_me_reconnect_success_total 4552
telemt_me_reader_eof_total 4781
telemt_me_idle_close_by_peer_total 4781
telemt_me_route_drop_no_conn_total 38857
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81688
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 42
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 4616
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 4522
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 81682
telemt_user_connections_current{user="hello"} 346
telemt_user_octets_from_client{user="hello"} 1638949492 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 55687655000 (51.86 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 20190.0 (5h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 282133
telemt_connections_bad_total 28530
telemt_connections_current 1311
telemt_connections_me_current 1311
telemt_handshake_timeouts_total 14654
telemt_upstream_connect_attempt_total 4321
telemt_upstream_connect_success_total 4321
telemt_upstream_connect_attempts_per_request{bucket="1"} 4321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2054
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3304
telemt_me_reconnect_success_total 3295
telemt_me_reader_eof_total 3473
telemt_me_idle_close_by_peer_total 3473
telemt_me_route_drop_no_conn_total 81025
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231859
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1206
telemt_desync_full_logged_total 462
telemt_desync_suppressed_total 744
telemt_desync_frames_bucket_total{bucket="1_2"} 226
telemt_desync_frames_bucket_total{bucket="3_10"} 476
telemt_desync_frames_bucket_total{bucket="gt_10"} 504
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3332
telemt_me_writer_restored_same_endpoint_total 3280
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 231880
telemt_user_connections_current{user="hello"} 1311
telemt_user_octets_from_client{user="hello"} 2520311096 (2.35 GB)
telemt_user_octets_to_client{user="hello"} 124040749872 (115.52 GB)
telemt_user_unique_ips_current{user="hello"} 527
telemt_user_unique_ips_recent_window{user="hello"} 127
```